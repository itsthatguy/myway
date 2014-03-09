# myway

A middleman starting point and generator

# Installation

Requirements:

* Ruby
* git
* bower [bower.io](http://bower.io/)

Steps (In Terminal.app do the following commands):

**1. Make the ~/bin directory and add it to your PATH environment variable**

    mkdir ~/bin && echo "export PATH=$PATH:$HOME/bin" >> ~/.bash_profile && source ~/.bash_profile

**2. Download your own version of myway, and create a symlink to the bash script**

```
git clone https://github.com/itsthatguy/myway.git
cd myway
ln -s bin/mway ~/bin/mway
chmod +x ~/bin/mway
```

# Usage

To start a new project based on the myway template:

    mway <name of project>


Running

    cd <name of project>
    bundle exec middleman


Browsing

> navigate your browsing device to: **http://localhost:4567/**
