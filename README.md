# Install aliases

1. download `.aliases` file to homedir

  `curl -s https://raw.githubusercontent.com/fordnox/dotfiles/master/.aliases --output ~/.aliases`

1. check bash file syntax

  `bash -n ~/.aliases`

1. edit `~/.zprofile` and insert following lines

  ```
  if [ -f ~/.aliases ]; then
    source ~/.aliases
  fi
  ```

1. run

  `source ~/.zprofile`

1. list aliases

  `alias`

1. run first install

  `fresh_install`
