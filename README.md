# Curse of the Bone Lord  

This is a game I fully developed in one month by myself using Unity.  
Only the SFX and music were AI-generated or sourced from various free sound effect websites like [Freesound.org](https://freesound.org/).  
All assets are created by myself as well.  

A full playthrough can be seen here: [Watch on YouTube](https://www.youtube.com/watch?v=bzEGGz48WN0)  

---

## About the Game  

Curse of the Bone Lord is 3D dungeon crawler like game or more a prototyp of it. The Dungeon is fully procedual generated as well as the position of the enemies, chests and all decoration. 
There is only a min and max size for each room. Only the start and end room have fixed size placed opposite of each other so the player has to walk through the dungeon. 
<p align="center">
  <img src="https://imgur.com/ngvKTeg.png" alt="Game Screenshot">
</p>

---

## Procedual Generation & Assets
For the procedual generation I used this video mainly and used the idea of it  [Source](https://www.youtube.com/watch?v=rBY2Dzej03A&t)
The algorithm creates a set of Rooms on different Positions in a pre defined space for example 15x15. Then it triangulates the rooms and creates a complete graph. 
On this graph I search a MST(minimal spanning tree) and add some edges back. Those edges become then the hallways. In the picture below you can get a grasp of the algorithm. 
The rooms are blue the hallways white/grey and the start and end room yellow.
There are still some bugs sometimes regarding enemie spawn or the connecntion of rooms. Sometimes they are still disconnected.
<p align="center">
  <img src="https://imgur.com/KBvD9YH.png" alt="Game Screenshot">
</p>

I created the assets for the game all by myself using blender. Below you can see most of them:
<p align="center">
  <img src="https://imgur.com/6lxZhJU.png" alt="Game Screenshot">
</p>

## Gameplay
- navigate through the dungeon using your minimap to help
- defeat enemies, collect gold and keys to defeat the final boss
- upgrade your weapon on failed runs with the money you found in previous runs
- heal yourself with random drops from enemies
- Fight a boss enemy with unique attacks at the end

---
### Buying a new Weapon
<p align="center">
  <img src="https://media0.giphy.com/media/j06MSUMsPgi7jINMXv/giphy.gif" alt="First Level">
</p>

### Defeating Enemies and opening chests
<p align="center">
  <img src="https://media0.giphy.com/media/ePjviDXyttPjmW53qn/giphy.gif" alt="Second Level">
</p>

### Boss fight
<p align="center">
  <img src="https://media.giphy.com/media/aLoN442UznVpOx8z6P/giphy.gif" alt="Third Level">
</p>
