# brew-file

My personal setup for brew built around `brew bundle`...

## requirements

- nit == `gem install nit`

## installation

The contents of this repo are designed to be installed in a `~/.brew-file` folder.  This is the location used by the included `bru` script.

Running the `bru` script will check your brew configuration and update the packages defined in the `Brewfile`.  I use this to easily keep my development tools updated.

YMMV...

## example

```
➜  ~ bru
[brew]:
-- update
Already up-to-date.
-- check
The Brewfile's dependencies are satisfied.
-- install
Using github/gh
Using heroku/brew
Using homebrew/bundle
Using homebrew/cask
Using homebrew/cask-fonts
Using homebrew/core
Using mongodb/brew
Using ack
Using bash
Using brew-gem
Using glib
Using gcc
Using openssl@3
Using ruby
Using gh
Using git
Using hub
Using python@3.8
Using imagemagick
Using node
Using nvm
Using php
Using wget
Using yarn
Using heroku/brew/heroku
Using font-victor-mono
Using qlimagesize
Using webpquicklook
Homebrew Bundle complete! 28 Brewfile dependencies now installed.
-- cleanup
-- outdated
-- doctor
Your system is ready to brew.
-- nit
/usr/local/bin/nit
-- yarn
/opt/homebrew/bin/yarn
1.22.18
-- verify
-- done
```


