
Disk Usage and Management
____________________________



Disk Usage Commands
Check Disk Space Usage
______________________________________________________
Command: df

Usage: df -h

Explanation: Shows disk space usage for all mounted filesystems in a human-readable format (e.g., GB, MB).

Example:



df -h
Output:

Filesystem      Size  Used Avail Use% Mounted on
/dev/sda1       50G   20G   28G  42% /
_________________________________________________________________________________________________

Check Disk Usage of a Directory

Command: du

Usage: du -sh /path/to/directory

Explanation: Shows the disk usage of a specific directory in a human-readable format.

Example:

du -sh /var/log
Output:

1.2G    /var/log
_______________________________________________________________________________________________

Check Free Disk Space

Command: df

Usage: df -h

Explanation: Displays available disk space on all mounted filesystems.

Example:

df -h
Output:

Filesystem      Size  Used Avail Use% Mounted on
/dev/sda1       50G   20G   28G  42% /
================================================================================================

Check Disk Usage of Individual Files

Command: du

Usage: du -h filename

Explanation: Shows the disk usage of a specific file.

Example:

du -h example.txt
Output:
mathematica

12K example.txt
Disk Management Commands
===================================================================================

List Disk Partitions

Command: lsblk

Usage: lsblk

Explanation: Lists all block devices and their partitions.

Example:

lsblk
Output:
graphql

NAME   MAJ:MIN RM  SIZE RO TYPE MOUNTPOINT
sda      8:0    0   50G  0 disk
├─sda1   8:1    0   40G  0 part /
└─sda2   8:2    0   10G  0 part [SWAP]

---------------------------------------------------------------------------------------------
Check Disk Health

Command: smartctl

Usage: sudo smartctl -a /dev/sda

Explanation: Displays detailed SMART (Self-Monitoring, Analysis, 
and Reporting Technology) information about a disk.

Example:

sudo smartctl -a /dev/sda
Create a New Partition

Command: fdisk

Usage: sudo fdisk /dev/sda

Explanation: Opens the fdisk utility to manage disk partitions on /dev/sda.

Example:

sudo fdisk /dev/sda
Follow the interactive prompts to create, delete, or modify partitions.

Format a Partition

Command: mkfs

Usage: sudo mkfs -t ext4 /dev/sda1

Explanation: Formats a partition (/dev/sda1) with the specified filesystem type (e.g., ext4).

Example:



sudo mkfs -t ext4 /dev/sda1
Mount a Filesystem

Command: mount

Usage: sudo mount /dev/sda1 /mnt

Explanation: Mounts a filesystem from a partition (/dev/sda1) to a directory (/mnt).

Example:



sudo mount /dev/sda1 /mnt
Unmount a Filesystem

Command: umount

Usage: sudo umount /mnt

Explanation: Unmounts the filesystem mounted at /mnt.

Example:

sudo umount /mnt
These commands help you manage and monitor disk usage, partitions, 
and filesystems in Linux.
