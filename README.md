This README was last updated 20240102.

# README for clamtk-kde

clamtk-kde is a simple plugin to allow a right-click, context menu scan of files or folders in Dolphin, a file manager in KDE.

All this plugin does is copy a desktop file to a directory. This makes it easy to scan a file or folder, without opening the virus scanner first and navigating to the file or folder of interest.

## Installation

### Automatic installation

There are deb and rpm packages to install this plugin:

#### On Ubuntu systems

`sudo dpkg -i clamtk-kde_0.20-1_all.deb`

#### On CentOS systems

`yum install clamtk-kde-0.20-1.el9.noarch.rpm`

or

`dnf install clamtk-kde-0.20-1.el9.noarch.rpm`

#### On Fedora systems

`dnf install clamtk-kde-0.20-1.fc39.noarch.rpm`

### Manual installation

To manually install it:  

Ensure ClamTk is installed. You will need to have root privileges for this step. Youwill need version 5.00 or newer, but you should use the 6.xx series by now.

Copy the clamtk-kde.desktop file to the services folder. For example:  
For KDE 4:  
`cp clamtk-kde.desktop /usr/share/kde4/services/`  
For KDE 5:  
`cp clamtk-kde.desktop /usr/share/kservices5/ServiceMenus/`  

DEPENDENCIES
------------

clamtk >= 5.00 (but you should be using >= 6.00)  
(KDE 4) kde-filesystem or (KDE 5) kf5-filesystem  

LINKS
-----

https://github.com/dave-theunsub/clamtk-kde
https://gitlab.com/dave_m/clamtk-kde  
http://dolphin.kde.org  
http://standards.freedesktop.org/desktop-entry-spec/latest/  

CONTACT
-------
Dave M, dave.nerd @gmail.com  
  [0xC81DF0FAC4AFEB22](https://davem.fedorapeople.org/RPM-GPG-KEY-DaveM-20230506)
