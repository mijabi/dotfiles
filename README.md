# dotfiles


---


# Create an dev environment by pale OSX. 23rd Oct '15


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

```zsh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```


##### If you have proxy probrem

```zsh
$ export http_proxy=http://example.com:8080/
$ export https_proxy=$http_proxy
$ export all_proxy=$http_proxy
```

proxy path witten on a .pac file


### Git

- install Git

```zsh
$ brew install git
```

### Show invisible files

```zsh
$ defaults write com.apple.finder AppleShowAllFiles TRUE
$ killall Finder
```

### Add git global setting for proxy. It enables to "git push"

```zsh
$ git config --global http.proxy http://sample.com:8080/
$ git config --global https.proxy http://sample.com:8080/
```


### Node

- Install [Node.js](https://nodejs.org/en/)


<!--
### $

git config --global url.https://github.com/.insteadOf git://github.com/
-->
