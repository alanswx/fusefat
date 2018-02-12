## FuseFat

This fork of FuseFat adds -o offset=<bytes>  you can use parted, or some similar tool and get the block offset (mulitiply it by the block size) and you will be able to mount the partition inside a file.  This is not tested 100% - it is minorly tested with FAT32 and FAT16 volumes. There are a lot of places in the code where I had to add the offset, I cannot guarantee that I was able to spot all of them.


## Original Information

This is a slight fork from: https://launchpad.net/ubuntu/+source/fuse-umfuse-fat/0.1a-1.1
http://wiki.v2.cs.unibo.it/wiki/index.php?title=UMView%2BUMFUSE


The code is already experimental (but it is converging quite quickly).

write access is still buggy.

April, 07 2007
