# Class 15 Reading Notes

## What is OAuth

1) OAuth is delegated authorization by a third party to access unrelated servers and services safely

2) One example for OAuth would be sites like ID.me that use specific authentication protocols to allow the user on sites for discounts that must be verified before proceeding 

3) The steps to verify the user are:

- The first website connects to the second websites on behalf of the user using OAuth
- The second site generates a one time token and one time unique transaction with the parties involved
- The first site gives the token and secret to the user's client software
- The clients software presents the token and the secret to the authorization provider (The second Site)
- If not authenticated the second site will require to user to authenticate, after the user is authenticated the client approves the transaction to the second site
- The use approves the interaction on the first site
- The User is given the Access token
- The user gives approved token to the first site
- The first site gives the token to the second site as proof of authentication
- The second site lets the first site access the site on behalf of the user
- The user sees the transaction as complete

4)OAuth is for machines accessing other machines on behalf of the user OpenID is for users to login into machines. A sign in for a password protected device.

## Authorization andAuthentication Flows

1) Authentication requires the users to enter a username and password in order to access a site whereas Authorization determines what the user can and cannot access.

2) Authorization Code Flow is for when the source code is not publicly exposed the flow can exchange an Authorization Code for a token

3) Authorization Code Flow with Proof Key for Code Exchange (PKCE) utilizes special challenges to access sites content.

4) Implicit Flow with Form Post is used for Public Clients that are unable to securely store Client secrets 

5) Client Credentials is when the system has an application running such as daemons that authenticates the app rather then asking the user

6) Device Authorization is when a device asks the user to confirm a link on a different computer or smartphone

7) The Resource owner flow is an interactive form for providing credentials