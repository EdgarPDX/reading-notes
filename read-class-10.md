Reading
User Modeling
    - Storing sensitive information should be encrypted using a hashing algorithm before its stored. Email  usernames and addresses are stored as plain text.
    - Use a second model to hide private information so that it won't be shared between users.
Cryptography
    - Science which studies moethods for endoing messages so that they can only be read by a person who know the secret information
Hash Algorithms
    - takes a piece of data and produces a hash that is deliberately difficult to reverse. 
    - hash password can be stored when a user model is created. 
Cypher Algorithms
    - User tokens can be created by associated a random unique string (tokenSeed) with a user account and, in turn, encrypting the tokenSeed with a secret key that only the server knows. We can then send the encrypted token to a client application. When the client makes a future request they send back the token. The server can reverse the token into the tokenSeed by decrypting it with the secret key. This is because the tokenSeed was unique to the database and can be queried to produce the user who made the request.
Basic Authorization
    - is a common method used to send a username and password in an HTTP request. username and passwords are joined with a : then 'bas64 encoded'.

    Bookmark / Skim
securing passwords
basic auth
intro to jwt
OWASP auth cheatsheet
bcrypt docs