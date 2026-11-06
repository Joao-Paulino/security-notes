# Linux

Short notes and commands.

## Mount a DVD or CD-ROM

mkdir -p /mnt/cdrom
mount -t iso9660 -o ro /dev/cdrom /mnt/cdrom

If the device is /dev/sr0, use that instead of /dev/cdrom.
