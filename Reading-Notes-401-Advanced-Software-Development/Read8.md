# Access Control and RBAC implementation (ACL)

  
1. Inventory your systems

Figure out what resources you have for which you need to control access, if you don't already have them listed. Examples would include an email system, customer database, contact management system, major folders on a file server, etc. 

2. Analyze your workforce and create roles

You need to group your workforce members into roles with common access needs.  Avoid the temptation to have too many roles defined. Keep them as simple and stratified as possible.

For example, you might have a basic user role, which includes the access any employee would need, such as email and the intranet site. Another role might be a customer service rep, that would have read/write access to the customer database, and a customer database administrator, that would have full control of the customer database. 

3. Assign people to roles

Now that you have a list of roles and their access rights, figure out which role(s) each employee belongs in, and set their access accordingly. 

4. Never make one-off changes

Resist any temptation to make a one-off change for an employee with unusual needs. If you begin doing this, your RBAC system will quickly begin to unravel. Change the roles as required or add new ones when really necessary. 

5. Audit

Periodically review your roles, the employees assigned to them, and the access permitted for each. If you discover, for example, that a role has unnecessary access to a particular system, change the role and adjust the access level for all employees in that role. 

![rbac](https://www.dnsstuff.com/wp-content/uploads/2019/10/role-based-access-control.jpg)


### When is Basic Authorization used vs. Bearer Authorization?

- `Basic` authorization used when in signing-up - sign-in process. 

- `Bearer` authorization used after basic auth done. 

### What does the JSON Web Token package do?

`JSON Web Token (JWT)`  is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

### What considerations should we make when creating and storing a SECRET?


- donâ€™t create a weak secret.

-  donâ€™t store it in a plain text.

- donâ€™t share your secret with anyone.

- donâ€™t use same secret for different accounts.




### There are some alternatives for/variations of RBAC, including:
- Access control lists (ACL)  
- Attribute-based access control (ABAC) 
Both of these options provide additional granularity of controls beyond the basic concept of RBAC, but can also greatly expand the effort required to create and maintain the necessary permissions 


![](https://sites.google.com/site/cacsolin/_/rsrc/1261008425131/role-based-access-control/Role%20Based%20Access%20Control.png)
### RBAC implementation : 
1. Inventory your systems
2. Analyze your workforce and create roles
3. Assign people to roles
4. Never make one-off changes
5. Audit
