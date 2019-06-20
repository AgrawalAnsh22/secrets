# secrets

Secrets is a web application where users register themselves and can submit there secrets anonymously which can be read by other users upon logging in. It is a very basic version with limited features as of now.
## Homepage
![Secrets Homepage](/public/images/Secrets_Home.JPG)
## Loginpage
![Secrets Loginpage](/public/images/secrets_login.JPG)
## Secrets page
![Secrets Secretpage](/public/images/secrets_secret.JPG)
## Submit page
![Secrets Submitpage](/public/images/secrets_submit.JPG)

The registration of user is encrypted using the passportjs- which is one of the most secure ways of registration.

This project also contains various levels of authentication for login, which I have saved on different commits for each level of authentication, if anyone wants to check the code for it, you can clone the repository and use git checkout to see the complete code for each authentication.<br>

The levels of authentication are - <br>
- Level 1 - Username & Password (with plain text)
- Level 2 - Database encryption with environmental variables
- Level 3 - U=Encryption using Hash functions
- Level 4 - Adding Salting to hash functions
- Level 5 - Passportjs
- Level 6 - OAuth along with passportjs
