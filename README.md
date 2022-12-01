## Scrum Application

This is a simple implementation of a Scrum Board, a tool that helps visualize and manage work. 
A Scrum Board is usually made of 3 columns - *TODO*, *InProgres*s & *Done*. In each column there are Post-it notes that represents task and their status.

As already stated this project is an implementation of such board and made of 3 separate Docker containers that holds:

- PostgreSQL database
- Java backend (Spring Boot)
- Angular frontend

The entry point for a user is a website which is available under the
address: **http://localhost:4200/**





### How to run it?

An entire application can be ran with a single command in a terminal:

```
$ docker-compose up -d
```



