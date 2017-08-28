# SkilStak Home Config Helper

This repo is to help you create the same workspace
on your own Linux/Mac computer or Raspberry Pi that
we use at SkilStak. The easiest way to use it is just to
clone it and run `setup`:

```bash 
cd ~
mkdir repos
cd repos
git clone http://github.com/skilstak/home-config
cd home-config
./setup
```

# Dependencies

Dependencies is a strong word. This is stuff you just need at
SkilStak. Eventually `setup` may including looking up dependencies
and prompting for installing them (packages, commands, apps). For
now you will have to ensure you have the following installed, (which
you learn to do in class if you don't know):

* [git](https://git-scm.com)
* [tmux](https://github.com/tmux/tmux/wiki)
* [vim 7.4+](http://www.vim.org) (7.3 will work)
* [Python 3](http://www.python.org)
* [Go](http://www.golang.org)
* [Node/NPM](http://nodejs.org)
* [Browser Sync](http://www.browsersync.io/)
* [Google Chrome](http://google.com/chrome)
* [Solarized terminal](solarized)

On a Mac you have to install [brew](http://brew.sh),
(which also installs Xcode), to do most of these:

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

```
Then you can use it to install about everything else:

* `brew install git`
* `brew install vim`
* `brew install tmux`
* `brew install python3`
* `brew install ruby`
* `brew install perl`
* `brew install go`
* `brew install curl`
* `brew install node`
* `brew install build-essential`
* `brew install bash-completion`

On Linux (including Windows 10 with `bash` command prompt) and Raspberry Pi use `apt-get install` or `apt install` instead:

* `sudo apt install git`
* `sudo apt install vim`
* `sudo apt install tmux`
* `sudo apt install python3`
* `sudo apt install ruby`
* `sudo apt install perl`
* `sudo apt install go`
* `sudo apt install curl`
* `sudo apt install build-essential`
* `sudo apt install nodejs`

