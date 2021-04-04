# Bearer Authorization

## Write the following steps in the correct order:
### 1. Register your application to get a client_id and client_secret
### 2. Ask the client if they want to sign in via a third party
### 3. Redirect to a third party authentication endpoint
### 4. Make a request to a third-party API endpoint
### 5. Receive authorization code
### 6. Make a request to the access token endpoint
### 7. Receive access token

## What can you do with an authorization code?
### The only thing you can do with the authorization code is to make a request to get an access token.

## What can you do with an access token?
### Once you have an access token you can use it to make calls from a mobile client, a web browser, or from your server to Facebook's servers. If a token is obtained on a client, you can ship that token down to your server and use it in server-to-server calls.
from(evelopers.facebook.com)

## What’s a benefit of using OAuth instead of your own basic authentication?
### It allows you to read data of a user from another application. It supplies the authorization workflow for web, desktop applications, and mobile devices. Is a server side web app that uses authorization code and does not interact with user credentials.
from(www.clowder.com)
<br>

# Terms

### Client ID: (cid) is a unique identifier for a browser–device pair that helps Google Analytics link user actions on a site. By default, Google Analytics determines unique users using this parameter.
from(www.owox.com)

### Client Secret: (OAuth 2.0 client_secret) is a secret used by the OAuth Client to Authenticate to the Authorization Server. The Client Secret is a secret known only to the OAuth Client and the Authorization Server. Client Secret must be sufficiently random to not be guessable.
from (ldapwiki.com)

### Authentication Endpoint: is an authentication mechanism used to verify the identity of a network's external or remote connecting device. ... This method ensures that only valid or authorized endpoint devices are connected to a network. These endpoint devices include laptops, smartphones, tablets and servers.
from(www.iotone.com)

### Access Token Endpoint: is an HTTP endpoint that micropub clients can use to obtain an access token given an authorization code.
from(indieweb.org)

### API Endpoint: an endpoint is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. For APIs, an endpoint can include a URL of a server or service. Each endpoint is the location from which APIs can access the resources they need to carry out their function.
from(smartbear.com)

### Authorization Code: is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.
from(www.investopedia.com)

### Access Token: contains the security credentials for a login session and identifies the user, the user's groups, the user's privileges, and, in some cases, a particular application. Typically one may be asked to enter the access token (e.g. 40 random characters) rather than the usual password (it therefore should be kept secret just like a password).
from (Wikipedia)

# Preview 

### JSON Web Token (JWT) is an Internet proposed standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. The tokens are signed either using a private secret or a public/private key. For example, a server could generate a token that has the claim "logged in as admin" and provide that to a client. The client could then use that token to prove that it is logged in as admin. The tokens can be signed by one party's private key (usually the server's) so that party can subsequently verify the token is legitimate. If the other party, by some suitable and trustworthy means, is in possession of the corresponding public key, they too are able to verify the token's legitimacy. The tokens are designed to be compact,[2] URL-safe,[3] and usable especially in a web-browser single-sign-on (SSO) context. JWT claims can typically be used to pass identity of authenticated users between an identity provider and a service provider, or any other type of claims as required by business processes.
from (Wikipedia)

### When should you use JSON Web Tokens?
* #### Authorization 
* #### Information Exchange

### JSON Web Token structure:
#### 1. Header
#### 2. Payload
#### 3. Signature

