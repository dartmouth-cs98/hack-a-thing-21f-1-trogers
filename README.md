# Unity Game Design/C#
 
## What you built?
 
In this Hack-a-thing, I wanted to try my hand at Unity game design. Since I have no experience, I thought it would be a good idea to start by creating a 2D game in order to pick up the basics and get a feel for C#. I followed a tutorial and built a game called "Monster Chase''. The game contains a user controlled player which uses the arrow keys and spacebar for movement. The object of the game is to avoid ghosts for as long as possible as they randomly spawn with varying speeds from the corners of the screen. When a ghost is contacted by the player, then the game ends. <br>
 
In order to create this game, I created multiple prefab characters including the ghost and player which required many attributes such as rigid bodies, multiple animations, and box colliders. For each, I also wrote a C# script which controlled movement from keypress or randomized (for the ghosts). Additionally, the game needed to randomly spawn ghosts which required it's own script.<br>
 
Lastly, I had to create the environment, combining small graphics to create a larger playing field and using box colliders to ensure the players wouldn't fall out of the game screen.
 
 
![Alt text](/screenshot.png?raw=true "Optional Title")
 
## What you learned
 
I am into this project with no experience in Unity or any game design. First, I learned about the Unity platform and all of the different windows which are necessary for game development. I learned how to create game objects, backgrounds, and animations based off of sprite pages and background photos. Next, I learned the basic syntax for C# including important principles for game design such as class inheritances which are used for character creation. Using this new knowledge of C#, I created scripts which governed the play of my game and learned how to access the attributes of the game objects within these scripts in order to handle collisions or change movements. I created prefabs for ghosts and players such that they could easily be reused and spawned as desired. Finally, I learned how to change the physics of the game, such as changing the gravity, mass, or dynamics for a specific character.
 
## Authors
 
Thomas Rogers
 
## Acknowledgments
 
Tutorial for Unity Download and Setup:<br>
https://www.youtube.com/watch?v=ewiw2tcfen8<br>
 
 
Tutorial for Unity, C#, and Game Design:<br>
https://www.youtube.com/watch?v=gB1F9G0JXOo&t=2263s<br>
* Monster Chase game and game asset design was taken from FreeCodeCamp and code is based off this tutorial