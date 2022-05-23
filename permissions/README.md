This directory contains steps to understand how the permissions in shell work.
0."su username" - use to change username
1."whoami" - use to print effective username of current user
2."groups" - List all the gropus the current user is part of.
3."chown" - Used to change the owner of a file 
4."touch empty" - To create an empty file 
5."chmod u+x hello" - Give execute permision to the owner of file
6."chmod +114 hello" - Give execute permission to user and group and read to everyone else.
7.4."touch empty" - To create an empty file 
5."chmod u+x hello" - Give execute permision to the owner of file
6."chmod +114 hello" - Give execute permission to user and group and read to everyone else.
7.4."touch empty" - To create an empty file 
5."chmod u+x hello" - Give execute permision to the owner of file
6."chmod +114 hello" - Give execute permission to user and group and read to everyone else.
7.4."touch empty" - To create an empty file 
5."chmod u+x hello" - Give execute permision to the owner of file
6."chmod +114 hello" - Give execute permission to user and group and read to everyone else.
7."chmod +111 hello" - Give everyone execution permission
8."chmod 007 hello" - Give owner and group no permission, give user all permissions.
9."chmod 753 hello" Giving owner all permission; group read and execute; user write y execute.
10."chmod --reference=olleh hello" Copying permissions from a file to another one.
11."chmod -R ugo+X ." Changing the permission of every subfolder.
12."mkdir -m 751 my_dir" Creating a directory witha specific permision.
13."chgrp school hello" Changing the group ownership of a file.
14.
