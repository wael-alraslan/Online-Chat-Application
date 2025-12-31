README — Online Chat Application

Introduction

This project is a simple online chat application developed in Java. It demonstrates socket programming, client-server communication, and a text-based user interface. Multiple clients can connect to a server, send messages, and receive broadcasted messages from other users in real-time.


Server Implementation

The server program (ChatServer.java) is responsible for:

* Handling incoming client connections
* Assigning a unique User ID to each connected client
* Maintaining and managing active users
* Broadcasting messages to all connected clients
* Using multithreading to support multiple users simultaneously

To start the server:

bash
javac ChatServer.java
java ChatServer


Client Implementation

The client program (ChatClient.java) performs the following:

* Connects to the server using sockets
* Sends messages from the user to the server
* Receives messages broadcasted from other users
* Provides a simple text-based user interface

To start a client:

bash
javac ChatClient.java
java ChatClient


Multiple clients should be launched in separate terminals for full functionality.


How It Works

1. Run the server first so it can listen for connections.
2. Open one or more terminals and launch the client program.
3. Each client will receive a unique User ID assigned by the server.
4. Users type messages and see messages from all other connected users displayed immediately.


User Interface

The application uses a simple console-based interface for:

* Inputting text messages
* Displaying chat messages from other users

Screenshots of the client interface are submitted separately as required.


Files Included

* ChatServer.java
* ChatClient.java
* README.md
* Text-based UI screenshot(s) — submitted separately


Notes

* The project follows clean code structure and readability standards.
* Multithreading ensures smooth message handling and continuous communication.
