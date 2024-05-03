The Console for an Airbnb Clone
The Airbnb project at Holberton School entails an extensive exploration of foundational concepts in higher-level programming. The primary aim of this project is to deploy a server replicating the functionality of the Airbnb website, dubbed HBnB. To facilitate object management for this website, a robust command interpreter has been developed.

Functionalities of the Command Interpreter
The command interpreter incorporates several essential functionalities:
Creating a New Object:
Initiating a new instance of an object, such as a User or a Place.
Retrieving an Object:
Fetching an object from a file, a database, or any other data source.
Object Operations:
Performing operations on objects, including counting objects and computing statistics.
Updating Object Attributes:
Modifying attributes of an object as required.
Destroying an Object:
Permanently removing an object.
Table of Contents
Environment
Installation
File Descriptions
Usage
Examples of Use
Bugs
Authors
License
Environment
This project is developed and tested on Ubuntu 14.04 LTS using Python 3 (version 3.4.3).

Installation
Clone this repository: git clone "https://github.com/Official0mega/AirBnB_clone_v4.git"
Access the AirBnb directory: cd AirBnB_clone_v4
Run hbnb (interactively): ./console and enter a command
Run hbnb (non-interactively): echo "<command>" | ./console.py
File Descriptions
console.py - The console serves as the entry point of the command interpreter. It supports the following commands:

EOF - exits the console
quit - exits the console
<emptyline> - overwrites the default emptyline method and does nothing
create - Creates a new instance of BaseModel, saves it (to the JSON file), and prints the id
destroy - Deletes an instance based on the class name and id (saving the change into the JSON file).
show - Prints the string representation of an instance based on the class name and id.
all - Prints all string representations of all instances based or not on the class name.
update - Updates an instance based on the class name and id by adding or updating attribute (saving the change into the JSON file).
