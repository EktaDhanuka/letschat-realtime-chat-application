# realtime-chat-application-letschat
It is an scalable realtime chatting application that provides an interface for multiple user chatting at the same time.
Here, I have used Socket.io module for a two-way connection/communication between client and server.
FrontEnd Technologies- HTML, CSS
BackEnd Technologies- JavaScript, Node.js

In UI, we have a Chat Box which contains messages from different clients and an input for adding our messages and a button for sending the messages.
In Backend, we have a node server which handles all events from different sockets

Functionalities:-
1. If any user enters, it asks for his/her name.
2. Once name is entered by the user, he can join the chat and everyone present in the room gets the message with a notification sound.
3. Once a user sends a message, his message comes in left side for other users and in right side for himself.
4. Once a user leaves the chat, other members in the room are informed with 'disconnect' event.

# run the chat app
1. Install the "live server" extension from VS Code
2. Open this repository using VS Code
3. Click on 'Go Live" from bottom right corner of VS Code UI from index.html
4. For multiple users, copy the url from the browser and open it in different tab/window or any browser
