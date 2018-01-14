# DBMS
A database management System in java which accepts requests for data from the application program and instructs the
operating system to transfer the appropriate data and store it in a specific format.

# Design pattern
Some of the design pattern used in this app:
- Singleton design pattern :in our application we just need one object
for each parser class, DataBaseControl class and Printer class so we
use singleton pattern by applying private constructor and static
method to get an instance of the classes.
- Delegation design pattern: We use object from data base control
inside parser class to use function of SQL command , and object
from printer inside database control class.
- Interface Design pattern : We provide interface for parser ,
Database control ,printer and save and load .
- MVC : 
  - Model to hanle write and read in json or XML file 
  - View to handle printing output of The DBMS in table.
  - Controller to handle the interaction of model and view.

