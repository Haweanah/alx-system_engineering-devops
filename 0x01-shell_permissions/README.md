"su betty" is the script that switches the current user to the user betty" 

"whoami" is the script that prints the effective username of the current user

"groups" is the script that prints all the groups the current user is part of

"chown betty hello" is the script that changes the owner of the file hello to the user betty

"touch hello" is the script that creates an empty file called hello
"chmod u+x hello" is the script that adds execute permission to the owner of the file hello

"chmod ug+x, o+r hello" is the script that adds execute permission to the owner and the group owner, and read permission to other users to the file hello

"chmod 007 hello" is the script that sets the permission to the file hello

"chmod 753 hello is the script that sets the mode of the file hello

"chmod --reference=olleh hello" is the script that sets the mode of the file hello the same as olleh’s mode

"chmod -R +x ." is the script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed

"chmod -m 751 my _dir" is the script that creates a directory called my_dir with permissions 751 in the working directory

"chgrp school hello" is the script that changes the group owner to school for th file hello

"chown vincent:staff" is the script that changes the owner to vincent and the group owner to staff for all the files and directories in the working director
y

"chownn-h vincent:staff_hello" is the script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
"chown --from=guillaume betty hello
