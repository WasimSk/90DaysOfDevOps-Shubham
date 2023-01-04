<h2>Day -2 : Basic Linux Commands (Part 1) </h2>
[#90DaysOfDevOps](https://wasimsk.hashnode.dev)

<br>After the Introduction to DevOps, today on our second day we are discussing the very basic linux commands


```ls option_flag arguments ```--> list the sub directories and files avaiable in the present directory


-  ``ls`` --> The ls command is used to list files or directories in Linux and other Unix-based operating systems.




- ``` ls -l ```--> Type this command to list the contents of the directory in a table format with columns including.

- ```ls -a``` --> Type this command to list files or directories including hidden files or directories. In Linux, anything that begins with a . is considered a hidden file.


- ```ls *.sh```--> Type this command to list all the files having .sh extension.
- ```ls -i```--> Type this command to list the files and directories with index numbers inodes
- ```ls -d */```--> Type this command to  list only directories.(we can also specify a pattern)

## Directory commands
- ```pwd``` --> (Print work directory) Use this command to know the present working directory
- ```cd path_to_directory``` --> Use this command to change the directory to the desired path.
- ```cd ~ ``` or just  ```cd ``` --> Use this command to change the directory to the home directory.

- ``` cd - ``` --> Use this command to go to the last working directory.

- ``` cd ..``` --> Use this command to change the directory to one step back.

- ``` cd ../..``` --> Use this command for the contents two levels above.

- ``` mkdir  directoryName``` --> Use this command to make a directory in a specific location

- ``` mkdir .NewFolder ``` --> Use this command to make a hidden directory (also . before a file to make it hidden)


- ```mkdir A B C D ``` --> Use this command to make multiple directories at the same time.

- ```mkdir /home/user/Mydirectory ``` --> Use this command to make a new folder in a specific location

- ```mkdir -p  A/B/C/D ``` --> Use this command to make a nested directory
- ```history``` --> Use this command to get all the used command history.
- ```clear``` --> Use this command to clear the terminal.

- ```rmdir A/B/C/D -p``` --> Use this command to delete a directory. Use -p flag to delete the parent directories as well.

- ```touch Myfile.txt``` --> Use this command to create a file.

- ```cat``` --> Use this command to view the content of a file.


- ```--help``` --> Use this command to know more about the command. Example ```ls --help```.





