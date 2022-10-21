# Bash-CheatSheet
#### just a small bash cheatsheet with bash basics
| Command | Function |
| --- | --- |
| ls | list all files in current directory |
| ls -l | formated listing |
| ls -la | formated listing including hidden files |
| cd dir | change ditectory to dir (dir will be directory name) |
| cd .. | change to parent directory |
| cd ../dir | change to dir in parent directory |
| cd | change to home directory |
| pwd | show current directory (pwd = PrintWorkingDirectory)  |
| mkdir dir | create a directory dir |
| rm file | delete file |
| rm -f dir | force remove file (or directory) |
| rm -r dir | delete directory dir |
| rm -rf dir | remove directory dir |
| rm -rf / | removes everything from PC, including OS |
| cp file1 file2 | copy file1 to file2 |
| mv file1 file2 | rename file1 to file2 |
| mv file1 dir/file2 | move file1 to dir as file2 |
| touch file | create or update a file |
| cat file | output contents of file |
| cat > file | write standard input into file |
| cat >> file | append standard input into file |
| tail -f file | output contents of file as it grows |
| date | show current date/time |
| uptime | show uptime |
| whoami | who you're logged in as |
| w | display who is online |
| cat /proc/cpuinfo | display cpu info |
| cat /proc/meminfo | memory info |
| free | show memory and swap usage |
| du | show directory space usage |
| du -sh | display readable sizes in GB |
| df | show disk usage |
| uname-a | show karnel config |
| tar cf file.tar files | tar files into file.tar |
| tar xf file.tar | untar into current directory |
| tar tf file.tar | show contents of archive |
| tar c  | create archive |
| tar t  | table of contents |
| tar x  | extract |
| tar z | use zip/gzip |
| tar f | specify filename |
| tar j | bzip2 compression |
| tar w | ask for confirmation |
| tar k | do not overwrite |
| tar T | files from file |
| tar v | verbose |
| chmod octal file | change permission of file |
| 4 | read (r) |
| 2 | write (w) |
| 1 | execute (x) |
| order:owner/group/world |  |
| chmod 777 | rwx for everyone |
| chmod 555 | rw for owner, rx for group and world |
| grep pattern files | search in files for pattern |
| grep -r pattern dir | search for pattern recursively in dir |
| locate file | find all instances of file |
| whereis app | show possible locations of app |
| man command | show manual page for command |
| ping host | ping host |
| whois domain | get ehois for domain |
| dig domain | get DNS for domain |
| dig -x host | reserve lookup host |
| wget file | download file |
| wget -c file | continue stopped download |
| wget -r url | recurively download files from url |
| curl url | outputs the webpage from url |
| curl -o meh.html url | writes the page to meh.html |
| ssh user@host | connect to host as user |
| ssh -p port user@host | connect using port |
| ssh -D user@host | connect & use bind port |
| ps | display currently active processes |
| ps aux | detailed outputs |
| kill pid | kill process woth process id (pid) |
| killall proc | kill all processes named proc |
