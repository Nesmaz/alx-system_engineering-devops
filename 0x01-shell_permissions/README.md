#Shell Permissions

This project is a collection of shell scripts that demonstrate the basics of shell permissions.

##Scripts   

*0-iam_betty.sh - Switches the current user to the user betty.

*`1-who_am_i.sh` - Prints the effective username of the current user.

*2-groups.sh - Prints all the groups the current user is part of.

*`3-new_owner.sh` - Changes the owner of the file hello to the user betty.

*4-empty.sh - Creates an empty file called hello.

*5-execute.sh - Adds execute permission to the owner of the file hello.

*6-multiple_permissions.sh - Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

*7-everybody.sh - Adds execution permission to the owner, the group owner and the other users, to the file hello.

*8-James_Bond.sh - Sets the permission to the file hello as follows:
       *Owner: no permission at all.
       *Group: no permission at all.
       *Other users: all the permissions.

*9-John_Doe.sh - Sets the mode of the file hello to this:
    *File hello will be in the working directory.

*10-mirror_permissions.sh - Sets the mode of the file hello the same  as olleh's mode.
    *File hello will be in the working directory.
    *File olleh will be in the working directory.

*11-directories_permissions.sh - Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

*`12-directory_permissions.sh` - Creates a directory called `my_dir` with permissions 751 in the working directory.

*13-change_group.sh - Changes the group owner to school for the file hello.

##How to use

To run the scripts, you will need to have a basic understanding of the shell navigation.
You can also use a text editor, such as vi or emacs, to view the code for the scripts.
Or just use the cat or less commands.

##Conclusion

This project has demonstrated the basics of shell permissions.



