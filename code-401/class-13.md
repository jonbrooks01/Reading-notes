# Class 13 Reading Notes

## Socket.io Chat Example

1) Utilizing sockets your able to create a simple chat application where the sender and receiver can exchange messages in real time.

2) You will see a user being connect as well as a user being disconnected in the terminal to verify proof of life

3) By using the socket.broadcast flag you can send a message to everyone except for a certain emitting socket

## Rooms

1) A room is where sockets can join/leave. it can be used to broadcast messages to a subset of clients

2) you would use socket.join to join a room

3) to leave a room you will simply use the socket.leave

## Namespaces

1) A namespace is a communication channel that allows you to split the logic of the application over a single shared connection

2) Each namespace has its own event handlers, rooms and middleware.

3) The possible use cases for namespaces would be creating a space where only authorized users have access, or allowing one tenant to have their own namespace
