# Class 4.12 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 1**
- [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
- [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
- [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)
- [Socket.io Documentation](https://socket.io/docs/)
- [Socket.io Server API](https://socket.io/docs/server-api)
- [Socket.io Client API](https://socket.io/docs/client-api)
- [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

****

**Web Sockets**

1. What is a Web Socket?
  - An advanced program which allows two-way communication between a users browser and server
2. Describe the Web Socket request/response handshake and what happens once the connection is established.
  - A request is sent from the clients websocket as a request and the server returns a resonse indicating a connection was made.
3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
  - Request


****
  
**Socket.io Tutorial**

1. What does the event handler io.on() do?
  - Handles connection / disconnection events.
2. Describe some possible proof of life or proof that the code works as expected
  - Using handlers such as socket.emit, io.on and socket.on, we can use console.log within these to print return messages when they are hit
3. What does socket.emit() do?
  - Sends messages or responses when hit

****
  
**Socket.io vs Web Sockets**

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
  - WebSocket: protocol which is established over the TCP connection
  - Socket.io: library to work with WebSocket
2. When would you use Socket.io?
  - Sockect.io supports broadcasting and can establish connection which proxies, as well as having fallback options
3. When would you use WebSockets?
  - Provides full-duplex communications on TCP connections 


## Things I want to know more about
