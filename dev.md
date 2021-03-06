# Dev

## Installation

Your computer needs:

* [Node.js](https://nodejs.org/en/) \(0.12 or greater\)
* [Git](https://git-scm.com/)

### Deal with your node versions

If you have some issues try to install **Node Version Manager,** a simple bash script to manage multiple active Node.js versions.

[https://github.com/creationix/nvm](https://github.com/creationix/nvm)

💡 **Protip:** Show the list of differents Node.js versions installed with `nvm list` and choose a default one with `nvm alias default 6.x.x`

![](/assets/nodejs.gif)

### Installing npm packages

There are two ways to install npm packages: locally or globally. You choose which kind of installation to use based on how you want to use the package.

For now we are going to use the **global installation** like this one:

```bash
$ npm install github-email --global
```

Magic! You just installed a new Command Line for your terminal, and you can use it like this:

```bash
$ github-email <GITHUB_USERNAME>
```

💡 **Protip:** Looking for other cool packages? You can search on [GitHub](https://github.com/explore) or [npmsearch](https://npmsearch.com/).

_Challenges:_

* [ ] Open my [GitHub profile](http://github.com/flexbox/) and follow me 😉
* [ ] Try to find my email with `github-email`

## Mastering the Foundation CLI

Install the Foundation CLI with this command:

```
$ npm install foundation-cli --global
```

Use this command to set up a new Foundation website

```bash
$ foundation new
```

The CLI will prompt you to give your project a name. The template will be downloaded into a folder with this name.

_Challenges:_

* [ ] Build your first foundation website with the CLI
* [ ] Choose _Handlebars templates and Sass/JS compilers_
* [ ] Launch your local server with `foundation watch`
* [ ] Commit your changes with theses commands
  * [ ] `$ git init`
  * [ ] `$ git add .`
  * [ ] `$ git commit --message 'Initial commit :new:'`



