# CRUD-Website
This Website is made by C# and ASP.NET framework with Visual Studio 2019.

Information :

(Front End) -> HTML and CSS

- Login page (LoginPage.aspx)        => Page for login if you have registered your name, email, and password. If you don't, 
you can click "Don't Have Account?" button at below Login button and then you will be directed to Register page.

- Register page (RegisterPage.aspx)  => Page for register account, you have to fill the name, email, and password form to create
account. I add some validation for check your input. If you have create account you will be directed to Home page.

- Home page (HomePage.aspx)          => Simple page just contains list user button for directing to list user page.

- List User page (ListUserPage.aspx) => Page for display the gridview about user data. I add validation for if database don't have 
some data. 

some CSS file for beautify the page.

(Back End) -> C# and SQL Server Database

- aspx.cs                             => Control the display of Front End. 

- User Controller Folder              => Contain C# code that aspx.cs file need and all of Validation are in here.

- User Factory Folder                 => Create a new object from Model.

- User Repository Folder              => Communicating with Database like create, read, update, and delete. 

- User Model Folder                   => Model for database.

If you want to add any page i recommend you to create update feature, i have made update database in UserRepository. 

Notes : First use have to create database for run this program.
Add new item in project, search sql server, and then don't forget to change the name with UserDatabase. 

![image](https://user-images.githubusercontent.com/113107463/229275402-04abcc2c-1a7a-4827-9b4c-1bb7a287db49.png)



