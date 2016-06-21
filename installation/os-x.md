# Installation Guide for OS X

## Homebrew

If you haven't already, install [Homebrew](http://brew.sh/)!

Copy-paste the command at the top of the homepage into a Terminal window.


## git

Once Homebrew is installed, you can install [git](https://git-scm.com/), the version control system, by running

```shell
$ brew update
$ brew install git
```

in a Terminal window.

Configure git by running

```shell
$ git config --global user.name "Your First and Last Name"
$ git config --global user.email "Your Email Address"
```

as well.


## Leiningen

[Leiningen](http://leiningen.org/) is a command-line tool for managing Clojure projects. Run

```shell
$ brew install leiningen
```

to install it.

Then, run

```shell
$ lein version
```

to verify that Leiningen has been installed.


## Editor

See ["Editors"](editors.md) for a list of Clojure extensions for various editors.

This is a relatively short session, so we won't have time to go deep on any specific one. Choose whichever feels most familiar to you!
