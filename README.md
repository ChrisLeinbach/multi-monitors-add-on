# Multi Monitors Add-On
This fork adds support for Gnome 47 and 48 to https://github.com/lazanet/multi-monitors-add-on. (By editing the metadata file, there are no code changes.)

Fork of https://github.com/spin83/multi-monitors-add-on rewritten (almost) from scratch for gnome-shell version 46.

# Versions
- Branch [master](https://github.com/lazanet/multi-monitors-add-on/tree/master) contains extension for GNOME 45, 46, 47, and 48
- Branch [gnome-42_44](https://github.com/lazanet/multi-monitors-add-on/tree/gnome-42_44) contains extension for GNOME 42, 43, 44
- Branch [gnome-3-32_3-36](https://github.com/spin83/multi-monitors-add-on/tree/gnome-3-32_3-36) contains extension for GNOME 3.32, 3.34 and 3.36
- Branch [gnome-3-24_3-30](https://github.com/spin83/multi-monitors-add-on/tree/gnome-3-24_3-30) contains extension for GNOME 3.24, 3.26, 3.28 and 3.30
- Branch [gnome-3-20_3-22](https://github.com/spin83/multi-monitors-add-on/tree/gnome-3-20_3-22) contains extension for GNOME 3.20 and 3.22
- Branch [gnome-3-16_3-18](https://github.com/spin83/multi-monitors-add-on/tree/gnome-3-16_3-18) contains extension for GNOME 3.16 and 3.18
- Branch [gnome-3-14](https://github.com/spin83/multi-monitors-add-on/tree/gnome-3-14) contains extension for GNOME 3.14
- Branch [gnome-3-10](https://github.com/spin83/multi-monitors-add-on/tree/gnome-3-10) contains extension for GNOME 3.10

# Installation from git

```sh
# clone repo
git clone git@github.com:lazanet/multi-monitors-add-on.git
# cd into cloned repo
cd multi-monitors-add-on
# create a local shared gnome shell extensions dir
mkdir -p ~/.local/share/gnome-shell/extensions
# create a symbolic link in the extensions dir to this extension
ln -sr multi-monitors-add-on@spin83 ~/.local/share/gnome-shell/extensions
```

Restart the shell and then enable the extension.

# License

Multi Monitors Add-On extension is distributed under the terms of the
GNU General Public License, version 2 or later. See the LICENSE file for details.
