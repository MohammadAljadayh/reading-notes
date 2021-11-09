# Access Control (ACL)

### When is Basic Authorization used vs. Bearer Authorization?

- `Basic` authorization used when in signing-up - sign-in process. 

- `Bearer` authorization used after basic auth done. 

### What does the JSON Web Token package do?

`JSON Web Token (JWT)`  is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

### What considerations should we make when creating and storing a SECRET?


- don’t create a weak secret.

-  don’t store it in a plain text.

- don’t share your secret with anyone.

- don’t use same secret for different accounts.


## Document the following Vocabulary Terms.

`encryption :` 

the process of converting information or data into a code, especially to prevent unauthorized access.


`token :` 

 is a piece of a two-factor authentication security device that may be used to authorize the use of computer services.



` bearer :` 

Bearer authentication (also called token authentication) is an HTTP authentication scheme that involves security tokens called bearer tokens.


`secret :` 

These non-human privileged credentials are often called “secrets” and refer to a private piece of information that acts as a key to unlock protected resources or sensitive information in tools, applications, containers, DevOps and cloud-native environments.



`JSON Web Token :` 

JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- access control
- authentication & authorization 
- Access Token 
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
-basic Authorization s
- JWT.
- Bearer Authorization 
> What are you most excited about trying to implement or see how it works?
-  more about access control
-----------------------------------------------------------------

# RBAC? 
`RBAC`  is nothing more than the idea of assigning system access to users based on their role within an organization. The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs
![](https://www.dnsstuff.com/wp-content/uploads/2019/10/role-based-access-control.jpg)

### There are some alternatives for/variations of RBAC, including:
- Access control lists (ACL)  
- Attribute-based access control (ABAC) 
Both of these options provide additional granularity of controls beyond the basic concept of RBAC, but can also greatly expand the effort required to create and maintain the necessary permissions 

### RBAC implementation : 
1. Inventory your systems
2. Analyze your workforce and create roles
3. Assign people to roles
4. Never make one-off changes
5. Audit

## Example : 
![](https://sites.google.com/site/cacsolin/_/rsrc/1261008425131/role-based-access-control/Role%20Based%20Access%20Control.png)