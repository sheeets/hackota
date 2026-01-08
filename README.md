# hackota
Settings and configurations for my personal edit on Arch Linux.

## Omarchy Changes

### Hyprland
- configure monitors and assign main display to correct workspace
```
monitor=DP-2,2560x1440@144,0x0,1
monitor=DP-1,2560x1440@144,2560x0,1
workspace=1,monitor:DP-2
```

### QEMU
Look into congfiguration file where this can be defined
- `export LIBVIRT_DEFAULT_URI="qemu:///system"`

