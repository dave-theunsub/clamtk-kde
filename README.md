# README for clamtk-kde

This README was last updated 20240128.

clamtk-kde adds a context menu item to allow for the ability to right-click
on a file or folder from within the Konqueror or Dolphin browsers
to easily scan the selected item for threats.

All this plugin does is copy a desktop file to a directory. This makes it
easy to scan a file or folder, without opening the virus scanner first and
navigating to the file or folder of interest.

## Installation

First, download clamtk-kde from its [Github](https://github.com/dave-theunsub/clamtk-kde) or [Gitlab](https://gitlab.com/dave_m/clamtk-kde) home.  RPM-based systems like Fedora, RedHat, CentOS, Alma, or Rocky (and others) will use an RPM (.rpm).  DEB-based systems like Debian or Ubuntu will use a DEB (.deb).

### Option A: Double-click to install

This is the easiest and recommended way.  Installing this way allows the system package manager to take care of installation details.

### Option B: Commandline install from downloaded package

#### On Ubuntu systems

`sudo dpkg -i clamtk-kde_0.21-1_all.deb`

#### On CentOS systems

`yum install clamtk-kde-0.21-1.el9.noarch.rpm`

or

`dnf install clamtk-kde-0.21-1.el9.noarch.rpm`

#### On Fedora systems

`dnf install clamtk-kde-0.21-1.fc39.noarch.rpm`

### Option C: Manual installation

To manually install it:  

Ensure ClamTk is installed. You will need to have root privileges for this step. Youwill need version 5.00 or newer, but you should use the 6.xx series by now.

1. Download the [.tar.xz](https://github.com/dave-theunsub/clamtk-kde/releases) file
2. Extract the contents:  
`tar xf clamtk-kde-0.21.tar.xz`
3. Change to the newly created directory:  
`cd clamtk-kde-0.21`
4. Copy the clamtk-kde.desktop file to the services folder. For example:  

For KDE 4:  
`cp clamtk-kde.desktop /usr/share/kde4/services/`  
For KDE 5:  
`cp clamtk-kde.desktop /usr/share/kservices5/ServiceMenus/`  

DEPENDENCIES

clamtk >= 5.00 (but you should be using >= 6.00)  
(KDE 4) kde-filesystem or (KDE 5) kf5-filesystem  

LINKS

[Github clamtk-kde](https://github.com/dave-theunsub/clamtk-kde)  
[Gitlab clamtk-kde](https://gitlab.com/dave_m/clamtk-kde)  
[KDE Dolphin page](http://dolphin.kde.org)  
[Desktop entry spec documentation](http://standards.freedesktop.org/desktop-entry-spec/latest/)  

CONTACT

Dave M, dave.nerd @gmail.com  
  [0xC81DF0FAC4AFEB22](https://davem.fedorapeople.org/RPM-GPG-KEY-DaveM-20230506)
