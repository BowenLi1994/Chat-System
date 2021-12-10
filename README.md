# Chat-System
## Project Objectives
1. Experiencing signal handling and thread programming
2. Mastering socket based networking application development
3. Getting familiar with application-layer network protocol design and development 4. Understanding how peer-to-peer systems such as Yahoo Messenger work




## Project Description
A messenger application has two components: a messenger server and messenger clients. A messenger server is an application program that maintains the user account information and their current location, which facilitates the direct communication between peers. When a client first starts, a user will send the username and password to the messenger server (assuming the user has registered with the server). After signing into the server system, the client will also send the current location information (including both IP address and port number) to the server to which its friends can connect. The server will forward the location information to the user's friends who are currently online. Relying on this location information, two users can directly talk to each other by establishing a direct TCP connection between them.

## Realized functions:

1. Register a user;
2. Login to the chat system;
3. Exit the chat system;
After log into the chat system, you can do the following tasks:
1. Invite friends;
2. Accept friends' invitation;
3. Sending message to you friends;
4. Log out users' account.
