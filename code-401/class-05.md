# Class 05 Reading Notes

## Securing Passwords

1)

2) Bcrypt is an adaptive hash function based on a Blowfish symmetric block cipher algorithm and introduces a security factor that allows you to determine how expensive a has will be.

3) You will need to use the Bcrypt when you are determining how slow a hash function will be, in turn it can change the speed of the hash values to make it harder for brute force attacks.

## Basic Auth

1) Basic Auth is a method for an HTTP user to make a request with a username and password

2)When making a request with Basic Auth the header field must contain credentials of an ID and password separated with a colon.

3)Username and passwords are encoded with the Base64 encryption.

## OWASP auth cheatsheet

1)

2) When encountering errors if the username doesn't exist then the reply would be Invalid username. In addition if the password is incorrect then the message would be incorrect password.
