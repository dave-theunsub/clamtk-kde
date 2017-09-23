This readme file was last updated 23 Sept 2017

# README for clamtk-kde

clamtk-kde is a simple plugin to allow a right-click,
context menu scan of files or folders in Dolphin,
a file manager in KDE.

All this plugin does is copy a desktop file to a
directory.  If this seems redundant, that's because it is:
this plugin depends on clamtk, which already has this directory
file. So, it stands to reason we should be able to just find that
file and copy it, rather than having our own copy.

## Installation

### Automatic installation

There are deb and rpm packages to install this plugin:

#### On Debian based systems (Ubuntu etc)

`sudo apt-get install clamtk-kde`

or, if you've already downloaded it:

`sudo dpkg -i clamtk-kde`

#### On CentOS systems

`yum install clamtk-kde-0.18-1.fc.noarch.rpm`

#### On Fedora systems

`dnf install clamtk-kde-0.18-1.fc.noarch.rpm`

### Manual installation

To manually install it:
Ensure ClamTk is installed. You'll need version 4.00 or newer,
but you should run at least the 5.xx series by now.

Copy the clamtk-kde.desktop file to the services folder. For example:  
For KDE 4:  
`cp clamtk-kde.desktop /usr/share/kde4/services/`  
For KDE 5:  
`cp clamtk-kde.desktop /usr/share/kservices5/ServiceMenus/`  
You will need to have root privileges for that step.  

DEPENDENCIES
------------

clamtk >= 5.00
(KDE4) kde-filesystem or (KDE5) kf5-filesystem

LINKS
-----

https://github.com/dave-theunsub/clamtk/
https://bitbucket.org/davem_/clamtk-kde/
http://dolphin.kde.org
http://standards.freedesktop.org/desktop-entry-spec/latest/

CONTACT
-------

email : Dave M, dave.nerd @ gmail.com
0x6ADA59DE
