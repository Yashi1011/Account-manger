# Account Manager

### How the code is managed

The above code is divided into different functions which include,
+ `welcome()`
+ `home(address)`
+ `login()`
+ `register()`
+ `validate(address, password)`
+ `addToDatabase(address, password)`
+ `transfer(address)`

The `welcome()` function is called initially and then different functions are returned according to the instructions.

## Getting started 

### Libraries used:-
+ `ipywidgets` - To create basic widgets. [Click here](https://ipywidgets.readthedocs.io/en/latest/).
+ `IPython.display` - To displaye the created widgets. [Click here](https://ipython.org/ipython-doc/dev/api/generated/IPython.display.html).
+ `mysql.connector` - To establish a connection to the sql server. [Click here](https://github.com/Yashi1011/SQL-Python).
+ `urllib` - To enter the cluster credentials. [Click here](https://docs.python.org/3/library/urllib.html).


### Conclusion.
This code makes use of database to store and access accounts.

We can either 
+ Create a new account in the database

or
+ Modify the account

As the code makes use of databse, we can store info of many people.
As the code progresses according to conditions, it is secure to use.

We can implement this in many __Banking Applications.__



