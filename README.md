# dotfiles


---


### Create an dev environment from nothing. 23rd Oct '15


#### Sublime Text

- download [Sublime Text](http://www.sublimetext.com/)
- Activate Package Controll from [here]()

##### When you are on proxy probrem

- You'd better to [install manualy](https://packagecontrol.io/installation#st2)
- Edit http_proxy & https_proxy on "Preferences" -> "Package Settings" -> "Package Control" -> "Settings Default"


#### iTerm

- download [iTerm 2](https://www.iterm2.com/)


#### Homebrew

- install Homebrew from [brew.sh](http://brew.sh/)

```zsh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```


##### If you have proxy probrem

```zsh
$ export http_proxy=http://example.com:8080/
$ export https_proxy=$http_proxy
$ export all_proxy=$http_proxy

# proxy paths witten on .pac file
```

[Qiita](http://qiita.com/gishi_yama/items/2e92d3d72e21c74704cb)


#### Git

- install Git

```zsh
$ brew install git
```


