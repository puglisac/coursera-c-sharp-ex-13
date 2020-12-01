# Exercise 13: More Unity Practice

This is an exercise for the coursera course [Introduction to C# Programming and Unity](https://www.coursera.org/learn/introduction-programming-unity)

### Problem 1 - Create a project and add sprites

Create a new 2D Unity project named Exercise13. Select the Main Camera and change Size to 3. Add a scenes folder in the Project window and save the current scene as scene0. Add a sprites folder in the Project window and use your OS to add the two teddy bear images I provided to that folder. 

### Problem 2 - Add sprites to scene

Drag the green teddy bear from the sprites folder in the Project window onto the Hierarchy window. 

Create a new prefabs folder in the Project window and drag the sprite from the Hierarchy window onto the prefabs folder in the Project window. Rename the prefab to TeddyBear. Rename the game object in the Hierarchy window GreenTeddyBear. Adjust the Position X and Y values in the Transform component of the GreenTeddyBear to move it toward the upper left of the scene.

Drag the TeddyBear prefab from the Project window onto the Hierarchy window. Rename the new game object in the Hierarchy window PurpleTeddyBear. Adjust the Position X and Y values in the Transform component of the PurpleTeddyBear to move it toward the lower left of the scene.

Drag the purple teddy bear from the sprites folder in the Project window onto the Sprite value of the Sprite Renderer component in the Inspector pane. As you can see, this changes the sprite used by the sprite renderer, turning the teddy bear purple.

### Problem 3 - Make teddy bears move

Select the TeddyBear prefab and add a Rigidbody 2D component. To do this, click the Add Component button near the bottom of the Inspector and select Physics 2D > Rigidbody 2D. Run the game and watch both teddy bears fall. Remove gravity from the game by selecting Edit > Project Settings > Physics 2D from the main menu bar and setting the Y component of Gravity to 0.

Create a new scripts folder in the Project window and add the TeddyBear.cs file I provided to that folder. Open up the script in your IDE and add code below the comment in the \tt{Start}Start method to get a teddy bear moving to the right at a reasonable speed. 

Compile your code in your IDE to make sure you don't have any compilation errors. Once your build succeeds, close your IDE.

Attach the TeddyBear script to your GreenTeddyBear game object and run the game. You'll see that the green teddy bear moves to the right but the purple teddy bear doesn't move.

Select the GreenTeddyBear game object. Near the top of the Inspector, click the Apply button to the right of Prefab. This applies the changes you made to the instance of the prefab (the game object in the scene) to the prefab itself.

Run the game again. Both teddy bears should now move to the right.
 
## Installation
To install, follow these steps:

Via Downloading from GitHub:

Download this repository onto your machine by clicking the "Clone or Download" button or Fork the repo into your own Github account
Download and extract the zip file to a directory of your choice.  

Via command line:

`$ git clone https://github.com/puglisac/coursera-c-sharp-ex13.git`  

add folder to [Unity](https://unity.com/) with [Unity Hub](https://unity3d.com/get-unity/download).
