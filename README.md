# 💬 Real-Time Chat Application (Spring Boot + WebSocket)

## 📖 Overview

A real-time chat application built using **Spring Boot** and **WebSocket (STOMP)** that enables multiple users to communicate instantly.
The application demonstrates event-driven communication between clients and server using persistent WebSocket connections.

---

## 🚀 Features

* 🔴 Real-time messaging (no page refresh)
* 👥 Multiple users chatting simultaneously
* 🔁 Instant message broadcasting
* ⚡ Lightweight and responsive interface
* 🔌 WebSocket-based communication (STOMP protocol)

---

## 🛠 Tech Stack

* **Backend:** Java, Spring Boot
* **Communication:** WebSocket, STOMP
* **Frontend:** Thymeleaf (server-side rendering), HTML, CSS, JavaScript
* **Build Tool:** Maven

---

## 🧠 How It Works

1. Client establishes a WebSocket connection with the server
2. Messages are sent to a specific endpoint
3. The server processes and broadcasts messages
4. All connected clients receive updates instantly

---

## 📂 Project Structure

```
src/main/java/com/example/chatapp
│── config/        # WebSocket configuration
│── controller/    # Message handling
│── model/         # Data models
```

---

## ▶️ Getting Started

### 🔧 Prerequisites

* Java 17+
* Maven

### 🚀 Run Locally

```bash
git clone https://github.com/yourusername/springboot-websocket-chat-app.git
cd springboot-websocket-chat-app
./mvnw spring-boot:run
```

---

## 🌐 Access the Application

```
http://localhost:8080
```


---

## 🔮 Future Improvements

* 🔐 Add authentication (JWT / Spring Security)
* 💬 Private messaging between users
* 💾 Message persistence using database
* 📱 Improve UI/UX

---



## 📌 Learning Outcomes

* Understanding WebSocket communication
* Implementing real-time systems
* Using STOMP protocol with Spring Boot
* Structuring backend applications

---

## 📧 Contact

If you have any questions or feedback, feel free to reach out.
