# myway

A middleman starting point and generator

# Installation

Requirements:

* RVM [http://rvm.beginrescueend.com/](http://rvm.beginrescueend.com/)
* Ruby/RubyGems
* git
* a ~/bin directory that is in your PATH environment variable (see steps below)

Steps (In Terminal.app do the following commands):

**1. Make the ~/bin directory and add it to your PATH environment variable**

    mkdir ~/bin && echo "export PATH=$PATH:$HOME/bin" >> ~/.bash_profile && source ~/.bash_profile

**2. Get the mway script and make it executable**

    curl -o ~/bin/mway -L https://github.com/itsthatguy/myway/raw/master/bin/mway  && chmod +x ~/bin/mway

# Usage

To start a new project based on the myway template:

    mway <name-of-new-project>

## Starting the application

    gem install bundler
    bundle install
    ruby app.rb

