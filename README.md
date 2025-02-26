# Building a Custom Redis Implementation
### Goal: The goal of this project is to create a lightweight, custom implementation of Redis using C/C++. The project aims to replicate core Redis functionalities, such as in-memory key-value storage, persistence, and simple client-server communication. By building Redis from scratch, the project provides hands-on experience with key concepts in database systems, memory management, networking, and distributed systems, all while optimizing for performance and scalability.

# Phase 1: Building the TCP Server and Client Models
I implemented the server and client using C and socket programming. The server listens on a specific port for incoming connections, processes client messages, and sends back responses. The client establishes a connection to the server, sends a message, and waits for the response.
