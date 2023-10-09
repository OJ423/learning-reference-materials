# CLI Cheat Sheet

1. **Navigation:**
   - `pwd`: Print working directory
   - `ls`: List files and directories
   - `cd [directory]`: Change directory
   - `cd ..`: Move up one directory
   - `cd ~`: Go to home directory

2. **File Operations:**
   - `touch [filename]`: Create an empty file
   - `cp [source] [destination]`: Copy file/directory
   - `mv [source] [destination]`: Move or rename file/directory
   - `rm [filename]`: Remove/delete file
   - `rmdir [directory]`: Remove/delete empty directory
   - `rm -r [directory]`: Remove/delete directory and its contents

3. **Viewing and Editing Files:**
   - `cat [filename]`: Display file content
   - `more [filename]` or `less [filename]`: View file content page by page
   - `nano [filename]` or `vim [filename]`: Open file for editing

4. **Working with Directories:**
   - `mkdir [directory]`: Create a new directory
   - `rmdir [directory]`: Remove/delete empty directory
   - `rm -r [directory]`: Remove/delete directory and its contents

5. **File Permissions:**
   - `chmod [permissions] [filename]`: Change file permissions
   - `chown [user:group] [filename]`: Change file owner

6. **Searching for Files:**
   - `find [directory] -name [filename]`: Search for a file
   - `grep [pattern] [filename]`: Search for a pattern in a file
   - `locate [filename]`: Find the location of a file

7. **System Information:**
   - `uname -a`: Display system information
   - `df -h`: Show disk space usage
   - `free -m`: Display free and used memory

8. **Processes:**
   - `ps`: Display information about active processes
   - `top`: Display dynamic real-time view of the system processes

9. **Networking:**
   - `ifconfig` or `ip addr`: Display network interface information
   - `ping [hostname]`: Test network connectivity
   - `traceroute [hostname]`: Display the route packets take to network host

10. **Compression and Archiving:**
   - `tar -cvf [archive_name.tar] [files/directories]`: Create a tar archive
   - `tar -xvf [archive_name.tar]`: Extract files from a tar archive
   - `gzip [filename]` or `gunzip [filename.gz]`: Compress or decompress a file

Remember to use the `man` command followed by the command you want more information about to access the manual pages for detailed information.
