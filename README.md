# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?
Header
Payload
Signature
2. What information does each part contain?
The header consists of the type of the hashing algorithm used and that it is a jwt, the payload is information and metadata about the user that would be useful for the server to have for whatever application they are logging into (like a cookie), and the signature is the password using the header hash that can only be decoded by the target server (using open key encryption like RSA).

3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.
They are smaller than previous authentication methods previously used, they can use more types of security algorithms, and they can be used on more types of platforms because most computers can parse JSON. Basically they are better in most ways (according to the people who made it YMMV).