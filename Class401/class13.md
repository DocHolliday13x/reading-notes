# Class 00 Reading: Message Queues

## Resources

- [Socket.io Chat Example](https://socket.io/get-started/chat/)
- [Rooms](https://socket.io/docs/v4/rooms)
- [Namespaces](https://socket.io/docs/v4/namespaces/)
- [Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-13/)

## Socket.io Chat Example

1. Explain to a non-technical recruiter what the Chat Example (above) does.
    - The server can push messages to clients. Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients.

2. What proof of life are we getting on the backend from the above app?
    - "Hello world" should show up on local host 3000.

3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
    - `broadcast` flag

## Rooms

1. What is a room and how might a room be useful?
    - A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.

2. How do you join a room?
    - `socket.join("some room")`

3. How do you leave a room?
    - `socket.leave("some room")`

## Namespaces

1. What is a namespace and what does it allow you to do?
    - A namespace is a way to separate sockets into different groups. It allows you to segment the users by purpose or function.

2. Each namespace potentially has its own ___________? (hint: 3 things)
    - Each namespace potentially has its own `default` room, `connection` event, and `disconnect` event.

3. Discuss a possible use case for separate namespaces.
    - A possible use case for separate namespaces is to separate the users by purpose or function. ie. you could have a namespace for the chat room and a namespace for the game room.

### Bookmark and Review

- [Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-13/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: My goal is simple - I want to create a chat room that allows users to send messages to each other.

#### Things I Want to Know More About

1. I want to learn how exactly sockets work. I want to know how to create a chat room that allows users to send messages to each other.

![GIF](https://media.giphy.com/media/vIwbtpMuWeV0I/giphy.gif)
