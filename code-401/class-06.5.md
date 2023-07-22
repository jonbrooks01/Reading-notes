# Class 07 Reading Notes

## Intro to JWT

1) A JSON web token is a self-contained way for securing transmitted information between two parties as a JSON object.

2) The two different ways to use JSON web tokens are Authorization and Information Exchange.

3) Claims can be found in the second part of the token the "payload"

## Are JWT's Secure

1) You can know if a JWT is secure by accessing the signature utilizing the hash(payload + secret) by using the signature you can verify if the information has been tampered with from the prior signature associated with the JWT

2) The sender and receiver both must know the hash(payload + secret) to ensure they can check the signature matches in order to verify the legitimacy of the JWT

3) When sending a JWT to another person unless its encrypted anyone can read that message, the message can be altered but if you don't know the secret way to sign the JWT the remaining signature wont contain the verification needed to prove legitimacy. By only sharing the private key with those that the message is intended for can the parties determine if the message has been altered or is still valid.

## JWT Explained

1) JWT is used to transfer information between any two bodies

2) JWT is a useful tool because it is self contained and compact. This means that JWT's can be send extremely fast like when submitting a form or an entry in a website. It also means that you don't have to additional queries to any database since all the information needed is contained within the JWT.

3) The three parts of the JWT are the Header, Payload and the signature.
