# diskimage-tools

The diskimage-tools project is a collection of convenience tools for
manipulating ISO and other disk images on FreeBSD.

The goal is to make it easier to mount, unmount, write, and in the future,
perform other common operations on disk images.

Tools currently included:

- img2dev: Write a disk image to a device, such as a USB thumb drive
- mount_image: Mount a disk image (creating a memory disk using mdconfig automatically)
- umount_image: Unmount a disk image (and release the memory disk if needed)
