# Install homebrew-cask
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew tap caskroom/cask;
```

# Install apps

## brew apps
```
cat brew_list | xargs brew cask install --force
```

## brew cask apps
```
cat cask_list | xargs brew cask install --force
```

# Upgrade cask apps
```
brew cask upgrade
```

# Update installation list
Update file `brew_list` and `cask_list` for the app installation list
