# Light-Em-All-Game
Puzzle game where multidirectional wires connect a power source that light up once the wires are properly connected.

This game was made using Java in Eclipse IDE using Northeastern Univeristy's [Image Library](https://course.ccs.neu.edu/cs2510h/image-doc.html). Source code can only be accessed by request due to plagarism standards. 

## Game Rules
- When game starts, a shuffled grid of wires and a power station will be displayed along with a game timer and score counter at the bottom of the screen
- You may left-click on any wire to rotate it and connect it to other wires on the board
- You may move the power station along the wires connected to it using the arrow keys
- The point of the game is to connect all wires and light up the grid with as few moves as possible (want a low score)
- For every wire you rotate, you will gain 10 points, and for every cell you move the power station, you will gain 5 points
- The power extending from the power station has a limited radius, so it may be necessary to move the power station to a position where the light can reach every end wire
- When all wires are lit up, a "Game Won" message will be displayed
- To play again, left-click on the screen with the displayed "Game Won" message

https://github.com/user-attachments/assets/9ce8a8b6-e97c-44a4-b202-130beac134a8

## Instructions for Download (with requested source code)
1. Install and set up EclipseIDE application
2. Download LightEmAll.zip file and javalib.jar, tester.jar files
3. Extract the LightEmAll.zip file in your local File Explorer
4. In the File Menu, select *New* then *Java Project*. Select *Finish* and name the file whatever you would like
5. Highlight your new project in the Package Explorer pane, then right-click it and select *Properties*. Select the *Java Build Path*, then the *Libraries* tab, then click *Add External JARs*. Select the javalib.jar and tester.jar files to import
6. Then, in your project, highlight the *src* tab. In the File Menu select *Import*. Navigate to your directory that contains the extracted LightEmAll.zip files, select all files within the folder and click *Finish*

## Instructions to Play Game
1. Open the *ExamplesLightEmAll.java* file in the *src* folder under your project
2. Click the *Run* tab, then *Run Configurations*
3. Name the configuration whatever you would like, select the *Project* as your project, the *Main Class* as tester.Main, then (under the *Arguments* tab) enter "ExamplesLightEmAll" for *Program arguments*.
4. Finally click *Run* and play the game

Note: The game will run with the default starter board of a 10 x 10 grid. To change the dimensions of your game, navigate to line 95 in the *ExamplesLightEmAll.java* file, and change the integers in "new LightEmAll(10, 10)" to your desired board dimensions. Width is the first integer, and height is the second. (reccomended to play at least width 7 for proper viewing)
