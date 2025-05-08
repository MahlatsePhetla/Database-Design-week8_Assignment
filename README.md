# Database-Design-week8_Assignment

#Library Management System 

##This ERD represents the database design for a Library Management System. It manages books, authors, members, borrowing activities and staff roles.

##It has the following Table

- Authors: Stores information about authors.

- Books: Contains book details like title.

- Book_Authors: Resolves the many-to-many relationship between books and authors.

- Members: Represents library members who borrow books.

- Staff: Represents library staff responsible for issuing books.

- Borrow_Records: Logs every book borrowing event, tracking dates and borrower.


2.  Each Book can have many Authors - Many to many relationships

    One Member can borrow many Books -One to many relationships

    One Staff issues many Books -one to many realtionships

    Each Book can appear in many borrow records -One to many relationships.

3.This Database helps ensure data is organized and the system can efficiently manage library operations.

#Steps to set up the project.

1. Open MySQL Workbench
2. Create a new database
3. Import  SQL file
4. Final Database is created with tables and relationship.

