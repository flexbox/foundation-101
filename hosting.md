# Hack the hosting

## Build folder

By convention the `dist`folder is used for compiled code.

In our case we are going to change that for a FREE hosting hack. Edit the `config.yml` file like this :

![](/assets/foundation-cli-build-hack.png)

Use this command to build the website

```bash
$ foundation build
```

_Challenges:_

* [ ] Commit your changes
* [ ] Push to GitHub

## GitHub

On the repository of your project, go to **Settings** &gt; **Options** &gt; **GitHub page**

![](/assets/github-pages-docs-folder.png)

_Challenges:_

* [ ] Open a your favorite web browser and open [https://&lt;USER\_NAME&gt;.github.io/&lt;PROJECT\_NAME&gt;](https://<USER_NAME>.github.io/<PROJECT_NAME>/)

## Link your own domain name

#### The lazy way

Go to **Settings** &gt; **Options** &gt; **GitHub page** and add your own domain name

#### ![](/assets/github-pages-custom-domain.png)

#### The hacker way

There are a lot of solutions for using a [custom domain with GitHub Pages](https://help.github.com/articles/using-a-custom-domain-with-github-pages/). The simple one is to change your DNS.

1. Update your A record for this adress `192.30.252.153`
2. Add a `CNAME`file [like this one](https://github.com/flexbox/davidl/blob/master/source/CNAME)

**NB** Each time ``foundation watch`` create CNAME files. 
