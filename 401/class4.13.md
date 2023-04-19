# Class 4.1 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 1**
- [Socket.io Chat Example](https://socket.io/get-started/chat/)
- [Rooms](https://socket.io/docs/v4/rooms)
- [Namespaces](https://socket.io/docs/v4/namespaces/)
- [Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

****

**Socket.io Chat Example**
1. Explain to a non-technical recruiter what the Chat Example (above) does.
  - This acts as a listener for a special event to happen. In this case, an a string is the input. The message is then routed to a handler which can then send it to the appropriate place.
2. What proof of life are we getting on the backend from the above app?
  - By broadcasting to users when a user connects / disconnects.
3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
  - Adding a 'not' conditional rather than checking for a value.

****
  
**Rooms**
1. What is a room and how might a room be useful?
  - An arbitrary channel that sockets can join and leave.
2. How do you join a room?
  - Calling socket.join
3. How do you leave a room?
  - Passing in disconnect

****
  
**Namespaces**
1. What is a Namespace and what does it allow you to do?
  - Anopen channel which users can connect / disconnect to / from.
2. Each namespace potentially has its own what? (hint: 3 things)
  - Client, server and the communication pipe / channel
3. Discuss a possible use case for separate namespaces
  - Perhaps if you are handling several different applications which use these


## Things I want to know more about
