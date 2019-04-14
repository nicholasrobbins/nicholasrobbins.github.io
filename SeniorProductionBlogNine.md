Beta Boss - The Pelican Spider
------

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For the game's beta phase, the Pelican Spider, the final boss of the game and the leader of the enemy faction needed to be created for the milestone, and I was tasked to lay the groundwork for it. The problem that I saw from the other bosses were that their systems were very scattered throughout the overall structure of it, making it hard to work with because you had to find the exact gameobject a script was on to edit it. Basically each system of the boss acted indipentantly from each other and there was no overarching control system. This boss in particular was designed with multiple attacks and phases in mind so the scattered technique of the previous bosses were not going to work with this.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The approach I took to constructing it was a component based structure which was organised in a "top-down" way. Each attack of the Pelican spider has its own script/container, allowing for easy editting access, and they all act like libraries to be called when the AI has decided to use it. This is the bottom layer of the structure. In the middle there is the "Pelican base" script which acts as a container of all references to all the attack scripts and other public variables such as the player gameobject to be referenced by any script. Then at the top, there is the "Pelican brain" object, which decides what actions the boss will do. The boss brain has a array of phases which contain delegates to the functions of the attack actions that it wants to do. Based off of what phase the boss is in, the rate of speed the boss attacks, and the percentage chance that an attack will happen is changed, and can easily be adjusted in the inspector. This allows for quick changes to the boss's attributes and iteration because everything is self contained in one location.