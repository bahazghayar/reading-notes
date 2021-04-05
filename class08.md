# Access Control (ACL)

## When is Basic Authorization used vs. Bearer Authorization?
### The Basic and Digest authentication schemes are dedicated to the authentication using a username and a secret (see RFC7616 and RFC7617). The Bearer authentication scheme is dedicated to the authentication using a token and is described by the RFC6750. Even if this scheme comes from an OAuth2 specification, you can still use it in any other context where tokens are exchange between a client and a server. Concerning the JWT authentication and as it is a token, the best choice is the Bearer authentication scheme. Nevertheless, nothing prevent you from using a custom scheme that could fit on your requirements.
from (stackoverflow.com)

## What does the JSON Web Token package do?
### for creating access tokens.

## What considerations should we make when creating and storing a SECRET?
1. ### Never store unencrypted secrets in .git repositories. Avoid git add * commands on git. Add sensitive files in .gitignore. Don't rely on code reviews to discover secrets.
2. ### Don't share your secrets unencrypted in messaging systems like slack.
3. ### Store secrets safely.
4. ### Restrict API access and permissions.
<br>

## Terms

### encryption: is the process of encoding information. This process converts the original representation of the information, known as plaintext, into an alternative form known as ciphertext. Ideally, only authorized parties can decipher a ciphertext back to plaintext and access the original information. Encryption does not itself prevent interference but denies the intelligible content to a would-be interceptor.
from(Wikipedia)

### token: These are words or symbols used by code to specify the logic of the application. These include things like + , - , ? , if , else , and var 
from(airbrake.io)

### bearer: service or data service is a service that allows transmission of information signals between network interfaces. These services give the subscriber the capacity required to transmit appropriate signals between certain access points, i.e. user network interfaces.
from(Wikipedia)

### secret: These non-human privileged credentials are often called “secrets” and refer to a private piece of information that acts as a key to unlock protected resources or sensitive information in tools, applications, containers, DevOps and cloud-native environments.
from(www.cyberark.com)

### JSON Web Token: (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.
from(jwt.io)
<br>

## Preview

### Role Based Access Control (RBAC): role-based security is an approach to restricting system access to authorized users. It is used by the majority of enterprises with more than 500 employees, and can implement mandatory access control (MAC) or discretionary access control (DAC).
### Role-based access control (RBAC) is a policy-neutral access-control mechanism defined around roles and privileges. The components of RBAC such as role-permissions, user-role and role-role relationships make it simple to perform user assignments. A study by NIST has demonstrated that RBAC addresses many needs of commercial and government organizations. RBAC can be used to facilitate administration of security in large organizations with hundreds of users and thousands of permissions. Although RBAC is different from MAC and DAC access control frameworks, it can enforce these policies without any complication.
from (Wikipedia)

## The advantage of RBAC?
### With the proper implementation of RBAC, the assignment of access rights becomes systematic and repeatable. Further, it is much easier to audit user rights, and to correct any issues identified.
### RBAC may sound intimidating, but it can in reality be easy to implement, and will make the ongoing management of access rights much easier and more secure.
### The data breach you prevent may be your own.
from (www.csoonline.com)