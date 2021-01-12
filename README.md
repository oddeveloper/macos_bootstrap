# Bootstrap repository for MacOS Sierra

Usage: just go to cloned dir, ```brew bundle```

Caution: check [homebrew install](https://brew.sh/) before ```brew bundle```

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

$ git clone https://github.com/oddeveloper/macos_bootstrap
$ cd macos_bootstrap && brew bundle

$ echo "/usr/local/bin/zsh" | sudo tee -a /etc/shells
$ chsh -s $(which zsh) # 이후 터미널 재시작
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## taps
* [homebrew/bundle](https://github.com/Homebrew/homebrew-bundle) : for using bundle / Brewfile
* [homebrew/dupes](https://github.com/Homebrew/homebrew-dupes) : for dupes (ex: grep)
* [caskroom/cask](https://caskroom.github.io) : enable cask
* [caskroom/versions](https://github.com/caskroom/homebrew-versions) : alternative versions
* [caskroom/fonts](https://github.com/caskroom/homebrew-fonts) : cask fonts

## Shell installation
* [zsh](http://www.zsh.org)

## GNU utils
* gnu-sed
* gnu-tar
* gnutls
* grep
* coreutils
* binutils
* diffutils

## TMUX
* [tmux](https://tmux.github.io)

## System utils
* gzip
* watch
* wget
* nmap
* htop
* gpg
* git

## Vim
* [vim](http://www.vim.org)

## Static Site Generator
* [hugo](https://gohugo.io)

## MacOS utilities
* [iterm2](https://www.iterm2.com)
* [google-chrome](https://www.google.com/chrome/)
* [spectacle](https://www.spectacleapp.com)

## Development Tools
* [github-desktop](https://desktop.github.com)
* [visual-studio-code](https://code.visualstudio.com)
* [firefoxdeveloperedition](https://www.mozilla.org/firefox/developer/)
* [java](http://www.oracle.com/technetwork/java/index.html)

## Jetbrains Toolbox
* [jetbrains-toolbox](https://www.jetbrains.com/toolbox/)

## Fonts
* [font-nanumgothic](http://hangeul.naver.com/font)
* [font-nanumgothiccoding](https://github.com/naver/nanumfont)
* [font-d2coding](https://github.com/naver/d2codingfont)
* [font-noto-sans-cjk](https://www.google.com/get/noto/help/cjk/)
* [font-awesome-terminal-fonts](https://github.com/gabrielelana/awesome-terminal-fonts)

## Ruby
* [rbenv](https://github.com/rbenv/rbenv)
* [ruby-build](https://github.com/rbenv/ruby-build#readme)

## Python
* [pyenv](https://github.com/yyuu/pyenv)
* [pyenv-virtualenv](https://github.com/yyuu/pyenv-virtualenv)
* [pipenv](https://github.com/pypa/pipenv)

## Setting (based MacOS Sierra)
* [Sierra Setup](https://blog.funspaces.org/2016/12/09/sierra-setup/)
