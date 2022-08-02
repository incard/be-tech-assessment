# incard tech assessment


Create a service that will handle multi user management. The service should let users login and perform certain actions based on their role.  


- Create an endpoint to register, login and to add new users. 
- Possible values for setting a role while adding new users `owner, admin, employee`.
- Each role will have certain restrictions when calling api e.g.
  - `owner` can edit/create/delete/read
  - `admin` can edit/create/read
  - `employee` can read only
- The above actions should only be performed once authorised with the server.

Please organize, design, test, document and deploy your code as if it were going into production, then send us a link to the hosted repository (e.g. Github, Bitbucket...).

You are also free to use any web framework. If you choose to use a framework that results in boilerplate code in the repository, please detail in your README which code was written by you (as opposed to generated code).



