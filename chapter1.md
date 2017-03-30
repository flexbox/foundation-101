# Hack the hosting

## Build folder

By convention the `dist`folder is used for compiled code.

In our case we are going to change that for a FREE hosting hack. Edit the `config.yml`file like this :![](/assets/Capture d’écran 2017-03-26 à 23.27.44.png)Use this command to build the website

```bash
$ foundation build
```

_Challenges:_

* [ ] Commit your changes
* [ ] Push to GitHub
* [ ] Open a your favorite web browser and open [https://&lt;USER\_NAME&gt;.github.io/&lt;PROJECT\_NAME&gt;/](https://<USER_NAME>.github.io/<PROJECT_NAME>/)

## GitHub

On the repo of your project, go to **Settings** &gt; **GitHub page**

![](/assets/Capture d’écran 2017-03-26 à 23.23.10.png)

## Link your domain name

1. Update your A record for this adress `192.30.252.153`
2. Add a `CNAME`file [like this one](https://github.com/flexbox/davidl/blob/master/source/CNAME) 



