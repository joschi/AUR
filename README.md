# Arch Linux User Repository PKGBUILDs

Source repository for [AUR packages](https://aur.archlinux.org/packages/?SeB=m&K=joschi).

## Docker

The included `Dockerfile` is based on http://devboxes.org/base/archlinux-aur.html

### Build

    docker build -t archlinux-aur .

### Usage

    docker run -it --rm=true -v $(pwd):/AUR archlinux-aur
