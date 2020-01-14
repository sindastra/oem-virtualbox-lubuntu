# VirtualBox Lubuntu LTS (HWE) Image - Ready to use

#### Kernel:

    Linux VirtualBox 5.0.0-37-generic #40~18.04.1-Ubuntu SMP Thu Nov 14 12:06:39 UTC 2019 x86_64 x86_64 x86_64 GNU/Linux

#### Release:

    Distributor ID:	Ubuntu
    Description:	Ubuntu 18.04.3 LTS
    Release:	18.04
    Codename:	bionic
    
#### VirtualBox Guest Additions installed:

6.1.0

#### Tested on:

6.1.0 r135406

#### Creation Date:

2020-01-14 21:03 UTC

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