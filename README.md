# Chatting Application

## Overview
This is a simple desktop-based chatting application implemented in Java using Swing for the user interface and socket programming for network communication. The project demonstrates real-time text-based messaging between a server and a client over a network.

## Features
- Real-time text-based communication.
- Client-server architecture with reliable message delivery.
- Simple and intuitive graphical user interface.

## Tools & Technologies
- Programming Language: Java SE
- GUI: Swing and AWT
- Networking: Java's `java.net` package (TCP/UDP protocols)

## How It Works
1. Start the server application on one machine.
2. Launch the client application on another machine and connect it to the server using its hostname and port number.
3. Type messages in the input box and click "Send" to transmit them.
4. Messages are relayed via the server and displayed in real time.

## Requirements
- JDK 1.2 or later installed on both client and server machines.
- Basic understanding of Java programming.

## Future Enhancements
- File sharing capabilities.
- Voice and video chat support.
- Enhanced UI design.

## How to Run
1. Compile both `Server.java` and `Client.java`.
2. Run `Server.java` first to start the server.
3. Run `Client.java` on another system, enter the server details, and connect.
4. Start chatting!

## Acknowledgments
Special thanks to our mentors and peers who supported this project development journey!
