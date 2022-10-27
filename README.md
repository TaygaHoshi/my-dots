# my-dots
Configuration files I use. This will be updated as I improve things. Also, feel free to contribute.

This repository is a part of the "Configurations" wiki page project on [my website](https://wiki.tyghsh.net/configs).

## Using
Clone in your home directory:
```bash
cd ~
git clone https://github.com/TaygaHoshi/my-dots.git
```

## Updating
Pull the github repository:
```bash
cd ~/my-dots
git pull
```

## bashrc_extend
Add the following line at the end of your ~/.bashrc:
```bash
source "$HOME/my-dots/bashrc_extend"
```

The file "bashrc_extend" is configured for the APT package manager. You should change it depending on your distro. Also, you can append the string below to the "updt" alias if you have flatpak and snaps.
```bash
"&& snap refresh && flatpak update"
```
