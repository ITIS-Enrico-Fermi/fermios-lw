# FermiOS Lightweight

## Specifications

### Notifications manager
[Herbe](https://github.com/dudik/herbe)

### Terminal emulator
[urxvt](https://linux.die.net/man/1/urxvt)

Shortcuts:
- Alt+c --> copy text
- Alt+p --> paste text
- Alt-s --> search inside the terminal. Hit _n_ to go ahead

### Shell
[zsh](https://www.zsh.org/)

### Text editor
[vim](https://www.vim.org/)

### File manager
[lf](https://github.com/gokcehan/lf)

### Launcher
[dmenu](https://tools.suckless.org/dmenu/)

### File transfer
[qrpc](https://github.com/claudiodangelis/qrcp)

### Widget toolkit
[gtk](https://www.gtk.org/)

Theme: [akwa-dark](https://github.com/berkiyo/akwa)

Icons: [adwaita](https://gitlab.gnome.org/GNOME/gtk/tree/master/gtk/theme/Adwaita)

Fonts:
- [Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed) for GUI's text
- [Tamsyn](http://www.fial.com/~scott/tamsyn-font/) for terminal

### Tiling window manager
[i3-gaps](https://github.com/Airblader/i3)

[picom](https://github.com/yshui/picom/tree/master)

### Power management
[powertop](https://01.org/powertop/)

[tlp](https://github.com/linrunner/TLP)

[cpufreq](https://github.com/konkor/cpufreq)

### Bootloader
[grub](https://www.gnu.org/software/grub/)

### Display manger
[lightdm](https://github.com/canonical/lightdm)

Default user: _fermios-user_
Password: _fermi_

Root user: _root_
Password: _fermi_

### Keymap
`setxkbmap it`

### Color palette
[Nord](https://www.nordtheme.com/)

## Drivers

### Broadcom WiFi BCM43xx
Drivers installed using official [Void guide](https://wiki.voidlinux.org/Macbook).
In order to connect to WiFi you may want to use [Connman](https://wiki.archlinux.org/index.php/ConnMan#Wi-Fi)
Automated configuration using scripts will be soon provided.

## Toolset
FermiOS is shipped with a pre-installed set of tools extremely useful for ICT students, along with 3 VMs (KVM virtualization).
These VMs are carefully configured so that they take up a minimal amount of memory and other resources.

- Nmap
- sshd
- pio-cli
- miniterm

## References
- https://docs.voidlinux.org/
- https://wiki.voidlinux.org/Post_Installation
- https://wiki.archlinux.org/index.php/LightDM
- https://wiki.archlinux.org/index.php/rxvt-unicode
