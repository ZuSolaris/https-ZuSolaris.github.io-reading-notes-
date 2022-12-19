# Reading: Message Queues

## Socket.io Chat Example

### Explain to a non-technical recruiter what the Chat Example (above) does.
This is an example of a client and a server. But lets just put it as a post office and mail man. The office gives the mail man directions and he abides by those and the post office looks for confirmations and replies. The communcation is what socket.io handles. 

### What proof of life are we getting on the backend from the above app?

When a server is started, connections and disconnection notices.


### Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

socket.to is the flag used to omit!

## Rooms

## What is a room and how might a room be useful?

They are channels that sockets and connect and disconnect multiple connect. Great for having multiple pathways for communication.

## How do you join a room?

io.on("connection", (socket) => {
  socket.join("some room");
});

## how do you leave a room?

io.on("connection", socket => {
  socket.on("disconnecting", () => {
    console.log(socket.rooms); // the Set contains at least the socket ID
  });

  socket.on("disconnect", () => {
    // socket.rooms.size === 0
  });
});

## Namespaces

## What is a Namespace and what does it allow you to do?

What is a Namespace and what does it allow you to do?

A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection also called "multiplexing".

### Each namespace potentially has its own what? (hint: 3 things)

Events Handlers

Room

Middlewares


### Discuss a possible use case for separate namespaces

Make it where only authorized users have access to a seperate namespace with it's own individual roles and such.ls
