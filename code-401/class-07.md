# Bearer Authorization

1. Write the following steps in the correct order:

Register your application to get a client_id and client_secret
Ask the client if they want to sign in via a third party
Make a request to a third-party API endpoint
Redirect to a third party authentication endpoint
Make a request to the access token endpoint
Receive access token
Receive authorization code

2. What can you do with an authorization code?

The authorization code is a temporary code that the client will exchange for an access token. The code itself is obtained from the authorization server where the user gets a chance to see what the information the client is requesting, and approve or deny the request.

3. What can you do with an access token?

Access tokens are used in token-based authentication to allow an application to access an API. The application receives an access token after a user successfully authenticates and authorizes access, then passes the access token as a credential when it calls the target API. The passed token informs the API that the bearer of the token has been authorized to access the API and perform specific actions specified by the scope that was granted during authorization.

4. What’s a benefit of using OAuth instead of your own basic authentication?

An open protocol to allow secure authorization in a simple and standard method from web, mobile and desktop applications.

`Client ID`The client_id is a public identifier for apps. Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string. It must also be unique across all clients that the authorization server handles. If the client ID is guessable, it makes it slightly easier to craft phishing attacks against arbitrary applications.

`Client Secret`A client secret is a secret known only to your application and the authorization server. It protects your resources by only granting tokens to authorized requestors.

`Authentication Endpoint`:is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service.

`Access Token Endpoint`a key that allows you to enter protected resources.

`access token` contains the security credentials for a login session and identifies the user, the user's groups, the user's privileges, and, in some cases, a particular application.