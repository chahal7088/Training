# OSI Model
Author- Sunny Chahal
- Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network.  
- Mac address - Media Access control Address, Physical and hardware gets to know. network adapter can be digested. Mac address unique, permanent address.
  can not be changed . Mac address 48 bit mac address divided into 6 parts. each part has 8 bit (1 byte ).

1. Application Layer 
  _At the very top of the OSI Reference Model stack of layers, we find the Application layer which is implemented by the network applications.
  _These applications produce the data to be transferred over the network. This layer also serves as a window for the application services to access the 
  _network and for displaying the received information to the user. 
 
  _Example: Application – Browsers, Skype Messenger, etc. 

2. The Presentation Layer
  
  _The presentation layer is primarily responsible for translating data from network data to the formats expected by an application.
  _For example, data encodings and encryption are managed at Layer

3. The Session Layer

  _The session layer manages sessions between nodes and acts on the “data” PDU. Session management includes setup, authentication, termination, and reconnections.
  _This layer allows users on different machines to establish active communications sessions between them. It is responsible for establishing, maintaining, synchronizing,
  _terminating sessions between end-user applications. In Session Layer, streams of data are received and further marked, which is then resynchronized properly, so that
  _the ends of the messages are not cut initially and further data loss is avoided. This layer basically establishes a connection between the session entities.    This layer handles and manipulates data which it receives from the Session Layer as well as from the Presentation Layer.

4. The Transport Layer

  _The transport layer is the first of four “host” layers with the rest referred to as “media” layers. The transport layer PDU is the “segment” or “datagram”.
  -This layer manages the transmission of data between nodes, including ensuring that data arrives in the correct sequence and that any errors are corrected.
  -The Transmission Control Protocol (TCP) operates at Layer 4
 
5. Network Layer

  _The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end.
  _The other is routing packets by discovering the best path across a physical network. The network layer uses network addresses (typically Internet Protocol addresses) to route packets to a destination node.

6. The Data Link Layer

  _The data link layer breaks data to be transmitted into frames for transmission at the physical layer. It also manages connections between two different nodes,
  _including setting up the connection, identifying and correcting any bit errors that occur at the physical layer,and terminating the connection once the session is complete.

7. The Physical Layer

  _The physical layer is where the raw bitstream is physically transmitted over a physical medium. The Layer 1 PDU is the “symbol”.
  _This includes translating bits to electricity, light, or radio signals and controlling the rates at which they are sent over the chosen medium.