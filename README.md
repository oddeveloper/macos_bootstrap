# Dev Envrionments Setup for MacOS

Usage: just go to cloned dir in mac os terminal and install.

Check: [homebrew install](https://brew.sh/) before ```brew bundle```

```
## if brew is not installed mac.
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

## repository clone and brew bundle
$ git clone https://github.com/oddeveloper/macos_bootstrap
$ cd macos_bootstrap && brew bundle

## set zsh
$ echo "/usr/local/bin/zsh" | sudo tee -a /etc/shells
$ chsh -s $(which zsh) # 이후 터미널 재시작
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Inside Brewfile

### Brew and Cask
* [homebrew/bundle](https://github.com/Homebrew/homebrew-bundle) : for using bundle / Brewfile
* [caskroom/cask](https://caskroom.github.io) : enable cask
* [caskroom/versions](https://github.com/caskroom/homebrew-versions) : alternative versions
* [caskroom/fonts](https://github.com/caskroom/homebrew-fonts) : cask fonts

### Shell installation
* [zsh](http://www.zsh.org)

### GNU utils
* gnu-sed
* gnu-tar
* gnutls
* grep
* coreutils
* binutils
* diffutils

### Tmux (Not Required)
* [tmux](https://tmux.github.io)

### System utils
* gzip
* watch
* wget
* nmap
* htop
* gpg
* git

### Vim
* [vim](http://www.vim.org)

### Static Site Generator (Not Required, Just Blogging)
* [hugo](https://gohugo.io)

### MacOS utilities
* [iterm2](https://www.iterm2.com)
* [google-chrome](https://www.google.com/chrome/)
* [zoom](https://zoom.us/)

### Development Tools
* [visual-studio-code](https://code.visualstudio.com) (Temporary Required)
* [firefoxdeveloperedition](https://www.mozilla.org/firefox/developer/) (Not Required)
* [postman](https://www.postman.com/)
* [docker](https://www.docker.com/)

### Jetbrains Toolbox
* [jetbrains-toolbox](https://www.jetbrains.com/toolbox/)

### Productivity
* [slack](http://slack.com/)
* [notion](https://www.notion.so/)

### Fonts (Not Required and Install Before Needs Svn)
* [font-nanumgothic](http://hangeul.naver.com/font)
* [font-nanumgothiccoding](https://github.com/naver/nanumfont)
* [font-d2coding](https://github.com/naver/d2codingfont)
* [font-noto-sans-cjk](https://www.google.com/get/noto/help/cjk/)
* [font-awesome-terminal-fonts](https://github.com/gabrielelana/awesome-terminal-fonts)

### Asdf (Not Required)
* [Asdf](https://asdf-vm.com/#/)

### Ruby
* [rbenv](https://github.com/rbenv/rbenv)
* [ruby-build](https://github.com/rbenv/ruby-build#readme)

### Python (Not Required)
* [pyenv](https://github.com/yyuu/pyenv)
* [pyenv-virtualenv](https://github.com/yyuu/pyenv-virtualenv)
* [pipenv](https://github.com/pypa/pipenv)

### Nvm
* [nvm](https://github.com/nvm-sh/nvm)

### PHP (Not Required)
* [php](https://www.php.net/)

### Database
* [mysql](https://www.mysql.com/)
* [dynamodb](https://aws.amazon.com/ko/dynamodb/)
* [postgresql](https://www.postgresql.org/) (Not Required)

### AWS
* [aws-cli]()https://aws.amazon.com/ko/cli/

### Reference Link
* [Sierra Setup](https://blog.funspaces.org/2016/12/09/sierra-setup/)
