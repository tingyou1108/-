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
100+

Network Protocol:
TCP
