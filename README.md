Dottle is sort of a cross between Homesick and Zach Holmans dotfiles repository.

Topic layout:
name/
  init -- script that will be sourced for the topic
  install -- script that will be run when the topic is installed
  filename.ext.symlink -- will be symlinked to $HOME/.file.ext
  _dir/file.symlink -- will symlink file into $HOME/.dir/


