# Day 4 : Basic Linux Shell Scripting for DevOps Engineers.

 ## What is Kernel
 
 The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.
 
 ## What is Shell

 A shell is a special user program that provides an interface for the user to use operating system services. Shell accepts human-readable commands from a user and converts them into something which the kernel can understand. It is a command language interpreter that executes commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or starts the terminal.
 
 ## What is Linux Shell Scripting?

 A shell script is a computer program designed to be run by a Linux shell, a command-line interpreter. The various dialects of shell scripts are considered to be scripting languages. Typical operations performed by shell scripts include file manipulation, program execution, and printing text.

**Tasks**

 
 - What is `#!/bin/bash?` can we write `#!/bin/sh` as well?
 - Write a Shell Script which prints `I will complete #90DaysOofDevOps challenge`
 - Write a Shell Script to take user input, input from arguments and print the variables.
 - Write an Example of If else in Shell Scripting by comparing 2 numbers


#### Q. What is Shell Scripting for DevOps?

 Shell is a macro processor which allows for interactive or non-interactive command execution. The shell can be defined as a command interpreter within an operating system like Linux/GNU or Unix. The shell allows you by use of commands to interact with your computer, hence retrieve or store data, process information and various other simple or even extremely complex tasks. The shell, acts as the user interface, interpreting user commands and starting applications Scripting. Scripting allows for an automatic command execution that would otherwise be executed interactively one by one.


#### Q. What is #!/bin/bash? can we write #!/bin/sh as well?

 There are different types of shells in Linux. Each of these shells has properties that make them highly efficient for a specific type of use over other shells. some of them are bash (Bourne again shell), bourne shell(sh), shell (csh), Korn shell (shell) etc.
Adding `#!/bin/bash` as the first line of your script tells the OS to invoke the specified shell to execute the commands that follow in the script. `#!` is often referred to as a "hash-bang", "she-bang" or "sha-bang".
`#!/bin/sh`: It is used to execute the file using sh, which is a Bourne shell, or a compatible shell
we can find out which shell we are using in our system by giving a command $ which shell
So, we can use any of the shell types in our scripts based on our use case and the availability of the type of shell we are using in our system.


#### Q. Write a Shell Script that prints 'I will complete the #90DaysOofDevOps challenge'.

 In shell scripting, we use echo to print the output `$ echo ("Hello, World ! ")`

#### Q. Write a Shell Script to take user input, input from arguments and print the variables.

 Here is a shell script, we use the "read" command to take input from the user. Just like how we have a "scanf" statement in C
`$ read <variable_name>`.
Ex. User login to our portal we will ask him his name and show him the message 'Hi <username>, Good Morning !'
 
 
#### Q. Write an example of If else in Shell Scripting by comparing 2 numbers.
 Here "vi" is a CLI text editor just like how we have a notepad in our windows OS.
Inside the file named compare.sh, I have written some lines of the script.
Once script writing is done, I executed the file by giving the command$ bash compare.sh or we can execute it as `$ ./compare.sh` 
Note: In some cases, by default file may not have executable permission. In that case, we need to use `$ chmod +x <filename>` before giving execution commands.
  
  
  
