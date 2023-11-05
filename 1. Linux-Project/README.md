# Linux Project Implementation

In this project i will be implementing some basic linux command 

## Sudo Command 

 The ``sudo command`` is the superuser do command that performs tasks that require administrative or root permissions. To use this sudo command you can use the following syntax 

 ![sudo](./img/1.%20sudo%20update%20and%20upgrade%20.png)
 ![sudo](./img/1.%20sudo%20update%20end%20result%20.png)

 ## Pwd Command 

 The ``pwd command ``is used to find the path of your current/present working directory. 

 ![pwd](./img/2.%20pwd%20command%20.png)

 ## Cd Command 

 The ``cd command`` is used to navigate through the linux files and directories, use the cd command depending on your current working directory. 

 ![cd](./img/3.%20cd%20command%20.png)

 ## ls Command 

  The ``ls command`` list files and directories within a system. Running it without a flag or parameter will show the current working directory's content. 

  ![ls](./img/4.%20ls%20command%20.png)

## cat command 

The ``cat or concatenate command`` is one most frequently used linux command. It lists, combines, and writes file content to the standard output. 

![](./img/5.%20cat%20command%20.png)

## cp Command 

The ``cp command`` is used to copy files or directories and their content. 

![cp](./img/6.%20cp%20command%20.png)

## mv command 

The primary use of the ``mv command`` is to move and rename files and directories. It does not produce an output upon execution. when you see my syntax i moved ``Devops2 to devops2`` and i also renamed ``devops2 to practice1`` using the same ``mv command``

![mv](./img/7.%20mv%20command%20.png)

## mkdir Command

The ``mkdir command`` is used to create one or multiple directories at once and set permissions for each of them. The user executing this command must have the privilege to make a new folder in the parent directory or they may receive a permission denied error. 

![mkdir](./img/8.%20mkdir%20command%20.png)

## rmdir command 

The ``rmdir command`` is used to permanently delete an empty directory, to use the rmdir command remember that the user running this command should have sudo privileges in the parent directory. 

![rmdir](./img/9.%20rmdir%20command%20.png)

## rm command 

The ``rm command`` is used to delete files within a directory. Make sure that the user performing this command has write permissions.To remove the file I needed to create an empty ``file1 and file2`` and that is what I removed/deleted from my directory.   

![rm](./img/10.%20rm%20command%20.png)

## touch command 

The ``touch command`` allows you to create an empty file or generate and modify a timestamp in the linux command line. 

![touch](./img/11.%20touch%20command%20.png)

## locate command 

The ``locate command`` can find a file in the database system

![locate](./img/12.%20locate%20command%20.png)

## find command 

The ``find command`` is used to search for files within a directory and perform subsequent operations. Here's the general syntax

![find](./img/13.%20find%20command%20.png)

## grep command 

The ``grep command`` is Another basic linux command on the list, ``grep or global`` regular expression print. It lets you find a word by searching through all the tests in a specific file. 

![grep](./img/14.%20grep%20command%20.png)

## df command

The ``df command`` is used to report the system's disk space usage, shown in percentage and kilobyte (KB). Here's the general syntax:

![df](./img/15.%20df%20command%20.png)

## du command 

The ``du command`` is used to check how much space a file or a directory takes up, use the du command. You can run this command to identify which part of the system uses the storage excessively. 

![du](./img/16.%20du%20command%20.png)

## head command 

The ``head command`` allows you to view the first ten lines of a text. Adding an option lets you change the number of lines shown. Here's the general syntax:

![head](./img/17.%20head%20command%20.png)

## tail command 

The ``tail command`` displays the last ten lines of a file. It allows users to check whether a file has new data or to read error messages.

![tail](./img/18.%20tail%20command%20.png)

## diff command 

The ``diff command`` compares two contents of a file line by line. After analyzing them, it will display the parts that do not match. 

![diff](./img/19.%20diff%20command%20.png)

## tar command 

The ``tar command`` archives files into TAR FILE. a common linux format similar to ZIP with optional compression. Here are the basic syntax: 

![tar](./img/20.%20tar%20command%20.png)

## chmod command 

The ``chmod command``is a common command that modifies a file or directort's read, write, and execute permissions. In linux, each file is associated with three user classes- owner, group member, and others.
Here's the basic syntax: 

![chmod](./img/21.%20chmod%20command%20.png)

## chown command 

The ``chown command`` lets you change the ownership of a file, directory, or a symbolic link to a specified username. Here's the basic syntax: 

![chown](./img/22.%20chown%20newuser%20.png)

![chown](./img/22.%20chown%20newuser.rootuser%20.png)

## jobs command 

The ``job command`` is a process that the shell starts. The jobs command will display all the running processes along with their statuses. This is the basis syntax : 

![jobs](./img/23.%20jobs%20command%20.png)

![jobs](./img/23.%20Jobs%20command%20barground%20.png)

## kill command 

The ``kill command`` is used to kill or terminate an unresponsive program manually. It will signal misbehaving applications and instruct them to close their processes. You have to know the ``PID`` to kill a running process Here's the basis syntax:

![kill](./img/24.%20kill%20command%20A%20.png)
![kill](./img/24.%20kill%20command%20B%20.png)
![kill](./img/24.%20kill%20command%20C%20.png)
![kill](./img/24.%20kill%20command%20pstree%20.png)

## ping command 

The ``ping command`` is one of the most basic linux commands for checking whether a network or server is reachable. It's also used to troubleshoot various connectivity issues. Here's the general format: 

![ping](./img/25.%20ping%20command%20.png)

## wget command 

The ``wget command`` line lets you download files from the internet using the wget command. It works in the background without hindering oher running processes.

![wget](./img/26.%20wget%20command%20.png)

## uname command 

The ``uname or unix command`` will print detailed information about your linux system and hardware. Here's the basic syntax:

![uname](./img/27.%20uname%20command%20.png)

## top command 

The ``top command`` in linux Terminal will display all the running and dynamic rea-time of the current system. it sums up the resource utilization, from the CPU to the memory usage. 

![top](./img/28.%20top%20command%20.png)

## history command 

With ``history``, the system will list up to 500 previously executed commands, allowing you to reuse them without reentering. Only the sudo users have privileges to execute this command. 

![history](./img/29.%20history%20command%20.png)
![history](./img/29.%20history%20command%20b.png)

## man command 

The ``man command`` provides a user manual or any command or utilities you can run in Terminal.including the name, description, and options.

![man](./img/30.%20man%20command%20.png)

![man](./img/30.%20man%20command%20ctb%20.png)

## echo command 

The ``echo command`` is a built-in utility that displays a line of text or string using the standard output. Here is the basic syntax: 

![echo](./img/31.%20echo%20command%20.png)

## zip,unzip command 

The ``zip command`` is used to compress your files into a ZIP file, a universal format commonly used on linux. Here's the basuc syntax:

![zip](./img/32.%20zip%20command%20.png)

![unzip](./img/32.%20unzip%20command%20.png)

## hostname command 

Run the ``hostname command`` to know the system's hostname. You can execute it with or without an option. Here's the general syntax: 

![hostname](./img/33.%20hostname%20command%20.png)

## useradd userdel command 

The ``useradd`` is used to create a new account as Linux is a multi-user system. Only those with root privileges or sudo can run the useradd command. Here's the basic syntax:

![useradd]()

## apt get command 

The ``apt-get command`` is a command line tool for handling Advanced package tool(APT) libraries in Linux. it lets you retrieve information and bundles from authenticated sources to manage,update,remove,and install software and its dependencies. Here's the main syntax:

![apt get](./img/35.%20apt-get%20command%20.png)

## nano,vi command 

The ``Nano,vi command`` in Linux allows users to edit and manage files via a text editor

![nano](./img/36.%20nano%20command%20.png)

![vim](./img/36.%20vim%20command%20.png)

## alias, unlias command 

The ``alias command`` allows you to create a shortcut with the same functionality as a command, file name, or text. when executed, it instructs the shell to replace one string with another. Here's some basic syntax: 

![alias](./img/37.%20alias%20unalias%20command%20.png)

## su command 

The ``su command or switch user command`` allows you to run a program as a different user. it changes the administrative account in the current log-in session. Here's the general syntax:

![su](./img/38.%20su%20command%20.png)

## htop command 

The``htop command`` is an interactive program that monitors system resources and server processes in real time.

![htop](./img/39.%20htop%20command%20.png)

## ps command 

The ``process status or ps command`` produces a snapshot of all running processes in your system. The statis results are taken from the virtual files in the /proc file system. 

![ps](./img/40.%20ps%20command%20.png)



