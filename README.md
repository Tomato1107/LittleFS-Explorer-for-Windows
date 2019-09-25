# LittleFS-Windows-Explorer

This is still under construction. Should be finished soon.

LittleFS is a fail-safe file system designed for microcontrollers: https://github.com/ARMmbed/littlefs

The only disadvantage with LittleFS is that one can't edit the file system in Windows. There is a FUSE driver for Linux, but I'm developing under Windows, so I needed an interface from where I could format the SD card to LittleFS, browse, edit, add and remove files. So I decided to write a file explorer for LittleFS in Windows.  

![GitHub Logo](/images/ExplorerWAbout.jpg)

## Features
* Automatically detects, mount and unmount LFS formatted disks.
* Format any accessible disk to LFS.
* Define custom LFS configuration parameters when formatting a disk.
* Browse folders.
* Drag and drop, single or multiple, files and folders from Windows explorer to LFSE.
* Create new folders.
* Rename and delete files and folders.
* View and edit files with the default associated Windows program.
* View and edit files with a specific Windows program.
* Grid view or detail view (file size).

## Pending features
* Migrate from a previous version of LFS (LFS_MIGRATE). 
* Drag and drop, single or multiple, files and folders from LFSE to Windows explorer. 
* Folder and file search.
* Cut, copy and paste folders and files inside LFSE.

## User guide and more
https://bluscape.blog
