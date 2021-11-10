# Authorization/Authentication

### What header(s) are used in authentication and authorization

> The WWW-Authenticate and Proxy-Authenticate response headers define the authentication method that should be used to gain access to a resource. They must specify which authentication scheme is used, so that the client that wishes to authorize knows how to provide the credentials

### What is safe to put into a JWT

>  The general opinion is that they're good for being used as ID Tokens or Access Tokens and that they're secure - as the tokens are usually signed or even encrypted. ... A JSON Web Token (JWT, pronounced “jot”) is a compact and url-safe way of passing a JSON message between two parties. It's a standard, defined in RFC 7519.


### How are JWTs validated
> Check signature. The last segment of a JWT is the signature, which is used to verify that the token was signed by the sender and not altered in any way. The Signature is created using the Header and Payload segments, a signing algorithm, and a secret or public key (depending on the chosen signing algorithm).



## Document the following Vocabulary Terms.

` RBAC :`

In computer systems security, role-based access control (RBAC) or role-based security is an approach to restricting system access to authorized users

`User Roles :` 

User Roles are permission sets that control access to areas and features within the Professional Archive Platform. Each User account requires a Role assignment.

`JWT Token :`

JSON Web Token is a proposed Internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. The tokens are signed either using a private secret or a public/private key. 

# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- User Role 
- authentication & authorization 
- Access Token 
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
-basic Authorization s
- JWT.
- Bearer Authorization 
> What are you most excited about trying to implement or see how it works?
-  more about access control using CRUD function 