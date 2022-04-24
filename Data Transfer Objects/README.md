# Data Transfer Objects

## Create Data Transfer Objects (DTOs)
Right now, our web API exposes the database entities to the client. The client receives data that maps directly to your database tables. However, that's not always a good idea. Sometimes you want to change the shape of the data that you send to client. For example, you might want to:

- Remove circular references (see previous section).
- Hide particular properties that clients are not supposed to view.
- Omit some properties in order to reduce payload size.
- Flatten object graphs that contain nested objects, to make them more convenient for clients.
- Avoid "over-posting" vulnerabilities. (See Model Validation for a discussion of over-posting.)
- Decouple your service layer from your database layer.


## How to use Data Transfer Objects in ASP.NET Core 3.1
Learn the benefits of Data Transfer Objects, why they should be immutable, and how to take advantage of them in your ASP.NET Core applications


###  Create an ASP.NET Core 3.1 API project
First off, let’s create an ASP.NET Core project in Visual Studio. Assuming Visual Studio 2019 is installed in your system, follow the steps outlined below to create a new ASP.NET Core API project in Visual Studio.

1. Launch the Visual Studio IDE.
2. Click on “Create new project.”
3. In the “Create new project” window, select “ASP.NET Core Web Application” from the list of the templates displayed.
4. Click Next. 
5. In the “Configure your new project” window, specify the name and location for the new project.
6. Click Create. 
7. In the “Create New ASP.NET Core Web Application” window shown next, select .NET Core as the runtime and ASP.NET Core 3.1 (or later) from    the drop-down list at the top.11.Select “API” as the project template to create a new ASP.NET Core API application. 
8. Ensure that the check boxes “Enable Docker Support” and “Configure for HTTPS” are unchecked as we won’t be using those features here.
9. Ensure that Authentication is set as “No Authentication” as we won’t be using authentication either.
10. Click Create. 



### Why use Data Transfer Objects (DTOs)?
When designing and developing an application, if you’re using models to pass data between the layers and sending data back to the presentation layer, then you’re exposing the internal data structures of your application. That’s a major design flaw in your application.