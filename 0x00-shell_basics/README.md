echo "$pwd" : scirpt that prints absolute pathway of the current working directory
echo "$(ls)" :displays the contents list of your current directory
cd: chnages working directory to home directory
 echo "$(ls -l)":Displays current directory content in a long format
echo "$(ls -l -a)": displays current diectory content including hidden files starting with .
echo "$(ls -lna)" : Dipslay current directory content ..long format.. user id and group id ..hidden files (starting with  .)
$(mkdir /tmp/holberton/) : A script that creates a directory named holberton in the /tmp/ directory