### Basic Linux Commands

#### find - (find -- walk a file hierarchy)

Find command recursively walk over a given directory and list all files/directories matching with given Pattern.

* *__find files with name in current directory__*
	- find . -name config.xml
* *__find files of type = file with particular name in given directory__*
	- find /tmp -type -f -name "sample.txt"
	
#### Linux Useful SystemAdmin Command(s)
 
* du -k | sort -n -r **(Sort based on file size decending)**
* du -k | sort -n **(Sort based on file size decending)**
* last reboot **(Check LastTime System rebooted)**
* last reboot | less **(Check lastTime System rebooted with Less information)**
* cat /proc/meminfo **(CheckMemory information)**
* cat /etc/os-release Or lsb_release -a **(Check OS information)**
* lscpu **(CheckCPU information)**
