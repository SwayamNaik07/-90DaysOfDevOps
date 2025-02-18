In DevOps, Linux commands are essential for managing servers, automation, and troubleshooting. Here are some of the most important commands categorized by their usage:

File and Directory Management
ls – Lists files and directories.
cd – Changes the current directory.
pwd – Displays the present working directory.
cp – Copies files and directories.
mv – Moves or renames files and directories.
rm – Removes files and directories.
mkdir – Creates a new directory.
rmdir – Removes an empty directory.
find – Searches for files and directories.
touch – Creates an empty file.


Permission and Ownership Management
chmod – Modifies file and directory permissions.
chown – Changes the ownership of a file or directory.
chgrp – Changes the group ownership of a file or directory.
umask – Sets default permissions for new files.


Process Management
ps – Displays currently running processes.
top – Shows real-time system resource usage.
htop – An interactive version of top for monitoring processes.
kill – Terminates a process using its PID.
pkill – Kills a process by name.
nice – Starts a process with a specified priority.
renice – Changes the priority of a running process.
nohup – Runs a process in the background even after logout.



User Management
whoami – Displays the current logged-in user.
id – Shows user and group IDs.
who – Lists logged-in users.
w – Displays currently logged-in users with their activity.
useradd – Creates a new user.
usermod – Modifies an existing user.
userdel – Deletes a user.
passwd – Changes a user's password.
groupadd – Creates a new group.
groupdel – Deletes a group.



Networking Commands
ifconfig – Displays or configures network interfaces (deprecated, replaced by ip).
ip – Shows or modifies network interfaces.
ping – Tests connectivity to a host.
netstat – Displays network connections, routing tables, and statistics (deprecated, replaced by ss).
ss – Provides detailed information about network sockets.
traceroute – Traces the route packets take to a host.
nslookup – Queries DNS records.
dig – Retrieves detailed DNS information.
curl – Transfers data from or to a server using various protocols.
wget – Downloads files from the web.



Disk and Storage Management
df – Displays disk space usage.
du – Shows disk usage of files and directories.
fdisk – Partition management tool.
mkfs – Formats a partition with a filesystem.
mount – Mounts a filesystem.
umount – Unmounts a filesystem.
lsblk – Lists information about block devices.



Package Management
Debian-based (Ubuntu, Debian):
apt-get / apt – Installs, updates, or removes packages.
dpkg – Installs or removes .deb packages manually.
RHEL-based (CentOS, Fedora, Red Hat):
yum / dnf – Installs, updates, or removes packages.
rpm – Manages .rpm packages manually.



Log Management
cat /var/log/syslog – Displays system logs.
cat /var/log/auth.log – Shows authentication logs.
journalctl – Views system logs from the journal.
dmesg – Displays kernel logs.
System Monitoring and Performance
uptime – Shows system uptime and load average.
free – Displays memory usage.
vmstat – Reports system performance statistics.
iostat – Shows CPU and disk usage statistics.
sar – Collects and displays system performance data.



Archiving and Compression
tar – Archives files into a .tar format.
gzip – Compresses files using .gz format.
gunzip – Decompresses .gz files.
zip – Compresses files into a .zip archive.
unzip – Extracts .zip archives.



Version Control (Git)
git clone – Clones a repository.
git status – Shows the status of changes.
git add – Stages changes.
git commit – Commits changes.
git push – Pushes commits to a repository.
git pull – Fetches and integrates remote changes.


Automation and Scripting
crontab -e – Edits scheduled cron jobs.
crontab -l – Lists scheduled cron jobs.
systemctl – Manages system services.
bash – Executes shell scripts.
awk – Text processing tool.
sed – Stream editor for text manipulation.
systemctl – Manages system services.
bash – Executes shell scripts.
awk – Text processing tool.
sed – Stream editor for text manipulation.
These commands are fundamental in DevOps workflows for managing servers, automating tasks, monitoring performance, and troubleshooting issues effectively.
