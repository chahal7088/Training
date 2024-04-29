# OSI Model
 - The Open Systems Interconnection (OSI) model is a conceptual framework that defines how networking systems communicate and send data from a sender to a recipient.
   Developed by the International Organization for Standardization (ISO) in 1984, this model provides a systematic approach to understanding network communication by dividing it into seven distinct layers.
   Let’s explore these layers  
 
1. ### Application Layer 
     -  The topmost layer that interacts directly with user applications.
     -  Provides network services to applications.
     -  Examples of Application Layer protocols: HTTP, SMTP, FTP, and DNS

2. ### The Presentation Layer

     -  Responsible for data translation, encryption, and compression.
     -  Ensures data is in a format that both sender and receiver can understand.
     -  Examples of Presentation Layer tasks: Data encryption, character encoding, and data compression.
    
3. ### The Session Layer

     -  Manages sessions (dialogues) between applications.
     -  Establishes, maintains, and terminates connections.
     -  Handles synchronization points and checkpoints.
     -  Examples of Session Layer functions: Session establishment, data exchange, and session termination.

    
4. ### The Transport Layer

     -  Ensures end-to-end communication and reliable data transfer.
     -  Segments data into smaller units (segments or datagrams).
     -  Provides error detection, flow control, and sequencing.
     -  Examples of Transport Layer protocols: TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).
   
5. ### Network Layer

     -  Handles routing and logical addressing.
     -  Determines the best path for data packets to reach their destination.
     -  Examples of Network Layer devices: Routers and Layer 3 switches.
    
6. ### The Data Link Layer

     -  Manages data link between two directly connected nodes.
     -  Ensures reliable data transfer over a physical link.
     -  Divided into two sublayers: Logical Link Control (LLC) and Media Access Control (MAC).
     -  Responsible for framing, error detection, and flow control.
   
7. ### The Physical Layer

    -   The physical layer is where the raw bitstream is physically transmitted over a physical medium. The Layer 1 PDU is the “symbol”.
    -   This includes translating bits to electricity, light, or radio signals and controlling the rates at which they are sent over the chosen medium.
    -   The lowest layer of the OSI model.
    -   Responsible for the physical connection between devices.
    -   Transmits individual bits from one node to the next.

   #  MAC ADDRESS

   -   Media Access control Address, Physical and hardware gets to know. network adapter can be digested. Mac address unique, permanent address.
       can not be changed . Mac address 48 bit mac address divided into 6 parts. each part has 8 bit (1 byte ).

