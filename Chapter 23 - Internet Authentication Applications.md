## Kerberos Overview
- Initially developed at MIT
- Software utility available in both the public domain and in commercially supported versions
- Issued as an Internet standard and is the defacto standard for remote authentication
- Overall scheme is that of a trusted third party authentication service
- Requires that a user prove his or her identity for each service invoked and requires servers to prove their identify to clients

## Kerberos Protocol
- Involves clients, application servers, and a Kerberos server
	- Designed to counter a variety of threats to the security of a client/server dialogue
	- Obvious security risk is impersonation
	- Servers must be able to confirm the identities of clients who request service
- Use an Authentication Server (AS)
	- User initially negotiates with AS for identity verificaiton
	- AS verifies identity and then passes information on to an application server which will then accept service requests from the client
- Need to find a way to do this in a secure way
	- If client sends user's password to teh AS over the network an opponent could observe the password
	- An opponent could impersonate the AS and send a false validation
- Summary:
	- Client sends info to authentication server
	- Authentication server then gets private information, negotiates verificaiton, then goe sto ticket server (LOOK ON SLIDES) then user is allowed to pass information to applicaiton service
	- Basically, prevents users from sending passwords (an other private information) over unsafe networks
		- Prevents eavsedropping, man-in-the-middle, etc...

## Kerberos Realms
- Kerberos environment conisists
	- Keberos server
		- Authenticaiton server
		- Ticket granting server
	- Number of clients
		- All registered with server
	- Number of applicaiton servers
		- Sharing keys with servers
- Referred to as a realm
	- Networks of clients and servers under different administrative organizations generally constitute different realms
- If multiple realms:
	- Their kerberos servers must share a secret key and turst the Kerberos server in the other realm to authenticate its users
	- Participating servers in second realm must also be willing to trust the Kerberos server in the first realm
	- Less steps for interactive with servers in different realm as they have a shared secret key (???)

## Kerberos Versions 4 and 5
- 4 used DES transcription
	- 56 bit key, not too safe in modern times
- Kerberos version 5
	- Addressed scalability issue

## Kerberos Performance Issues
- Larger client-server installations
- Very little performance impact in a large-scale environment if the system is properly configured
- Kerberos security is best assured by placing the Kerberos server on a separate, isolate machine
- Motivation for multiple realms is administrative, not performance related

## Certificate Authority (CA)
- Certificate consists of:
	- A public key with the identity of the key's owner
	- Signed by a trusted third party
	- Typically the third party is a CA that is trusted by the user community (such as a government agency, telecommunications company, financial institution, or other trusted peak organization)
- User can present his or her public key to teh authority in a secure manner and obtain a certificate
	- User can then publish the certificate or send it to others
	- Anyone needing this user's public key can obtain the certificate and verify that it is valid by way of the attached trusted signature

## X.509
- Specified in RFC 5280
- Most widely accepted format for public-key certificates
- Certificates are used in most network security applicaitons, including:
	- IP security (IPSEC)
	- Secure sockets layer (SSL)
	- Secure elecgtronic transactions (SET)
	- S/MIME
	- eBusiness applications
-
## Specialized Variants
- LOOK ON SLIDES
- Conventional (long-lived) certificates
- Short-lived certificates
- Proxy certificates
	- LOOK ON SLIDES
- Attribute certificates
	- Based on roles (not identity)

## Public infastruction (???)
- # LOOK ON SLIDES

