[![Issues](https://img.shields.io/github/issues/Airblader/unclutter-xfixes.svg)](https://github.com/Airblader/unclutter-xfixes/issues)
[![Forks](https://img.shields.io/github/forks/Airblader/unclutter-xfixes.svg)](https://github.com/Airblader/unclutter-xfixes/network)
[![Stars](https://img.shields.io/github/stars/Airblader/unclutter-xfixes.svg)](https://github.com/Airblader/unclutter-xfixes/stargazers)

# unclutter-xfixes

## About

This is a rewrite of the popular tool unclutter, but using the x11-xfixes extension. This means that this rewrite doesn't use fake windows or pointer grabbing and hence causes less problems with window managers and/or applications.

## Installation

### Arch / Manjaro (AUR)

unclutter-xfixes is available in the AUR as [unclutter-xfixes-git](https://aur.archlinux.org/packages/unclutter-xfixes-git/).

### Manual

unclutter-xfixes is make-based. Hence, you can clone the git repository and compile and install it via

```
git clone https://github.com/Airblader/unclutter-xfixes
cd unclutter-xfixes
make
sudo make install
```

## Usage

See `man unclutter` after installation.
