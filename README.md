# 🔐 Secure Chat Application using Python

This project is a **Secure Chat Application** built with **Python sockets** and **Fernet encryption** from the `cryptography` module. It allows two users to communicate securely over a network using end-to-end encrypted messages.

---

## 🧠 Project Objective

To simulate a basic **client-server chat system** where all messages are encrypted before transmission and decrypted upon receipt, ensuring **confidentiality and privacy** during communication.

---

## ⚙️ Features

- 🔒 **End-to-End Encryption** using Fernet (symmetric encryption)
- 🔁 Real-time communication using Python’s `socket` and `threading` modules
- 🖥️ Simple command-line interface (CLI)
- 🚫 No messages are stored or logged
- ✅ Secure communication over LAN

---

## 🛠️ Tech Stack

- Python 3.x  
- `socket` – for client-server communication  
- `cryptography` – for encryption and decryption  
- `threading` – to handle sending/receiving simultaneously

Install dependencies:
pip install cryptography
Start the Server:
python server.py
Start the Client (on another terminal or device):
python client.py
Make sure both client and server are on the same network or update IP settings accordingly.

🔐 How Encryption Works
A Fernet key is generated and securely shared between server and client.

Each message is encrypted using the key before being sent.

The receiving side decrypts the message in real-time.

📂 Project Structure
secure-chat-app/
├── server.py       # Server-side script
├── client.py       # Client-side script
└── key.key         # Fernet key (shared between server & client)
📚 Learning Outcomes
Built a real-time encrypted chat system

Understood client-server communication using sockets

Learned to apply encryption to real-world applications

Practiced secure key sharing and message handling

🛡️ Disclaimer
This app is designed for educational use only and should not be used for actual sensitive communications without enhancements like:
Authentication
Key exchange protocols (e.g., Diffie-Hellman)
Secure channels (e.g., TLS)

👨‍💻 Built With
Python
Cryptography (Fernet)
Socket Programming


🚀 Open to Opportunities
Currently exploring roles in cybersecurity, Python development, and secure software engineering. Let’s connect if you’re looking for someone passionate about building secure systems!

