# 💬 Java Chat Messenger with Log Facility

## 📌 Introduction
Java Chat Messenger is a simple client-server communication application developed using Java Socket Programming. It enables two-way communication between a client and a server over a network connection.

---

## 🎯 Objective
The objective of this project is to demonstrate networking concepts in Java such as:
- Socket Programming
- Streams (Input/Output)
- Client-Server Architecture

---

## 🏗️ System Architecture

Client → Socket Connection → Server

The client sends messages to the server using TCP communication.  
The server receives messages, displays them on the console, logs them into a file, and sends responses back to the client.

---

## 🔑 Key Components

### 👤 Client
- Successful connection with the server
- Sends messages to the server
- Receives responses from the server

### 🖥️ Server
- Listens for incoming client connections
- Accepts client requests
- Handles message exchange
- Stores communication logs

---

## 📝 Logging Mechanism
The server maintains a log file (`chat_log.txt`) where all chat messages are saved.

Implemented using:
- `FileWriter`
- `BufferedWriter`

### Example Log Entry:
- Client : Hello Server
- Server : Hi Client

---

## ⚙️ Technologies Used
- Java
- Socket Programming
- Java IO Streams
- TCP Networking

---

## 🚀 Possible Enhancements
- Support for multiple clients with improved messaging features  
- Add GUI (Java Swing), secure communication, and message history tracking    

---

## 📂 Project Structure

```
Java-Chat-Messenger-With-Log-Facility
│
├── src
│   ├── Client.java
│   └── Server.java
│
├── logs
│   └── chat_log.txt
│
├── docs
│   └── project_overview.md
│
├── README.md
└── .gitignore
```
