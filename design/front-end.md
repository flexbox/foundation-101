# Front-end Architecture for Large-Scale UIs

## Content

Add your first piece of website. For exemple: **an amazing footer.**

## Stylesheets

Add architecture for sass

```bash
$ mkdir atoms molecules pages
```

## Externals librairies

### Dependencies 101

Welcome in the new JavaScript dependencies ~~world,~~ jungle 🌴🌴🌴  
First everything is gonna be alright, just take a breath and read theses sentences.

> **Npm** is a package manager for Node.js  
> **Bower** is a JavaScript package manager 💀  
> **Yarn** is a package manager for your code 🚚✨

Remember just one thing every dependencies lives in `package.json` or `bower.json`

For example if you want the same layout as medium.com you can install the [headroom.js](http://wicky.nillia.ms/headroom.js/) library

###### Install with npm

```
$ npm install headroom.js --save
```

###### Install with bower

```
$ bower install https://unpkg.com/headroom.js/bower.zip --save
```

###### Install with yarn

```
$ yarn add headroom.js --save
```

🚓 Never omit `--save`option because it update automatically the dependecy file. Remember you work in a team. If you install a local dependency without saving it, you are going to break the project for others.

### Import External librairies in your project

You know how works the dependencies in the JavaScript world.

`config.yml`



