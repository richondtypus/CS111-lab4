# Hey! I'm Filing Here

In this lab, I successfully implemented a 1 MiB ext2 file system with 2 directories, 1 regular file, and 1 symbolic link.

## Building
To build the program simply run,
```
make
```
## Running
To compile, run:
```
./ext2-create
```
To mount, run:
```
mkdir mnt sudo mount -o loop cs111-base.img mnt
```

## Cleaning up
To unmount the filesystem, run:
```
sudo unmount
```
To delete the directory used for mounting, run:
```
rmdir mnt
```
To clean up, run:
```
make clean
```


