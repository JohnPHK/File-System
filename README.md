# File-System
File system created using C. This file system is newly designed from the memory only able to store binary bits. 

The file system is consisting of superblocks which stores meta data of file system, inode bitmap and data bitmap which are used to direct the system to the correct data blocks, and yes data blocks which store the data in binary bits.

It is able to replicate all the linux commands, the examples are in below.

![](https://github.com/JohnPHK/File-System/blob/main/filesystem1.png)

![](https://github.com/JohnPHK/File-System/blob/main/filesystem2.png)

The above are what is produced from running runit.sh file. As one can see, using this file system, one can perform commands such as mkdir, touch, cd, ls, etc... as if one is in a new linux system
