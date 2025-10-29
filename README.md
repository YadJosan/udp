# UDP Chat Server (Node.js)

A simple UDP server built using Node.js `dgram` module.  
It listens for messages from clients, stores their information, and allows the server operator to send messages back to connected clients via standard input.

---

## 🚀 Features

- Lightweight UDP server using Node.js
- Handles multiple client connections
- Receives and broadcasts messages
- Allows server operator to send messages manually
- Graceful shutdown with `exit` command

---

## 🧠 How It Works

1. The server listens for UDP datagrams on the provided IP and port.
2. When a message is received, it logs it to the console and stores the client’s address and port.
3. The server operator can type messages in the terminal — these are sent back to the connected clients.
4. Type `exit` and press **Enter** to stop the server.

---

## ⚙️ Installation & Usage
 
You can now run your server with:

npm install

npm start <PORT> <ADDRESS>
