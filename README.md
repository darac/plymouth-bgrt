
# plymouth-bgrt theme

A theme for plymouth which uses your system's UEFI logo (aka BGRT).

## DEPRECATION WARNING

Note: Many Linux Distributions are now shipping a `bgrt` theme which uses the `two-step` module. This module is able to read the BGRT image at run-time and is better supported than this script. Consider switching to `bgrt` instead of `plymouth-bgrt`.

## Installation

```sh
    sudo ./install.sh	# Fetches your BGRT, adjusts the theme to suit and installs it.
    sudo plymouth-set-default-theme -R plymouth-bgrt
```

## GRUB Theme

You may also want to pair this with my [GRUB theme](https://github.com/darac/grub-bgrt).

## License

All the files in this project are distributed under the [GNU General Public License](./LICENSE).

## Author

Paul Saunders
