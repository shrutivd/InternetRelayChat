**Project:** Internet Relay Chat<br />
**Group Members:** Shruti Deshmukh, Gauri Kasar 

# Introduction:
This is the final project for "Internetworking Protocol" class for fall 2022. <br />
This project covers functionalities related to the communication between client and server. 

## Usage of functionality:

### Initiate server and clients
The server is initiated at port 1002 by default.

Using a default port 1002:
To start server using command line type command:<br />
**command:** java Server<br />
**command:** java Client<br />

Using port of your choice:
To start client using command line type command:<br />
**command:** java Server \<portnumber> <br />
**command:** java Client localhost \<portnumber><br />

### Get help:
1. To get help<br />
   **command:** help
  
### Exchange messages:

1. To send private message<br />
   **command:** pvt_msg @clientname \<type message>

2. To send a message to all users at once<br />
   **command:** pub_msg \<type message>

3. To send a sercured message to user<br />
   **command:** secure \<password> @clientname \<type message>

4. To decrypt the message<br />
   **command:** decrypt \<password>
 
### Room related commands

1. To create a room<br />
   **command:** room create \<room_name>

2. To join a room<br />
   **command:** room join \<room_name>

3. To leave a room<br />
   **command:** room leave \<room_name>

4. To enlist all members of a room<br />
   **command:** room members \<room_name>

5. To enlist all available users<br />
   **command:** enlist_users

6. To enlist all the rooms available<br />
   **command:** room names
   
7. To send message to a room<br />
   **command:** room chat \<room_name> \<type message> 


