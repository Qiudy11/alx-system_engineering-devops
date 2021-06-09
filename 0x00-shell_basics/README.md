echo "$pwd" : scirpt that prints absolute pathway of the current working directory
echo "$(ls)" :displays the contents list of your current directory
cd: chnages working directory to home directory
 echo "$(ls -l)":Displays current directory content in a long format
echo "$(ls -l -a)": displays current diectory content including hidden files starting with .
echo "$(ls -lna)" : Dipslay current directory content ..long format.. user id and group id ..hidden files (starting with  .)
$(mkdir /tmp/holberton/) : A script that creates a directory named holberton in the /tmp/ directory
move the file betty from /tmp/ to /tmp/holberton : $(mv /tmp/betty /tmp/holberton/) \n
Delete the file betty in /tmp/holberton : $(rm /tmp/holberton/betty)
Delete the directory holberton that is in the /tmp directory : $(rmdir /tmp/holberton/)
A script that changes the working directory to the previous  one : cd -
Script that lists all files, (even the ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format echo "$(ls -l -a . .. /boot)"