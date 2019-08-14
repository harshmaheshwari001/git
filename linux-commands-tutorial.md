### Basic Linux Commands

#### Adding/Modify Swapspace
https://askubuntu.com/questions/927854/how-do-i-increase-the-size-of-swapfile-without-removing-it-in-the-terminal

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

#### Vim Editor Useful Command(s)
* i			**(Insert at cursor (goes into insert mode))**
* a			**(Write after cursor (goes into insert mode))**
* A			**(Write at the end of line (goes into insert mode))**
* ESC			**(Terminate insert mode)**
* u			**(Undo last change)**
* U			**(Undo all changes to the entire line)**
* o			**(Open a new line (goes into insert mode))**
* dd 			**(Delete line)**
* 3dd			**(Delete 3 lines.)**
* D			**(Delete contents of line after the cursor)**
* C			**(Delete contents of a line after the cursor and insert new text. Press ESC key to end insertion.)**
* dw			**(Delete word)**	
* 4dw			**(Delete 4 words)**
* cw			**(Change word)**
* x			**(Delete character at the cursor)**
* r			**(Replace character)**
* R			**(Overwrite characters from cursor onward)**
* ~			**(Change case of individual character)**
* :set number  ->  **(Go to Command mode)** 
* :set nonumber  ->  **(Go to Command Mode & Turn off number)** 
* /string		 ->	**(search forward for occurrence of string in text)**
* ?string		 ->	**(search backward for occurrence of string in text)**
* n			 ->	**(move to next occurrence of search string)**
* N			 ->	**(move to next occurrence of search string in opposite direction)**
* :%s/foo/bar/g -> **(Replace occurance of foo with bar inentire file)** 
