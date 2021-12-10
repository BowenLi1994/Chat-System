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

## Instructions:
1. make --  to compile the code
2. serve user_info_file configration_file --to set up the server
3. client configration_file  -- to open the client you should open 2 clients
4. r -- to register two users, input your name and you password,like:
  - name:n1 password:p1
  - name:n2 password:p2
5. l -- to log into the chat system, input your name and you password
6. i -- invite friends in following format:  i username [message],like:
  - i p2 [hi]
7. ia -- accept friend's invitation: ia username [message]
  - ia p1 [hello]
8. m -- send message to friends: m username message
  - m p1 hi
  - m p2 hello
9. logout -- logout of you account.
10. exit -- quit the program.
11. when you type control+c on client and server to stop the program.

-P.S. And I use select function on client side and use pthread on server side.
