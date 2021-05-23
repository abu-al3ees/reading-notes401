## What is the benefit of transforming data into packets?
Packets are intended to transfer data reliably and efficiently. Instead of transferring a large file as a single block of data, sending smaller packets helps ensure each section is transmitted successfully.

## UDP is often refereed to as a connectionless protocol. Why is this?
UDP is a connectionless protocol. It is known as a datagram protocol because it is analogous to sending a letter where you don't acknowledge receipt. Examples of applications that use connectionless transport services are broadcasting and tftp .

## Can a socket server application have multiple socket connections?
yes The server can handle 65,536 sockets per single IP address
## Can a socket connection application be connected to multiple socket servers?
Yes, a socket connection application can connect to multiple socket server Theoretically but it is not practical.
## Can an application be both a socket server and a socket connection? 
no


## Terms

### Observer Pattern
 is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods
### Listener
 is a procedure or function in a computer program that waits for an event to occur
### Event Handler
 scripts that are automatically executed when an event occurs

### Event Driven Programming
 is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads
### Event Loop
 is a programming construct or design pattern that waits for and dispatches events or messages in a program
### Event Queue
is a repository where events from an application are held prior to being processed by a receiving program or system.
### Call Stack
 is a stack data structure that stores information about the active subroutines of a computer program
### Emit/Raise/Trigger
to run or fire ana event
### Subscribe
a function that defines how to obtain or generate values or messages to be published
### database
 is a collection of information that is organized so that it can be easily accessed, managed and updated


 ## WebSocket
  is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the Client or server to terminate the request.


  ### Socket.IO 
  is a library that enables real-time and full-duplex communication between the Client and the Web servers