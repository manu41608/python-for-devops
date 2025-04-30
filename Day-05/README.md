# Command Line Arguments in Python

The arguments that are given after the name of the program in the command line shell of the operating system are known as Command Line Arguments. Python provides various ways of dealing with these types of arguments. The three most common are: 

Table of Content

Using sys.argv
Using getopt module
Using argparse module
## Using sys.argv

```
import sys

print(sys.argv[1])
  
print(sys.argv[2])
  ```
  python index.py 1 2


# Environment Variables in Python

Environment variables are key-value pairs that live in our system’s environment. Python reads some of these variables at startup to determine how to behave, for example, where to look for modules or whether to enter interactive mode.


Example:


export token="123drr”

```
import os

print(os.getenv("token"))

```

