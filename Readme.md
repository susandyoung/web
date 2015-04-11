# Susan Young

The [personal blog](http://susandyoung.com) of Susan Young.

# System Requirements

* [Node.js](http://node.js.org) (v^0.12.0)
* [Hexo](http://hexo.io) (v^3.0.0)

## Installation

```
npm i -g hexo
```

## Usage

**Starting the local development server**

```
hexo server
```

**Creating a new blog entry**

```
hexo new "{TITLE}"
```

**Adding the new post to source control**

```
git add .
git commit -m 'Your message'
git push origin master
```

Note: If your Git commit message has single quotes in it, you'll want to use double quotes to enclose the message (otherwise, you'll terminate the message before you intend to).

**Deploying to your hosting provider***

```
hexo generate --deploy
```

**Updating your local copy of the blog after changes have been pushed to GitHub by someone else**

```
git pull origin master
```

## License

Unless otherwise specified, all code, markup, and design in this repository is &copy; 2015 Susan Young. All Rights Reserved.

The [Casper Theme](https://github.com/TryGhost/Casper) is owned by Ghost Foundation and used herein under the MIT License.
