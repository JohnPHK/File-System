# File-System
File system created using C. This file system is newly designed from the memory only able to store binary bits. 

The file system is consisting of superblocks which stores meta data of file system, inode bitmap and data bitmap which are used to direct the system to the correct data blocks. The data blocks are the actual data of files used to run program.

It is able to replicate all the linux commands, the examples are in below.

<img src="https://github.com/JohnPHK/File-System/blob/main/filesystem1.png" width=300 height=500>

<img src="https://github.com/JohnPHK/File-System/blob/main/filesystem2.png" width=300 heigh=500>

The above are what is produced from running runit.sh file. As one can see, using this file system, one can perform commands such as mkdir, touch, cd, ls, etc... as if one is in a new linux system
