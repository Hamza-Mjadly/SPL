# TFTP Server and Client

## Overview
This project involves implementing an **Extended TFTP (Trivial File Transfer Protocol)** server and client in Java. The server follows a Thread-Per-Client (TPC) pattern to handle multiple clients simultaneously.

---

## Features
- **Client Commands**:
  - `LOGRQ`: User login.
  - `RRQ/WRQ`: Download/upload files.
  - `DELRQ`: Delete files on the server.
  - `DIRQ`: List files on the server.
  - `DISC`: Disconnect from the server.
- **Server Functionality**:
  - Handles multiple clients with TPC design.
  - Supports bi-directional communication.
  - Broadcasts file updates to all connected clients.
- **Protocol Enhancements**:
  - Extended binary packet format.
  - Robust error handling and reporting.

---

## How to Run
1. Build the server:
   - `mvn compile`
   - `mvn exec:java -Dexec.mainClass="bgu.spl.net.impl.tftp.TftpServer" -Dexec.args="<port>"`
2. Build the client:
   - `mvn compile`
   - `mvn exec:java -Dexec.mainClass="bgu.spl.net.impl.tftp.TftpClient" -Dexec.args="<ip> <port>"`

---

## Notes
- Follow the provided binary encoding guidelines for message handling.
- Ensure compliance with TCP-based communication standards.
- Test using the provided client-server examples.
