shell basics
#0. Where am i?
The script should print the current working directory
pwd
#-1. What’s in there?
Display the contents list of your current directory.
ls 
#-2There is no place like home
Write a script that changes the working directory to the user’s home directory.
cd~
#3- The long format
 Display current directory contents in a long format
ls -l
#4-4. Hidden files
Display current directory contents, including hidden files (starting with .). Use the long format.
ls-al
#5. I love numbers
Display current directory contents.
Long format
with user and group IDs displayed numerically
And hidden files (starting with .)
ls -aln
#6. Welcome
Create a script that creates a directory named my_first_directory in the /tmp/ directory.
mkdir /tmp/my_first_directory/
#7. Betty in my first directory
Move the file betty from /tmp/ to /tmp/my_first_directory.
mv /tmp/betty /tmp/my_first_directory/
#8. Bye bye Betty
Delete the file betty.
rm /tmp/my_first_directory/betty
#9. Bye bye My first directory
Delete the directory my_first_directory that is in the /tmp directory.
rmdir /tmp/my_first_directory 
#10. Back to the future
Write a script that changes the working directory to the previous one.
cd -
#11. Lists
Write a script that lists all files (even ones with names beginning 
with a period character, which are normally hidden) in the current directory and the parent 
of the working directory and the /boot directory (in this order), in long format.
ls -al . .. /boot
#12-Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
file /tmp/iamafile
#13-. We are symbols, and inhabit symbols
Create a symbolic link to /bin/ls, named __ls__. 
The symbolic link should be created in the current working directory.
ln -s /bin/ls __ls__
#14-. Copy HTML files
Create a script that copies all the HTML files from the current working directory to the parent of the working directory,
 but only copy files that did not exist in the parent of the working directory or were newer
  than the versions in the parent of the working directory.
  cp -u *.html ..
#15-Let’s move
Create a script that moves all files beginning with an uppercase letter
 to the directory /tmp/u.
 mv [[:upper:]]* /tmp/u 
#16-. Clean Emacs
Create a script that deletes all files in the current working directory 
that end with the character ~.
rm -r *~
#17-Tree 
Create a script that creates the directories
welcome/, welcome/to/ and welcome/to/school in the current directory.
mkdir -p welcome/to/school
#18-. Life is a series of commas, not periods
A script to list all the content of the current directory, separated by commas and directory name should end with /
ls -apm
#19. File type: School
a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
0 string SCHOOL School data
!:mime School

























  
