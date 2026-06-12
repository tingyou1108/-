online 1v1 1A2B GAME


Project Features
✓ TCP Socket Communication
✓ Client-Server Architecture
✓ Two-Player Real-Time Gameplay
✓ State Synchronization
✓ Turn-Based Game Control
✓ Win/Lose Detection
Challenge:
Player states became inconsistent
when network messages arrived unexpectedly.

Solution:
Designed a state-machine-based
turn control mechanism to synchronize
both clients.

## Project Overview

This project is a two-player online 1A2B game
implemented using Winsock TCP sockets.

The objective of this project is to learn
network programming, client-server architecture,
and game state synchronization.

Player 1
   |
 TCP
   |
Server
├─ Connection Manager
├─ Game State Manager
└─ Result Dispatcher
   |
 TCP
   |
Player 2

Project Statistics

Development Time:
10weeks

Language:
C++

Source Files:
3

Lines of Code:
150+

Network Protocol:
TCP
## Screenshots

### Server Console

<img width="865" height="314" alt="image" src="https://github.com/user-attachments/assets/81a69261-ce11-4415-8ab1-684c9926e9ef" />


### Client 1
### Client 2
<img width="865" height="274" alt="image" src="https://github.com/user-attachments/assets/7f289e02-1a20-41a5-96cc-80966459ea95" />

