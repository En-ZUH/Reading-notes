# Socket.io

## 1. What is the benefit of transforming data into packets?

#### to transfer the file in faster ansd efficient manner, over the network, and to minimize the transmission latency, by broke the  data into small pieces of variable length.


## 2. UDP is often refereed to as a connectionless protocol. Why is this?

#### it is analogous to sending a letter where you don't acknowledge receipt, so ther is no need for the 
#### connection to be established between the source and destination before you transmit the data, UDP doesn't #### have a mechnism to make sure theat the deployed is not corrupted,
#### As a result, the apllication must take care of data integrity all by itself.
 

## 3. Can a socket server application have multiple socket connections?
#### while the server socket can listen to a single port, it is able to share the same server-side IP/PORT pair as long as they are associated with difference client-side IP/PORT pairs.
 
 
## 4. Can a socket connection application be connected to multiple socket servers?
#### it may be possible, to run out of avaliable ports if you can make a lot of connections in a short amount of time.
 
## 5. Can an application be both a socket server and a socket connection?
#### Yes, the application can be both a socket server, and a socket connections.




## Vocabulary Terms

| Term                     | Definition                                                                                                                                                                                                                                 |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Observer Pattern         | is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods                    |
| Listener                 | is a procedure in JS that waits for an event to occur                                                                                                                                                                                      |
| Event Handler            | a function that runs when a specific event occurs.                                                                                                                                                                                         |
| Event Driven Programming | is when a program is designed to respond to user engagement in various forms.                                                                                                                                                              |
| Event Loop               | is a programming construct or design pattern that waits for and dispatches events or messages in a program. The event loop works by making a request to some internal or external "event provider", then calls the relevant event handler. |
| Event Queue              | is a repository where events from an application are held prior to being processed by a receiving program or system                                                                                                                        |
| Call Stack               | is a stack data structure that stores information about the active subroutines of a computer program.                                                                                                                                      |
| Emit/Raise/Trigger       | in event-driven programming, emit sends a message to trigger a response and raise an event                                                                                                                                                 |
| Subscribe                | subscribe dom events in browser or node.js events.                                                                                                                                                                                         |
| database                 | is a data structure that stores organized information               

****
<!-- ## Preview
 
### 1. Which 3 things had you heard about previously and now have better clarity on?
### 2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
### 3. What are you most excited about trying to implement or see how it works? -->

## Preparation Materials

## what is TCP?
###  The Transmission Control Protocol (TCP) is widely used by application-layer protocols in the Internet Protocol Suite. TCP creates two-way communication between two hosts and provides reliable, ordered, and error-checked byte streams between the applications. 
*  TCP data transfers manage network congestion and use flow control to limit the rate a sender transfers data to guarantee reliable delivery. 
*  Each IP packet between the hosts carries a single TCP Segment. 
*  A TCP segment is made up of header and data sections. 


## what is the WebSocket?
#### WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

### the Difference between WebSocket and Socket.io:

|                       Web-Sockets                         |                                  Socket.io                                   |
| :------------------------------------------------------------: | :----------------------------------------------------------------------------: |
| It is the protocol that is established over the TCP connection |                    It is the library to work with WebSocket                    |
|    It provides full-duplex communication on TCP connections    |       Provides the event-based communication between browser and server        |
|     Proxy and load balancer is not supported in WebSocket.     | A connection can be established in the presence of proxies and load balancers. |
|                It doesn’t support broadcasting                 |                           It supports broadcasting..                           |
|               It doesn’t have a fallback option.               |                         It supports fallback options.                          |

****

#### Refrences
* [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
* [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)
* [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
* [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
* [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)
* [Socket.io Documentation](https://socket.io/docs/v4/index.html)
* [Socket.io Server API](https://socket.io/docs/v3/server-api/index.html)
* [Socket.io Client API](https://socket.io/docs/v3/client-api/index.html)


[Back](https://github.com/En-ZUH/Reading-notes/tree/main/401)
