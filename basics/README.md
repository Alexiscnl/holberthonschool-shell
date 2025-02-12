<div align="center"><img src="https://github.com/ksyv/holbertonschool-web_front_end/blob/main/baniere_holberton.png"></div>

# Shell Navigation and Manipulation

## Resources <a name="Resources"></a>

* [What Is “The Shell”?](https://linuxcommand.org/lc3_lts0010.php)
* [Navigation](https://linuxcommand.org/lc3_lts0020.php)
* [Looking Around](https://linuxcommand.org/lc3_lts0030.php)
* [A Guided Tour](https://linuxcommand.org/lc3_lts0040.php)
* [Manipulating Files](https://linuxcommand.org/lc3_lts0040.php)
* [Working With Commands](https://linuxcommand.org/lc3_lts0060.php)
* [Reading Man pages](https://linuxcommand.org/lc3_man_pages/man1.html)
* [Keyboard shortcuts for Bash](https://www.howtogeek.com/181/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)
* [LTS](https://wiki.ubuntu.com/LTS)
* [Shebang](https://en.wikipedia.org/wiki/Shebang_%28Unix%29)
* [Linux file systems explained](https://en.wikipedia.org/wiki/Shebang_%28Unix%29)
* man or help:
    * `cd`
    * `ls`
    * `pwd`
    * `less`
    * `file`
    * `ln`
    * `cp`
    * `mv`
    * `rm`
    * `mkdir`
    * `type`
    * `which`
    * `help`
    * `man`

## Learning Objectives <a name="Learning-Objectives"></a>

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

* **General**
    * What does RTFM mean?
    * What is a Shebang
    * What is the Shell
    * What is the difference between a terminal and a shell
    * What is the shell prompt
    * How to use the history (the basics)
* **Navigation**
    * What do the commands or built-ins `cd`, `pwd`, `ls` do
    * How to navigate the filesystem
    * What are the `.` and `..` directories
    * What is the working directory, how to print it and how to change it
    * What is the root directory
    * What is the home directory, and how to go there
    * What is the difference between the root directory and the home directory of the user root
    * What are the characteristics of hidden files and how to list them
    * What does the command `cd -` do
* **Looking Around**
    * What do the commands `ls`, `less`, `file` do
    * How do you use options and arguments with commands
    * Understand the `ls` long format and how to display it
* **A Guided Tour**
    * What does the `ln` command do
    * What do you find in the most common/important directories
    * What is a symbolic link
    * What is a hard link
    * What is the difference between a hard link and a symbolic link
* **Manipulating Files**
    * What do the commands `cp`, `mv`, `rm`, `mkdir` do
    * What are wildcards and how do they work
    * How to use wildcards
* **Working with Commands**
    * What do `type`, `which`, `help`, `man` commands do
    * What are the different kinds of commands
    * What is an alias
    * When do you use the command `help` instead of `man`
* **Reading Man Pages**
    * How to read a man page
    * What are man page sections
    * What are the section numbers for User commands, System calls and Library functions
* **Keyboard Shortcuts for Bash**
    * Common shortcuts for Bash
* **LTS**
    * What does LTS mean?

## Requirements <a name="Requirements"></a>

* **General**
    * Allowed editors: `vi`, `vim`, `emacs`
    * All your scripts will be tested on Ubuntu 22.04 LTS
    * All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
    * All your files should end with a new line (why?)
    * The first line of all your files should be exactly `#!/bin/bash`
    * A `README.md` file at the root of the repo, containing a description of the repository
    * A `README.md` file, at the root of the folder of *this* project, describing what each script is doing
    * You are not allowed to use backticks, `&&`, `||` or `;`
    * All your scripts must be executable. To make your file executable, use the `chmod` command: `chmod u+x FILENAME_GOES_HERE`.
* **More Info**
    * Example of line count and first line:
    ```bash
    julien@ubuntu:/tmp$ wc -l 12-file_type 
    2 12-file_type
    julien@ubuntu:/tmp$ head -n 1 12-file_type 
    #!/bin/bash
    julien@ubuntu:/tmp$ 
    ```
    * In order to test your scripts, you will need to use this command: `chmod u+x FILENAME_GOES_HERE`.
