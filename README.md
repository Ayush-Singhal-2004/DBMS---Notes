<h1>Unit 1</h1>

<h3>Q1 : What is DBA?</h3>
- Database Administrator (DBA) is a person responsible for the installation, configuration, upgrading, monitoring, maintenance & security of databases in an organization. They are overall commander of Database system. He also co-ordinates & implements security measures to save the database. </br>

<h3>Q2 : What are the responsibility of DBA?</h3>
- responsibility of DBA are: </br></br>
i. Deciding the hardware device, depending upon the cost, performance and efficiency of the hardware, it is DBA who have the duty of deciding which hardware device will suit the company requirement. It is hardware that is an interface between end users and database so it needed to be of best quality. </br>
ii. Decides Data Recovery and Back up method </br>
iii. Managing Data Integrity: Data integrity should be managed accurately because it protects the data from unauthorized use. DBA manages relationship between the data to maintain data consistency. </br>
iv. Database design:The logical design of the database is designed by the DBA.</br>
v. Implement Security Feature: DBA maintains the database is not accessible by unauthorized user. DBAs control who has access and what type of access they are allowed. For instance, a user may have permission to see only certain pieces of information, or they may be denied the ability to make changes to the system. </br>
vi. Decides content of the database: A database system has many kind of content information in it. DBA decides fields, types of fields, and range of values of the content in the database system. One can say that DBA decides the structure of database files.</br>
vii. Provides help and support to user: If any user needs help at any time then it is the duty of DBA to help him. Complete support is given to the users who are new to database by the DBA.</br>

<h3>Q3 : Explain client/server architectrure?</h3>
- The client-server architecture is the most common distributed system architecture which decomposes the system into two major sub-systems or logical processes.</br>
i. Client − This is the first process that issues a request to the second process i.e. the server. </br>
ii. Server − This is the second process that receives the request, carries it out, and sends a reply to the client. </br>
- In this architecture, the application is modelled as a set of services that are provided by servers and a set of clients that use these services. </br>

<h3>Q4 : What is distributed database?</h3>
- A distributed database is basically a database that is not limited to one system, it is spread over different sites, i.e, on multiple computers or over a network of computers. </br>
- A distributed database system is located on various sites that don’t share physical components. This may be required when a particular database needs to be accessed by various users globally. It needs to be managed such that for the users it looks like one single database. </br>
- FEATURES OF DISTRIBUTED DATABASES: </br>
i. Location independency  </br>
ii. Distributed query processing </br>
iii. Distributed transaction management  </br>
iv. Seamless integration </br>
v. Transaction processing </br>

<h3>Q5 : Explain the term DBMS?</h3>
- Database Management System is a collection of programs that enable you to store ,modify & extract information from a database. </br>
- The DBMS provides user and programmer with a systematic way to create, retrieve, update and manage data. </br>
- It allows to user creation and manipulation of database. </br>
- It allowing users to store and analyze data easily. </br>
- DBMS provides us with an interface or a tool, to perform various operations like creating database, storing data in it, updating data, creating tables in the database etc. </br>
- The DBMS is most useful for providing a centralized view of data that can be accessed by multiple users, from multiple locations in a controlled manner. </br>
- End users and software programs are free from having to understand where the data is physically located or what type of storage media is used because the DBMS handles all the requests. </br>

<h3>Q6 : Define instances?</h3>
- The data stored in database at a particular moment of time is called instance of database. Database schema defines the variable declarations in tables that belong to a particular database; the value of these variables at a moment of time is called the instance of that database. </br>

<h3>Q7 : What is a data model?</h3>
- In simple terms, a data model in a Database Management System (DBMS), it is like a blueprint that defines how data is organized, stored, and accessed in a database. It specifies the structure of the data, the relationships between different pieces of information, and the rules for interacting with the stored data.

<h3>Q8 : Give the levels of data abstraction (schema)?</h3>
- In a Database Management System (DBMS), there are three levels of data abstraction : </br>
i. Physical Level : Deals with how data is stored and retrieved at the lowest level, involving details such as storage structures, file organization, and access mechanisms. </br>
ii. Logical Level : Focuses on representing the data independent of how it is physically stored. This level defines the database schema, specifying tables, relationships, and constraints. </br>
iii. View Level : Presents a higher-level, user-friendly abstraction of the data. It involves creating views that display specific subsets of the database for different users or applications, providing a customized perspective on the data. </br>

<h3>Q9 : Define the term record in DBMS?</h3>
- In a Database Management System (DBMS), a record refers to a collection of related data items that are treated as a single unit. It is often used to represent a row in a database table. Each record contains fields, which store specific pieces of information, and these fields collectively represent a complete set of data for a particular entity or object within the database. </br>

<h3>Q10 : Describe various disadvantages of file system as compared to database management system?</h3>
i. Data Redundancy : In a file system, data may be duplicated across multiple files, leading to redundancy and inconsistency. </br>
ii. Data Inconsistency : Updates or changes to data in a file system can result in inconsistencies if not properly managed, as there's no centralized control. </br>
iii. Limited Data Sharing : File systems make it challenging to share data between different applications or users efficiently. </br>
iv. Data Dependence : Programs are closely tied to the file structure, making it difficult to modify the structure without affecting the applications. </br>
v. Concurrency Issues : File systems may lack mechanisms to handle concurrent access to data, leading to potential conflicts and data integrity problems. </br>
vi. Security Concerns : File systems often have limited security features, making it harder to control access and protect sensitive information. </br>
vii. Lack of Data Integrity : Ensuring data integrity in a file system is more challenging, as there is no built-in support for constraints or rules. </br>
viii. Limited Query Capabilities : Retrieving specific data can be cumbersome in file systems, lacking the powerful querying capabilities provided by database management systems. </br>

<h3>Q11 : What is Distributed DBMS? Explain advantages of DBMS and Distributed DBMS?</h3>
- A Distributed Database Management System (DDBMS) is a system that manages a database across multiple locations or nodes, allowing data to be stored and accessed from different locations. </br></br>
- Advantages of DBMS : </br>
i. Data Centralization : DBMS centralizes data storage, reducing redundancy and improving data consistency. </br>
ii. Data Integrity : Enforces rules and constraints to maintain data accuracy and integrity. </br>
iii. Data Security : Provides access control features to secure sensitive information. </br>
iv. Concurrency Control : Manages simultaneous access to data, preventing conflicts and ensuring consistency. </br>
v. Data Independence : Separates the physical storage details from the application, allowing easier changes to the database structure. </br></br>
- Advantages of Distributed DBMS : </br>
i. Improved Performance : Distributing data across multiple locations can enhance query and transaction performance. </br>
ii. Increased Availability : Redundant data storage across nodes improves system availability; if one node fails, others can still provide access to the data. </br>
iii. Scalability : Allows for easy expansion by adding more nodes, accommodating growing data and user needs. </br>
iv. Fault Tolerance : Redundancy and distribution contribute to fault tolerance, reducing the impact of node failures. </br>
v. Local Autonomy : Each site in a distributed system can manage its data independently, making it more responsive to local needs. </br>
vi. Reduced Data Transfer : Minimizes the need for transferring large amounts of data between locations, optimizing network usage. </br>

<h3>Q12 : Define Database Anomalies?</h3>
- Database anomalies are errors or inconsistencies that can occur in a database due to issues like incomplete or conflicting information. These anomalies can be of three types : </br>
i. Insertion Anomaly : Adding new data may be challenging if the required information includes fields that can't be left blank. </br>
ii. Deletion Anomaly : Removing data related to a certain entity may unintentionally eliminate information about another entity. </br>
iii. Update Anomaly : Modifying data in one place might result in inconsistencies if the change is not propagated to all relevant locations. </br>

<h1>Unit 2</h1>

<h3>1. Define entity?</h3>
- A real-world thing either living or non-living that is easily recognizable and nonrecognizable. </br>
- It is anything in the enterprise that is to be represented in our database. </br>
- It may be a physical thing or simply a fact about the enterprise or an event that happens in the real world. </br></br>
- Examples of entities:
i. Person: Employee, Student, Patient </br>
ii. Place: Store, Building </br>
iii. Object: Machine, product, and Car </br>
iv. Event: Sale, Registration, renewal </br>
![](https://qph.cf2.quoracdn.net/main-qimg-d1114e14f139d17718b8c1b9d1772680)
</br>
- Entity Set : It is a collection of the entities of the same type i.e. entities which share some common property or object. Example - </br> 
i. The collection of all the students from the student table at a particular instant of time is an example of 
an entity set. </br>
ii. The collection of all the employees from the employee table at a particular instant of time is an example of entity set. </br>
![](https://www.gatevidyalay.com/wp-content/uploads/2018/05/Weak-Entity-Set-Example.png)
</br>
- Entity Type: It refers to the category that a particular entity belongs to. </br>
i. A table named student in a university database. </br>
ii. A table named employee in a company database. </br>
![](https://afteracademy.com/images/what-is-an-entity-entity-type-and-entity-set-entity-set-example-63baca2f9d502076.jpg)
</br>

<h3>2. Define weak and strong entity?</h3>
</br>
![](https://cms.boardmix.com/images/articles/entity-in-dbms.png)
</br>
i. Strong Entity Type : </br>
-  It is also called Long or Independent Entity. An entity type which has primary key is termed as Strong Entity. </br>
- It is represented by a rectangle. In the above example, Roll_no identifies each element of the table uniquely and hence, we can say that STUDENT is a strong entity type. </br>
![](https://static.javatpoint.com/dbms/images/entity-in-dbms2.png)
</br>
ii. Weak Entity Type : </br>
- It is also called as Dependent Entity.Weak entity type doesn't have a key attribute. </br> 
- Weak entity type can't be identified on its own. It depends upon some other strong entity for its distinct identity. </br>
- There can be a room only if building exits. There can be no independent existence of a room. </br>
- A weak entity is represented by a double outlined rectangle.For example – a bank account cannot be uniquely 
identified without knowing the bank to which the account belongs, so bank account is a weak entity. </br>
![](https://static.javatpoint.com/dbms/images/entity-in-dbms3.png)
</br>

<h3>3. How many relationships are possible between two entities ?</h3>
- In a relational database management system (DBMS), the possible relationships between two entities are typically categorized as one-to-one, one-to-many, or many-to-many. These relationships define how records in one table are related to records in another. </br>

<h3>4. what is primary key?</h3>
- Primary key is a candidate key that is most appropriate to become the main key for any table. </br>
- It is a key that can uniquely identify each record in a table. </br>
- There can be more than one candidate key in a relation out of which one can be chosen as primary key. </br>
- For Example, STUD_NO as well as STUD_PHONE both are candidate keys for relation STUDENT but STUD_NO can be 
chosen as primary key (only one out of many candidate keys). </br>

<h3>5. Define many to many relationships ?</h3>
- In a many-to-many relationship in a database, multiple records in one table can be associated with multiple records in another table, and vice versa. This is achieved through the use of an intermediary or junction table that links the related records. This intermediary table contains foreign keys from both tables, establishing connections between them. Many-to-many relationships are common when entities can have multiple instances related to each other. </br>

<h3>6. List various types of attributes?</h3>
- In a database management system (DBMS), attributes are characteristics or properties that describe the entities in a database. There are various types of attributes, including : </br>
i. *Simple Attribute:* Represents atomic, indivisible values. </br>
ii. *Composite Attribute:* Composed of multiple simple attributes that can be further divided. </br>
iii. *Derived Attribute:* Calculated or derived from other attributes in the database. </br>
iv. *Key Attribute:* Part of the primary key that uniquely identifies a record in a table. </br>
v. *Single-valued Attribute:* Holds a single value for each entity. </br>
vi. *Multi-valued Attribute:* Can hold multiple values for a single entity. </br>
vii. *Null Attribute:* Represents an unknown or undefined value. </br>

<h3>7. Explain primary key and foreign key?</h3>
- Primary Key : </br>
i.  Primary key is a candidate key that is most appropriate to become the main key for any table. </br>
ii. It is a key that can uniquely identify each record in a table. </br>
iii. There can be more than one candidate key in a relation out of which one can be chosen as primary key. </br>
iv.  For Example, STUD_NO as well as STUD_PHONE both are candidate keys for relation STUDENT but STUD_NO can be chosen as primary key (only one out of many candidate keys).   </br> </br>
- Foreign Key : </br>
i. Foreign keys are the column of the table which is used to point to the primary key of another table. </br>
ii. If an attribute can only take the values which are present as values of some other attribute, it will be foreign key to the attribute to which it refers.  </br>
iii. In a company, every employee works in a specific department, and employee and department are two different entities. </br>
iv. So we can't store the information of the department in the employee table That's why we link these two tables through the primary key of one 
table.</br>
v. We add the primary key of the DEPARTMENT table, Department_Id as a new attribute in the EMPLOYEE table.</br>
vi. Now in the EMPLOYEE table, Department_Id is the foreign key, and both the tables are related. Generally foreign key is a primary key from one table, which has a relationship with another table. </br>

<h3>8. Explain super key and Candidate key?</h3>
- Super Key : </br>
i. A super key is a set of attributes that can identify each tuple uniquely in the given relation. </br>
ii. A super key is not restricted to have any specific number of attributes. Thus, a super key may consist of any number of attributes. </br>
iii. Super Key is a superset of Candidate key. </br>
iv.  In the table defined above super key would include student_id, (student_id, name), phone etc.  </br></br>
- Candidate Key : </br>
i. Candidate keys are those attributes that uniquely identify rows of a table. </br>
ii.  The Primary Key of a table is selected from one of the candidate keys. </br>
iii. So, candidate keys have the same properties as the primary keys explained above. There can be more than 
one candidate keys in a table.  </br>
iv. In our example, student_id and phone both are candidate keys for table Student. </br></br>
◦ A candidate key can never be NULL or empty.  </br>
◦ Its value should be unique.</br>
◦ There can be more than one candidate keys for a table.</br>
◦ A candidate key can be a combination of more than one columns(attributes).</br>

<h3>9. Briefly explain various types of database models?</h3>
- Database models in Database Management Systems (DBMS) provide conceptual frameworks for organizing and structuring data. Here are brief explanations of various types of database models :</br>
i. *Hierarchical Model :* </br>
- Represents data in a tree-like structure.</br>
- Parent-child relationships between data elements.</br>
- Widely used in early databases.</br></br>
ii. *Network Model:*</br>
- Extends the hierarchical model with more complex relationships.</br>
- Records can have multiple parent and child records.</br>
- Uses pointers to establish connections between records.</br></br>
iii. Relational Model:*</br>
- Organizes data into tables (relations) with rows and columns.</br>
- Emphasizes the use of primary and foreign keys to establish relationships.</br>
- SQL (Structured Query Language) is commonly used to manipulate data.</br></br>
iv. *Entity-Relationship Model (ER Model):*</br>
- Represents entities, their attributes, and relationships between entities.</br>
- Uses diagrams to visualize the structure of the database.</br>
- Often used during the initial design phase.</br></br>
v. Object-Oriented Model:*</br>
- Represents data as objects, which can encapsulate both data and methods.</br>
- Supports concepts like encapsulation, inheritance, and polymorphism.</br>
- Suitable for complex data structures and real-world scenarios.</br></br>
vi. Object-Relational Model:*</br>
- Combines features of both relational and object-oriented models.</br>
- Extends the relational model to handle complex data types.</br>
- Supports object-oriented concepts within a relational database.</br></br>
vii. *NoSQL Models (e.g., Document, Key-Value, Graph, Column-Family):*</br>
- NoSQL databases provide flexible structures for various types of data.</br>
- Document databases store data in JSON-like documents.</br>
- Key-Value stores use simple key-value pairs.</br>
- Graph databases model relationships between entities.</br>
- Column-Family stores organize data in columns rather than rows.</br></br>
* Each model has its strengths and weaknesses, and the choice depends on the specific requirements and characteristics of the data being managed.</br>

<h3>10. Draw and explain ER diagram for college management system?</h3>
- Representation of an Entity-Relationship (ER) diagram for a college management system. </br></br>
i. Entities :</br>
1. *Student:*</br>
- Attributes: StudentID (Primary Key), Name, DateOfBirth, Email, Phone</br>
2. *Course:*</br>
- Attributes: CourseID (Primary Key), Title, Credits</br>
3. *Faculty:*</br>
- Attributes: FacultyID (Primary Key), Name, Email, Phone</br>
4. *Department:*</br>
- Attributes: DepartmentID (Primary Key), Name, HeadOfDepartment</br>
5. *Class:*</br>
- Attributes: ClassID (Primary Key), ClassName</br>
6. *Enrollment:*</br>
- Attributes: EnrollmentID (Primary Key), StudentID (Foreign Key), CourseID (Foreign Key), EnrollmentDate</br>
7. *Teaching:*</br>
- Attributes: TeachingID (Primary Key), FacultyID (Foreign Key), CourseID (Foreign Key) </br></br>
ii. Relationships : </br>
- One-to-Many relationship between Department and Faculty (One Department can have many Faculty members).</br>
- One-to-Many relationship between Department and Course (One Department can offer many Courses).</br>
- Many-to-Many relationship between Student and Course through Enrollment (A Student can enroll in many Courses, and a Course can have many Students).</br>
- Many-to-Many relationship between Faculty and Course through Teaching (A Faculty member can teach many Courses, and a Course can be taught by many Faculty members).</br></br>
* This ER diagram represents the basic structure of a college management system, capturing relationships between students, courses, faculty, departments, classes, and enrollments.</br>

<h3>11. What is weak attribute?</h3>
- In database management systems (DBMS), a weak attribute is an attribute that does not have a primary key of its own. It is dependent on a strong entity, typically part of a composite key, for its existence. </br></br>
- Unlike strong attributes, weak attributes cannot uniquely identify an entity on their own. They need the support of the associated strong entity and its primary key. Weak entities and their weak attributes are often used in situations where certain properties are only meaningful in the context of another entity.</br></br>
- For example, consider a "Room" entity with a weak attribute "RoomNumber." The RoomNumber alone may not be unique across all rooms in a building, but when combined with the building's identity, it becomes unique. In this case, the Room entity is the strong entity, and RoomNumber is a weak attribute.</br></br>

<h3>12. Design an ER diagram for university registrar office.office maintains data about each class,including the constructor,the enrolment,time and place of the class meeting?</h3>
- Entity-Relationship (ER) diagram for a university registrar office : </br>
i. Entities:</br></br>
1. *Class:*</br>
- Attributes: ClassID (Primary Key), ClassName, Instructor, Time, Place</br>
2. *Enrollment:*</br>
- Attributes: EnrollmentID (Primary Key), StudentID (Foreign Key), ClassID (Foreign Key)</br>
3. *Student:*</br>
- Attributes: StudentID (Primary Key), Name, DateOfBirth, Email, Phone</br></br>
ii. Relationships:</br></br>
- One-to-Many relationship between Class and Enrollment (One Class can have many Enrollments, but each Enrollment is associated with only one Class).</br>
- Many-to-Many relationship between Student and Class through Enrollment (A Student can enroll in many Classes, and a Class can have many Students).</br></br>
* This ER diagram reflects the relationships between classes, students, and enrollments in the context of a university registrar office. The Class entity includes details about the class, such as the instructor, time, and place, while the Enrollment entity links students to specific classes. </br>

<h1>Unit 3</h1>

<h3>1. Explain different set operations in relational algebra with an example?</h3>
- Set operations in relational algebra include union (∪), intersection (∩), and difference (-). For example, if we have sets A = {1, 2, 3} and B = {3, 4, 5}, then A ∪ B is {1, 2, 3, 4, 5}, A ∩ B is {3}, and A - B is {1, 2}.  </br>

<h3>2. Explain the symbol used in σp(r)?</h3>
- The symbol σp(r) represents the selection operation in relational algebra. It retrieves tuples from relation r that satisfy a certain condition specified by predicate p.  </br>

<h3>3. What do you mean by arity of relation?</h3>
- The arity of a relation is the number of attributes or columns it contains. It indicates the degree of the relation. For example, if a relation has attributes A, B, and C, its arity is 3.  </br>

<h3>4. Explain hierarchical, network, and relational models?</h3>
- *Hierarchical Model:* Organizes data in a tree-like structure with parent-child relationships. </br>
- *Network Model:* Represents data as a graph with nodes and edges, allowing more complex relationships.</br>
- *Relational Model:* Organizes data into tables (relations) with rows and columns, offering simplicity and flexibility.</br>

<h3>5. Explain set operation in short?</h3>
- Set operations in relational algebra (union, intersection, difference) manipulate data sets to combine or extract information from different relations.  </br>

<h3>6. What do you mean by functional dependency?</h3>
- Functional dependency (FD) is a concept in database design where the value of one attribute uniquely determines the value of another attribute in a relation.  </br>

<h3>7. What are the advantages of normalizing database design?</h3>
- Normalizing a database reduces data redundancy, improves data integrity, and minimizes update anomalies. It enhances overall database structure and efficiency.  </br>

<h3>8. What do you mean by normalization? Explain BCNF, 3NF, and 2NF with a suitable example?</h3>
- Normalization is the process of organizing data in a database to reduce redundancy and dependency. </br>
- *BCNF (Boyce-Codd Normal Form):* Ensures that every non-trivial functional dependency is a superkey.</br>
- *3NF (Third Normal Form):* Deals with transitive dependencies and ensures that non-prime attributes are not transitively dependent on a superkey.</br>
- *2NF (Second Normal Form):* Ensures that no non-prime attribute is partially dependent on a candidate key.</br>

<h3>9. What is a functional dependency? Explain FD and multivalued functional dependency with an example?</h3>
- *Functional Dependency (FD):* A relationship between two sets of attributes in a relation where the value of one uniquely determines the value of the other.</br>
- *Multivalued Functional Dependency (MVD):* Describes dependencies between sets of attributes, where a change in one set can affect another set independently.</br></br>
Example: In a relation with attributes {A, B, C}, if A → B is an FD and B → C is another FD, it's a multivalued dependency if A → B and A → C also hold independently. </br>

<h1>Unit 4</h1>

<h3>1. What is the integrity constraints?</h3>
- Integrity constraints are rules defined on a database schema to ensure the accuracy, consistency, and reliability of data. These constraints enforce the correctness of data values and relationships within a database. </br>

<h3>2. Explain DDL, DML, DCL using examples.</h3>
- *DDL (Data Definition Language):* It deals with the structure and definition of the database schema. </br>
Example: CREATE TABLE Students (ID INT, Name VARCHAR(50)); </br></br>
- *DML (Data Manipulation Language):* Involves operations for manipulating data stored in the database. </br>
Example: INSERT INTO Students VALUES (1, 'John');  </br></br>
- *DCL (Data Control Language):* Manages access and permissions to the database. </br>
Example: GRANT SELECT ON Students TO User1; </br>

<h3>3. What do you mean by the term ‘query’ in DBMS?</h3>
-  In DBMS, a query is a request or command to retrieve specific information from a database. It is typically written using a query language (e.g., SQL) and allows users to interact with the database to extract relevant data based on specified criteria. </br>

<h3>4. 4. Define Data Definition Language (DDL).</h3>
- Data Definition Language (DDL) is a subset of SQL used to define, manage, and modify the structure of a database. DDL includes commands like CREATE (to create tables and schemas), ALTER (to modify existing structures), and DROP (to delete tables or databases).  </br>

<h1>Unit 5</h1>

<h3>1. What do you mean by filter?</h3>
-  In MS Access, a filter is a mechanism to selectively display data in a datasheet or form based on specified criteria. It allows users to view only the records that meet certain conditions, facilitating focused data analysis. </br>

<h3>2. What is the size limitation for MS Access database?</h3>
- The size limitation for a single MS Access database file (.accdb) is 2 gigabytes. This includes all objects, such as tables, forms, reports, and queries. </br>

<h3>3. What are the field types in MS Access?</h3>
- MS Access supports various field types, including Text, Memo, Number, Date/Time, Currency, Yes/No, and more. Each field type is designed for specific data types and purposes.  </br>


<h3>4. What is datasheet view?</h3>
- Datasheet view in MS Access is a tabular view that displays data in a table format. It allows users to easily navigate and edit records, similar to a spreadsheet, making it a convenient way to interact with the data stored in a table.  </br>

<h3>5. What do you mean by filter?</h3>
- In MS Access, a filter is a mechanism to selectively display data in a datasheet or form based on specified criteria. It allows users to view only the records that meet certain conditions, facilitating focused data analysis. </br>

<h3>6. Explain how to create a table in MS-ACCESS?</h3>
-  To create a table in MS Access, open the database, go to the "Table Design" view, define the fields with their data types and properties, set a primary key, and save the table. </br>

<h3> 7. What are link tables?</h3>
- Link tables in MS Access are used to establish relationships between two or more tables. These relationships are created by linking the primary key of one table to a foreign key in another, enabling data consistency and integrity. </br>

<h3>8. What are the types of filters in MS Access?</h3>
- MS Access offers various types of filters, including filter by selection, filter by form, advanced filter/sort, and filter for unique values. These filters help users refine and analyze data based on specific criteria.  </br>

<h3>9. What are the field types in Access?</h3>
- MS Access supports field types such as Text, Memo, Number, Date/Time, Currency, Yes/No, and more. Each field type is designed for specific data types and purposes. </br>

<h3>10. What are the field properties in MS Access?</h3>
- Field properties in MS Access define characteristics such as field size, format, input mask, and validation rules. These properties ensure data integrity and provide control over how data is entered and displayed in a table. </br>

<h1>Unit 6</h1>

<h3>1. What do you mean by queries?</h3>
- In the context of databases, queries refer to requests for specific information from a database. Queries are used to retrieve, filter, and manipulate data based on defined criteria. </br>

<h3>2. Write steps to create a query?</h3>
1. Open the database in MS Access.</br>
2. Go to the "Query Design" view.</br>
3. Select the tables or queries you want to include.</br>
4. Drag and drop the desired fields onto the query grid.</br>
5. Specify criteria for filtering data.</br>
6. Run the query to view results.</br>

<h3>3. Define Types of Queries?</h3>
- *Select Query:* Retrieves data from one or more tables.</br>
- *Action Query:* Performs actions on data (e.g., update, delete).</br>
- *Parameter Query:* Prompts users to input criteria.</br>
- *Crosstab Query:* Summarizes data in a spreadsheet-like format.</br>
- *Make Table Query:* Creates a new table based on query results.</br>
- *Append Query:* Adds records from one table to another.</br>
- *Delete Query:* Removes records based on specified criteria.</br>

<h1>Unit 7</h1>

<h3>1. What is a sub-form?</h3>
- A sub-form in MS Access is a form embedded within another form. It allows you to display related data from another table or query within the main form, enabling a hierarchical organization of data. </br>

<h3>2. What are the forms? Explain their types in MS Access?</h3>
- 
