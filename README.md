# ChatBot Server

## Overview
Welcome to the ChatBot Server project! This repository contains the implementation of a multithreaded server application designed for real-time communication between multiple clients and a central server. Built using C, POSIX Threads, and TCP/IP socket programming, this project showcases a robust and efficient client-server interaction mechanism with integrated chatbot functionality.

## Features
- **Multithreaded Server**: Handles concurrent client connections efficiently.
- **Bidirectional Communication**: Enables seamless message exchange between clients and the server.
- **Basic Chatbot**: Provides intelligent responses to client messages based on predefined logic.
- **Thread Synchronization**: Ensures thread safety using mutex locks and condition variables.

## Technologies Used
- **Programming Language**: C
- **Libraries**: POSIX Threads (pthread), Socket Programming (TCP/IP)
- **Development Tools**: Standard C libraries (stdio.h, stdlib.h, etc.), Linux command line tools for compilation and execution.

## Getting Started

### Prerequisites
- GCC Compiler
- Linux Operating System (recommended for POSIX threads)

### Installation
1. Clone the repository:
  
   git clone https://github.com/Noorhub12/ChatBotServer.git

   cd ChatBotServer


2. Compile the server and client:
  
   gcc -pthread -o server server.c

   gcc -o client client.c


### Usage

#### Running the Server
1. Start the server:
  
   ./server


#### Running the Client
1. Open a new terminal and run the client:

   ./client


2. Connect multiple clients by opening new terminals and running the client command again.

## Project Structure
- `server.c`: Contains the implementation of the multithreaded server.
- `client.c`: Contains the implementation of the client.
- `README.md`: Project documentation.

## Future Enhancements
- **Advanced Chatbot**: Integrate machine learning or NLP techniques for more intelligent responses.
- **Security Enhancements**: Implement secure communication protocols (e.g., SSL/TLS) and user authentication.
- **GUI Development**: Create a graphical user interface for clients to enhance usability.
- **Scalability**: Optimize server performance for handling larger numbers of concurrent client connections.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Author
- Noor-ul-Huda (22PWCSE2117)



---

Feel free to explore, use, and contribute to the ChatBot Server project. Happy coding! 🎉

---
