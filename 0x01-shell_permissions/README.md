shell permissions descripe
#0i-am_betty
The script switches the current user to the a user called betty by using the su (Switch User)
#1-who_am_i
script that prints the effective username of the current use
  whoami
#2-groups
script that prints all the groups the current user is part of
   id 
#3-3-new_owner
script that changes the owner of the file hello to the user betty. 
   sudo chown
#4-Empty
script that creates an empty file called hello.
 touch hello
#5-Execute
script that adds execute permission to the owner of the file hello.
 chmod
#6- Multiple permissions
script that adds execute permission to the owner and the group owner
, and to other users, to the file hello.  
chmod as well
#7-Everybody!
script that adds execution permission to the owner, 
the group owner and the other users, to the file hello
symbolic mode as well 
#8-James Bond
script that sets the permission to the file hello as follows
chmod as well
#9-John Doe
script that sets the mode of the file hello to this:
use chmod with symbolic link 
#10Look in the mirror
script that sets the mode of the file hello the same as olleh’s mode.
chmod --reference
#11Directories
script that adds execute permission to all subdirectories of the current directory
group owner and all other users. Regular files should not be changed.
chmod -R
#12More directories
 script that creates a directory 
 called my_dir with permissions 751 in the working directory
 mkdir -m
#13-Change group
 script that changes the group owner to school for the file hello
 chown
#14-Owner and group
script that changes the owner to vincent and the group owner to 
staff for all the files and directories in the working directory
chown -R newOwner:newGroup
#15-Symbolic links
The same as previous script by we will add -h because it's a Symolic link and that will help us not change the reference of this link as well.
#16-If only
The script changes the owner of the file hello to betty only if it's owned by guillaume by using chown --from=wanted_user
#17-Star Wars
The script plays the StarWarsIV episode in the terminal by using telnet towel.blinkenlights.nl
Assuming that telnet was installed in the system.
