# P2P-Chatroom
Peer-to-peer chatroom program that manages and establishes communication and connection between peers throughout the network using distributed systems methodology.

# System Description
This program contains code for the peer process. Each peer process (the user) will be responsible for connecting to the registry which resides in a centralized server in order to retreive the inital list of peer processes.
The peer system consist of:
  - Group Management: Listen, update, and ping other peers in the peer list
  - Snippet Management: System wide broadcast of our messages to other peers in the system
  - Lamport Logical Clock: Ensure message will satisfy a happens-before order
  - Security Consistency:  Detection and removal of unwanted disruptive spam-like peers in the system
  - Communication Fault Tolerant: Manage dropped stop, and snip messages

  # Demo Video
  [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/PVOUd6fOQA8/0.jpg)](https://www.youtube.com/embed/PVOUd6fOQA8)
