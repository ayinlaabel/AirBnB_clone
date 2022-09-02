0x00. AirBnB clone - The console

0x00.Table of contents

0x01 Introduction

0x02 Environment

0x03 Installation

0x04 Testing

0x05 Usage

0x06 Authors

0x01 Introduction

Team project to build a clone of AirBnB.



The console is a command interpreter to manage objects abstraction between objects and how they are stored.



To see the fundamental background of the project visit the Wiki.



The console will perform the following tasks:



create a new object

retrive an object from a file

do operations on objects

destroy an object

Storage

All the classes are handled by the Storage engine in the FileStorage Class.



0x02 Environment

Suite CRM terminal python Suite CRM Suite CRM git distributed version control system Github



Style guidelines:

pycodestyle (version 2.7.*)

PEP8

All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3. The editors used were VIM 8.1.2269, VSCode 1.6.1 and Atom 1.58.0 . Control version using Git 2.25.1.



0x03 Installation

git clone https://github.com/aysuarex/AirBnB_clone.git

change to the AirBnb directory and run the command:



 ./console.py

Execution

In interactive mode



$ ./console.py

(hbnb) help



Documented commands (type help <topic>):

========================================

EOF  help  quit



(hbnb)

(hbnb)

(hbnb) quit

$

in Non-interactive mode



$ echo "help" | ./console.py

(hbnb)



Documented commands (type help <topic>):

========================================

EOF  help  quit

(hbnb)

$

$ cat test_help

help

$

$ cat test_help | ./console.py

(hbnb)



Documented commands (type help <topic>):

========================================

EOF  help  quit

(hbnb)

$
