# lnch
Simple stupid application launcher. Not pretty, but mostly works in my cases.


## Licence
This software is distributed under `Do What The Fuck You Want To` licence.


## Demo

![](https://raw.githubusercontent.com/m3xan1k/lnch/master/assets/lnch.gif)


## Usage
It's designed to run in a "popup" terminal, alacritty, st, gnome-terminal or whatever you use.

Firstly create symlink or move lnch to your `$PATH`, f.e. `~/.local/bin` OR run `make install`.

Then I just bind new system-wide shortcut to something like this.

```
alacritty \
  -o "window.decorations=none" \
  -o "window.position.x=540" \
  -o "window.position.y=320" \
  -o "window.dimensions.columns=60" \
  -o "window.dimensions.lines=10" \
  -e lnch
```
