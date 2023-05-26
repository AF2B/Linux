# Hi! I'm glad to see you here! =)
# I'm going to tell you about some useful commands for your experience with Linux. =)

### Every command has a structure like this:

  command -option1 -option2 -option3

or

  command -option1 -option2 -option3 argument1 argument2 argument3

for example

  ls -la -> list all files and directories in long format


### 1. ls: List all files inside an specific directory
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ls</td>
    <td>List files and directories</td>
  </tr>
  <tr>
    <td>ls -a</td>
    <td>List all files and directories</td>
  </tr>
  <tr>
    <td>ls -l</td>
    <td>List files and directories in long format</td>
  </tr>
  <tr>
    <td>ls -la</td>
    <td>List all files and directories in long format</td>
  </tr>
  <tr>
    <td>ls -lh</td>
    <td>List files and directories in long format with readable file size</td>
  </tr>
  <tr>
    <td>ls -lha</td>
    <td>List all files and directories in long format with readable file size</td>
  </tr>
  <tr>
    <td>ls -lhaS</td>
    <td>List all files and directories in long format with readable file size and sort by size</td>
  </tr>
  <tr>
    <td>ls -lhaSr</td>
    <td>List all files and directories in long format with readable file size and sort by size in reverse order</td>
  </tr>
  <tr>
    <td>ls -lhaSr | head -n 10</td>
    <td>List 10 biggest files and directories in long format with readable file size and sort by size in reverse order</td>
  </tr>
  <tr>
    <td>ls -lhaSr | tail -n 10</td>
    <td>List 10 smallest files and directories in long format with readable file size and sort by size in reverse order</td>
  </tr>
</table>

### 2. cd: Navigate inside directories
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>cd</td>
    <td>Change directory</td>
  </tr>
  <tr>
    <td>cd ..</td>
    <td>Go to parent directory</td>
  </tr>
  <tr>
    <td>cd /</td>
    <td>Go to root directory</td>
  </tr>
  <tr>
    <td>cd ~</td>
    <td>Go to home directory</td>
  </tr>
  <tr>
    <td>cd -</td>
    <td>Go to previous directory</td>
  </tr>
  <tr>
    <td>cd /path/to/directory</td>
    <td>Go to specific directory</td>
  </tr>
</table>

### 3. mkdir: Create directories
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>mkdir</td>
    <td>Make directory</td>
  </tr>
  <tr>
    <td>mkdir -p</td>
    <td>Make directory with parents</td>
  </tr>
  <tr>
    <td>mkdir -p /path/to/directory</td>
    <td>Make directory with parents</td>
  </tr>
</table>

### 4. rm: Remove files and directories (be careful with this command)
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>rm</td>
    <td>Remove file or directory</td>
  </tr>
  <tr>
    <td>rm -r</td>
    <td>Remove directory</td>
  </tr>
  <tr>
    <td>rm -rf</td>
    <td>Remove directory with files and subdirectories</td>
  </tr>
  <tr>
    <td>rm -rf /path/to/directory</td>
    <td>Remove directory with files and subdirectories</td>
  </tr>
</table>

### 5. cp: Copy files and directories
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>cp</td>
    <td>Copy file or directory</td>
  </tr>
  <tr>
    <td>cp -r</td>
    <td>Copy directory</td>
  </tr>
  <tr>
    <td>cp -r /path/to/directory /path/to/destination</td>
    <td>Copy directory to destination</td>
  </tr>
</table>

### 6. mv: Move files and directories or you can rename files and directories
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>mv /path/to/file /path/to/destination</td>
    <td>Move file</td>
  </tr>
  <tr>
    <td>mv /path/to/directory /path/to/destination</td>
    <td>Move directory</td>
  </tr>
  <tr>
    <td>mv /path/to/file /path/to/destination/new_name</td>
    <td>Move file with new name</td>
  </tr>
  <tr>
    <td>mv /path/to/directory /path/to/destination/new_name</td>
    <td>Move directory with new name</td>
  </tr>
  <tr>
    <td>mv directory new_name</td>
    <td>Rename directory</td>
  </tr>
  <tr>
    <td>mv file new_name</td>
    <td>Rename file</td>
  </tr>
</table>

### 7. touch: Create files
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>touch file_name</td>
    <td>Create file</td>
  </tr>
  <tr>
    <td>touch /path/to/file_name</td>
    <td>Create file</td>
  </tr>
</table>

### 8. cat: Show file content
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>cat file_name</td>
    <td>Show file content</td>
  </tr>
  <tr>
    <td>cat /path/to/file_name</td>
    <td>Show file content</td>
  </tr>
</table>

### 9. less: Show file content with scrolling
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>less file_name</td>
    <td>Show file content with scrolling</td>
  </tr>
  <tr>
    <td>less /path/to/file_name</td>
    <td>Show file content with scrolling</td>
  </tr>
</table>

### 10. head and tail: Show first and last lines of file
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>head file_name</td>
    <td>Show first 10 lines of file</td>
  </tr>
  <tr>
    <td>head /path/to/file_name</td>
    <td>Show first 10 lines of file</td>
  </tr>
  <tr>
    <td>head -n 20 file_name</td>
    <td>Show first 20 lines of file</td>
  </tr>
  <tr>
    <td>head -n 20 /path/to/file_name</td>
    <td>Show first 20 lines of file</td>
  </tr>
  <tr>
    <td>tail file_name</td>
    <td>Show last 10 lines of file</td>
  </tr>
  <tr>
    <td>tail /path/to/file_name</td>
    <td>Show last 10 lines of file</td>
  </tr>
  <tr>
    <td>tail -n 20 file_name</td>
    <td>Show last 20 lines of file</td>
  </tr>
  <tr>
    <td>tail -n 20 /path/to/file_name</td>
    <td>Show last 20 lines of file</td>
  </tr>
</table>

### 11. grep: Search pattern in file
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>grep -option1 -option2 -option3 'pattern' file_name</td>
    <td>Search pattern in file with specified options</td>
  </tr>
  <tr>
    <td>grep option 'pattern' file_name</td>
    <td>Search pattern in file</td>
  </tr>
  <tr>
    <td>grep -i option 'pattern' file_name</td>
    <td>Search pattern in file with ignoring case</td>
  </tr>
  <tr>
    <td>grep -r option 'pattern' file_name</td>
    <td>Search pattern in file with recursive</td>
  </tr>
  <tr>
    <td>grep -n option 'pattern' file_name</td>
    <td>Search pattern in file with showing line number</td>
  </tr>
  <tr>
    <td>grep -c option 'pattern' file_name</td>
    <td>Search pattern in file with showing count of matches</td>
  </tr>
  <tr>
    <td>grep -i -n -c option 'pattern' file_name</td>
    <td>Search pattern in file with ignoring case and showing line number and count of matches</td>
  </tr>
  <tr>
    <td>grep -i -n -c option 'pattern' file_name | head -n 10</td>
    <td>Search pattern in file with ignoring case and showing line number and count of matches and show first 10 lines</td>
  </tr>
</table>

### 12. find: Find files and directories by pattern
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>find /path/to/directory -name 'pattern'</td>
    <td>Find files and directories by pattern</td>
  </tr>
  <tr>
    <td>find /path/to/directory -name 'pattern' -type f</td>
    <td>Find files by pattern</td>
  </tr>
</table>

### 13. chmod: Change file and directory permissions
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>chmod 777 file_name</td>
    <td>Change file permissions</td>
  </tr>
  <tr>
    <td>chmod 777 /path/to/file_name</td>
    <td>Change file permissions</td>
  </tr>
  <tr>
    <td>chmod 777 directory_name</td>
    <td>Change directory permissions</td>
  </tr>
  <tr>
    <td>chmod 777 /path/to/directory_name</td>
    <td>Change directory permissions</td>
  </tr>
</table>

<h2>Explanations about chmod</h2>
<p>
  Inside the architecture of Linux, there are 3 types of users: owner, group and others. <br>
  Each user has 3 types of permissions: read, write and execute. <br>
  Each type of permission has a number: read = 4, write = 2, execute = 1. <br>
  So, if you want to give all permissions to a file or directory, you have to sum the numbers of permissions. <br>
</p>
  <table>
    <tr>
      <th>Permission</th>
      <th>Value</th>
      <th>Explanation</th>
    </tr>
    <tr>
      <td>All Permissions</td>
      <td>7</td>
      <td>4 (Read) + 2 (Write) + 1 (Execute)</td>
    </tr>
    <tr>
      <td>Read and Write Permissions</td>
      <td>6</td>
      <td>4 (Read) + 2 (Write)</td>
    </tr>
    <tr>
      <td>Read and Execute Permissions</td>
      <td>5</td>
      <td>4 (Read) + 1 (Execute)</td>
    </tr>
    <tr>
      <td>Write and Execute Permissions</td>
      <td>3</td>
      <td>2 (Write) + 1 (Execute)</td>
    </tr>
    <tr>
      <td>Read Permissions</td>
      <td>4</td>
      <td>4 (Read)</td>
    </tr>
    <tr>
      <td>Write Permissions</td>
      <td>2</td>
      <td>2 (Write)</td>
    </tr>
    <tr>
      <td>Execute Permissions</td>
      <td>1</td>
      <td>1 (Execute)</td>
    </tr>
  </table>

<h2>
  14. systemctl: Manage services in Linux (systemctl is a command for systemd, a system and service manager for Linux)
</h2>
<p>
  Inside the architecture of Linux, there are services that are running in the background. <br>
  You can manage these services with systemctl. <br>
  You can start, stop, restart, enable, disable, status and reload services. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>systemctl start service_name</td>
    <td>Start service</td>
  </tr>
  <tr>
    <td>systemctl stop service_name</td>
    <td>Stop service</td>
  </tr>
  <tr>
    <td>systemctl restart service_name</td>
    <td>Restart service</td>
  </tr>
  <tr>
    <td>systemctl enable service_name</td>
    <td>Enable service</td>
  </tr>
  <tr>
    <td>systemctl disable service_name</td>
    <td>Disable service</td>
  </tr>
  <tr>
    <td>systemctl status service_name</td>
    <td>Show status of service</td>
  </tr>
  <tr>
    <td>systemctl reload service_name</td>
    <td>Reload service</td>
  </tr>
</table>

<h2>
  15. ifconfig and ip: Show network information
</h2>
<p>
  Inside the architecture of Linux, there are network interfaces. <br>
  You can show network information with ifconfig or ip. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ifconfig</td>
    <td>Show network information</td>
  </tr>
  <tr>
    <td>ip</td>
    <td>Show network information</td>
  </tr>
</table>

<h2>
  16. ping: Test network connection
</h2>
<p>
  Inside the architecture of Linux, there are network interfaces. <br>
  You can test network connection with ping. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ping domain_name</td>
    <td>Test network connection</td>
  </tr>
  <tr>
    <td>ping ip_address</td>
    <td>Test network connection</td>
  </tr>
</table>

<h2>
  17. df: Show disk usage
</h2>
<p>
  Inside the architecture of Linux, there are disks. <br>
  You can show disk usage with df. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>df</td>
    <td>Show disk usage</td>
  </tr>
  <tr>
    <td>df -h</td>
    <td>Show disk usage with readable file size</td>
  </tr>
</table>

<h2>
  18. top: Show processes running in the system
</h2>
<p>
  Inside the architecture of Linux, there are processes running in the system. <br>
  You can show processes running in the system with top. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>top</td>
    <td>Show processes running in the system</td>
  </tr>
</table>

<h2>
  19. ps: Show processes running in the system
</h2>
<p>
  Inside the architecture of Linux, there are processes running in the system. <br>
  You can show processes running in the system with ps. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ps</td>
    <td>Show processes running in the system</td>
  </tr>
  <tr>
    <td>ps -a</td>
    <td>Show all processes running in the system</td>
  </tr>
  <tr>
    <td>ps -u</td>
    <td>Show processes running in the system with user</td>
  </tr>
  <tr>
    <td>ps -aux</td>
    <td>Show all processes running in the system with user</td>
  </tr>
</table>

<h2>
  20. kill: Kill processes running in the system
</h2>
<p>
  Inside the architecture of Linux, there are processes running in the system. <br>
  You can kill processes by ID running in the system with kill. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>pkill process_name</td>
    <td>Kill process</td>
  </tr>
  <tr>
    <td>pkill -9 process_name</td>
    <td>Kill process</td>
  </tr>
  <tr>
    <td>kill process_id</td>
    <td>Kill process</td>
  </tr>
  <tr>
    <td>kill -9 process_id</td>
    <td>Kill process</td>
  </tr>
</table>

<h2>
  21. history: Show history of commands
</h2>
<p>
  Inside the architecture of Linux, there are commands that you can use. <br>
  You can show history of commands with history. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>history</td>
    <td>Show history of commands</td>
  </tr>
  <tr>
    <td>history 10</td>
    <td>Show last 10 commands</td>
  </tr>
</table>

<h2>
  22. clear: Clear terminal
</h2>
<p>
  Inside the architecture of Linux, there are commands that you can use. <br>
  You can clear terminal with clear. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>clear</td>
    <td>Clear terminal</td>
  </tr>
</table>

<h2>
  23. exit: Exit terminal
</h2>
<p>
  Inside the architecture of Linux, there are commands that you can use. <br>
  You can exit terminal with exit. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>exit</td>
    <td>Exit terminal</td>
  </tr>
</table>

<h2>
  24. wget: Download files from the web
</h2>
<p>
  Inside the architecture of Linux, there are commands that you can use. <br>
  You can download files from the web with wget. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>wget file_url</td>
    <td>Download file from the web</td>
  </tr>
  <tr>
    <td>wget -O file_name file_url</td>
    <td>Download file from the web with new name</td>
  </tr>
</table>

<h2>
  curl: Download files from the web
</h2>
<p>
  Inside the architecture of Linux, there are commands that you can use. <br>
  You can download files from the web with curl. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>curl file_url</td>
    <td>Download file from the web</td>
  </tr>
  <tr>
    <td>curl -o file_name file_url</td>
    <td>Download file from the web with new name</td>
  </tr>
</table>
<h2>
  25. diff: Compare files
</h2>
<p>
  Inside the architecture of Linux, there are files. <br>
  You can compare files with diff. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>diff file1 file2</td>
    <td>Compare files</td>
  </tr>
</table>

<h2>
  26. ln: Create links to files or directories
</h2>
<p>
  Inside the architecture of Linux, there are files and directories. <br>
  You can create links to files or directories with ln. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ln -s /path/to/source/file /path/to/link</td>
    <td>Create a symbolic link from source file to link</td>
  </tr>
  <tr>
    <td>ln /path/to/source/file /path/to/link</td>
    <td>Create a hard link from source file to link</td>
  </tr>
  <tr>
    <td>ln -s /path/to/source/directory /path/to/link</td>
    <td>Create a symbolic link from source directory to link</td>
  </tr>
  <tr>
    <td>ln -r /path/to/source/directory /path/to/link</td>
    <td>Create a hard link from source directory to link (not commonly used)</td>
  </tr>
</table>

<h2>
  27. tar: Create and extract archives
</h2>
<p>
  Inside the architecture of Linux, there are files and directories. <br>
  You can create and extract archives with tar. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>tar -cf file.tar file1 file2 ...</td>
    <td>Create a tar archive</td>
  </tr>
  <tr>
    <td>tar -czf file.tar.gz file1 file2 ...</td>
    <td>Create a tar.gz archive (compressed with gzip)</td>
  </tr>
  <tr>
    <td>tar -cjf file.tar.bz2 file1 file2 ...</td>
    <td>Create a tar.bz2 archive (compressed with bzip2)</td>
  </tr>
  <tr>
    <td>tar -xf file.tar</td>
    <td>Extract a tar archive</td>
  </tr>
  <tr>
    <td>tar -xzf file.tar.gz</td>
    <td>Extract a tar.gz archive (compressed with gzip)</td>
  </tr>
  <tr>
    <td>tar -xjf file.tar.bz2</td>
    <td>Extract a tar.bz2 archive (compressed with bzip2)</td>
  </tr>
</table>

<h2>
  28. locate: Find files and directories by pattern
</h2>
<p>
  Inside the architecture of Linux, there are files and directories. <br>
  You can find files and directories by pattern with locate. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
    <tr>
    <td>locate pattern</td>
    <td>Find files and directories by pattern</td>
  </tr>
</table>

<h2>
  29. which: Find commands by pattern
</h2>
<p>
  Inside the architecture of Linux, there are commands. <br>
  You can find commands by pattern with which. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
    <tr>
    <td>which pattern</td>
    <td>Find commands by pattern</td>
  </tr>
</table>

<h2>
  30. mount: Mount devices and partitions
</h2>
<p>
  Inside the architecture of Linux, there are devices and partitions. <br>
  You can mount devices and partitions with mount. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
    <tr>
    <td>mount /dev/sda1 /mnt</td>
    <td>Mount device or partition</td>
  </tr>
</table>

<h2>
  31. umount: Unmount devices and partitions
</h2>
<p>
  Inside the architecture of Linux, there are devices and partitions. <br>
  You can unmount devices and partitions with umount. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
    <tr>
    <td>umount /dev/sda1</td>
    <td>Unmount device or partition</td>
  </tr>
</table>

<h2>
  32. fdisk: Manage devices and partitions
</h2>
<p>
  Inside the architecture of Linux, there are devices and partitions. <br>
  You can manage devices and partitions with fdisk. <br>
</p>
<table>
  <tr>
    <th>Command</th>
    <th>Description</th>
  </tr>
    <tr>
    <td>fdisk -l</td>
    <td>Show devices and partitions</td>
  </tr>
    <tr>
    <td>fdisk /dev/sda</td>
    <td>Manage device or partition</td>
  </tr>
</table>
