---
layout: default
title: Mac Laptop Setup
permalink: /setup/
---
## Mac Setup

All students must bring their own MacBook laptop. Your MacBook should have a minimum of 4 GB of RAM and 128 GB of hard drive space. Those are minimum specs, and I recommend getting 8 GB of RAM and a 256 GB hard drive, but that’s your choice to make. Any MacBook model (including Air and Pro) made in 2012 or after will work well. If you already own a Mac and it's older than that, send me an email and we can talk.

Your MacBook must be running OS X Yosemite. This is a free upgrade from the App Store.

There is no commercial software required for the class.

As soon as possible after receiving your Mac, run through the following steps. If you've done a lot of your own configuration, some of these steps may have to change.  If you run into ANY PROBLEMS, send me an e-mail at:

<mike.sweeney@theironyard.com>

Again, we want to have all of these kinks worked out in advance, so PLEASE e-mail if things don't work as described below.

* Install OSX Yosemite (or newer), if you haven’t already.
    1. You'll need to sign in to the Mac App Store with you Apple ID. If you don't have one, [sign up here](https://appleid.apple.com/).
    1. Download the Yosemite upgrade from the Apple Store: [download here](https://itunes.apple.com/us/app/os-x-yosemite/id915041082?mt=12).
    1. Double-click "Install OS X Yosemite” to begin installation.

  **WARNING:** The OS X upgrade can take a bit of time to complete and will require a restart. Plan on doing this in the evening or over a lunch break.

* Install [Sublime Text 3](http://www.sublimetext.com/3)

* Install [Google Chrome](https://www.google.com/intl/en/chrome/browser/)

* Install [NodeJS](https://nodejs.org/en/)

* Install XCode Command Line Tools
    1. Go to the [Apple Developer Downloads site](https://developer.apple.com/downloads/).
    1. You will have to register.
    1. Look for "Command Line Tools (OS X 10.10) for Xcode - Xcode 6.2" and download them.
    1. Once downloaded, open the downloaded file by double-clicking on it. This should bring up a new window with a file that ends in .pkg. Double-click it and follow all the prompts.

* Install Homebrew
    1. Open up Terminal.app. If you have any trouble here, go through [the command-line prework](/prework#topic-3-the-command-line).
    1. Run `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` and follow all the prompts.
    1. Run `brew doctor`

* Create an SSH key (__do not__ give it a password when it asks for one)
    * Run `ssh-keygen` in your terminal.