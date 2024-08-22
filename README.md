# ubuntu_OS


#sudo apt update

#sudo apt upgrade                     --- to install the upgrades available ( will no remove packages )
#sudo apt full-upgrade                ---  

#apt update : refreshes the list of available packages.
#apt upgrade  : installs the newest versions of the packages already installed on your system.However, it only upgrades the packages that can be upgraded without removing or installing any other packages.

apt update && apt upgrade -y
---------------------------------------------------------
To view ubuntu release version:


#lsb_release -a

root@mytestvm:~# lsb_release -a
No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 24.04 LTS
Release:	24.04
Codename:	noble

--------------------------------------------------------------


