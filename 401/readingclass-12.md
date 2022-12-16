# Reading 12: Sockets

## Web Sockets

### What is a Web Socket?

It is a computer communications protocol, utilizing full duplex communication channels over a TCP connection. 

### Describe the Web Socket request/response handshake and what happens once the connection is established.

Starts with an HTTP reques, and once the connection is established, the communication switches to a bidirectional binary protocol.

### Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

handshake!

# Socket.io Tutorial

### What does the event handler io.on() do?

This sets up callback functions for various events on the Websocket connection.

### Describe some possible proof of life or proof that the code works as expected

You can make the socket connect to a local host server, and configure it to write on HTML and once that goes through correctly it you can write console logs that will say the appropriate line.

### What does socket.emit() do?

It sends a message to all connected clients. Can be used when wanting to notify a userbase that someone has connected to a server.


# Socket.io vs Web Sockets


### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

Websocket is the technology that enables two way communication. Socket.IO just allows the dev to bring that tech through a package, and simplifying the process to use it.

### When would you use Socket.IO?

You would use it when making a comms circuit or or a chat room.

### When would you use WebSockets?

When making data charts to visualize traffic values.

# Videos
## OSI Model Explained

### What are a couple of key takeaways from this video?

OSI models simplifies the communication between different system architecture.

It shows the process of how data goes from a signal to binary all the way up to the user, using various techniques of compression and decompression.


### TCP Handshakes Explained

### Translate the gist of this video to a non-technical friend

So you are talking to someone about a thing they have no experience in. You then share the knowledge and ensure that you are both on the same page then you shake on it and confirm. But before you do all that you ask again how it works.

