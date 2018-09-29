# Install homebrew-cask
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew tap caskroom/cask;
```

# Install brew apps and cask apps

```
cat brew_list | xargs brew install
cat cask_list | xargs brew cask install
```

# Upgrade apps
```
brew cask upgrade
```
