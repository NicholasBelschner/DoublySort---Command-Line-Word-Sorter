# DoublySort-Command-Line-Word-Sorter
DoublySort is a C program that reads a text file, extracts individual words, and provides options for sorting and outputting those words. This README provides an overview of the program's features, and usage instructions.

Features

Command-line argument parsing using getopt.
Reading words from a text file and storing them in a doubly linked list.
Sorting and outputting words to the command line or an output file.
Case-insensitive word processing using the tolower() function.
Usage

Compile the program using a C compiler. For example:

Copy code
gcc -o doublysort doublysort.c
Run the program with the following syntax:

./doublysort [-d] [-o output_file_name] input_file_name
-d: Print sorted words to the command line.
-o output_file_name: Write sorted words to the specified output file.
input_file_name: Provide the input text file.
