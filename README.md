# Linux-Basic
Linux-command-line
##### 7/3/2020
- '$' sign mean you work on regular account
- '#' you work on root account
pwd: command check directory you working on 
- cd: change directory
- cd /tmp: move to tmp directory
- cd /: navigating to root directory 
- cd ~ or cd: navigating to home directory 
- cd /dev/cpu: move in subdirectory cpu of dev 
- cd ..: move up one directory level 
#####  A path in computing is the address of a file or folder.
- ls: check list in current directory
- ls -R: all directory sub, and file inside
- ls -al: 
##### For example
```
- drwxr-xr-x 22 guru99 guru99 4096 2013-01-04 23:57
- drwxr/-xr-x: file types and access permission
- 22: memory blocks
- guru99: owner of file
- guru99: user group
- 4096: size(bytes)
```
- hidden files start with "." period symbol
- ls -a: view hidden file
- cat: create text file
- cat > file1: create file and add content to file1
- cat file1: view content of that file1
- cat file1 file2 > newfile: combine file1 and file2 into a newfile
- rm file1: remote file1
- sudo mv test home/guru99/Files: use mv command should use sudo test to new destination is Files
- mv test test1: rename test to test1. You can compine move and rename as the same time
- mkdir song: create new directory name song in current directory
- mkdir /tmp/music: create music directory under tpm
- ls /tmp: check all directory in tmp
- mkdir dir1 dir2 dir3: creaty multiple directory (dir1, dir2, dir3)
- rmdir dir1: remote directory dir1
- man ls: terminal give you information about ls command
- history: these command you was type
- clear: clear window
- ctr + shift + v or shift+ insert: paste to terminal
##### Printing in terminal
- pr: printing on terminal
- pr -3 tools: divide the file content of file tools into 3 columns
- pr - h HomeTools tools: create header (HomeTools) to file tools
- pr -n tools: denote all file line with number
- lp tools or lpr tools: print hard copy of file tools
- lp -nN tools: printing N copies of file tools
- lpr N tools: printing N copies of file tools also
- lp -dPrintername Filename
- lpr -PPrintername Filename
##### Installing Sofware
- sudo apt-get install Softwarename: installing a software
##### Sending email
- Use mailx application with syntax to send email
- mailx giao.pnq92@gmail.com then hit enter you will ask to enter subject and body press Ctrl+D to finish 
- mail -s "subject" -c "cc-address" -b "bcc- address" "to-address"






