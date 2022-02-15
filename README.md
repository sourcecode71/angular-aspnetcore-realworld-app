# .NET 6, Angular, Web API, XUnit, EF practical project 

My own experience developing client-server systems.
Here I have added server side code. It is developing on .NET Core 6

  ## Project  -------------  Description 
  
  Flone	    -------------   Project for controllers, mapping between domain model and API model, API configuration

  Flone.Api.Common	 -----   At this point, there are collected exception classes that are interpreted in a certain way by filters to return correct HTTP codes with errors to the user

  Flone.Api.Models	-----    Project for API models

  Flone.Data.Repository -----	Project for interfaces and implementation of the Unit of Work pattern

  Flone.Data.Model	-----    Project for domain model

  Flone.Queries	   -----     Project for query processors and query-specific classes

  Flone.Security	  -----      Project for the interface and implementation of the current user's security context


To run the project change the database connection. 
Then you need to start creating the initial migration for the database by opening the Package Manager Console, 
switching to the Expenses.Data.Access project (because the EF context lies there) and running the Add-Migration InitialCreate command
