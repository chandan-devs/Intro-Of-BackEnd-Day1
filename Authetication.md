# AUTHETICATION 

## SignUp      
- username,email,password -----> SignUp Button -------> Data goes to the Backend.

## SignIn
- username.password ------>SignIn Button ------->Data goes to the Backend.

## Implementing a Signup process
1. Create a API for signup button.
2. Name the API/SignUp.
3. Accept name,email,password.
4. Redirect to some page.
5. Name the API as /api/v1/signup/
6. If everything is Ok.

## DIVIDE & CONQUER

### For Step No.1

- Create the API we need to Create the server and then create the HTML where user can go and easily Input the data.
- To create a server we require a package called Express.
- In single laptop we can create a multiple server.
- To diffrentiate between a server we call it as a PORT.
- This the POST call that we need to accept something in the body because variable in post that require body.
> Create an Express app we need to install the package Express.

> Create a PORT.

> Accept the body.

> Create the HTML page
> >The Landing Page.

> >SignUp Page.

> >SignIn Page.

### For Step No.2

- Performance --- Written in a most perfomed manner or not DSA helps at lot here.
- Security ---- How it is preventive from the Hacker or not POST/SignUp post handle the security part.
- Edge cases ---- Diffrentiate between frontend and backend example:- /api/version1/signup/ or /api/version2/signup/

### For Step No.3

 - {"name":"value","email":"value","password":"value"}
 - Convert each value as string.
 - Have Validation in email and password.
 - Encryt the password by using a library called bcrypt.
 - If there is an error send them alert if not then redirect to the next page.
   