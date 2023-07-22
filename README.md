# User-Management-System
Created a User Management Application with the help of Spring Boot. Here I have used the basic Java concept to create the business logic. for creating the application I have used Spring MVC(Model View Controller) architecture. The Application performs multiple tasks like creating a list of Users and in the list, we can perform CRUD operations like creating the list of Users, reading the list of Users, updating the list based on the User id, and deleting a particular User from the list.

## Languages and Framework
java and spring boot.

## Controller
A controller is a package in which we have a userController class that deals with all the APIs.

## Services
A Service is a package in which we have written all the business logic for creating the User Management Application.

## Repository
For storing the data we have used ArrayList. Here we have created an ArrayList which will store all the data.

## Data Flow

 1. Controller (RestroController.java)

```bash
  getAllUsers()
  getUserByUserid()
  addUser()
  DeleteUserById()
  UpdateUser()
```
2. Service  (UserService.java)

```bash
 DeleteUser()
 getAllUser()
 createUser()
 getUserById()
 updateUserContact()
```
3. model  (Restaurant.java)

```bash
 User()
```
4. Repository  (RestroRepo.java)

```bash
 getUsers()
 delete()
```
5. Configuration  (Beanmanager.java)

```bash
getInitializedList()
```




## Data Structure Used

```bash
 List, ArrayList
```

## Summary
The User Management Application is designed with Spring Boot which has functionalities like managing a list of users their type, contact number, and age and we can update the email and other details. we have divided the user into different categories like customer, admin and internal, and many more.
