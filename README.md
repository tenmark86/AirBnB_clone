AIRBNB CLONE
Built using python language
DESCRIPTION
This project implements the Airbnb clone It uses th BaseModel class as the super class The datetime, cmd and uuid modules are used in its implementation The "shell" works in interactive and non-interactive mode. Every directory is a package

COMMAND INTERPRETER
How to start it:
The command interpreter(shell) is started by running the console.py module:

$./console.py

Usage
It(coommand interpreter) supports various commands: -create -destroy -all -update -quit

create
Creates new instance of BaseModel and saves it to the JSON file and prints a unique id:

$ create BaseModel

destroy
Deletes an instance based on the class name and id(changes are saved in the JSON file):

$ destroy BaseModel 1243-1243-1243

all
Prints string representation of all instances:

$ all

Also prints the string representation of a specified instance:

$ all BaseModel 1243-1243-1243

update
Updates instances based on the class name and id by adding or updating an attribute(saved to the JSON file):

$ update BaseModel 1243-1243-1243 email "airbnbclone@alxSE.com"

## quit
Quits the console:

$ quit

## Author
Mark Mutuota

David Olago
