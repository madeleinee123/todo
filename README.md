# ToDo List App
## Introduction
## Design Decisions
An exhaustive list of all the design decisions that went into creating this web 
application. It will also include a commentary on what went right, what went wrong (and then right 😊), 
and what was enjoyable to work on.  
### Commit 1 - Setting up the app with Spring Boot
Spring Boot is perfect for this project because we will be creating a RESTful API and Spring boot provides default dependencies
and converters from the get go.  Spring Boot is also useful because of its autoconfiguration feature. 
### Commit 2 - Creating a profile for the developer-specific environment 
A profile is created for the developer-specific environment through the addition of the 
`applications-dev.profiles` file in the resources package. This spring profile enables the programmer to limit
the load of the application depending on the active profile.  This developer profile will allow us not to be running tests 
that need to be run in a different environment such as the test environment or the stage environment. 
