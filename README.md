# .NET 6, Web APi, Auth, XUnit, Angular Project

Several years ago, I got the “Pro ASP.NET Web API” book. This article is the offshoot of ideas from this book, a little CQRS, 
and my own experience developing client-server systems. Here is the project descriptions 

## Project               ------  Description 
  
  Flone.Web	             ------    Project for controllers, mapping between domain model and API model, API configuration

  Flone.Api.Common	     ------    At this point, there are collected exception classes that are interpreted in a certain way by filters to return correct HTTP codes with errors to the user

  Flone.Api.Models	     ------    Project for API models

  Flone.Data.Repository  ------	   Project for interfaces and implementation of the Unit of Work pattern

  Flone.Data.Model	     ------    Project for domain model

  Flone.Queries	         ------    Project for query processors and query-specific classes

  Flone.Security	     ------    Project for the interface and implementation of the current user's security context
