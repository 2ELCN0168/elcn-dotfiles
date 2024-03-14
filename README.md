![screenshot](./readme_images/capture_01.png)

# elcn's dotfiles

> [!WARNING]
> Don't blindly use my settings unless you know what you are doing, these could break your setup. Use at your own risk!

# How to install :

Actually, there's no way to install my files automatically, you will need to do it manually.

```bash
git clone https://github.com/2ELCN0168/elcn-dotfiles
cd elcn-dotfiles/.config
```
From here, choose the files you want and copy them to your `$HOME/.config` directory. Make sure to backup YOUR files before doing that, they could be erased by mine!

You can use these command to copy  :

```bash 
cp -a $HOME/elcn-dotfiles/.config/[the directory you want] $HOME/.config/
```

This will get the directory you want and copy it to your `.config` directory. Make sure to rename your own directory or select only the files you want.

> [!WARNING]
> This is a work-in-progress repository, your apps may look weird/vanilla/unfinished by installing my files. Don't be surprised and stay up-to-date.

## Apps needed :

### Bootloader :
- Refind.

***

### Fonts :
- [Nerd Fonts ;](github.com/ryanoasis/nerd-fonts)
- [Terminus ;](terminus-font.sourceforge.net)
- [Noto Fonts Emoji](github.com/googlefonts/noto-emoji)

***

### Firewall:
- [iptables ;]()
- [firewalld ;]()

***

### Audio:
- [alsa-utils ;]()
- [pulseaudio ;]()
- [pulseaudio-bluetooth ;]()
 
***

### Bluetooth:
- [bluez ;]()
- [bluez-utils ;]()
- [bluez-tools ;]()

***

### Display Manager :
- [Sddm ;]()

***

### Window manager :
- Hyprland ;
- Hyprpaper ;

***

### Lockscreen :
- [Swaylock ;](github.com/mortie/swaylock-effects)

***

### Notifications:
- [swaync ;]()

***

### Status Bar :
- Waybar ;
- wlogout ;
- pavucontrol ;
- [eww ;]()

***

### Terminal Emulator :
- Kitty ;
- [Tmux ;]()

***

### File Manager :
- Thunar ;
    - thunar-volman + gvfs (for automounting removable media)
- [xdg-user-dirs ;]()

***

### Terminal File Manager :
- Ranger ;
- nnn (optional) ;

***

### Application launcher :
- Wofi ;
- Rofi (choose one between those two) ;

***

### Text Editor : 
- Vim ;
- Neovim ;
- Nano ;

***

### Help:
- [man-{db,info} ;]()
- [texinfo ;]()
- [tldr ;]()

***

### Servers:
- [Mosh ;]()
- [Open SSH ;]()
- [Cups ;]()

***

### Shell :
- Zsh ;
- Bash ;
- [Fish ;](github.com/fish-shell/fish-shell)

***

#### Zsh Plugins :
- [zsh-syntax-highlighting ;](github.com/zsh-users/zsh-syntax-highlighting)
- [zsh-autosuggestions ;](github.com/zsh-users/zsh-autosuggestions)
- [zsh-history-substring-search ;]()
- [zsh-completions ;]()

- [powerlevel10k ;](github.com/romkatv/powerlevel10k) (prompt)

***

### Various Term Apps (Optional) :
- [Pokeget-rs ;](github.com/talwat/pokeget-rs)

- [Neofetch ;](github.com/dylanaraps/neofetch)
- [Nitch ;](github.com/ssleert/nitch)
- [Rxfetch ;](github.com/Mangeshrex/rxfetch)

- [ncmatrix ;](github.com/EnronEvolved/NCMatrix)
- [no-more-secrets ;]()

- [bat ;]()
- [colorls ;]()
- [tree ;]()

***

### Programming langages:
- [Python ;]()
- [Rust ;]()

***

### Monitoring:
- [htop ;]()
- [btop ;]()

***

### Web Browsers:
- [Brave ;]()

***

### Media players:
- [VLC ;]()
- [Elisa (music) ;]()

***

### Images Viewers:
- [Oculante ;]()
- [imv ;]()
- [swayimg ;]()

***

### PDF Viewers:
- [Zathura ;]()

***

### Passwords Manager:
- [KeepassXC ;]()

***

> [!WARNING]
> Distribution Specific Packages :

<details>

<summary>Archlinux :</summary>

- AUR Helper :
    - [Paru ;](github.com/Morganamilo/paru)

</details>

***

## Coming soon :

- [ ] A script to automate the installation of the files ;
- [ ] A script to automate the installation of these packages depending on the distribution used ;

## FAQ :

Q : Hey, what are these files?

A : These files are commonly called "dotfiles", they are used to customize the applications you want. Most of the applications you download will get their config files to the `/etc` directory, but if there's a personnal configuration in `$HOME/.config`, it will look there first.

Q : How can I be sure this won't fuck up my system?

A : Just look by yourself. I looked around a lot to try others config files, and some of them, scripts especially broke up my system. By publishing my dotfiles, I try to make a clean repository with an explicit list of what is required for it to work properly. I don't want you to trust me blindly, but all I can tell you is to check everything by yourself.

Q : This file is not working/looks weird

A : Maybe, it's a work in progress, don't be surprised.

Q : Who are you?

A : ~~Luke Skywalker~~ I'm a system administrator student. The stuff I publish on GitHub is here to make it more easy for me when I install a new system somewhere.

Q : Is it possible to contribute to your projects?

A : It depends, it wasn't in the plan but you can always contact me to discuss about that.

Q : When will \[insert a file name\] will be updated? 

A : I'm working a lot and have not that much of a free time, but I know what should be done and I'll do it... Someday. 

