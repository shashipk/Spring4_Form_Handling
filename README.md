# Spring4_Form_Handling
In this project following things have been done . Form value binding – JSP and Model. Form validation and display error message. Form POST/REDIRECT/GET pattern, and add messages to flash attribute. CRUD operations, add, get, update and delete with an HTML form.


Technologies used :

Spring 4.1.6.RELEASE
Maven 3
Bootstrap 3
HSQLDB driver 2.3.2
Logback 1.1.3
JDK 1.7
JSTL 1.2
Eclipse IDE

What you’ll build :
A simple user management project, you can list, create, update and delete an user, via HTML forms. You’ll also see how to perform the form validation and display the error message conditionally. This project is styling with Bootstrap 3, and data are stored in the HSQL embedded database.

The URI structure :

URI	Method	Action
/users	GET	Listing, display all users
/users	POST	Save or update user
/users/{id}	GET	Display user {id}
/users/add	GET	Display add user form
/users/{id}/update	GET	Display update user form for {id}
/users/{id}/delete	POST	Delete user {id}
