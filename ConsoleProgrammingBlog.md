Analytics Tool Feature List and Schedule - 2/3/19
------

Feature List:
1. Allow the user to specify specific variables to keep track of through C# reflection
2. Allow users to record specific game events or use new tracking options built into the system
3. Visually represent the data recorded within the editor
4. Calculate significance (P-value) of recorded data sets uisng different data calculation methods (Wilcoxon, Mann-Whitney-Wilcoxon, PANAS, etc)

Stretch Goals:
5. Upload data gathered online
6. Send data to exterior tools to create graphs and automatic spreadsheets

Schedule:

For the breakdown of the project, I have to keep in mind that there is overall only three months to make this tool, while also including my other classes and tasks, I do not want to take away from my other projects.



* **Febuary 15th -** All current unknowns have been researched and now are known. C# reflection is implemented and has been tailored to get rid of all unnecessary variables and public functions. 
* **Febuary 22nd -** Users can select what varaibles that they can have tracked along with specific game events which will output to an external file.
* **March 1st -** Allow the user to read in the data created back into the editor to create a visual representation (such as a heatmap) of their data.
* **March 8th -** Create the first iteration of the significance testing application to allow for user studies by using the tool.
* **March 22nd -** Polish week of core systems.
* **April 5th -** Research for stretch goals have been completed and their construction has been planned.
* **April 12th -** Finish stretch goals implementation.
* **April 19th -** Overall systems bugs fixing.
* **April 26th -** Complete Application should be completed save for any last bugs to be fixed.
* **Exam Week -** Product is completed.

Backup Plans:
Currently the data gathering and analytics stands as two different systems which will make one overall tool. The data gathering systems allows the user to gather desired data, and be able to visually represent that, whether in editor or with another external tool. The data analytics tool lets the user run user studies and assess on a mathematical level the significance of the change they are making within the game. Overall, without the data, there is no data analytics, and my bottomline goal is to have a tool that can gather important data for the user so that they can themselves look over the numbers and see it within their editor and know what they are doing is having a positive or negative impact on their game. Therefore, if the data gathering and representing part of this project proves difficult, then I plan on cutting the significance testing portion of the project so that I can have more time working on the main core of the project.

------
------

Console Programming Initial Plan - 1/28/19
------

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;My plan is to create a built-in unity tool which allows the user to easily set up data gathering to then process them through data analytics. I want the system to be flexible to keep track of many different types of variables such as individual values, game events, the time it takes the player to exit a room or defeat an enemy, and positional data of where players tend to move within the environment. Depending on the data being gathered, the raw data can be enough for a development team to make conclusions about their game and take that knowledge further into development. Other data is best represented visually, or studied closer. Therefore, I want to also include data visualization tools built into unity, such as creating heatmaps within the engine itself, and I want to allow the user to also conduct data analytics to make definite conclusions through significant figures. This would allow developers to run studies through QA builds that have slight changes to them, and through analyzing specific data about what the study is focusing on, the system will return a P-value and indicate whether the test conducted was significant or not.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The reason for this topic of interest is because I enjoy making tools to assist in project development, and have made some tools already for my capstone project Arachnotron. The team would like to go to as many QA sessions as possible, so it is my desire to create a tool that will allow the team to get the most out of each QA session to inform possible changes in design. The main challenge of this project will be keeping the interface easy to use, mostly though visual interfaces with some code in the background. Overall, using the tool should be easier than the task it is trying to accomplish. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The current unknowns about the project is how I am going to allow the user to choose the different variables to track, from individual variables to full events. I also have to figure out how I am going to compile all the data once a play session has completed in a format that can be reimported into the editor to analyse the data. For Arachnotron specifically, I will need to figure out a way to keep track of a player's movements within a 3D space instead of just a floor 2D space. Finally, I will have to re-research all of the different data analytics formulas and integrate those within the project. If I have trouble with any of these different systems, I plan on cutting the data analytics portion of the tools, as I think that is mainly supplementary to the rest, for the sake of time. And lastly, I do not see any external dependencies on people or resources, so I do not have to worry about the possibility of something ruining progress on the project.
