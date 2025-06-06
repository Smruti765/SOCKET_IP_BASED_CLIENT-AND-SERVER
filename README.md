# 🔌 Socket IP-Based Client & Server Chat Application

This project is a real-time TCP/IP socket-based chat system built using **C# Windows Forms (WinForms)**. It demonstrates how a server can handle **multiple clients**, allowing real-time message exchange using a simple and clean GUI.

---

## 🧠 Features

- 📡 IP-based TCP Socket Communication
- 👥 Multiple Client Connections
- 🔁 Message Broadcasting from Server to All Clients
- 📥📤 Real-Time Messaging and Logging
- 🎨 User-Friendly WinForms UI
- 🧵 Asynchronous Message Handling with `Task`

---

## 📁 Project Structure

SOCKET_IP_BASED_CLIENT_AND_SERVER/
│
├── server/ # WinForms Server Application
│ ├── Form1.cs
│ ├── Form1.Designer.cs
│ └── Program.cs
│
├── client/ # WinForms Client Application
│ ├── Form1.cs
│ ├── Form1.Designer.cs
│ └── Program.cs
│
├── SOCKET_IP_BASED_CLIENT_AND_SERVER.sln
├── README.md
└── .gitignore


---

## 🚀 How to Run

### 🖥️ Server App

1. Open solution in **Visual Studio**.
2. Set `server` project as **Startup Project**.
3. Build and run.
4. Click **Start** to listen on port `5000`.

### 💬 Client App

1. Set `client` project as **Startup Project**.
2. Build and run **multiple instances** to simulate multiple clients.
3. Click **Connect** to connect to the server.
4. Type your message and click **Send**.

> Default IP: `127.0.0.1`  
> Default Port: `5000`

---

## 🔧 Technologies Used

- 🧑‍💻 C# .NET Framework (WinForms)
- 🌐 TCP/IP Networking (`TcpClient`, `TcpListener`, `NetworkStream`)
- 🧵 Multi-threading with `Task`
- 📊 WinForms Controls (Textbox, Buttons, Logging)

---

## 📸 Screenshots (Optional)

| Server | Client |
|--------|--------|
| ![Server UI](https://via.placeholder.com/400x250.png?text=Server+UI) | ![Client UI](https://via.placeholder.com/400x250.png?text=Client+UI) |

> *(Replace with real screenshots later if needed)*

---

## 🧪 Use Cases

- Learn basics of socket programming in .NET
- Build foundations for:
  - Chat Applications
  - Remote Monitoring Systems
  - IoT Device Messaging Interfaces

---

## 📄 License

This project is licensed under the **MIT License** – you are free to use, modify, and distribute it.

---

## 🙋‍♀️ Developed By

**Smruti Jaiswar**  
💼 .NET Developer | Web Developer  
📍 Mumbai, India  
📧 [LinkedIn](https://www.linkedin.com/in/smruti-jaiswar) *(Update link if needed)*

---


