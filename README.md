# Dottle

Dottle is sort of a cross between Homeshick and Zach Holmans dotfiles repository.

## Installation

* Clone dottle:
    git clone git@github.com:rustygeldmacher/dottle.git ~/.dottle
* Make your `~/.bashrc` only this:

```
#!/bin/bash
source $HOME/.dottle/bootstrap
```

* Start a new shell so dottle is enabled
* Clone a repository, for instance:
    dottle clone <your-github-name>/dotfiles dotfiles
* Either use your entire repo:
    dottle use dotfiles
* Or use specific topics:
    dottle use dotfiles/<topic>

## Topics

Topic layout:
* `name/`
  * init -- script that will be sourced for the topic
  * install -- script that will be run when the topic is installed
  * filename.ext.symlink -- will be symlinked to $HOME/.file.ext
  *  _dir/file.symlink -- will symlink file into $HOME/.dir/
