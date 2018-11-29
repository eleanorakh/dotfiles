# [fresh] ~/.dotfiles

## Installation

Ensure you've got brew installed and follow the prompts to install Xcode CLI tools:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

``` sh
FRESH_LOCAL_SOURCE=eleanorakh/dotfiles bash -c "`curl -sL get.freshshell.com`"
```

My dotfiles are managed by [fresh].

[fresh]: https://github.com/freshshell/fresh

### Setting up new laptop

- Do the brew installation to get CLI tools (and get Xcode downloading anyway)
- Do above installation to get dotfiles
- Install rbenv `brew install rbenv` and follow instructions in https://github.com/rbenv/rbenv#installation
- Install correct ruby version with rbenv `rbenv install 2.5.1` and set it with `rbenv global 2.5.1`
- Install rails `sudo gem install rails`
- Install VSCode https://code.visualstudio.com/
- Set git author `git config --global --edit`
- Install postgres `brew install postgres`
- don't forget to bundle
- Add ssh keys e.c.t
