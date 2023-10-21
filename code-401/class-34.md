# Class 34 Reading Notes

## Review API Server Build

1) A path parameter would lead you to a specific entry in a data model where as a query string would send all the information that match the one parameter you sent

2) "http://our-site.com/api/v3/stuff/things"

3) Having a dynamic API with an interface means that it is user friendly for someone who does not know how an API works, for example Amazon has a dynamic API where every click you make on there website corresponds to information that you are trying to get with little to no effort.

## Review Auth Server Build

1) I would implement middleware to handle the basic and bearer authorizations by incorporating them into the code and then when the user send a request based on the information they send in the middleware would take that information and if it matches allows the user to enter the website/specific page if it didn't match then the user would be send an error message

2) The handshake Oauth would need in order for the user enter a website would be. The user would authenticate using a third party application like Oauth then the third party would receive the information send it to the server if the information matched then the server would send a message saying the user can enter. Oauth would receive that message and send the user to the webpage that they were trying to access.

3) Role based is when a website say linkedIn has multiple different levels of access for things behind the scenes and for the users portal. when you log into linkedin you have basic user permission, you can access your information and interact with the website. Above that are permission that allow the owners of the website to make changes, delete user profiles that are deemed as scam's and take the website down for maintenance. having these different roles helps the website maintain its integrity and operability.
