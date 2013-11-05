# git-commit-training-wheels-mode.el

Helps you craft well formed commit messages with `git-commit-mode`
Directives for what makes a well formed commit come from
tpope: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html

Based in part on https://github.com/re5et/magit-commit-training-wheels

## Installation

### Manual

Just drop `git-commit-training-wheels-mode.el`. somewhere in your `load-path`.

```lisp
(add-to-list 'load-path "~/somewhere")
```

### MELPA

If you're an Emacs 24 user or you have a recent version of package.el
you can install `git-commit-training-wheels-mode.el` from the [MELPA](http://melpa.milkbox.net/) repository.

## Usage

Add the following to your emacs init file:

    (require 'git-commit-training-wheels-mode) ;; Not necessary if using ELPA package
    (add-hook 'git-commit-mode-hook 'git-commit-training-wheels-mode)
