# senior-backend-developer-assignment
Assignment for Backend developer for senior roles

## Role Based Access Control:

Implement a role based auth system. System should be able to assign a role to a user and remove a role from a user.

Entities are USER, ACTION TYPE, RESOURCE, ROLE

ACTION TYPE defines the access level (Ex: READ, WRITE, DELETE)

Access to resources for users are controlled strictly by the role. One user can have multiple roles. Given a user, action type and resource, the system should be able to tell whether user has access or not.


Please list down the assumptions made. 

***Note:***

1. A **command line application with in memory models** will suffice, a REST API or DBs are not required. Our main interest is in code organisation and logic. Please make sure you use OOP concepts & implementation as much as possible to keep the code clean & extendable

2. Use can create an admin user with full access during the init of your program. 

3. Use any object oriented programming language.

4. Code should be maintainable and production ready

5. Follow the best practices of engineering and design patterns.

6. If you are using any existing RBAC system as reference (like jenkins, google cloud IAM etc), you can mention that. 

7. extra points for Unit tests(not necessary)


## init system
You can init system with few Resources, Roles(which have resources with different permission set), Admin User(admin) and Normal User(User1)


## sample command line interaction:
hi! you are logged in as admin <br/>
press 1 for login as another user<br/>
press 2 for create user<br/>
press 3 for edit role<br/><br/>

hi! you are logged in as User1<br/>
press 1 for login as another user<br/>
press 2 for view roles<br/>
press 3 for access resource<br/><br/>

**Note** - Feel free to implement the command line interactions in any other way you feel is suitable for the problem statement. Just mention the details and assumptions clearly.


## submission steps

Create a README that talks about the files the interviewer should look at. Considering you might be using a framework which the interviewer is not be aware of, it is worthwhile to highlight relevant files in the README.
