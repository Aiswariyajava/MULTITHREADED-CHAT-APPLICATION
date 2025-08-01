# MULTITHREADED-CHAT-APPLICATION

COMPANY:CODTECH IT SOLUTIONS

NAME:AISWARIYA.K

INTERN ID:CT04DZ963

DOMAIN:JAVA PROGRAMMING

DURATION:4 WEEKS

MENTOR:MUZAMMIL


 DESCRIPTION: Multithreaded Client-Server Chat Application Using Java Sockets
This project is a console-based chat application built using Java Sockets and Multithreading, allowing multiple clients to communicate with each other in real-time through a single server.

The application is divided into three main components:

Server:
The Server.java class is responsible for accepting client connections and managing them using separate threads. It listens on a specific port (e.g., 1234) and creates a new ClientHandler thread for each connected client. All messages from one client are broadcast to all other connected clients.

ClientHandler:
The ClientHandler.java class runs as a separate thread for each client. It handles the client's messages and uses shared resources to forward those messages to other clients. This enables simultaneous chatting between multiple users without blocking other connections.

Client:
The Client.java class connects to the server and allows the user to send and receive messages. It runs two threads:

One for reading user input and sending it to the server.

Another for continuously listening to and displaying incoming messages from the server.


 Learning Outcomes:
Hands-on experience with Java Sockets.

Understanding of client-server architecture.

Thread management and concurrency in Java.

I/O stream handling and inter-thread communication.

 How It Works:
Start the server using java Server.

Run multiple clients using java Client.

Each client provides a name and can start chatting.

Messages are sent to all connected clients instantly.

Clients can type exit to disconnect gracefully.



No file chosenNo file chosen
ChatGPT can make mistakes. Check important info. See Cookie Preferences.
