0-current_working_directory script prints the absolute path name of the current working directory.
<br>
1-listit script display the contents list of the current directory.
<br>
2-bring_me_home script that changes the working directory to the user’s home directory.
<br>
3-listfiles script Display current directory contents in a long format.
<br>
4-listmorefiles script Display current directory contents, including hidden files (starting with .) in a long format.
<br>
5-listfilesdigitonly script Display current directory contents(Long format with user and group IDs displayed numerically And hidden files (starting with .))
<br>
6-firstdirectory script that creates a directory named my_first_directory in the /tmp/ directory.
<br>
7-movethatfile script that Moves the file betty from /tmp/ to /tmp/my_first_directory.
<br>
8-firstdelete script delete The file betty is in /tmp/my_first_directory.
<br>
9-firstdirdeletion script delete the directory my_first_directory that is in the /tmp directory.
<br>
10-back script that changes the working directory to the previous one.
<br>
11-lists script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
<br>
12-file_type script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory.
<br>
13-symbolic_link script Create a symbolic link to /bin/ls, named __ls__ .
<br>
14-copy_html script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
<br>
100-lets_move script that moves all files beginning with an uppercase letter to the directory /tmp/u.
<br>
101-clean_emacs script that deletes all files in the current working directory that end with the character ~.
<br>
102-tree script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
<br>
103-commas script that lists all the files and directories of the current directory, separated by commas (,):
	- Directory names should end with a slash (/)
	- Files and directories starting with a dot (.) should be listed
	- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
	- Only digits and letters are used to sort; Digits should come first
	- You can assume that all the files we will test with will have at least one letter or one digit
	- The listing should end with a new line
