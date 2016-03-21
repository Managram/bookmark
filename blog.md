Understanding Databases
-------------------

**Persistence** in computer science is when some form of data is saved after the time that you created it.

Why persist data?
-----------------

We persist data because sometimes we are going to need for longer than the process created it.

**Example**
 When you sign up on a website you are required to add some user information in the sign up form. You would want that data to be stored some where so that you don't have to provide it again every time you visit the website.

Database Persistence vs. Session Persistence
-----------------

Like in the example earlier, if you sign up all that information can be made to exist on the website during the whole period that you are signed up. It can be stored in something called a **session**. The problem with that is that once you end the session by closing your browser or ending the connection, the information is completely gone from the session.
**Session only last for the time it takes to complete the task or transaction**
Database Persistence on the other hand is persistence over the long term. You would store all this information in an organized collection usually consisting of columns and rows. This collection is called a **database**. You can also store this information in the files and read and write the files whenever you need to access the information in it.


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

**TABLE:** A database is typically made up of tables that are divided into columns horizontally.

**ROW:** Each row is an individual record in the the table. Usually displayed horizontally

**COLUMN:** These records are divided into columns, columns are representation of the fields in the records.

Like Excel.

**PostgreSQL:**  is an open source relational database management system
a **Relational Database System** is any database structured to recognize relations between stored items of information.
