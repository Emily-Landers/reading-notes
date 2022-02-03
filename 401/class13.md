# Message Queues

- What does it mean that web sockets are bidirectional? Why is this useful?
    - Websockets allow real time communication between client/server and client/client by operating asynchronously
- Does socket.io use HTTP? Why?
    - It can attach to an HTTP server for communication
- What happens when a client emits an event?
    - the server begins listening
- What happens when a server emits an event?
    - it sends data to all connected clients
- What happens if a client “misses” an event?
    - the message will be ignored
- How can we mitigate this?
    - with a function to store data until the client reconnects

Document the following Vocabulary Terms

- Socket: an endpoint of two way communication between two programs on a network
- Web Socket: a protocol that allows for TCP connection between server and client
- Socket.io: a JavaScript library for realtime web applications that allows for bidirectional dataflow
- Client: a computer or program that sends requests to another program
- Server: a computer or computer program which manages access to a centralized resource or service in a network.
- OSI Model: (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system.
- TCP Model: stands for Transmission Control Protocol/Internet Protocol. The TCP/IP model is a concise version of the OSI model. It contains four layers, unlike seven layers in the OSI model.
- TCP: a transport protocol that is used on top of IP to ensure reliable transmission of packets. 
- UDP: a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet.
- Packets: a formatted chunk of data sent over a network. 

- Which 3 things had you heard about previously and now have better clarity on?
    - TCP, UDP, and Packets
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - TCP, UDP, and Packets
- What are you most excited about trying to implement or see how it works?
    - TCP
