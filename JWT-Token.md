## JWT Token Details

> JWT website [JWT link](https://jwt.io/#debugger-io)

> JWT token is a JSON object used to verify authenticity of user of a web api/app.

> It is generated when a user authenticates with web api via login procedure, and is sent back to client in HTTP header.

> For further client api communication , client has to send this JWT token in api requests.


> JWT token structure has three parts :
1)Header
2)Payload 
3)Signature

> It is a string with the format **header.payload.signature**.

### Header info:

1)type of token which is JWT 

2)Hashing algorithm that is used to create the signature component of the JWT token.


### Payload info:

1)user information including user uuid

2)the expiration time of the token etc


### Signature info

1)The header and the payload generated are Base64 encoded and joined together with a period (.)

2)The string is hashed along with the secret (password) using the hashing algorithm specified in the JWT header.

3)This hashed data is then Base64 encoded to generate the signature.


`Once the user is authenticated(logged in), each subsequent request will include the JWT, allowing the user to access services and resources`


