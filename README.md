
---------------------------------
---------------------------------


---------------------------------
## We are deployed on Azure!

coming sooon
---------------------------------
## Web Application
Buisnesses sign up on the web application and recieve a 10 digit code (ID CODE)
buisnesses advertise the mobile application and hand out the 10 digit code requesting feedback from users or clientele
users download app, and are prompted to enter a code to identify which buisness they are sending feedback too
after entering the code, verifying it through the api and database, and recieving back a verification code
User can enter in plain text a simple feedback report, and click "send" on their device. The process is complete.

Buisnesses can later sign into the web application and CRUD the reviews left by people who have entered their buisness code into the application for feedback


Building web application to handle the regiistry of the buisnesses or liscences for anonymous feedback. next i will need to create an API to handle the request and response cycle for both the mobile application and the web application to interface with the same databases with the same api functions.

---------------------------------

## Tools Used


- C#
- ASP.Net Core
- Entity Framework
- MVC
- xUnit
- Bootstrap
- Azure


---------------------------------

## Recent Updates




---------------------------

## Getting Started

Clone this repository to your local machine.
```
$ git clone https://github.com/YourRepo/YourProject.git
```
Once downloaded, you can either use the dotnet CLI utilities or Visual Studio 2017 (or greater) to build the web application. The solution file is located in the AmandaFE subdirectory at the root of the repository.
```
cd YourRepo/YourProject
dotnet build
```
The dotnet tools will automatically restore any NuGet dependencies. Before running the application, the provided code-first migration will need to be applied to the SQL server of your choice configured in the /AmandaFE/AmandaFE/appsettings.json file. This requires the Microsoft.EntityFrameworkCore.Tools NuGet package and can be run from the NuGet Package Manager Console:
```
Update-Database
```
Once the database has been created, the application can be run. Options for running and debugging the application using IIS Express or Kestrel are provided within Visual Studio. From the command line, the following will start an instance of the Kestrel server to host the application:
```
cd YourRepo/YourProject
dotnet run
```
Unit testing is included in the ======= project using the xUnit test framework. Tests have been provided for models, view models, controllers, and utility classes for the application.

---------------------------------

## Usage


### Overview of Recent Posts


### Creating a Post


### Enriching a Post


### Viewing Post Details


---------------------------
## Data Flow (Frontend, Backend, REST API)
***[Add a clean and clear explanation of what the data flow is. Walk me through it.]***


---------------------------
## Data Model

### Overall Project Schema
***[Add a description of your DB schema. Explain the relationships to me.]***


---------------------------
## Model Properties and Requirements

### Message

| Parameter | Type | Required |
| --- | --- | --- |
| ID  | int | YES |



### User


---------------------------

## Change Log
***[The change log will list any changes made to the code base. This includes any changes from TA/Instructor feedback]***


------------------------------

## Authors
Tanner Percival

------------------------------

