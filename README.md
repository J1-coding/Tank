# Tank Blitz

## Introduction

Tank Blitz is a multiplayer tank game inspired by a mini-game from Mario Party. This game allows players to operate tanks, shoot cannons, and battle against each other in a Mario Party-themed environment. Each tank has a specified health point (HP), which decreases when hit. Once a tank's HP reaches zero, the tank is defeated. The game continues until only one tank remains undefeated.

Tank Blitz is built using Unity and leverages the Photon RPC for multiplayer game execution. 

## Gameplay

The game has two primary modes of firing the cannon:

1. **Parabolic Shot**: By right-clicking the mouse, players can shoot the cannon in a parabolic trajectory.
2. **Straight Shot**: By left-clicking the mouse, players can shoot the cannon straight.

![ezgif com-optimize](https://github.com/J1-coding/TankBlitz/assets/83527213/05017604-cc2b-45f8-95fd-0531ed4df629)


The game is played in rooms that can host a specific number of players. Players enter a room by typing their nickname and the room name. Once inside, they can set the maximum number of players allowed in the room. As more players join, the room name appears on a public room list that others can view and join.

## How to Join a Game

1. Enter your nickname.
2. Type the room name.
3. Set the maximum number of players for the room.
4. Click 'Join Room' to start playing with other players.

## Inspiration

The motivation behind Tank Blitz originates from the mini tank game of Mario Party. The game scene is designed to resemble the Mario Party theme, providing a fun and familiar environment for players.

## Built With 

- [Unity](https://unity.com/)
- [Photon RPC](https://www.photonengine.com/en-US/Photon)
