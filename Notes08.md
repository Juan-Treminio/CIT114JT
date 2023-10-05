CIT114-Juan Treminio 

# Notes 08: Databases 

### Database: 
is a shared collection of related data used to support the activities of a particular organization. A database can be viewed as a repository of data that is defined once and then accessed by various users. 

 
### Database management system (DBMS): 
is a collection of programs that enables users to create and maintain databases and control all access to them. The primary goal of a DBMS is to provide an environment that is both convenient and efficient for users to retrieve and store information. 

 
### Relation: 
also known as a table or file, is a subset of the Cartesian product of a list of domains characterized by a name. And within a table, each row represents a group of related data values. A row, or record, is also known as a tuple. The columns in a table is a field and are also referred to as an attribute. You can also think of it this way: an attribute is used to define the record and a record contains a set of attributes. 

 
# Quotes: 

“DynamoDB lets you offload the administrative burdens of operating and scaling a distributed database so that you don't have to worry about hardware provisioning, setup and configuration, replication, software patching, or cluster scaling.” I found this quote interesting because many businesses should implement this type of service to make their workflow run smooth and they can put resources in other areas of the business. 

“Using Amazon Aurora can reduce your database costs while improving the reliability and availability of the database. As a fully managed service, Aurora is designed to automate time-consuming tasks like provisioning, patching, backup, recovery, failure detection, and repair.” I found this quote interesting because this service will do everything on the backend to make sure it's up to date and running efficiently. 

 
# New Facts: 

## The following are the basic DynamoDB components: 

### Tables: 

Similar to other database systems, DynamoDB stores data in tables. A table is a collection of data. People could use it to store personal contact information about friends, family, or anyone else of interest. You could also have a Cars table to store information about vehicles that people drive. 

### Items: 

Each table contains zero or more items. An item is a group of attributes that is uniquely identifiable among all of the other items. In a People table, each item represents a person. For a Cars table, each item represents one vehicle. 

 
### Attributes: 

Each item is composed of one or more attributes. An attribute is a fundamental data element, something that does not need to be broken down any further. For example, an item in a People table contains attributes called PersonID, LastName, FirstName, and so on. For a Department table, an item might have attributes such as DepartmentID, Name, Manager, and so on. Attributes in DynamoDB are similar in many ways to fields or columns in other database systems. 
