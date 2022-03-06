# what is the terminal?
-It is important to get familiar with the terminal as a developer. With the terminal we can do a series of tasks, for example:
    1- Navigate throughout my system folders and files.
    2- Set up cloud servers.
    3-Run tests.
    4-Manage and update the databases for your apps!

# The terminal is also our user interface that connects us to our operating system.
- We interact everyday with our operating system, and the graphical system, that ys why we can see the icons and dibujitos. THE TERMINAL is basically the same but it is a command line or CLI (command line interface).
-Regulars user will not use the terminal, instead they use icons or GUIs to manage and organize information in their computers, but as a developers we need to use the terminal!!!!!

# Commands in the terminal:

    1-CAT: This will give you access to a particular file and it will display the text in the terminal window.
        for example: If we type, cat todo.txt it will access out to do file because it is within out ~/home/Xiomina, BUT if we want to access to another file like cat diary. txt we will get an answer like "no such a file or directory" because we gave it a bad path and my terminal still thinks that I am at ~/home/Xiomina. For this, there are two ways to access that directory, and we aware that we have to give it a good path. 
        2- RELATIVE PATH, and this will be: cat documents/diary.text (Notice that we do not need a slash for the first directory becaue we are already in and it is the root directory of the machine.)
        3- ABSOLUTE PATH, this will be: cat/home/xiomina/documents/diary.txt. The outpus it the same.
        4- But, I can do something dofferent and it is moving from where I am looking, in this case, I will move from Home to  to documents. 
    2- CD directory:  Following the last example, we can just use:
        CD documents and THEN use cat --> cd documents
                                            cat  diary.txt ---> the output will be the same.

# More Basic Commands: 

    1- PWD(Present working sirectory), use this when you do not know where you are! lol, I truly don't know.
    2- ls: use this command to see all the files that are in the currently directory you are at. 
    3- ls -l( list files-long form): Use the 'ls -l' command to see a long form, representation of the directories and files inside your current directory.
    4 -cd: 
    5- cd / :This command will change to the root directory of your computer. From this folder, you can access your application folders.
    6- mkdir new_directory_name: This command will make a new directory named 'new_directory_name'. Whatever argument you pass into this command will be the name of your new file. After making the directory, you could run 'cd new_folder_name' to enter into that directory.
    7 - rm directory_name or rmdir directory_name : Delete an empty folder.
    8- rm -rf directory_name : Delete a non-empty folder

