
# OSI Model

OSI stands for Open Systems Interconnection, where open stands to say non proprietary.It is a 7-layer architecture with each layer having specific functionality to perform.
All these 7 layers work collaboratively to transmit the data from one person to another across the globe. The OSI reference model was developed by ISO – ‘International Organization for Standardization‘, in the year 1984.
The OSI model provides a theoretical foundation for understanding network communication. However it is usually not directly implemented in its entirety in real-world networking hardware or software.
Instead, specific protocols and technologies are often designed based on the principles outlined in the OSI model to facilitate efficient data transmission and networking operations.

_ _ Application Layer

- The topmost layer that interacts directly with user applications.
- Provides network services to applications (e.g., email, web browsing, file transfer).
- Examples of Application Layer protocols: HTTP, SMTP, FTP, and DNS.

_ _ Presentation Layer

- Translates data between the application layer and lower layers.
- Handles data formatting, encryption, and compression.
- Ensures data compatibility between different systems.
- Examples of Presentation Layer tasks: Data encryption, character encoding, and data compression.

_ _ Session Layer

- Establishes, maintains, and terminates communication sessions between applications.
- Manages dialog control, synchronization, and checkpointing.
- Examples of Session Layer functions: Authentication, encryption, and session management.

_ _ Transport Layer

- Ensures reliable end-to-end communication.
- Segments data into smaller units (segments) and manages flow control.
- Provides error detection and correction.
- Examples of Transport Layer protocols: TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).

_ _ Network Layer

- Handles routing and forwarding of data packets.
- Determines the best path for data to travel across different networks.
- Uses logical addressing (IP addresses) to identify devices.
- Examples of Network Layer devices: Routers and Layer 3 switches.

_ _ Data Link Layer

- Manages communication between directly connected devices.
- Responsible for framing data into frames, error detection, and flow control.
- Includes sublayers: Logical Link Control (LLC) and Media Access Control (MAC).
- Examples of Data Link Layer devices: Network switches and network interface cards (NICs).

_ _ Physical Layer

-The lowest layer in the OSI model.
- Responsible for the actual physical connection between devices.
- Transmits individual bits from one node to the next.
- Functions include bit synchronization, defining transmission rates, specifying physical topologies (e.g., bus, star, mesh), and determining transmission modes (simplex, half-duplex, full-duplex).
- Examples of Physical Layer devices: Hub, Repeater, Modem, and Cables.