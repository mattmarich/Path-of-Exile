The included batch script is for cloning your PoE folder to RAMDisk and launching from that location

**You'll want to make sure you setup the RAMDisk using an application such as SoftPerfect RAM Disk, here's my current config:**

![alt text](http://matthewmarich.com/images/ramdisk.png "Example Ramdisk Config")

Does the following steps:
* Launches the client.exe to check for updates (close the update window of PoE once update check complete)
* Clears out RAMDisk PoE Folder if exists
* Copies PoE application folder to RAMDisk
* Removes Client.txt file from RAMDisk then symlinks to the one on disk (important for storing logs on the actual system)
* Launches 64-bit PoE application
* Launches Mercury Trade/Whatever other goodies you want to tuck in there
