Seed code - Boilerplate for Assessment - Keep Note Assessment

Assessment Step Description
In this Case study: Keep Note , we will create a RESTful application.
Representational State Transfer (REST) is an architectural style that specifies constraints.
In the REST architectural style, data and functionality are considered resources and are accessed using Uniform Resource Identifiers (URIs), typically links on the Web.
Resources are manipulated using a fixed set of four create, read, update, delete operations: PUT, GET, POST, and DELETE.

POST creates a new resource, which can be then deleted by using DELETE.
GET retrieves the current state of a resource in some representation.
PUT transfers a new state onto a resource.


Problem Statement
In this case study, you will develop a RESTful application with which we will register a user, create a note and delete a note, add a note and update a note. Also, we will perform authentication like login and log out. Check the performance of the operations with the help of Postman API.

Solution Step
    Step 1: Configure Postman 
    Step 2: Use URI's mentioned in the controller to check all the expected operations using Postman.

Following are the broad tasks:

Create a new user, update the user, retrieve a single user, delete the user.
Login using userId and password, log out using userID.
Create a Note, update a note,  delete a note, get all notes of a specific userId.

User
	This class should have five fields i.e. userId,userName,userPassword,userMobile,userAddedDate
Note
	This class should have six fields i.e. noteId,noteTitle,noteContent,noteStatus,createdAt,createdBy






