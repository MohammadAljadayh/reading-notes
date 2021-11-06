
# Authentication

### Explain what a “Singleton” is (in Computer Science terms)

In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.

### Explain how the Singleton pattern can be used with Node modules, specifically with classesss

 Creating `singleton` in Node.JS is very easy. When we take advantage of Node.JS caching then this is trivial. In this article we showed two ways of achieving the same results and I strongly recommend to use the latter one.

### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

Bind application-level middleware to an instance of the app object by using the app.use() and app.METHOD() functions, where METHOD is the HTTP method of the request that the middleware function handles such as GET, PUT, or POST in lowercase.


## Document the following Vocabulary Terms.

`Router` is used to manage these incoming requests. It kind of routes your requests to correct handler/code

`Dynamic Module Loading :`

Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.



`Singleton Pattern :`

the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleto

` CRUD -> REST Method Matches `

CRUD (Create, Read, Update, Delete) is an acronym for ways one can operate on stored data. It is a mnemonic for the four basic functions of persistent storage

`Mock Testing :`

 Mocking means creating a fake version of an external or internal service that can stand in for the real one, helping your tests run more quickly and more reliably. When your implementation interacts with an object's properties, rather than its function or behavior, a mock can be use

 --------------------------------------------------------------------------

# Preview
> Which 3 things had you heard about previously and now have better clarity on?
- Linked list
- singel linked list with head and tails pointer  
> Which 3 things are you hoping to learn more about in the upcoming lecture/demo? 
- Multi Linked list
- More JavaScript Algorithm
- More About Testing
> What are you most excited about trying to implement or see how it works?
-  checking the errorr using debugger tools 
-----------------------------------------------------------------
### Securing Passwords : 
Passwords are the first line of defense against cyber criminals. It is the most vital secret of every activity we do over the internet and also a final check to get into any of your user account, whether it is your bank account, email account, shopping cart account or any other account you have.
- Cryptographic hash algorithms MD5, SHA1, SHA256, SHA512, SHA-3 are general purpose hash functions, designed to calculate a digest of huge amounts of data in as short a time as possible 
- The benefit of hashing is that if someone steals the database with hashed passwords, they only make off with the hashes and not the actual plaintext passwords
![](https://i.ytimg.com/vi/ejgjMJwxVTA/maxresdefault.jpg)

#### PROBLEMS WITH CRYPTOGRAPHIC HASH ALGORITHM
- Brute Force attack 
- Hash Collision attack

**Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.** 

----------------------------------------------------------------------

- `basic access authentication` :  is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request . 

- HTTP Basic authentication (BA) implementation is the simplest technique for enforcing access controls to web resources because it does not require cookies, session identifiers, or login pages; rather, HTTP Basic authentication uses standard fields in the HTTP header.
- Protocol : 
1. Server side  : When the server wants the user agent to authenticate itself towards the server after receiving an unauthenticated request, it must send a response with a HTTP 401 Unauthorized status line[5] and a WWW-Authenticate header field
2. Client side : When the user agent wants to send authentication credentials to the server, it may use the Authorization header field.

---------------------------------------------------------------------

### OWASP auth cheatsheet : 
`Authentication`  is the process of verifying that an individual, entity or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.

![](https://owasp.org/www-project-barbarus/assets/images/barbarus-sequence.png)

