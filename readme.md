# Dries's Dotfiles

## What Is This?

This repository serves as my way to help me setup and maintain my Mac :computer:. It takes the effort out of installing everything manually. Everything which is needed to install my preffered setup of OS X is detailed in this readme. Feel free to explore, learn and copy parts for your own dotfiles. Enjoy! :smile:

## A Fresh OS X Setup

Follow these install instructions to setup a new Mac.

1. Update OS X to the latest version with the App Store
2. Set your preferred computer name in the sharing settings
3. Install Xcode from the App Store, open it and accept the license agreement
4. Install OS X Command Line Tools
5. Copy public and private SSH keys to `~/.ssh`. Make sure they're set to `600`
6. Clone this repo to `~/.dotfiles`
7. Copy the env file `cp .dotfiles_env $HOME/.dotfiles_env` and change the values if needed
8. Append `/usr/local/bin/zsh` to the end of your `/etc/shells` file
9. Run `install.sh` to start the installation
10. Set OS X preferences with `source .osx`
11. Make sure Dropbox is set up and synced
12. [Install the remaining apps](./apps/readme.md)
13. Restore preferences by running `mackup restore`
14. Restart your computer to finalize the process

Your Mac is now ready to use!

## Thanks To...

I first got the idea for starting this project by visiting the [Github does dotfiles](https://dotfiles.github.io/) project. Both [Zach Holman](https://github.com/holman/dotfiles) and [Mathias Bynens](https://github.com/mathiasbynens/dotfiles) were great sources of inspiration. [Sourabh Bajaj](https://twitter.com/sb2nov/)'s [Mac OS X Setup Guide](http://sourabhbajaj.com/mac-setup/) proved to be invaluable. And lastly, I'd like to thank [Maxime Fabre](https://twitter.com/anahkiasen) for [his excellent presentation on Homebrew](https://speakerdeck.com/anahkiasen/a-storm-homebrewin) which made me migrate a lot to a `Brewfile` and [Mackup](https://github.com/lra/mackup).

In general, I'd like to thank every single one who open-sources their dotfiles for their effort to contribute something to the open-source community. Your work means the world. :earth_africa: :heart:

## License

The MIT License. Please see [the license file](license.md) for more information.
