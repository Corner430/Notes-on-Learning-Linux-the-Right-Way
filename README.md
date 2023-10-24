# Notes on Learning Linux the Right Way

English | [简体中文](README_cn.md)

1. [Installation](1.installation.md) introduces the issues encountered during system installation.
2. [RPM and YUM](2.RPM_and_YUM.md) covers the usage of RPM and YUM.
3. [Systemd](3.systemd.md) explains the usage of systemd.
4. [Bash and Command](4.bash_and_command.md) explores both the long and short formats of bash and commands.
5. [Frequently Used Commands](5.frequently_command.md) presents commonly used commands.
6. [Basic Concepts](6.basic_concept.md) provides insight into several fundamental concepts:
   - Environment variables
   - Environment variable PATH
   - Network card configuration information
   - User identity UID
   - User group GID
   - Passwords and passphrases
7. [Vim](7.vim.md) demonstrates the usage of Vim.
8. [Shell Fundamentals and Script Programming](8.Shell_Fundamentals_and_Script_Programming.md) covers the basics of Shell and script programming:
   - Common escape characters in Shell
   - Five types of redirection techniques
   - Pipeline command symbol `|`
   - Command line wildcards
   - Basic steps for writing Shell scripts
   - How Shell scripts accept user arguments
   - The `$?` symbol
   - Conditional expressions in Shell
   - Control flow statements `if`, `for`, `while`, `case`
9. [File and Permission Management](9.File_and_Permission_Management.md) delves into file and permission management:
   - File permissions and ownership
   - Special permissions for files
   - File hiding attributes
   - File Access Control Lists (ACL)
10. [System Services and Tasks](10.System_Services_and_Tasks.md) covers system services and tasks:
   - Scheduled task services, **including one-time and long-term scheduled tasks**
   - The `su` command and the `sudo` service
11. [Storage Structure and Disk Partition](11.Storage-structure-and-disk-partition.md) introduces the storage structure and disk partition.
   - File System Hierarchy Standard (FHS)
   - /dev/
   - Primary Partition, Extended Partition, Logical Partition
   - File Systems: Ext3, Ext4, XFS, Btrfs, ReiserFS, JFS, F2FS, ZFS
   - Inode Table
   - Partitioning, Formatting, Mounting
   - Adding Swap Partition, Disk Space Quotas
12. [Using RAID and LVM disk array technology](12.Using_RAID_and_LVM_disk_array_technology.md) introduces the usage of RAID and LVM disk array technology
   - LVM technology adds a logical layer between hard disk partitions and the file system, providing an abstract volume group that allows you to combine multiple hard disks.
   - LVM also has "snapshot" volume functionality.
   - LVM deletion is ordered.
13. [iptables, firewalld and ufw](13.iptables_firewalld_and_ufw.md) introduces the usage of iptables, firewalld and ufw
   - Firewall rules have priority based on the order in which they are matched.
   - Five Rule Categories
14. [ssh](14.ssh.md) introduces the usage of ssh to manage remote hosts
   - `nmtui` is a command-line tool for configuring network connections in a text-based interface.
   - Using `nmcli` to Create Network Sessions
   - Binding Multiple Network Cards
   - sshd Service Configuration
   - `scp` (Secure Copy) Command
   - Persistent Sessions (`screen`)
15. [Deploy static websites using Apache services](15.Deploy_static_websites_using_Apache_services.md) introduces the usage of Apache services to deploy static websites
   - IIS, Nginx, and Apache
   - Installation and Configuration of Apache Services
   - SELinux Security Subsystem
   - Virtual Host Functionality
16. [Transfer files using vsftpd services](16.Transfer_files_using_vsftpd_services.md) introduces the usage of vsftpd services to transfer files
   - FTP
   - vsftpd(very secure ftp daemon)
   - PAM(Pluggable authentication module)
   - TFTP(Trivial File Transfer Protocol)
17. [Use Samba or NFS to achieve file sharing](17.Use_Samba_or_NFS_to_achieve_file_sharing.md)
   - Samba allows multiple systems to share files and printers
   - NFS shares files and directories between Linux systems
18. [Using BIND to provide domain name resolution service](18.Using_BIND_to_provide_domain_name_resolution_service.md) introduces the usage of BIND to provide domain name resolution service