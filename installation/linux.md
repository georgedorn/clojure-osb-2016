# Installation Guide for Linux

## git

Install the [git](https://git-scm.com/) version control system by running

```sh
$ sudo apt-get install git
```

from a Terminal window.

Configure git by running

```shell
$ git config --global user.name "Your First and Last Name"
$ git config --global user.email "Your Email Address"
```

as well.


## Leiningen

[Leiningen](http://leiningen.org/) is a command-line tool for managing Clojure projects.

To install it, go to the [Leiningen homepage](http://leiningen.org/#install), right-click on the "lein script" link, and save it to your `Downloads` folder. Then, run

```shell
$ sudo mkdir -p /usr/local/bin/
$ sudo mv ~/Downloads/lein* /usr/local/bin/lein
$ sudo chmod a+x /usr/local/bin/lein
$ export PATH=$PATH:/usr/local/bin
```

from a Terminal window. Note that you'll be prompted to enter your password.

After running the above commands, run

```shell
$ lein version
```

to verify that Leiningen has been installed.


## Editor

See ["Editors"](editors.md) for a list of Clojure extensions for various editors.

This is a relatively short session, so we won't have time to go deep on any specific one. Choose whichever feels most familiar to you!
