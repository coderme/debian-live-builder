# debian-live-builder
* A collection of scripts for building live-cd of Debian.

## Features
* Minimal (no GUI).
* Live Debian Stable 11 (bullseye).
* sysv is the init :)
* Handy utils included: tmux, curl, vim and more.
* Clean builds inside a docker container.


## Usage
- Clone it: `git clone https://github.com/coderme/debian-live-builder`
* Change to directory: `cd debian-live-builder`
- Optionally customize the build script: `build.live`
- **Recommended:** run the build inside a container: `./build.docker`

## Defaults
- root password: `123`
- Output iso name: `debian-live.iso`
- Built ISO may contain:
    - curl
    - fdisk
    - gdisk 
    - htop
    - iproute2
    - less
    - linux-image-generic
    - live-boot
    - man-db
    - openssh-client
    - sysvinit-core
    - tmux
    - tree
    - vim
    - zfsutils-linux

## License
* See LICENSE.


