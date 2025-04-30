Command Line Arguments in Python
Last Updated : 17 Mar, 2025
The arguments that are given after the name of the program in the command line shell of the operating system are known as Command Line Arguments. Python provides various ways of dealing with these types of arguments. The three most common are: 

Table of Content

Using sys.argv
Using getopt module
Using argparse module
Using sys.argv
The sys module provides functions and variables used to manipulate different parts of the Python runtime environment. This module provides access to some variables used or maintained by the interpreter and to functions that interact strongly with the interpreter.
One such variable is sys.argv which is a simple list structure. It’s main purpose are:

It is a list of command line arguments.
len(sys.argv) provides the number of command line arguments.
sys.argv[0] is the name of the current Python script.

` import sys

  print(sys.argv[1])
  
  print(sys.argv[2])
  `
  python index.py 1 2
