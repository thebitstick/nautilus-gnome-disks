# nautilus-gnome-disks
Allows you to restore/write/flash a disk image to storage devices using GNOME Disks from Nautilus

## Usage
Right-click on any `.iso` or `.img` disk image and click "Flash to Storage Media". This will open GNOME Disks to restore/write/flash your image to a storage device.

## Installation
### AUR
`$ yay -S nautilus-gnome-disks-git` for [nautilus-gnome-disks-git](https://aur.archlinux.org/packages/nautilus-gnome-disks-git)
### PKGBUILD
`$ makepkg -sic`
### Other
`$ install --mode=644 nautilus-gnome-disks.py /usr/share/nautilus-python/extensions/`

OR

`$ mkdir -p ~/.local/share/nautilus-python/extensions/`

`$ cp nautilus-gnome-disks.py ~/.local/share/nautilus-python/extensions/`
