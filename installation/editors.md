# Editors

This is a list of popular text editors, along with the _basic_ packages and extensions you'll need to use them with Clojure.

Note that although there's several editors listed, kf has mostly just used Atom, IntelliJ, and Sublime for Clojure development and will be using Atom during the actual session.


## Contents
* [Atom](#atom)
* [Emacs](#emacs)
* [IntelliJ](#intellij)
* [Sublime Text](#sublime-text)
* [vim](vim)


## Atom

There are two packages you'll definitely find useful:

* [`language-clojure`](https://atom.io/packages/language-clojure), which provides Clojure language support for Atom, and
* [`proto-repl`](https://atom.io/packages/proto-repl), which provides an in-editor REPL for Clojure.


## Emacs

There are two packages you'll definitely find useful:

* [`clojure-mode`](https://github.com/clojure-emacs/clojure-mode), which provides Emacs support for Clojure and ClojureScript, and
* [`CIDER`](https://github.com/clojure-emacs/cider), which provides an interactive environment for Clojure development.

You will also find it helpful to enable [RainbowDelimeters](https://www.emacswiki.org/emacs/RainbowDelimiters).


## IntelliJ

If you're an IntelliJ user, [Cursive](https://cursive-ide.com/) is the plugin for you!

Download it via the [Cursive homepage](https://cursive-ide.com/); see the official ["User Guide"](https://cursive-ide.com/userguide/) for detailed installation instructions.

Note that, unless you're accustomed to using Paredit already, you'll likely want to [disable structural editing](https://cursive-ide.com/userguide/paredit.html).

You'll also want to navigate to `Settings > Languages & Frameworks > Clojure` and check the box for "Rainbow parentheses".


## Sublime Text

If you haven't installed it already, you might want to install [SublimeREPL](https://github.com/wuub/SublimeREPL).


## vim

The package you'll find most useful is [`vim-fireplace`](https://github.com/tpope/vim-fireplace), which will enable interactive development in Clojure via vim.
