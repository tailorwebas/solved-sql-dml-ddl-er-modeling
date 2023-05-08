Download Link: https://assignmentchef.com/product/solved-sql-dml-ddl-er-modeling
<br>
Starting this week, we are going to do DDL/DML exercises. As I mentioned in our previous lectures that any kind of development work requires “Empirical Science”. I stated this in our lesson like the other famous “Computer Scientists” in the past. It means that the only way to learn is to get your hands dirty and see how they work. That’s the only way to understand how they tick. In addition, we will be doing relationship diagram exercises as well to prepare you for your Signature Assignment that is due at the end of the trimester. Check your previous lessons, labs, and writing assignments for references how to do these labs and assignments.

Note:1.      Include the DDL, DML, and the output. You may cut and paste.

2.      The exercises are like your “Midterm”, but they are much in a bigger scale.

3.      The labs and writing assignment will also help you to do your Signature Assignments. Your “SA” could be used as a portfolio, a proof that you’re able to perform basic application DBA, system DBA, Database concepts/design, and system environment setup.

4.      Your remaining labs and writing assignments will be combined with increasing difficulty. Therefore, you should be able to perform the previous labs to do the upcoming labs.

II – DDL SQL Exercises

i.            Create tables (Create DDL) 4 points (Application DBA/Developer)Instruction: Don’t use the tools to create the tables. Use the command line of DBMS. Cut and paste your answer.

Table 1 (2 points):  Create a table named “PERSON” table with a person ID. Table includes first name, last name, height, weight, hair color, and eyes color. The primary key is the person ID. Note: You may use datatype “varchar” on all of them. And make all the tables created with “uppercase”.

ANS: Cut and paste your DDL and the output of your command here (inside of this box).

Table 2 (2 points): Create a table named “CAR” table with a VIN #, color of the car, type of car, length, &amp; person owner id. The primary key is the VIN # and the foreign key is the person owner id. Note: You may use datatype “varchar” on all of them. And make all the tables created with “uppercase”.

ANS: Cut and paste your DDL and the output of your command here (inside of this box).

ii.            Create a relationship (Create DDL) – 4 points. (Application DBA/Developer)

Instruction: Don’t use the tools (Workbench/Oracle Modeler) to create the relationship. Use the command line. See your previous lessons for references.

Writing Assignment Story: Based on the tables you just created, according to the

requirements, this “PERSON” owns many “CARS” because he/she loves cars.

1.       (2 points) Is this 1 to 1, 1 to many, or many to many? Please explain your reason why it’s 1:1, 1:M, M:M.

Write your answer here inside of this box (sentences):

2.       (2 points) Based on your analysis on #1, create the DDL (relationship) from #1.

ANS: Cut and paste your DDL and the output of your command here (inside of this box).

III – DML Exercises (12 points) – (Application DBA/Developer)

Instruction: You’re going to perform select, insert, update, and delete that you created on “Section II.” Before you start doing this part, make sure you have created two tables and established a relationship based on “II-DDL SQL Exercises” section.

Note: Check the previous lesson (syntax) how to do this or you may google it. Try to understand the concept first before you memorize it. We’ll do this weekly so that you’ll get used to it.

1.       INSERT: Based on the Table 1 you just created it, insert the following data (1 point)

Person ID: 1001

Height: 66 inches

Eyes: Brown

Hair: Red

First Name: Jim

Last Name: Crow

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

2.       INSERT: Based on the Table 1 you just created it, insert the following data (1 point)

Person ID: 1002

Hight: 59 inches

Eyes: Blue

Hair: Black

First Name: Liza

Last Name: Sanchez

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

3.       INSERT: Based on the Table 1 you just created it, insert the following data (1 point)

Person ID: 1003

Height: 72 inches

Eyes: Green

Hair: Blond

First Name: Greg

Last Name: Pitt

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

4.       INSERT: Based on the Table 2 you just created it, insert the following data (1 point).

VIN #: 2GKALWEK3C6142125

Color: White

Length: 16.4 ft.

Person ID: 1001

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

5.       INSERT: Based on the Table 2 you just created it, insert the following data (1 point)

VIN #: 19UYA31581L000000

Color: Red

Length: 20.4 ft.

Person ID: 1002

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

6.       INSERT: Based on the Table 2 you just created it, insert the following data (1 point)

VIN #: 29TYA31581L0012340

Color: Yellow

Length: 18.5 ft.

Person ID: 1010ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

Note: You would get an error here. Explain why?

7.       INSERT: Based on the Table 2 you just created it, insert the following data (1 point)

VIN #: 555YA31668190012733

Color: Green

Length: 3.5 ft.

Person ID: 1001

ANS: Cut and paste snapshot of your command line here. Run it and paste the resUlts inside of this box.

8.       UPDATE: Update VIN # 19UYA31581L000000 by changing the Length of the car to 15 ft. (1 point)

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

9.       UPDATE: Update Person’s height with the Person ID # of 1001. The height is 52 inches. (1 point)

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

10.   DELETE: Delete a row on “CAR” table with a VIN # of 555YA31668190012733. Display all the contents. (1 point)

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

11.   SELECT: Display all the rows and columns of Person Table. (1 point)

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

12.   SELECT: Display all the rows and columns of Car Table. (1 point)

ANS: Cut and paste snapshot of your command line here. Run it and paste the results inside of this box.

IV – Database Administrator (System Level) – 6 points

Learning the “Principles of Database” is not complete until you learn the basic administration of the DBMS (Database Management System). In this part of exercise, we’re going to perform database catalog search. This is one of the tasks of being DBA by browsing around the contents of your database. Catalog consists of metadata (stored in tables) in which definitions of DB objects such as base tables, synonyms, indexes, users, etc. are stored. If you don’t have “GUI” but a command line, knowing the catalog of your database will give you more the inner workings of how your objects stored and recorded.

1.       (2 points) Create a user “MAYA” with any password. Check your previous lab how to create a user. After you create the user, check if the user “MAYA” is created by using this command below:

Oracle Command: “DBA_USERS” table is one of the tables where it keeps all the usernames

being created. Only a person with a DBA privilege able to “Select” this table.MySQL Command:

Note: As a DBA, you should be able to check user’s existence.

NS: Cut and paste your screenshot’s output here. Check if your user is created. (1 point)

2.       (2 points) The CAR and PERSON tables you created. Check if they are created by using this command:

As a DBA, you will be able to view and query the contents of “DBA_TABLES” (Oracle) or INFORMATION_SCHEMA.TABLES (MySQL) where all the tables’ names are created. You don’t update these tables because they are being managed by the DBMS. You’ll corrupt your DB if you mess around with these tables. You only query these tables to see if your DB objects creation work.

Oracle Command:

MySQL Command:

ANS: Cut and paste your screenshot’s output here. Check if your user is created. (1 point)

3.       (2 points) Check the columns of each table – CAR and PERSON. Check the columns by using this command:

desc &lt;table name;

Note: There is a semi-colon at the end of the command. It means end of the command and execute it.

Cut and paste your screenshot’s output here. Check if your user is created. (1 point)V – Entity-Relationship Modeling (Application DBA/Developer)– 4 points

Entity Relationships

Instruction: Use your tool to create the relationships and the table. Conceptual design is only required to create the diagram. If you want to include the logical design by adding attributes along with it, that’s fine. Note: No DML or DDL required on this part of the lab.

1.       (1 point) Each “Division” has many “Branches”.

Paste your diagram here using your tool (Oracle Modeler/MySQL Workbench)2.       (1 point) “Employees” reports to many “Managers” and Managers are assigned with many “Employees”.

Paste your diagram here using your tool (Oracle Modeler/MySQL Workbench)

3.       (1 point) “Staff” may be assigned to different “Department”.

Paste your diagram here using your tool (Oracle Modeler/MySQL Workbench)

4.       (1 point) “Employees” are assigned to many “Projects”. Each “Project” is assigned to one and only one “Manager”.

Paste your diagram here using your tool (Oracle Modeler/MySQL Workbench)