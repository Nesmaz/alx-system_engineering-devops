# Basics of Shell Scripting

This project is a collection of shell scripts that demonstrate the basics of shell scripting.

## Scripts


* `0-current_working_directory.sh` - Prints the absolute path name of the current working directory.

* `1-listit.sh` - Displays the contents list of the current directory.

* `2-bring_me_home.sh` - Changes the working directory to the user's home directory.

* `3-listfiles.sh` - Displays current directory contents in a long format.

* `4-listmorefiles.sh` - Displays current directory contents, including hidden files (starting with .). Use the long format.

* `5-listfilesdigitonly.sh` - Displays current directory contents.
    * Long format
    * with user and group IDs displayed numerically
    * And hidden files (starting with .)

* `6-firstdirectory.sh` - Creates a directory named`my_first_directory` in the /tmp/ directory.

* `7-movethatfile.sh` - Moves the file betty from /tmp/ to`/tmp/my_first_directory`.

* `8-firstdelete.sh` - Deletes the file betty.

* `9-firstdirdeletion.sh` - Deletes the directory `my_first_directory` that is in the /tmp directory.

* `10-back.sh` - changes the working directory to the previous one.

* `11-lists.sh` - lists all files (even ones with names beginning with a period character,
                  which are normally hidden) in the current directory and the parent of the working directory
                  and the /boot directory (in this order), in long format.

* `12-file_type.sh` - prints the type of the file named iamafile.

* `13-symbolic_link.sh` - Creates a symbolic link to /bin/ls, named __ls__. in the current working directory.

* `14-copy_html.sh` - copies all the HTML files from the current working directory to the parent of the working directory,
                      but only copy files that did not exist in the parent of the working directory,
                      or were newer than the versions in the parent of the working directory.

## How to use

To run the scripts, you will need to have a basic understanding of the shell navigation.
You can also use a text editor, such as vi or emacs, to view the code for the scripts.
or just use the cat or less commands.

## Conclusion

This project has demonstrated the basics of shell scripting.

