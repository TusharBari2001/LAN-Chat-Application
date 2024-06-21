# LAN Chat Application

This is a simple LAN (Local Area Network) chat application implemented in C for server and client communication. The server listens for incoming connections, and the client connects to the server to exchange messages over the local network.

## Features

- Basic client-server architecture.
- TCP socket communication for message exchange.
- Allows multiple clients to connect to the server.
- Simple console-based user interface.

## Prerequisites

- C compiler (e.g., GCC for C programs).
- Linux environment (recommended) or Windows with a compatible compiler.
- Basic understanding of sockets and network programming.

## Usage

### Server Side

1. Compile the server program:
   ```bash
   gcc chat_server.c -o chat_server
   ```

2. Run the server:
```bash
  ./chat_server
```

3. The server will start listening for incoming connections on the specified port.

### Client Side 
1. Compile the client program
   ```bash
   gcc chat_client.c -o chat_client

   ```

2. Run the client:
```bash
  ./chat_client

```

3. Enter the server IP address when prompted and start chatting.


### Customization

- Modify the PORT constant in the chat_server.c and chat_client.c files to change the communication port.
- Update the SERVER_IP constant in the chat_client.c file with the actual IP address of the server.


### Security Considerations

- This is a basic example and does not include encryption for messages.
