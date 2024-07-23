# The Dots

This repo contains the dots to my current Arch system so that if I have to (once again) reinstall it for some reason, I don't have to configure everything from scratch.

## Requirements
You'll need these things: 

### Git

```
sudo pacman -S git
```

### Stow
```
sudo pacman -S stow
```

## Installation

First, you gotta clone the repository.

```
git clone git@github.com:sma918/dotfiles.git
cd dotfiles
```

Then you need to use stow to create the symlinks for the files.

```
stow .
```

## Additional Info
If you need some extra info on how to use stow and all of that stuff, watch this video again: [GNU Stow Video](https://www.youtube.com/watch?v=y6XCebnB9gs)
