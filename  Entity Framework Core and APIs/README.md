# Read: 12 - Entity Framework Core and APIs

## MVC with EF Get Started
he ASP.NET MVC framework is a lightweight, highly testable presentation framework that (as with Web Forms-based applications) is integrated with existing ASP.NET features, such as master pages and membership-based authentication. The MVC framework is defined in the System.Web.Mvc namespace and is a fundamental, supported part of the System.Web namespace.

### The Model-View-Controller (MVC
![image](../%20Entity%20Framework%20Core%20and%20APIs/1.0.png)
- Models: Model objects are the parts of the application that implement the logic for the application s data domain.
- Views: Views are the components that display the application s user interface (UI). 
- Controllers: Controllers are the components that handle user interaction, work with the model, and ultimately select a view to render that displays UI.

## Entity Framework Core

Entity Framework (EF) Core is a lightweight, extensible, open source and cross-platform version of the popular Entity Framework data access technology.

EF Core can serve as an object-relational mapper (O/RM), which:

- Enables .NET developers to work with a database using .NET objects.
- Eliminates the need for most of the data-access code that typically needs to be written.
---------------------------------------------------------------------------------------------
### The model
With EF Core, data access is performed using a model. A model is made up of entity classes and a context object that represents a session with the database
### Querying
Instances of your entity classes are retrieved from the database using Language Integrated Query (LINQ). For more information, see Querying Data.
### Saving data
Data is created, deleted, and modified in the database using instances of your entity classes. See Saving Data to learn more.
### EF O/RM considerations
While EF Core is good at abstracting many programming details, there are some best practices 



=============================================================================================================================================
## Data Seeding
Data seeding is the process of populating a database with an initial set of data.

There are several ways this can be accomplished in EF Core:
- Model seed data
- Manual migration customization
- Custom initialization logic

===============================================================================================================================================
## Razor Pages with Entity Framework Core in ASP.NET

![image](../%20Entity%20Framework%20Core%20and%20APIs/dd%20(2).jpg)

=========================================================================
## Intro to APIs
Let's create a Web API with the latest version of ASP.NET Core and Entity Framework Core.
In this guide, we'll use WideWorldImporters database to create a Web API.
REST APIs provide at least the following operations:
- GET
- POST
- PUT
- DELETE
There are other operations for REST, but they aren't necessary for this guide.
Those operations allow clients to perform actions through REST API, so our Web API must contain those operations.
WideWorldImporters database contains 4 schemas:

- Application
- Purchasing
- Sales
- Warehouse

- Prerequisites
  -Software
     - .NET Core
     - Visual Studio 2017 with last update
     - SQL Server
     - WideWorldImporters database
  -Skills
      - C#
      - ORM (Object Relational Mapping)
      - TDD (Test Driven Development)
      - RESTful services

