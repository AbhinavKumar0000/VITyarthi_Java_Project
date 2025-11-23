# Java Chat Application

A multi-user chat application built in Java, supporting both a command-line interface (CLI) and a graphical user interface (GUI) for clients. The server handles multiple concurrent client connections, enabling real-time messaging with unique username registration.

## Features

- **Multi-user Chat**: Supports simultaneous chatting for multiple clients.
- **CLI and GUI Clients**:
  - `ChatClient`: Command-line interface for simple text-based chatting.
  - `ChatClientGUI`: Swing-based GUI with a chat window, user list, and input field.
- **Commands**:
  - `/help`: Lists available commands.
  - `/users`: Displays online users.
  - `/quit`: Disconnects from the server.
- **Username System**: Ensures unique usernames for each client.
- **Threaded Server**: Handles clients concurrently using Java threads.

## Project Structure

- `ChatServer.java`: Manages client connections and message broadcasting.
- `ClientHandler.java`: Processes individual client interactions and commands.
- `ChatClient.java`: CLI client for connecting and chatting.
- `ChatClientGUI.java`: GUI client with a user-friendly interface.
- `ChatApplication.java`: Launcher to start the server or CLI client.

## Prerequisites

- Java Development Kit (JDK) 8 or higher.
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or terminal for compilation.
