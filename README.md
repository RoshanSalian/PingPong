# Multiplayer PING-PONG Game
> Python game implemeted using pygame and PodSixNet

Classical Ping-Pong game with multiplayer functionality playable in LAN connected individual systems. The Host system needs to host a game and client connects to this request. Each of the connected system can control the player using keyboard keys. Goal is to keep the ball with the bounds.

![alt text](screenshot.png)

## Installation
```sh
pip install PodSixNet
```

## Usage
One system runs the server program
```sh
python server.py
```
Enter the IP address on the device running the server program.</br>

For the client device, run the client program,
```sh
python client.py
```
Enter the IP address of the server.
 
