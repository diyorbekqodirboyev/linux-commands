Linux Commands

### 1. `cd` — Change Directory
**Example:** Change to the `/home/user/Documents` directory.
```bash
cd /home/user/Documents
```

### 2. `ls` — List Directory Contents
**Example:** List all files, including hidden ones, in the current directory.
```bash
ls -a
```

### 3. `pwd` — Print Working Directory
**Example:** Display the full path of the current directory.
```bash
pwd
```

### 4. `cat` — Concatenate and Display Files
**Example:** Display the contents of a file named `file.txt`.
```bash
cat file.txt
```

### 5. `touch` — Create an Empty File
**Example:** Create an empty file named `newfile.txt`.
```bash
touch newfile.txt
```

### 6. `cp` — Copy Files and Directories
**Example:** Copy `file.txt` to the `backup/` directory.
```bash
cp file.txt backup/
```

### 7. `mv` — Move or Rename Files and Directories
**Example:** Rename `file.txt` to `renamed_file.txt`.
```bash
mv file.txt renamed_file.txt
```

### 8. `rm` — Remove Files and Directories
**Example:** Delete a file named `unnecessary.txt`.
```bash
rm unnecessary.txt
```

### 9. `mkdir` — Create a New Directory
**Example:** Create a directory named `new_folder`.
```bash
mkdir new_folder
```

### 10. `rmdir` — Remove an Empty Directory
**Example:** Remove an empty directory named `old_folder`.
```bash
rmdir old_folder
```

### 11. `grep` — Search for a Pattern in a File
**Example:** Search for the word "error" in `logfile.txt`.
```bash
grep "error" logfile.txt
```

### 12. `chmod` — Change Permissions of Files and Directories
**Example:** Make `script.sh` executable.
```bash
chmod +x script.sh
```

### 13. `ps` — List Running Processes
**Example:** Display all running processes.
```bash
ps aux
```

### 14. `top` — Display System Resource Usage and Process Information
**Example:** Open the `top` interface to monitor processes.
```bash
top
```

### 15. `kill` — Send a Signal to a Process to Terminate It
**Example:** Terminate a process with the PID (Process ID) `1234`.
```bash
kill 1234
```

### 16. `df` — Display Free Disk Space on the File System
**Example:** Show disk usage for all mounted filesystems.
```bash
df -h
```

### 17. `ping` — Test Connectivity to a Network Host
**Example:** Ping Google's DNS server to check connectivity.
```bash
ping 8.8.8.8
```

### 18. `scp` — Secure Copy Files Between Hosts
**Example:** Copy `file.txt` to a remote server.
```bash
scp file.txt user@remote_host:/path/to/destination
```

### 19. `curl` — Transfer Data from or to a Server Using Various Protocols
**Example:** Download a file from a URL.
```bash
curl -O http://example.com/file.zip
```

### 20. `tar` — Archive Files
**Example:** Create a compressed archive of the `project/` directory.
```bash
tar -czvf project.tar.gz project/
```
**Example:** Extract the files from a `project.tar.gz` archive.
```bash
tar -xzvf project.tar.gz
```

### 21. `find` — Find Files and Directories Matching a Pattern
**Example:** Find all `.txt` files in the `/home/user` directory.
```bash
find /home/user -name "*.txt"
```

### 22. `awk` — Pattern Scanning and Processing Language
**Example:** Print the second column of a space-separated file.
```bash
awk '{print $2}' file.txt
```

### 23. `sed` — Stream Editor for Filtering and Transforming Text
**Example:** Replace the word "old" with "new" in `file.txt`.
```bash
sed 's/old/new/g' file.txt
```

### 24. `head` — Display the First Few Lines of a File
**Example:** Show the first 10 lines of `file.txt`.
```bash
head -n 10 file.txt
```

### 25. `tail` — Display the Last Few Lines of a File
**Example:** Show the last 10 lines of `logfile.txt`.
```bash
tail -n 10 logfile.txt
```

### 26. `sort` — Sort Lines of a File
**Example:** Sort the lines in `file.txt` alphabetically.
```bash
sort file.txt
```

### 27. `uniq` — Remove Duplicate Lines from a File
**Example:** Remove duplicate lines from `file.txt` (assumes file is sorted).
```bash
sort file.txt | uniq
```

### 28. `wc` — Count Lines, Words, and Characters in a File
**Example:** Count the number of lines, words, and characters in `file.txt`.
```bash
wc file.txt
```

### 29. `diff` — Compare Two Files Line by Line
**Example:** Compare `file1.txt` and `file2.txt`.
```bash
diff file1.txt file2.txt
```

### 30. `patch` — Apply a Patch to a File
**Example:** Apply a patch to `file.txt`.
```bash
patch file.txt < file.patch
```

### 31. `chown` — Change the Owner of a File or Directory
**Example:** Change the owner of `file.txt` to `user`.
```bash
chown user file.txt
```

### 32. `chgrp` — Change the Group Ownership of a File or Directory
**Example:** Change the group of `file.txt` to `staff`.
```bash
chgrp staff file.txt
```

### 33. `du` — Display Disk Usage of Files and Directories
**Example:** Show the disk usage of the `Documents/` directory in a human-readable format.
```bash
du -h Documents/
```

### 34. `df` — Display Free Disk Space on the File System
**Example:** Show disk space usage for all mounted filesystems in a human-readable format.
```bash
df -h
```

### 35. `mount` — Mount a File System
**Example:** Mount a USB drive to the `/mnt/usb` directory.
```bash
mount /dev/sdb1 /mnt/usb
```

### 36. `umount` — Unmount a File System
**Example:** Unmount the USB drive from the `/mnt/usb` directory.
```bash
umount /mnt/usb
```

### 37. `ssh` — Secure Shell Remote Login and Command Execution
**Example:** Log into a remote server.
```bash
ssh user@remote_host
```

### 38. `rsync` — Remote File and Directory Synchronization
**Example:** Synchronize the `source/` directory with the `destination/` directory on a remote server.
```bash
rsync -avz source/ user@remote_host:/path/to/destination/
```

### 39. `wget` — Retrieve Files from the Web Using Various Protocols
**Example:** Download a file from a URL.
```bash
wget http://example.com/file.zip
```

### 40. `ftp` — File Transfer Protocol Client
**Example:** Connect to an FTP server.
```bash
ftp ftp.example.com
```

### 41. `sftp` — Secure File Transfer Protocol Client
**Example:** Connect to an SFTP server.
```bash
sftp user@remote_host
```

### 42. `telnet` — Telnet Client
**Example:** Connect to a remote server using Telnet.
```bash
telnet remote_host
```

### 43. `nslookup` — DNS Lookup Utility
**Example:** Lookup the IP address of `example.com`.
```bash
nslookup example.com
```

### 44. `dig` — DNS Lookup Utility
**Example:** Perform a DNS lookup for `example.com`.
```bash
dig example.com
```

### 45. `netstat` — Display Network Connections and Statistics
**Example:** Display all active connections.
```bash
netstat -a
```

### 46. `ifconfig` — Configure Network Interfaces
**Example:** Display the network configuration for all interfaces.
```bash
ifconfig
```

### 47. `route` — Display or Modify the Routing Table
**Example:** Display the current routing table.
```bash
route -n
```

### 48. `iptables` — Firewall and Packet Filtering Utility
**Example:** List all rules in the filter table.
```bash
iptables -L
```

### 49. `hostname` — Display or Set the Hostname of the System
**Example:** Display the current hostname.
```bash
hostname
```

### 50. `date` — Display or Set the System Date and Time
**Example:** Display the current date and time.
```bash
date
```

### 51. `timedatectl` — Control the System Date and Time
**Example:** Display the current date and time settings.
```bash
timedatectl
```

### 52. `uname` — Display System Information
**Example:** Display the system's kernel version.
```bash
uname -r
```

### 53. `whoami` — Display the Current User ID
**Example:** Display the current user's username.
```bash
whoami
```

### 54. `id` — Display User and Group Information
**Example:** Display the user ID, group ID, and group memberships for the current user.
```bash
id
```

### 55. `su` — Switch User to Become Another User
**Example:** Switch to the root user.
```bash
su -
```

### 56. `sudo` — Execute a Command with Superuser Privileges
**Example:** Run `apt-get update` as a superuser.
```bash
sudo apt-get update
```

### 57. `passwd` — Change the Password of a User Account
**Example:** Change the password for the current user.
```bash
passwd
```

### 58. `useradd` — Create a New User Account
**Example:** Create a new user named `newuser`.
```bash
sudo useradd newuser
```

### 59. `userdel` — Delete a User Account
**Example:** Delete the user `newuser`.
```bash
sudo userdel newuser
```

### 60. `usermod` — Modify a User Account
**Example:** Add `newuser` to the `sudo` group.
```bash
sudo usermod -aG sudo newuser
```

### 61. `groupadd` — Create a New Group
**Example:** Create a new group named `developers`.
```bash
sudo groupadd developers
```

### 62. `groupdel` — Delete a Group
**Example:** Delete the `developers` group.
```bash
sudo groupdel developers
```

### 63. `groupmod` — Modify a Group
**Example:** Rename the `developers` group to `devs`.
```bash
sudo groupmod -n devs developers
```

### 64. `finger` — Display Information About Users on the System
**Example:** Display information about the user `newuser`.
```bash
finger newuser
```

### 65. `last` — Display Information About Recent Logins
**Example:** Display the last logins on the system.
```bash
last
```

### 66. `history` — Display Command History
**Example:** Show the last 20 commands executed.
```bash
history 20
```

### 67. `echo` — Print a Message to the Terminal
**Example:** Print "Hello, World!" to the terminal.
```bash
echo "Hello, World!"
```

### 68. `printf` — Format and Print Data
**Example:** Print a formatted string.
```bash
printf "Name: %s, Age: %d\n" "Alice" 30
```

### 69. `lshw` — Display Hardware Information
**Example:** Display detailed hardware information about the system.
```bash
sudo lshw
```

### 70. `lspci` — Display Information About PCI Buses and Devices
**Example:** List all PCI devices.
```bash
lspci
```

### 71. `lsusb` — Display Information About USB Buses and Devices
**Example:** List all USB devices.
```bash
lsusb
```

### 72. `hwinfo` — Display Detailed Hardware Information
**Example:** Display detailed information about all hardware.
```bash
sudo hwinfo
```

### 73. `free` — Display Memory Usage
**Example:** Display memory usage in a human-readable format.
```bash
free -h
```

### 74. `vmstat` — Display System Memory, Processor, and I/O Statistics
**Example:** Display virtual memory statistics.
```bash
vmstat
```

### 75. `iostat` — Display CPU and Disk I/O Statistics
**Example:** Display CPU and I/O statistics.
```bash
iostat
```

### 76. `uptime` — Display System Uptime and Load Averages
**Example:** Display how long the system has been running along with the load averages.
```bash
uptime
```

### 77. `journalctl` — Display the System Journal
**Example:** Display all journal entries.
```bash
journalctl
```

### 78. `dmesg` — Display the Kernel Ring Buffer
**Example:** Display messages from the kernel ring buffer.
```bash
dmesg
```

### 79. `crontab` — Schedule Recurring Tasks
**Example:** Edit the crontab to schedule a task.
```bash
crontab -e
```

### 80. `at` — Schedule a One-Time Task
**Example:** Schedule a command to run at a specific time.
```bash
echo "backup.sh" | at 2:30 AM
```

### 81. `service` — Manage System Services
**Example:** Start the `nginx` service.
```bash
sudo service nginx start
```

### 82. `systemctl` — Control System Services in Systemd-Based Distributions
**Example:** Restart the `nginx` service.
```bash
sudo systemctl restart nginx
```

### 83. `traceroute` — Trace the Network Path to a Remote Host
**Example:** Trace the route to `example.com`.
```bash
traceroute example.com
```

### 84. `bzip2` — Compress Files Using the bzip2 Algorithm
**Example:** Compress `file.txt` using `bzip2`.
```bash
bzip2 file.txt
```

### 85. `unzip` — Extract Files from a ZIP Archive
**Example:** Extract `archive.zip`.
```bash
unzip archive.zip
```

### 86. `tee` — Redirect Output to Multiple Files
**Example:** Write the output of a command to a file and display it simultaneously.
```bash
echo "Hello" | tee output.txt
```

### 87. `chroot` — Change the Root Directory for a Process
**Example:** Run a command in a chroot environment.
```bash
sudo chroot /newroot /bin/bash
```

### 88. `ps aux` — Display Information About All Running Processes
**Example:** List all running processes with detailed information.
```bash
ps aux
```

### 89. `less` — Display File Contents in a Paginated Format
**Example:** View the contents of `file.txt` one page at a time.
```bash
less file.txt
```

### 90. `more` — Display File Contents One Page at a Time
**Example:** View the contents of `file.txt` one screen at a time.
```bash
more file.txt
```

### 91. `ln` — Create Links Between Files
**Example:** Create a symbolic link `linkname` to `file.txt`.
```bash
ln -s file.txt linkname
```

### 92. `realpath` — Print the Resolved Absolute Path of a File
**Example:** Get the absolute path of `file.txt`.
```bash
realpath file.txt
```

### 93. `watch` — Execute a Command Periodically and Display the Output
**Example:** Run the `df -h` command every 2 seconds.
```bash
watch -n 2 df -h
```

### 94. `cal` — Display a Calendar
**Example:** Display the current month's calendar.
```bash
cal
```

### 95. `tar -xzvf` — Extract Files from a Compressed Archive
**Example:** Extract files from `archive.tar.gz`.
```bash
tar -xzvf archive.tar.gz
```

### 96. `tar -czvf` — Create a Compressed Archive
**Example:** Create a compressed archive of the `folder/` directory.
```bash
tar -czvf archive.tar.gz folder/
```

### 97. `whereis` — Locate the Binary, Source, and Manual Page Files for a Command
**Example:** Find the location of the `bash` binary.
```bash
whereis bash
```

### 98. `locate` — Find Files by Name
**Example:** Find all files named `file.txt`.
```bash
locate file.txt
```

### 99. `which` — Display the Full Path to an Executable
**Example:** Find the full path of the `python` executable.
```bash
which python
```
### 100. `alias` — Create Aliases for Commands
**Example:** Create an alias `ll` for `ls -l`.
```bash
alias ll='ls -l'
```
---
&copy; 2024 Diyorbek Qodirboyev