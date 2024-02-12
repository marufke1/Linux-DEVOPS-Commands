****# Linux-DEVOPS-Commands
**The most important commands to learn for Devops engineer.**
- WHO  =   Provides the current user logging info in dtail way.
- WHOAMI = Provides only the current user logging info ex- ec2-user
- PWD =    Print the current working directory information ex- /home, /root
- CD =     Allows to change the directory cd root/ - cd home/
- SUDOSU = Super user has all the permissions to take any actions.
- MAN =    Provides the detail information about other commands like- man touch
- LS =     Shows the list for all the files and directories have been created.
- LS-L =   Exactly does the same things like ls but adding more info about the file and directories ex- permissions, user, group, creation time etc.
- TOUCH =  Allows to create an empty file. ex- touch linuxfile.txt
- CAT =    Allows to show the content inside of the file
- ECHO =   Allows to print any output in the terminal also can redirect the contant with the file
- VI/NANO = Editor command allows to creat a file and put content inside the file at a same time
- MKDIR =  Create a directory ex- mkdir devops
- CLEAR =  Clear the temrinal
- DATE = show the current date of the system
- CD .. = allows to one step back from the current directory ex- (cd devops/ cd home/)
- RM = remove the file from the system
- RMDIR = remove the empty directory
- RM -R = remove any non empty directory by using recursively
- CP = make a copy of the file and directory
- MV = moving the file from one location to another
- HEAD = allows to print frist 5/10 lines of the content from the file ex- (head -n 5 linux.txt)
- TAIL = allows to print last 5/10 lines of the content from the file ex - (tail -n 10 linux.txt)
- MORE/LESS = 
- WC =   Provides the information about the file like- number of lines, number of columns and number of words.
- SOFT-LINK/ HARD-LINK = Allows to create a link beteen of the file to make suce can access the content of the file very easily.
  (ln /home/devops/linuxfile.txt hard-link.txt | ln -s /home/devops/linuxfile.txt soft-link.txt.) the main deifference between of 
  them if we delete the main file then harlink file still remains to acces it but softlink file will be deleted even cant be 
  accessible anymore. 
- CUT =  Provides the small portion of the content from the file ex - (cut -b 1-3 linuxfile.txt) 
- TEE = Allows to print any output in the terminal and also can create a file and store the output inside of the file as well. 
  ex- (echo "Hello World!" | tee linuxfile.txt)
- SORT = Allows to sort the content of the file based on the alphabet.
- DIFF = Difference between of multiple files.
- DF-H = Disk usuage commands allowss to show the information about the system disk like- used, available, etc
- FREE = Provides the information about the memory for the system like - free, used, available etc.
- NOHUP = 
- VMSTAT = Provides in info about virtual machine memory
- WHICH
- UPTIME
- UNAME
- ID
- SHUTDOWN = Terminate the machine.
- YUM/APT =  Updating the machine and installing the packages for the machine ex- (yum install update -y | yum install git -y)
- USERADD =  Create a newuser ex- useradd x.
- PASSWD =   Create a passwrod for the user.
- SU USER =  Switch between of the users.
- GROUPADD = Create gorup ex- groupadd devops
- USER DELETE / GROUP DELETE = Delete user and groups.
- CHMOD = Allows to change the permission for the file and directoreies. There are 3 levels of permission on user, group and 
  others. It contains read = 4 , write =2, and excute level permission =1 for the file and directories. ex- chmod 777 
  linuxfile.text means this file has read, write, and execute permission for user group and others level.
- CHOWN = Change the user ownership for the file and directories.
- CGGRP = Change the group permission for the file and directories.
- TAR =  Compress multiple files together ex- (tar - cvzf devops.tar.gz devops | ex- extract- tar -xvzf devops.tar.gz devops)
- AWK = Allows to print any specific line or column of the content from the file. ex- (awk '{print $1, $5}' linuxfile.txt)
- SED = Allows to replace the keyword of the content from the file also can overwriiten the content within the file ex - (sed 's/devops/cloud/' linuxfile.txt) | (sed 's/devops/cloud/' linuxfile.txt >> linuxfile.txt)
- GREP
- PING = Check the connectivity for the machine make sure can communaite with other server over the internet. ex- ping google.com.
- IFCONFIG = Provides the information about current network interface for the server.
- NETSTAT = Shows the status of the network.
- TRACE ROUTE = Count the hop count to forward the packet from source to destination. 
- NSLOOKUP = Retrieve the ip addres inofrmation for the dns record.
- IP = provides info about the machine ip address like - private and public.
- HOSTNAME = info about the hostname
- DIG = Exactly does the same thing like nslookup but in more detail way.
- ARP = provides the information about the machine physical address like - mac address.
- CURL/WGET = allows to download any packages for the system over the internet.
****
