### 1. Update and upgrade
```
sudo apt update && sudo apt upgrade
```

### 2. Install stuff

##### i. Libraries etc.
```
sudo apt install ubuntu-restricted-extras gnome-tweaks vlc gdebi default-jre nomacs htop git
```

##### ii. Dash to Panel

1. [Install from webpage](https://extensions.gnome.org/extension/1160/dash-to-panel/)
2. Right click 'Show Applications' -> 'Dash to Panel #Settings' -> 'About' -> 'Import from file'
3. Import [dash_to_panel_settings](./dash_to_panel_settings)

##### iii. [Sublime Text](https://www.sublimetext.com/docs/3/linux_repositories.html)

### 3. Add 'New empty file' option to right-click menu
```
touch ~/Templates/empty
```

### 4. Set keyboard hortcuts

1. Settings -> Keyboard Shortcuts -> Navigation
2. Set Move to workspace above, Move to workspace below, Switch windows

### 5. Set git username and email
```
git config --global user.email "shivam.bansal@live.com"
git config --global user.name "ratherlongname"
```
