# Shell-Commands
  - Executes in Linux Shell which supports commands with multiple arguments 
  - Handles interrupt signal.
  - Written in C programming language.
  - Works on a linux server.

## How to Run
  - Save the code in a file named 'code.c' and then save it in a directory.
  - For running the code, type 'gcc code.c -pthread -o code'
  - Then press 'Enter' and type './code'
  - Try executing various commands as mentioned below:

    ### One word commands:
    ls - lists contents of a directory
    pwd - prints name of the current directory. 

    ### Two word commands:
    mkdir Student - makes a directory named Student.
    du code.c - estimates file space usage.
    rm code - removes file named code

    ### Three word commands:
    cp code.c copycode.c - copies the contents of code.c to copycode.c
    mv code.c copycode.c - renames the file name from code.c to copycode.c

## How to catch interrupt signal
  - Press Ctrl+C and a message will be displayed stating 'Ctrl+C was pressed by user'.

## How to exit the program
  - Type 'exit' and the program will end.

 **Programmer: Saee A. Gore**
