# ![❏](https://raw.github.com/Springerle/springerle.github.io/master/static/img/logo-64.png) Springerle Cookie Jar

This is a repository comprised of `git` submodules with all the Springerle molds, for easy installation and updates.

![Apache 2.0 license](http://img.shields.io/badge/license-Apache_2.0-red.svg)


## Adding and updating submodules

```sh
# Add initially
git submodule add «git-url»
( cd «module» && git checkout «tag» )
# → commit + push
```

```sh
# Update
( cd «module» && git fetch && git checkout «tag» )
# → commit + push
```
