# alu-AirBnB_clone

# Description
This is the first phase of the AirBnB clone project: a command-line interpreter for managing AirBnB objects. It provides a foundation for future web application development by implementing object creation, storage, retrieval, and manipulation through a simple shell interface.
Command Interpreter
# How to Start
Run the console in interactive mode:
bash$ ./console.py
(hbnb)
Or in non-interactive mode:
bash$ echo "help" | ./console.py
How to Use
The console supports the following commands:

create - Create a new object
show - Display an object
destroy - Delete an object
all - Display all objects
update - Update an object's attributes
quit or EOF - Exit the console

# Examples
bash(hbnb) create User
(hbnb) show User 1234-5678
(hbnb) all
(hbnb) update User 1234-5678 email "user@example.com"
(hbnb) destroy User 1234-5678
(hbnb) quit
Features

BaseModel class for object initialization and serialization
File storage engine using JSON
Multiple model classes: User, State, City, Place, Amenity, Review
Comprehensive unit tests

# Testing
# Run all tests:
bash$ python3 -m unittest discover tests
Run specific test file:
bash$ python3 -m unittest tests/test_models/test_base_model.py
