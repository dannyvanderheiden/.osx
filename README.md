# OSX Settings

This repository contains my OSX settings.


## Installation

Run the following to install the OSX settings:

    git clone git://github.com/dannyvanderheiden/.osx.git ~/.osx

    cd ~/.osx

    ./script/install

The installation will symlink the available dot files.


## Upgrading

To get the latest version:

    cd ~/.osx
    git pull origin master



## Configuration

### iTerm2

In the iTerm2 general settings, check `Load preferences from a user-defined folder or URL`.

Fill in `/Users/your_name/.osx/iterm2` in the text field.

You might need to restart iTerm2 after that.
