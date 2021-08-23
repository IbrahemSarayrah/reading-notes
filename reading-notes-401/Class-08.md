# Reading: Access Control (ACL)

## When is Basic Authorization used vs. Bearer Authorization?

* The basic Auth is dedicated to the authentication , and basic Auth allow you to access the API directly with your credential : user/password.

* Bearer authentication that involves security tokens called bearer tokens, The client must send this token in the Authorization header when making requests to protected resources

## What does the JSON Web Token package do?

* JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object, This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

## What considerations should we make when creating and storing a SECRET?

* Never store unencrypted secrets in .git repositories

* Don’t share your secrets unencrypted in messaging systems

* Use encryption to store secrets within .git repositories and Use environment variables

* Use "Secrets as a service" solutions

## Document the following Vocabulary Terms

* encryption: Encryption is a way of scrambling data so that only authorized parties can understand the information. In technical terms, it is the process of converting human-readable plaintext to incomprehensible text, also known as ciphertext. In simpler terms, encryption takes readable data and alters it so that it appears random.

* token: is the basic component of source code. Characters are categorized as one of five classes of tokens that describe their functions (constants, identifiers, operators, reserved words, and separators) in accordance with the rules of the programming language.

* bearer: is an opaque string, not intended to have any meaning to clients using it. Some servers will issue tokens that are a short string of hexadecimal characters, while others may use structured tokens such as JSON Web Token

* secret: sensitive information used to access systems that require authentication. This includes login credentials such as usernames, email addresses, and passwords, as well as access tokens and private keys.

* JSON Web Token: is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.
