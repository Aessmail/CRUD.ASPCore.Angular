# CRUD.ASPCore.Angular
CRUD Using ASPCore and Angular
a web application using ASP.NET Core 2.0 and Angular with the help of Entity Framework Core database first approach. I will be creating a sample Employee Record Management system. To read the inputs from the user, I am using Angular Forms with required field validations on the client side. I am also going to bind a dropdown list in the Angular Form to a table in the database using EF Core.

Execute the following commands to create both tables

CREATE TABLE tblEmployee (  
EmployeeID int IDENTITY(1,1) NOT NULL PRIMARY KEY,  
Name varchar(20) NOT NULL ,  
City varchar(20) NOT NULL ,  
Department varchar(20) NOT NULL ,  
Gender varchar(6) NOT NULL   
)  
GO  
  
CREATE TABLE tblCities (  
CityID int IDENTITY(1,1) NOT NULL PRIMARY KEY,  
CityName varchar(20) NOT NULL   
)  
GO

INSERT INTO tblCities VALUES('Cairo');  
INSERT INTO tblCities VALUES('Giza');  
INSERT INTO tblCities VALUES('Alex');  
INSERT INTO tblCities VALUES('Port Said');
