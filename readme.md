## Student Collaboration Chat Protocol Implementation using QUIC in GO

## Overview
The Student Collaboration Chat Protocol Application is a network-based chat application designed to facilitate communication among students. It uses the QUIC protocol for secure, reliable communication and supports both server and client modes. This project is implemented in Go.

## Team Members
- **Rohit Annasaheb Ragde**: [rar369@drexel.edu](mailto:rar369@drexel.edu)
- **Disha Yadav**: [dcy26@drexel.edu](mailto:dcy26@drexel.edu)

## Features

#### Real-Time Messaging

- **Basic Messaging:** Implement basic functionality for sending and receiving messages between clients.
- **QUIC Protocol:** Utilizes the `quic-go` library to handle QUIC sockets for efficient and reliable communication.
- **Message Encoding/Decoding:** Custom PDU (Protocol Data Unit) format is used for message encoding and decoding to ensure efficient data transmission.
- **Emoji Support:** Supports sending and receiving messages with emojis as part of the Unicode standard.

#### Secure Communication

- **TLS Encryption:** Utilizes TLS for secure communication over QUIC, ensuring that all messages are encrypted.

#### User Management

- **Username Handling:** Users can join the chat with a specified username.
- **User Join/Leave Notifications:** Notifies all users when someone joins or leaves the chat.

#### Broadcast Messaging

- **Message Broadcasting:** Sends messages to all connected clients, ensuring everyone in the chat room receives the messages.

#### Active Users Listing

- **List Active Users:** Allows users to request a list of active users in the chat room.






