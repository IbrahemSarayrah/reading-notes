# Reading: Authorization/Authentication

## What header(s) are used in authentication and authorization

* authentication define the authentication method that should be used to gain access to a resource. They must specify which authentication scheme is used, so that the client that wishes to authorize knows how to provide the credentials

* authorization equest headers contain the credentials to authenticate a user agent with a (proxy) server. Here, the `<type>` is needed again followed by the credentials, which can be encoded or encrypted depending on which authentication scheme is used.

## What is safe to put into a JWT

* Registered claims: These are a set of predefined claims which are not mandatory but recommended, to provide a set of useful, interoperable claims. Some of them are: iss (issuer), exp (expiration time), sub (subject), aud (audience)

* Public claims: These can be defined at will by those using JWTs. But to avoid collisions they should be defined in the IANA JSON Web Token Registry or be defined as a URI that contains a collision resistant namespace.

* Private claims: These are the custom claims created to share information between parties that agree on using them and are neither registered or public claims.

## How are JWTs validated

* Check signature, The last segment of a JWT is the signature, which is used to verify that the token was signed by the sender and not altered in any way. The Signature is created using the Header and Payload segments

## Document the following Vocabulary Terms

* RBAC: is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.

* User Roles: are permission sets that control access to areas and features within the Professional Archive Platform. Each User account requires a Role assignment.

* JWT Token: JSON Web Token (JWT) access tokens conform to the JWT standard and contain information about an entity in the form of claims. They are self-contained therefore it is not necessary for the recipient to call a server to validate the token.
