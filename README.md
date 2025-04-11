# os-release
Here lies the /etc/os-release file from as many Linux distros as possible.
Think of it kind of like a <distrowatch.com> but defined as environment variables!

## About
`/etc/os-release` is a standard file used to identify a Linux distribution. It has become a standard file on systemd distros, but it can be found in just about every modern Linux distro.

## Use
The fields in /etc/os-release are standardized, but the values are not. For example, the only way to know that RedHat Enterprise Linux is 'rhel' or that openSUSE 15 is 'opensuse-leap' is to install each distro and check the file. This repo is a large collection of os-release files so you can do with them what you wish.

## Why?
Distro fragmentation has been a problem on Linux since the early days of Slackware, Debian, and SUSE.
Unless you only concern yourself with the big dog distros (Fedora, Debian, Ubuntu), you very quickly can become overwhelmed with the forks and clones that exist that serve basically every possible purpose one could desire from an operating system.
Hopefully this repo helps you mentally group similar distros together and identify some of the interesting ideas that some new distros on the block are bringing to the table.

## Basic Structure
Most modern Linux distributions worth using for production systems revolve primarily around the package manager(s) available and out-of-the-box tweaks for improving ease of setup.

As you poke around the os-release files, you'll notice that broad categories emerge that help simplify and classify categories of distributions
- apt-based (debian, ubuntu, mint)
- dnf-based (fedora, rhel, rocky, alma)
- pacman-based (arch, manjaro)
- gentoo

## Some other interesting distros
- containerized
  - rancher (discontinued): docker for everything
  - fedora coreos
  - ubuntu snappy
- clear
- wind river (embedded)
- declarative functional programming languages
  - nix
  - guix
