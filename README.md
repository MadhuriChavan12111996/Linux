Introduction to Linux:
●	Linux is an open-source operating system kernel used by various distributions (distros) like Ubuntu, Debian, CentOS, etc. It's widely used in servers, embedded systems, and personal computers.
●	The terminal is a text-based interface where users can interact with the system by typing commands.

File Management:

 | Command                   | Description                  | Example             |
| ------------------------- | ---------------------------- | ------------------- |
| ls                        | List files & directories     | ls -l               |
| cd <directory>            | Change directory             | cd /home/user       |
| pwd                       | Print current directory      | pwd                 |
| cp <source> <destination> | Copy file                    | cp file.txt /tmp/   |
| mv <source> <destination> | Move/rename                  | mv file.txt new.txt |
| rm <file>                 | Remove file                  | rm file.txt         |
| rm -r <directory>         | Remove directory recursively | rm -r old_folder    |
| cat <file>                | Display contents             | cat notes.txt       |
| less <file>               | View large file              | less log.txt        |
| head <file>               | First 10 lines               | head data.csv       |
| tail <file>               | Last 10 lines                | tail data.csv       |
| touch <file>              | Create empty file            | touch new.txt       |
| find <path> -name <file>  | Search files                 | find /home -name "  |

Folder Management:

| Command           | Description            | Example            |
| ----------------- | ---------------------- | ------------------ |
| mkdir <directory> | Create directory       | mkdir new_folder   |
| rmdir <directory> | Remove empty directory | rmdir empty_folder |
| tree              | Directory structure    | tree /var/log      |

Disk Management:

| Command                     | Description      | Example                   |
| --------------------------- | ---------------- | ------------------------- |
| df -h                       | Disk usage       | df -h                     |
| du -sh <path>               | Folder/file size | du -sh /home/user         |
| mount <device> <mountpoint> | Mount disk       | sudo mount /dev/sdb1 /mnt |
| umount <mountpoint>         | Unmount disk     | sudo umount /mnt          |
| lsblk                       | Block devices    | lsblk                     |
| fdisk -l                    | Partition table  | sudo fdisk -l             |

Package Management:

| Command                | Description                 | Example              |
| ---------------------- | --------------------------- | -------------------- |
| sudo apt update        | Update package index        | sudo apt update      |
| sudo apt upgrade       | Upgrade packages            | sudo apt upgrade     |
| sudo apt install <pkg> | Install package             | sudo apt install vim |
| sudo apt remove <pkg>  | Remove package              | sudo apt remove vim  |
| dpkg -l                | List installed deb packages | dpkg -l              |
| dpkg -i <package.deb>  | Install .deb file           | sudo dpkg -i app.deb |

User Management:

| Command                 | Description     | Example           |
| ----------------------- | --------------- | ----------------- |
| whoami                  | Current user    | whoami            |
| sudo adduser <username> | Add new user    | sudo adduser john |
| sudo passwd <username>  | Change password | sudo passwd john  |
| sudo deluser <username> | Delete user     | sudo deluser john |
| groups <username>       | Show groups     | groups john       |

Process Management:

| Command        | Description                  | Example         |
| -------------- | ---------------------------- | --------------- |
| ps aux         | List all processes           | ps aux          |
| top            | Real-time process viewer     | top             |
| htop           | Better process viewer        | htop            |
| kill <PID>     | Kill by PID                  | kill 1234       |
| killall <name> | Kill by process name         | killall firefox |
| bg / fg        | Background / foreground jobs | bg or fg        |

Networking:

| Command       | Description             | Example                                                         |
| ------------- | ----------------------- | --------------------------------------------------------------- |
| ip a          | Show network interfaces | ip a                                                            |
| ping <host>   | Test connectivity       | ping google.com                                                 |
| curl <url>    | Fetch URL               | curl [http://example.com](http://example.com)                   |
| wget <url>    | Download file           | wget [http://example.com/file.zip](http://example.com/file.zip) |
| netstat -tuln | Show open ports         | netstat -tuln                                                   |
| ss -tuln      | Modern port viewer      | ss -tuln                                                        |

General Troubleshooting:

| Command                    | Description    |
| -------------------------- | -------------- |
| dmesg                      | Kernel logs    |
| journalctl -xe             | System logs    |
| systemctl status <service> | Service status |
| sudo reboot                | Reboot         |
| sudo shutdown now          | Shutdown       |
| uptime                     | System uptime  |
| free -h                    | Memory usage   |



