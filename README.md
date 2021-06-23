# Overview
Install apps on your Mac using brew.

# Setup 
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";
brew tap homebrew/cask;
```

# Update list
Update file `brew_list` and `cask_list` for app installation list


# Install

brew apps
```
cat brew_list | xargs brew cask install --force
```

brew cask apps
```
cat cask_list | xargs brew cask install --force
```

# Upgrade
```
brew cask upgrade
```

