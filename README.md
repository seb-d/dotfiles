# Dotfiles

Personal dotfiles and a script for simplify new install.


## Installation

Clone this repository in your home directory

```console
$ cd ~
$ git clone https://github.com/seb-d/dotfiles.git
$ source /path/to/.dotfiles/install.sh
```


## Automatic config

- Essential packages install (require root)
- Terminal configuration
- Emacs/Spacemacs configuration
- Git configuration


## Manual config

- Set terminal color to solarized dark (text, background and palette)
- Install Alternatetab and Workspace matrix gnome-shell-extension
- Remove gnome-shell-extension-ubuntu-dock


## Switch around all windows in all workspaces

Set Alt+Tab shortcut to Switch windows (not Switch applications) then set:

```console
$ gsettings set org.gnome.shell.window-switcher current-workspace-only false
```
