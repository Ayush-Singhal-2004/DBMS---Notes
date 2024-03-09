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
