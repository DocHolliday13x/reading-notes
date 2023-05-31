# Class 12 Reading: Socket.io

## Resources

- [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
- [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
- [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)
- [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
- [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)
- [Socket.io Docs](https://socket.io/docs/v4/)
- [Socket.io Server API](https://socket.io/docs/v4/server-api)
- [Socket.io Client API](https://socket.io/docs/v4/client-api)
- [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-12/)

## Web Sockets

1. What is a web socket?
    - A web socket is a communication protocol that provides a full-duplex communication channel over a single TCP connection. It is used to create interactive web applications that support real-time communication between a client and a server.

2. Describe the Web Socket request/response handshake and what happens once the connection is established.
    - The client sends a request to the server to establish a connection. The server responds with a 101 status code if the connection is successful. Once the connection is established, the client and server can send messages to each other.

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
    - Web Sockets provide a standardized way for the server to send content to a client without first receiving a request from that client.

## Socket.io Tutorial

1. What does the event handler `io.on()` do?
    - The event handler `io.on()` listens for events and executes a callback function when the event is triggered.

2. Describe some possible proof of life or proof that the code works as expected:
    - The server console logs a message when a client connects to the server.
    - The client console logs a message when the client connects to the server.
    - The client console logs a message when the client receives a message from the server.
    - The server console logs a message when the server receives a message from the client.

3. What does `socket.emit()` do?
    - The `socket.emit()` method sends a message to the server.

## Socket.io vs Web Sockets

1. What is the difference between WebSocket and Socket.io?
    - WebSocket is a communication protocol that provides a full-duplex communication channel over a single TCP connection. Socket.io is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

2. When would you use socket.io?
    - Socket.io is used to create interactive web applications that support real-time communication between a client and a server.

3. When would you use WebSockets?
    - WebSockets are used to create interactive web applications that support real-time communication between a client and a server.

## OSI Model Explained

1. What are a couple of takeaways from this video?
    - The OSI model is a conceptual model that describes the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.
    - The OSI model is a conceptual model that describes the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.
    - The OSI model is a conceptual model that describes the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology.

## TCP Handshakes Explained

1. Translate the gist of the video to a non-technical friend.
    - The TCP handshake is a three-way process that establishes a connection between a client and a server. The client sends a SYN packet to the server. The server responds with a SYN-ACK packet. The client responds with an ACK packet. The connection is established.

### Bookmark and Review

- [Socket.io Docs](https://socket.io/docs/v4/)
- [Socket.io Server API](https://socket.io/docs/v4/server-api)
- [Socket.io Client API](https://socket.io/docs/v4/client-api)
- [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-00/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: I want to understand how to use Socket.io to create interactive web applications that support real-time communication between a client and a server.

#### Things I Want to Know More About

1. Question 1?
    - Answer 1.

![GIF](https://media.giphy.com/media/l2Je4zlfxF6z0IWZi/giphy.gif)
