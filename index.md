
## **[About Me](https://nicholasrobbins.github.io/AboutMe)**

 

## **Panic - MilkShed Games Internal Project**
**Action Strategy** |  **(Unity 2019, C#)**  |  **Team Size: 6**  |  **2019 - 2020** 

In Panic the player must navigate themself through a hostile environment where the enemies move when they do. The goal is to pick up keystones scattered within a level to unlock the exit, while also trying to complete it within the fewest steps possible. When coming within the sight of certain enemies the player will "panic" which releases them from the grid for free movement while all of the enemies start acting on their own. Using the panic mechanic is the best way to obtain the best score!

For this project I worked primarily on setting up the AI infrustructure which coincided with a design pipline for creating levels. Using Unity's tilemap system, the designers of the team were able to go in and block out levels using the sprites within the tilemap. Then by clicking the generate button in the navmesh tool I created, it would look through all the sprites within the tilemap and place nodes at legal positions. After that is done, it would then link each node to its neighbors so that it could be used for the A-Star pathfinding for the enemies later. This system did include allowing diagonal connections as well for possible enemy types in the future but was never used in the end. 

Other aspects of the level design pipeline included level data objects that were used for loading levels and determining whether or not the player reached a new high score or were within the steps range for bronze, silver, and gold. With these medals, I added in skin unlocks for the player once they completed the game, and gained all of the different types of medals. 

The other aspects of the game I worked on included most of the UI, level tranistions and loading, and setting up all of the main level select screen. The level select screen in particular included splines between each level and kept track of the player's highest score and tier of medal they achieved on that level.

**Click the image for the game's full trailer!**

[![Tile Fall Screencap](https://nicholasrobbins.github.io/images/Panic.png)](https://www.youtube.com/watch?v=GD_jvedD5WY)

[Download Here](https://milkshed-games.itch.io/panic-2020)
 

## **Arachnotron - Champlain College Senior Production**
**Solo 3rd Person Shooter**  |  **(Unity 2018, C#)**  |  **Team Size: 13**  |  **2018 - 2019** 

Arachnotron is a 3rd person shooter where the player takes control of a robot spider tank to fight against enemy robot bugs from the enemy faction S.W.A.R.M. In this game, the player has the capability to walk on any surface of the environment allowing new dimensions of gameplay to occur that is not traditional within the shooter genere. 

Most of my work consisted of AI implementation of the small enemies and the final boss, and backend systems which includes AI systems which allowed the enemies to deal with the complete three-dimensional movement of the player. Other work that I did included the inverse kinematics of the spider legs on the tank itself, which was used to make the spider feel a lot more realistic to the player while also reducing tremendous amount of work off of our artist.

**Click the image for the game's full trailer!**
[![Tile Fall Screencap](https://nicholasrobbins.github.io/images/Arachnotron.png)](https://www.youtube.com/watch?v=9ssWFu5WxMA)

[Download Here](https://wrong-warp-games.itch.io/arachnotron)




## **RV Punch**
**Action Racing-Game**  |  **(Unity 2017, C#)**  |  **Team Size: 8**  |  **2018** 

### **[Multiple Award Winner](https://nicholasrobbins.github.io/RvPunchAwards)**
   
Players punch their opponents out of their way in this up to four player racing game, where they race as different model RVs equppied with giant mechanical fists. These fists act as the game's main mechanic which can be used to punch other racers off the track or stun them, and even "jump" off the walls by punching them. 

For this project, I primarily worked on backend systems for the races and the main menu UI.

Project made within Champlain College's Production 2 course.

**Click the gif for the game's full trailer!**


[![RV Punch Gif](https://media.giphy.com/media/9VtKPiHFVRsvIM8RPN/giphy.gif)](https://www.youtube.com/watch?v=mn1Y-4wrkfY "RV Punch")

[Download Here](https://milkshed-games.itch.io/rvpunch)




## **Opportunity Knocks - Global Game Jam 2018**
**Adventure**  |  **(Unity 2017, C#)**  |  **Team Size: 4**  |  **2018** 

This game's main mechanic inspired by the jam's theme of "transmission" has the player control the mars rover as it moves across the surface of the planet. Because of the weak connection between the player and the rover, the signal that you transmit to it is laggy. By making lag a central game mechanic, the player must be careful not to drive the rover down a cliffside and make it to the end of each level. The player may choose to "boost" the signal to reduce the lag, at the cost of using up more energy.

**Click the gif for the game's demo!**

[![](https://media.giphy.com/media/SiJYIT5CxwITBRDcCv/giphy.gif)](http://www.youtube.com/watch?v=CNaJentJf0M "Opportunity Knocks")

[Download Here](https://globalgamejam.org/2018/games/opportunity-knocks)




## **Tile-Fall - (Unity 5, C#)**
**PvP Strategy Game**  |  **(Unity 2017, C#)**  |  **Team Size: 4**  |  **2017** 

Tile-Fall can best be described as "Battleship, but you see the other player." Each player inputs their movement decisions at the same time and then guesses which spot the player moved to. After all these decisions are made, the game resolves and the players move to their chosen spots and fire upon the spot that they chose. If a player is hit, the player that predicted the position wins, otherwise the tile hit is destroyed and the player on that side cannot move onto it.

![Tile Fall Screencap](https://telden.github.io/images/Tilefallscreencap.png)


[Download Here](https://drive.google.com/file/d/1RMaQoPNHq_EggR_bJ-dGrhc2KXwAAGXE/view?usp=sharing)




## **Zelda Dungeon Recreation - (C++)** 
**Dungeon Crawler**  |  **C++**  |  **Team Size: 2**  |  **2017** 

A recreation of the first dungeon of Zelda using only C++ and Allegro for the final project of Champlain College's Game Architecture course. Working alongside [Matthew Roy](https://www.linkedin.com/in/matthew-roy-4ba050154/), we implemented multiple different gaming patterns including a component system and a defined game loop.


![Zelda Gif](https://media.giphy.com/media/OjI22jqHhPmpszPrBD/giphy.gif)


