<br/>
<p align="center">
  <h3 align="center">Search Light</h3>

  <p align="center">
    A GNOME Shell 42+ Extension
    <br/>
    <br/>
  </p>
</p>

![First Release](screenshots/Screenshot%20from%202022-11-03%2011-53-28.png)


This is a Gnome Shell extension that takes the apps search widget out of Overview. Like the macOS spotlight, or Alfred.

### Fork Status

This repository is my personal forked working version of Search Light.
I am actively building my own tweaks, quality-of-life improvements, and bug fixes on top of the original project.

### Notice

* Gnome 48 ready for testing
* Gnome 47 and prior will now be numer gnome-47 branch
* Gnome 46 port is ready for testing
* Gnome 45 port is ready for testing
* Gnome 44 and prior will be under g44 branch

### Features

* Popup search box
* Colors, background, borders customization
* Blurred background
* Multi-monitor support

## Blurred background

Blurred background feature requires **imagemagick** to be installed in the system which will generate the blurred image.

### Installation

Manual Installation: 
- Clone this repo
```bash
$ git clone https://github.com/ThorOdinson246/search-light
```
- Use the `Makefile` to build and install
```bash 
$ cd search-light
$ make
```

### Keybinding

Ctrl+Cmd+Space (change at the preference page)
Cmd - your Windows logo, or the command logo on mac. Linux also calls this the 'Super' key.

### Credits

Original project: https://github.com/icedman/search-light by icedman.
This repository builds on that work with my own fixes and tweaks.
Blur-My-Shell for background blurring code.
