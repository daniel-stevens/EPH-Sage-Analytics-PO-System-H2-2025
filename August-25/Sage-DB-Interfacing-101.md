# Plans to view and interface with data 

I will map out our EPH Specific Sage data structure in line with our version and used modules.

Enforcing read only access:
Enforce read only access in Sage using user permissions
1. I will then setup and configure the ODBC driver to have only read only access.

2. Enforce read only access in Datagrip marking the data source as read only preventing any write queries.

3. Enforce read only access when developing in Python by:
   - Using ODBC credentials with read only access
   - Ensuring to only use SELECT statements by enforcing a no writes rule

- This may involve creating a new sage user with read only access and connecting through this, but review after sage access granted.




- Datagrip using ODBC 
- Python for 