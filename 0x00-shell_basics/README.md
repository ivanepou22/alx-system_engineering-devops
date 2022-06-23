Task 0

pwd == Write a script that prints the absolute path name of the current working directory.



Task -1

ls == Display the contents list of your current directory.



Task 2

cd == Write a script that changes the working directory to the user’s home directory.



Task 3

ls -l == Display current directory contents in a long format



Task 4

ls -la == list directory contents in long form, including hidden files



Task 5

ls -aln == Display current directory contents.Long format with user and group IDs displayed numerically And hidden files (starting with .)



Task 6

mkdir -p /tmp/my_first_directory == Create a script that creates a directory named my_first_directory in the /tmp/ directory.



Task 7

mv /tmp/betty /tmp/my_first_directory/  == Move the file betty from /tmp/ to /tmp/my_first_directory.



Task 8 

rm /tmp/my_first_directory/betty == Delete the file betty. The file betty is in /tmp/my_first_directory.



Task 9

rm -r /tmp/my_first_directory  == Delete the directory my_first_directory that is in the /tmp directory.



Task 10

cd - == Write a script that changes the working directory to the previous one.



Task 11

ls -la . .. /boot == Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.



Task 12

file /tmp/iamafile == Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.



Task 13

ln -s /bin/ls __ls__ == Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.



Task 14

cp -u *.html ../ == Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. You can consider that all HTML files have the extension .html



Task 15

mv [[:upper:]]* /tmp/u == Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u. You can assume that the directory /tmp/u will exist when we will run your script.



Task 16

rm *~ == Create a script that deletes all files in the current working directory that end with the character ~



Task 17

mkdir -p welcome/to/school == Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces (and lines) in your script, not more.



Task 18

ls -apm | sort -d == Write a command that lists all the files and directories of the current directory, separated by commas (,).



Task 19

Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

==

0 string SCHOOL School data

!:mime School






