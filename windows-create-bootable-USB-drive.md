# How to make an bootable USB drive

- Copy all the files that is inside the `usbXXXXXX.zip` or on the CD onto an usb drive, directly on the drive, not inside any directory/folder.
- It is OK if there are other files on the USB drive from before, they will not be removed.
- Install bootloader on the USB drive, from command prompt in windows (start the command line with "run as administrator" if possible)
`X:syslinux.exe -ma X`:
    - Replace X: with the drive letter the USB drive shows up as (DO NOT USE C:)
- If it seems like nothing happened, it is usually done.
- A file named `ldlinux.sys` may appear on the USB drive, that is normal.
- The drive should now be bootable.
- Please know that getting some computers to boot from USB is worse than from CD, you may have to change settings, or some will not simply work at all.
