# Data-Processing-and-Storage

How to Run the Code: 
The code is written in Python so you will need to make sure you have an environment set up that is able to run Python (examples would be PyCharm or VSCode). If you do not have Python set up, you will need to install it first. You can install python from https://www.python.org/downloads/

To run the code you will edit the InMemoryDB file and write your testing code beneath the class code. You need to make an instance of the inMemoryDB class. 
ex. new_db = inMemoryDB()

Then you can call each of the functions of the inMemoryDB class and see the output in the command line. 
ex. new_db.begin_transaction()
ex. new_db.put('five', 5)


Future Suggestions:
I think this assignment can be modified by giving specific error messages that should pop up when a user does an action that is not supported (ex. trying to put something when a transaction is not running). Currently I made up error messages based on what I thought they should be, but having clear expected error messages would make this a lot easier to understand and test. An additional method that could be added is a delete functionality that would delete a key value pair from the database if it exists. Finally, my last suggestion would be to maybe give some starter skeleton code for students in several different languages. This would help structure our code properly and have uniform file and class names, making the project easier to grade as well.
