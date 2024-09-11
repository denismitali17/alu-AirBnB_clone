# AirBnB clone - The console 🏠🏠

![295226950-9f3f3ede-75d4-44fc-a1b3-7a71152e9633](https://github.com/user-attachments/assets/7313191b-b6e5-455a-97ee-f7212c3f49e9)



# Description of the project

This project is a simple clone of the AirBnB website. The first stage implements a backend interface or console to manage program data(like shell). Console commands allow users to create, update, destroy objects, and manage file storage. 

# The console - tasks
-  Put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of  future instances <br>
-  Create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
-  Create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
-  Create the first abstracted storage engine of the project: File storage.
-  Create all unittests to validate all our classes and storage engine


# Description of the command interpreter

The command interpreter helps us to manage the objects of our project by:

- Creating a new object (ex: a new User or a new Place)
- Retrieving an object from a file, a database etc…
- Doing operations on objects (count, compute stats, etc…)
- Updating attributes of an object
- Destroying an object

alu-AirBnB
An AirBnB clone project.

Description
alu-AirBnB is a full stack web application that replicates main functionalities of AirBnB App. It integrates database, a back-end API, and a front-end. This is the foundational of a larger project, with CLI for managing data, including user and place objects, and setting up the base classes for future expansions like HTML/CSS , database storage, APIs, and front-end integration etc.

Key Features
Custom CLI to manage application data
Supports(CRUD) operations, create, read, update, and delete for different objects
BaseModel class for handling serialization/deserialization of objects
File storage engine
Unit tests
How to Start
To start the command interpreter:

Clone this repository: bash using git clone  cd cloned project  Start the command interpreter: bash ./console.py 

Usage
In the command-line interpreter, you can:

Create a new object (e.g., User, Place):

 create User
 create Place
Retrieve an object:

show User <user_id>
Update attributes of an object:

 update User <user_id> name "New Name"
Delete an object:

 destroy User <user_id>
Quit the interpreter:

quit

## How
``` to use the interpreter

## Tests
To run all the tests execute the following command:

```bash
$ python3 -m unittest discover tests
```
You can also run a single test by specifying the test file:

```bash
$ python3 -m unittest tests/test_models/test_city.py



# Authors

## [`Denis Mitali`](www.linkedin.com/in/mitali-denis-9826a02ba)
## [`Liliane Gikundiro`](https://www.linkedin.com/in/gikundiro-liliane/)
