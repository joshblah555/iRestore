# iRestore
A GUI wrapper for futurerestore on Windows

Futurerestore lets you restore your device to an unsigned (or signed) firmware if you have saved your shsh2 blobs. If you don't have blobs, don't attempt this.

To use, download iRestore.exe from this repository.

# Changelog

v14.0.1.0

-Graphical user interface redesign.
-URLs have been updated to download, verify and install the latest futurerestore.

v1.1.2
- Automatically checks version of latest futurerestore and installed version to decide whether to update or not
- Downloads futurerestore directly from s0uthwest's github to avoid license issues
- Added progress bar for download

v1.1.0
- Added option for no baseband and build manifest
- Downloads futurerestore on run

v1.0.0
- Initial release

# This uses marijuanARM's version of futurerestore

It can be found at https://github.com/marijuanARM/futurerestore

# Instructions:

A few things to consider prior to use:
- If you're on iOS 14.4 with A12 or higher, you cannot downgrade.
- You cannot get back to 13.x with this.
- It will not supply freshly baked cookies. Buy your own.
- Please don't modify/change it without asking first. 

To use iRestore, simply click on the program to launch.

- First, choose the IPSW. This is the firmware you wish to restore to.
- Second, select the blob. This is the .shsh2 file you saved for your device.
- Third, you may choose the SEP file (im4p). If you're confused about which files which, click the "Use Latest SEP" box.
- Fourth, you may choose the baseband file (bbfw). If you're confused about which files which, click the "Use Latest Baseband" box.
- Fifth, select the BuildManifest.plist file. This is located inside the IPSW of the latest firmware. If you have "Use Latest ... " selected, this is not necessary.
- Sixth, be sure you set the nonce on your jailbroken device! 
- Seventh, click Restore!

Any issues? Please report them. 


