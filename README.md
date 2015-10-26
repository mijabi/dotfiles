# dotfiles


---


# Create an dev environment with pale OSX. 23rd Oct '15


### Sublime Text

- download [Sublime Text](http://www.sublimetext.com/)
- Activate Package Controll from [here]()


##### When you are on proxy probrem

- You'd better to [install manualy](https://packagecontrol.io/installation#st2)
- Edit http_proxy & https_proxy on "Preferences" -> "Package Settings" -> "Package Control" -> "Settings Default"


### iTerm

- download [iTerm 2](https://www.iterm2.com/)


### Homebrew

- install Homebrew from [brew.sh](http://brew.sh/)

```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```


##### If you have proxy probrem

```bash
$ export http_proxy=http://example.com:8080/
$ export https_proxy=$http_proxy
$ export all_proxy=$http_proxy
```

proxy path witten on a .pac file


### Git

- install Git

```bash
$ brew install git
```

### Show invisible files

```bash
$ defaults write com.apple.finder AppleShowAllFiles TRUE
$ killall Finder
```

### Add git global setting for proxy. It enables a "git push"

```bash
$ git config --global http.proxy http://sample.com:8080/
$ git config --global https.proxy http://sample.com:8080/
```


### Node

- Install [Node.js](https://nodejs.org/en/)


### oh-my-zsh

- Insatll [Oh My ZSH!](https://github.com/robbyrussell/oh-my-zsh)

##### Install manually

```bash
$ git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
$ cp ~/.zshrc ~/.zshrc.orig
$ cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
$ zsh

# If you install manually, you have to update manually via code below
$ upgrade_oh_my_zsh
```

##### Select and edit [plugins](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins) of Oh My ZSH

```txt
: ~/.zshrc

# plugins=(git)
plugins=(git sublime sudo web-search)
```

[sublime](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#sublime) / [sudo](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#sudo) / [web-search](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#web-search)

All plugins are placed on ~./oh-my-zsh/plugins


##### Chagne [theme](https://github.com/robbyrussell/oh-my-zsh/wiki/themes) if you want

```txt
: ~/.zshrc

# ZSH_THEME="robbyrussell"
```

### Grunt

- Install [Grunt CLI](http://gruntjs.com/getting-started)

```zsh
% npm install -g grunt-cli
```

<!--
### $

git config --global url.https://github.com/.insteadOf git://github.com/
-->

---

## If you need

#### Ruby

My Yosemite may accepts only 2.0.0-p451
