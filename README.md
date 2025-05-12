
# Group_Chat_Server

📌 Overview
This is a simple Group Chat Server built in Java as part of a 1-day coding challenge during my Full-Stack Bootcamp. The goal of this project was to implement a basic server-client communication system where multiple users can connect to a server and chat in real time using the terminal/console.

🛠️ Technologies Used
Java 

Sockets 

Multithreading

🎯 Objectives
Practice Java networking using ServerSocket and Socket.

Use threads to handle multiple clients concurrently.

Broadcast messages from one client to all others.

Build a functional and interactive command-line group chat system.

⚙️ How It Works
The server listens on a specified port.

Each client connects to the server and is handled in a separate thread.

When a client sends a message, the server broadcasts it to all other connected clients.

The server manages client disconnection gracefully.

🚀 Getting Started

Run the Server

    javac ChatServer.java

Run the Client (in a new terminal for each client)

    javac ChatClient.java

🧠 What I Learned
How socket communication works in Java.

Basics of multithreading to handle multiple users.

Importance of input/output stream handling and user synchronization.

Debugging and improving real-time applications under time pressure.

📅 Challenge Time
This project was completed within 1 day as part of a bootcamp coding challenge, focusing on fast implementation and learning by doing.


