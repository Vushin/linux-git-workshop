# How to install Linux

Linux can be installed in a variety of ways, but it almost always starts with downloading the distribution's install ISO. Here are the links to a few common distros:

* Ubuntu: <https://ubuntu.com/download/desktop>
* Debian: <https://www.debian.org/distrib/>
* Kali Linux: <https://www.kali.org/get-kali>
* Linux Mint: <https://www.linuxmint.com/download.php>
* Fedora: <https://fedoraproject.org/workstation/>

## Installing on a Physical Machine

Once you have downloaded the ISO, use a USB flashing program (any of the below) to write the ISO to a USB drive.
* Window: [Rufus](https://rufus.ie/en/)
* MacOS / Linux:
    * [Balena Etcher](https://etcher.balena.io/)
    * The `dd` command command for experienced users
* Linux:
    * [Popsicle](https://github.com/pop-os/popsicle)
    * [KDE ISO Image Writer](https://apps.kde.org/isoimagewriter/)

Once the USB drive is written, boot the machine from the USB drive (using a BIOS or UEFI boot menu) and follow the instructions provided by the distro's installer.

## Installing on a Virtual Machine

Setting up a virtual machine is a great way to play with and learn Linux without having to install it on a physical machine. We recommend using [Oracle VirtualBox](https://www.virtualbox.org/) for this purpose since it's free and open source. You can download it here: <https://www.virtualbox.org/wiki/Downloads>.

To setup a linux Virtual Machine (VM), follow this guide: <https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview>. It's written for Ubuntu, but the steps for booting from the ISO image should be almost identical for other distros.