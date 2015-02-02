# Login

Bob Rhett - Monday, February 2, 2015
Proposal

I will create a program that may be used as the validation front-end for any other application that requires a user login. This program will provide a user interface for the following use cases:
1.	User login
2.	Change of password
3.	Recovery of a forgotten password
4.	Creation of a new user account
The following objects will be created to provide this functionality:
•	Account: This object will provide for interface to the account ddatabase and allow for creation and modification of accounts.
•	Cookie: This object will provide a repository for user preferences on the local device that will be maintained after a session has terminated.
•	Session: This object will provide a repository for session variables used only during the session.
•	Error: this object will provide the user with feedback in the event of invalid actions.
•	Password: this object will provide a standard method for encryption and decryption of the user password.

