# AirBnB_clone

AirBnB_clone is a higher-level complete web application composed of a command interpreter, a front-end website, a database, and an API that provides a communication interface between the front-end and data.

## Installation:
Clone the repository https://github.com/laurendobratz00/AirBnB_clone

## Usage:
Back-end access to AirBnB website

## Execution:
Your shell should work like this in interactive mode:
```bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```

Your shell should work like this in non-interactive mode:
```bash
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
```

## Requirements:
-Ubuntu 14.04 LTS

## Files:
- models directory will contain all classes used for the entire project. A class, called “model” in a OOP project is the representation of an object/instance.
- tests directory will contain all unit tests.
- console.py file is the entry point of our command interpreter.
- models/base_model.py file is the base class of all our models.
- models/engine directory will contain all storage classes.