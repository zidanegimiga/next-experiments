### Building an Authentication System on Next.Js
Tools used: Next-auth, An Express API Backend

## OTP
Stands for One Time password.
It is a combination of digits that are used to add an extra layer of security when authenticating users.
It is only valid for a single user session and is normally used in two factor authentication or when user requests for their password to be reset.
It would then be sent to the user either via email, phone or any other secure channel that the user has control of.

### JWT
A JWT stands for Json Web Token. It is a token that provides a secure way of exchanging claims between two parties.
JWT contains three parts: A header, Payload, and signature.
The header contains the information about the type of token and algorithm used to sign it.
The payload contains the user information (The claim).
The signature ensures integrity of the token.


### User Role Based Access
This is a design pattern where each user is assigned specific roles within a system.
It follows the principle of least privilege where a user can only access resources that they are permitted to.
By enforcing such, we can prevent data breaches and unauthorized information access.
