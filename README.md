# Install homebrew-cask
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)";

brew tap caskroom/cask;
```

# Install brew apps and cask apps

```
cat cask_list | xargs brew cask install -f
cat cask_list | xargs brew cask install -f
```

# Upgrade apps
```
brew cask upgrade
```
