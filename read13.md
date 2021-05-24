### What does it mean that web sockets are bidirectional? Why is this useful?
This means that, once the initial handshake has taken place and the connection is established, the client and server can both communicate with each other freely

### Does socket.io use HTTP? Why?
 Even when websockets can be used, the initial connection setup it done over HTTP. Also, a socket.io server will attach to an HTTP server so it can serve its own client code throug

### What happens when a client emits an event?
 When a client emits, it sends the data and the server will receive it when the client connect
### What happens when a server emits an event?
send data
### What happens if a client “misses” an event?
nothing will happen


### Socket
is a way of connecting two nodes on a network to communicate with each other
### Web Socket
 is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.
### Socket.io
enables real-time, bidirectional and event-based communication
### Client
 computer that connects to the network.
### Server
recive and send data to the client
### OSI Model
 is a conceptual framework used to describe the functions of a networking system
### TCP Model
It stands for Transmission Control Protocol/Internet Protocol. The TCP/IP model is a concise version of the OSI model. It contains four layers, unlike seven layers in the OSI model

### TCP
 is a standard that defines how to establish and maintain a network conversation through which application programs can exchange data.
### UDP
is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet
### Packets
 is a small amount of data sent over a network