# **ROOT DIRECTORY INFO**

Here's a brief overview of each directory listed in the Linux root (`/`) filesystem:

| **Directory**     | **Description**                                                                         |
| ----------------- | --------------------------------------------------------------------------------------- |
| `/bin`            | Essential binary executables (e.g., basic commands like `ls`, `cp`). Used by all users. |
| `/boot`           | Contains bootloader files (e.g., GRUB) and the Linux kernel (`vmlinuz`).                |
| `/dev`            | Device files for hardware components (e.g., `/dev/sda`, `/dev/null`).                   |
| `/dist`           | Not standard; might be used by you or Kali to store distributions or custom files.      |
| `/etc`            | Configuration files for system-wide settings and services.                              |
| `/home`           | User home directories (e.g., `/home/sonu`).                                             |
| `/initrd.img`     | Temporary root filesystem used during the boot process (initrd = initial RAM disk).     |
| `/initrd.img.old` | Backup of a previous initrd image.                                                      |
| `/lib`, `/lib64`  | Shared libraries needed by binaries in `/bin` and `/sbin`. `/lib64` is for 64-bit libs. |
| `/lib32`          | Shared libraries for 32-bit systems.                                                    |
| `/lost+found`     | Recovered file fragments (used by `fsck` after file system crashes).                    |
| `/media`          | Mount point for removable media (e.g., USB drives).                                     |
| `/mnt`            | Temporary mount point (e.g., for mounting partitions manually).                         |
| `/opt`            | Optional software and third-party packages.                                             |
| `/proc`           | Virtual filesystem for process and kernel information (e.g., `/proc/cpuinfo`).          |
| `/root`           | Home directory of the root user.                                                        |
| `/run`            | Runtime data for processes (e.g., PID files, sockets).                                  |
| `/sbin`           | System binaries for administrative tasks (e.g., `shutdown`, `mkfs`).                    |
| `/snap`           | Used for Snap packages (if Snap is installed).                                          |
| `/srv`            | Data for services like web or FTP (rarely used).                                        |
| `/sys`            | Virtual filesystem for kernel objects.                                                  |
| `/tmp`            | Temporary files (cleared on reboot).                                                    |
| `/timeshift`      | Likely used by Timeshift (backup/restore tool). Not a standard directory.               |
| `/usr`            | Secondary hierarchy: contains applications, libraries, documentation, etc.              |
| `/var`            | Variable data (e.g., logs, mail, spool files, cache).                                   |
| `/vmlinuz`        | Current Linux kernel executable (used at boot).                                         |
| `/vmlinuz.old`    | Previous Linux kernel (kept as backup).                                                 |

Would you like a visual hierarchy diagram of the Linux filesystem?
