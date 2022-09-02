0-current_working_directory should print the curent working directory

1-listit should print the contents of the current directory

2-bring_me_home changes the current directory to the home directory

3-listfiles lists the files in the directory in long mode

4-listmorefiles lists all files including hidden in the current directory

5-listfilesdigitonly lists all files including hidden and their user and group IDs

6-firstdirectory creates a "my_first_directory" folder in tmp folder

7-movethatfile moves the file betty from /tmp/ to /tmp/my_first_directory

8-firstdelete deletes the file named betty previously moved

9-firstdirdeletion deletes the /tmp/my_first_directory directory

10-back changes directory to the previous working directory

11-lists lists all files including hidden in the current directory and the parent of the working directory and the /boot directory in long format.

12-file_type prints the type of the file named iamafile

13-symbolic_link creates a symbolic link to /bin/ls, named __ls__ in the current working directory

14-copy_html copies all the HTML files from the current working directory to the parent of the working directory. Copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory

100-lets_move moves all files beginning with an uppercase letter to the directory /tmp/u.

101-clean_emacs deletes all files in the current working directory that end with the character ~.

102-tree creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

103-commas lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line

school.mgc 