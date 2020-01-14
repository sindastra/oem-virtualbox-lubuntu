# VirtualBox Lubuntu LTS (HWE) Image - Ready to use

I created this to have easy, ready to use images for myself when I quickly need a disposable Linux Desktop VM.

I decided to share this in the hope that it will be useful.

# Getting the images:

Since GitHub does now allow files in releases bigger than 2 GB, the releases in the releases page will link to an external site where to obtain the images from. To quickly check the file was not corrupted during transfer I provide a SHA256 file. For security I provide a signature file for both the SHA256 file and the image file itself. You can get my public key from https://keybase.io/sindastra where you can also obtain "proof".

## Image info:

#### Kernel:

    Linux VirtualBox 5.0.0-37-generic #40~18.04.1-Ubuntu SMP Thu Nov 14 12:06:39 UTC 2019 x86_64 x86_64 x86_64 GNU/Linux

#### Release:

    Distributor ID:	Ubuntu
    Description:	Ubuntu 18.04.3 LTS
    Release:	18.04
    Codename:	bionic
    
#### VirtualBox Guest Additions installed:

 - 6.1.0

#### Tested on:

 - 6.1.0 r135406

#### Creation Date:

 - 2020-01-14 21:03 UTC

#### Fully updated before packing:

- Yes.

#### Commands:

```
    1  sudo ufw enable
    2  sudo systemctl disable apport
    3  sudo systemctl disable apport-autoreport.path 
    4  sudo nano /etc/default/apport 
    5  sudo apt update
    6  sudo apt install dkms
    7  sudo apt upgrade
    8  sudo apt update
    9  cd /media/oem/VBox_GAs_6.1.0/
   10  ls
   11  sudo ./VBoxLinuxAdditions.run 
   12  sudo /sbin/rcvboxadd quicksetup all
   13  sudo history
   14  history
   15  sudo apt autoremove --purge
   16  sudo apt clean
   17  history
   18  uname
   19  uname -a
   20  lsb_release -a
   21  history
   22  sudo oem-config-prepare 
   23  history
```
