# GNU Hello - Custom Debian Package

This repository contains a customized version of the GNU `hello` software, 
packaged for Debian-based systems (Ubuntu). 
This project demonstrates the complete workflow of packaging, signing, 
and distributing software via a Personal Package Archive (PPA).

## Features
- **Customized Build:** Based on GNU `hello` 2.10.
- **Custom Script:** Includes an additional `testing.sh` script installed in `/usr/bin/`.
- **Automated Packaging:** Configured with custom `debian/` rules and post-installation hook.
- **PPA Distribution:** Fully functional PPA for automatic updates and installatin.

## PPA Installation
You can install this package directly from my personal repository:

## PPA pkg Link:
https://launchpad.net/~valeriog95/+archive/ubuntu/hello-ppa

```bash
# Add the PPA
sudo add-apt-repository ppa:valeriog95/hello-ppa

# Update your package list
sudo apt update

# Install the package
sudo apt install hello
