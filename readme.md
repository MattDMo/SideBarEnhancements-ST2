# SideBarEnhancements-ST2

This is my repo of the last version of SideBarEnhancements to be released for Sublime Text 2. I strongly urge you to upgrade to [ST3](https://sublimetext.com/3 "Sublime Text 3") if at all possible and use [this version](https://packagecontrol.io/packages/SideBarEnhancements) of the plugin. However, if you still need to stay with ST2 for whatever reason, this repo is here for you.

## Important Note

I do not plan on maintaining this package. If you absolutely *must* file an issue or a PR, go right ahead (I'm not disabling them), but don't feel bad if I ignore you.

## Installation

For now the only way to install it is manually. There are two ways to do this: by downloading an archive, or via git. Both methods require you know where your `Packages` folder is:

* Windows Regular Install: `%APPDATA%\Sublime Text 2\Packages`
* Windows Portable Install: `InstallationFolder\Sublime Text 2\Data\Packages`
* OS X: `~/Library/Application Support/Sublime Text 2/Packages`
* Linux: `~/.config/sublime-text-2/Packages`

The menu item **`Preferences → Browse Packages…`** will open the `Packages` folder in your operating system's file manager application (Windows Explorer, Finder, Nautilus, etc.).

### Archive

Download the [`zip` file](https://github.com/MattDMo/SideBarEnhancements-ST2/archive/master.zip) or [`tar.gz` file](https://github.com/MattDMo/SideBarEnhancements-ST2/archive/master.tar.gz). Go the the `Packages` folder and unzip/untar.gz the archive there. It'll create a `SideBarEnhancements-ST2` folder. Rename it to `SideBarEnhancements`. Completely restart Sublime and you're all set.

### Git

Go to the `Packages` folder in the command line and run

    git clone https://github.com/MattDMo/SideBarEnhancements-ST2.git SideBarEnhancements

to create a `SideBarEnhancements` folder. Completely restart Sublime and you're all set.

## Usage

The right-click menu is only operational on files contained within [project](http://docs.sublimetext.info/en/latest/file_management/file_management.html#projects) folders. Read [this](https://github.com/titoBouzout/SideBarEnhancements#readme) to get an idea of what SideBarEnhancements for ST3 does; then check the [changelog](https://github.com/titoBouzout/SideBarEnhancements#change-log) from version 1.2 to see what fixes *haven't* been applied to this version. Basically, just right-click on a file or folder in a project, look at what's in all the sub-menus, and see what they do. It's not rocket science, people.

# License

Copyright (C) 2012 Tito Bouzout <tito.bouzout@gmail.com>

This license apply to all the files inside this program unless noted
different for some files or portions of code inside these files.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation. http://www.gnu.org/licenses/gpl.html

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see http://www.gnu.org/licenses/gpl.html

---

Just in case it's not clear: ***I didn't write any of this. This is all Tito Bouzout's work, and all credit goes to him. This repo is simply a mirror of his code provided for the public good.***
