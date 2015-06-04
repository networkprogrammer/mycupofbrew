#!/bin/bash
ssh-keygen -t rsa
xcode-select --install
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null
brew install caskroom/cask/brew-cask
brew install iperf iperf3 python python3 wakeonlan curl wget
brew cask install anki github onyx transmission atom google-chrome macdown pycharm-ce vlc filezilla google-drive vmware-fusion flux iterm2 nosleep spectacle wacom-bamboo-tablet cord
brew cask install caskroom/homebrew-versions/java6

#brew cask install microsoft-office
#brew cask install royal-tsx
