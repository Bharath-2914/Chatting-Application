# Chatting-Application

# 🗨️ Group Chat Application

A **Java-based Group Chat Application** using **Sockets**, **Multithreading**, and **Swing GUI**. Users can send and receive messages in real-time.

## 📌 Features
- **Multiple Users Support**: Users can join the chat simultaneously.
- **Real-time Messaging**: Messages are instantly delivered to all connected users.
- **Graphical User Interface (GUI)** using **Swing**.
- **Server-Client Architecture**: One server handles multiple clients.

## 🛠️ Technologies Used
- **Java**
- **Swing** (for GUI)
- **Sockets** (for network communication)
- **Multithreading** (for handling multiple users)

## 🚀 How to Run

### 1️⃣ Prerequisites
- Install **Java JDK 8+**.
- Any **Java IDE** (e.g., NetBeans, IntelliJ, Eclipse) or command line.

### 2️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/chat-application.git
cd chat-application
```

### 3️⃣ Start the Server
Compile and run the **Server**:
```sh
javac Server.java
java Server
```
> The server listens on **port 2003**.

### 4️⃣ Start Chat Clients
Each user runs their respective client file (**UserOne.java**, **UserTwo.java**, etc.):
```sh
javac UserOne.java
java UserOne
```
```sh
javac UserTwo.java
java UserTwo
```
```sh
javac UserThird.java
java UserThird
```

## 📂 Project Structure
```
📦 Chat Application
 ┣ 📂 src/group/chatting/application/
 ┃ ┣ 📜 Server.java     # Handles multiple clients
 ┃ ┣ 📜 UserOne.java    # First user client
 ┃ ┣ 📜 UserTwo.java    # Second user client
 ┃ ┣ 📜 UserThird.java  # Third user client
 ┣ 📜 README.md         # Project documentation
```

## 🎮 How It Works
1️⃣ **Run `Server.java`** to start the server.  
2️⃣ **Run `UserOne.java`, `UserTwo.java`, and `UserThird.java`** to start the chat clients.  
3️⃣ **Users can send and receive messages** in real-time.  

## 🏆 Future Enhancements
- Add **User Authentication**.
- Implement **Database Integration** (store chat history).
- Improve **UI Design** with modern frameworks.

## 🤝 Contributing
Feel free to contribute! Fork the repository, make changes, and submit a pull request.

## 📜 License
This project is **open-source** and free to use.
