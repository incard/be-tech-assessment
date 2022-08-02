# incard tech assessment


Create a service that will manage multi companies and users. 

### Example 1

User A owns Company A but is an admin in Company B. 

- Company A > User A (owner)
- Company B > User A (admin)

### Example 2

A company could have many users with different role

- Company A > User A (owner)
- Company A > User B (admin)
- Company A > User C (employee)

## Functional spec

- Add CRUD endpoints to register (user, company), login, add new users and link users between two companies. 
- Possible values for a role while adding new users `owner, admin, employee`.
- Each role will have certain restrictions when calling api e.g.
  - `owner` can edit/create/delete/read
  - `admin` can edit/create/read
  - `employee` can read only
- The above actions should only be performed by a user once successfully authenticated.

## Tech spec

- nodejs with typescript.  
- postgres (feel free to save the data in the memory rather using an actual db)

You are also free to use any framework.

Please organize, design, test, document and deploy your code as if it were going into production, then send us a link to the hosted repository (e.g. Github, Bitbucket...).

Good luck 😊

