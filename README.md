# fzfOS - Spotlight for the terminal but with fzf

Spotlight for the terminal, but better...

##Current Features:
- App launching/switching
- Chrome tab switching
- Music searching (spotify, itunes, windows media player?)
- Filesystem find files/directories

##Desired Features:
- Open window switching? ie. fuzzy find open word docs, virtualbox VMs etc
- Browser tab switching (chrome, firefox, safari, IE)

## Install
- Clone repo
- source it in your .bashrc

```
source ~/fzfOS/fzfOS.sh
```

##Usage
Run the switcher command (shortened to "s"):
```
$ s

# Then Select a launcher type by typing a, c, o, p
# Now fuzzy find whatever you want...
```

##iTerm Hotkey window
Works quite well with iTerm2's Hotkey window feature: https://www.iterm2.com/features.html#hotkey-window

First enable the Hotkey window feature in the preferences:
![screenshot](iterm-prefs1.png)

Then set the startup command to run the switcher:
![screenshot](iterm-prefs2.png)


## TODO:
- Explain how the spotify choosing works... (it's crap)
- Add a gif of usage
