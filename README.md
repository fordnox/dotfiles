# Install aliases

1. download `.aliases` file to homedir

  `curl -s https://raw.githubusercontent.com/fordnox/dotfiles/master/.aliases --output ~/.aliases`

1. check bash file syntax

  `bash -n ~/.aliases`

1. edit `~/.bash_profile` and insert following lines

  ```
  if [ -f "~/.aliases" ]; then
    source "~/.aliases"
  fi
  ```

1. run

  `source ~/.bash_profile`

1. list aliases

  `alias`

1. run first install

  `fresh_install`
