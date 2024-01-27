# Secure Authentication API Implementation
In this project, the objective is to create a secure authentication API using the server language of your choice. The API performs the following tasks:

Takes a login and password.
Checks against a list (either in a database or saved in a text file) to verify if the login and password are valid.
Ensures that passwords in the list are not readable, allowing for basic encryption.
Implements a check to see if the login begins with the 2-letter country code of the login location.
Provides a different response for a username that does not meet the 2-letter country code criteria.
Key Features:
Authentication Logic:

The API receives a login code from the user for authentication.
Different login codes represent various scenarios, such as a successful login, a missing password or location, and incomplete information.
Security Measures:

Passwords in the authentication list are stored securely, implementing basic encryption to ensure they are not readable for a person.
Location-Based Check:

Before checking the validity of the username and password, the API verifies if the login begins with the 2-letter country code of the login location.
For example, a username like sggalvin will be acceptable if the login comes from Singapore.

Future Development:
Integration of a backend database or text file to store and retrieve login information securely.
Implementation of encryption methods for password protection.
Expansion of the API to handle various authentication scenarios and enhance security features.
This code serves as a foundation for building a secure authentication API and can be extended to meet specific security requirements and scalability needs.
