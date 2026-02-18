# Linux File System

Linux file system is a stuructuerd method of storing and organizing data on linux machine. It arranges files in a hierarchical format, starting from the root directory /.

## Top-Level Directories
- `/bin` : essential commands required for basic system operations '/bin/ls, /bin/mkdir'
- `/etc` : system-wide configuration files '/etc/passwd'
- `/home` : personal user data
- `/opt` : optional or third-party software '/opt/google/chrome'
- `/tmp` : temporary files, files usually deleted after system reboot
- `/usr` : user installed programs, utilities, and shared resources '/usr/bin/python, usr/git'
- `/var` : variable data such as log files that change frequently '/var/log/syslog, /var/nginx'

## Other Directories
- `/boot` : bootloader files, Linux kernel and configuration needed to start the system
- `/dev` : device files that represent hardware components 'disks, USB, terminals'
- `/lib` : shared libraries and kernel modules required by system programs and the kernel
- `/lost+found` : recovered file fragments after file system repair 'fsck'
- `/media` : mount point for removable devices 'USB drives and CDs'
- `/mnt` : temporary mount point for manually mounted file systems
- `/proc` : virtual file system providing live information about processes and system status via PIDs
- `/run` : temporary runtime data such as PID files and system state information
- `/sbin` : essential system administration commands 'mostly for root'
- `/srv` : data served by system services 'web or FTP server data'
- `/sys` : Virtual file system used to interact with hardware and access kernel information

## Absolute Path vs Relative Path
An absolute path is the complete path starting from the root directory.
- eg: /home/user/devops-journal/Linux/01-Basics/README.md

A relative path is defined relative to your current working directory.
- eg: 01-Basics/README.md

## Commands
- `rm -r`: remove directory and it's contents
- `cp` : copy file/directory from one location to another
- `mv` : move file/directory to another location or renames it
