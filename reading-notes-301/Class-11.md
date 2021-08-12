# Authentication

#### What is OAuth?

* OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

#### Give an example of what using OAuth would look like.

* when log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. then click on the button linked to the other website, the other website authenticates you.

#### How does OAuth work? What are the steps that it takes to authenticate the user?

1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

3. The first site gives this token and secret to the initiating user’s client software.

4. The client’s software presents the request token and secret to their authorization provider

5. The client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

6. The user approves (or their software silently approves) a particular transaction type at the first website.

7. The user is given an approved access token

8. The user gives the approved access token to the first website.

9. The first website gives the access token to the second website as proof of authentication on behalf of the user.

10. The second website lets the first website access their site on behalf of the user.

11. The user sees a successfully completed transaction occurring.

#### What is OpenID?

* OpenID is about authentication, and is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans.

#### What is the difference between authorization and authentication?

* authentication is for humans logging into machines, and authorization to authenticate users and get their authorization to access protected resources.

#### What is Authorization Code Flow?

* exchanges an Authorization Code for a token.

#### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

* The PKCE-enhanced Authorization Code Flow  by calling application that can be verified by the authorization server

#### What is Implicit Flow with Form Post?

* As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets.

#### What is Client Credentials Flow?

* The Client Credentials flow is a server to server flow. There is no user authentication involved in the process,in which they pass along their Client ID and Client Secret to authenticate themselves and get a token

#### What is Device Authorization Flow?

* With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.

#### What is Resource Owner Password Flow?

* requests that users provide credentials (username and password).
