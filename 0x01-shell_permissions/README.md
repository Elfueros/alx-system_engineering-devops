Shell permissions

Each file is a script that perfoms a shell permission action. 

0-iam_betty swithes the current user to user betty
1-who_am_i  prints the effective id of the current user
2-groups prints the groups of the current user
changes the owner of the file hello to the user betty
4-empty creates an empty file named hello
5-execute gives execute permission to the owner of the file named hello
6-multiple_permissions gives execute permission to the owner and group owner and read permission to others for the file hello
6-multiple_permissions gives execute permission to everybody for the file hello
8-James_Bond gives zero permission to owner and owner group but execute permission to other for the file hello
9-John_Doe gives  a special 753 permission for the file hello
12-directory_permissions creates a directory with 751 permission
13-change_group changes the owner group of file hello to "school"
10-mirror_permissions sets the mode of file hello to the same as olleh
11-directories_permissions adds execute permission to all directory inside of current directory
