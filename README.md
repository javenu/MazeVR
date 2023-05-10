# MazeVR
 Maze VR project demonstrating the XR Interaction Toolkit

## Instructions
Find the golden key and unlock the door to the red room!

## Screenshots
<img src="https://github.com/javenu/MazeVR/blob/development/.github/Screenshots.jpg" width="800">

## Notes
* As the Snap office resources were discontinued, I bought the [Simple Office Interiors Package](https://assetstore.unity.com/packages/3d/props/interior/simple-office-interiors-cartoon-assets-38028)
* The most challenging part of working with this package was the walls only had normals on one side, which required duplicating and reversing the walls to avoid seeing through them. 
* Another challenge was making sure users couldn't peek through walls by leaning into them which would defeat a maze. By setting the teleportation grid far enough away from walls, if a user leans forward, the guardian switches to pass-through. However, this work around could be defeated by changing the guardian boundary and wouldn't work if locomotion included continuous move.
* To make the maze more challenging, the key could disappear after use, requiring the user to go back and retrieve another key if they used it on the wrong door. But this could be annoying for a demo level.
* I included an exe in the Builds folder if the Editor hangs on Application.EnterPlayMode. I had mixed results with the Editor compiling the downloaded source, most likely due to conflicts with the Oculus app / Meta Link.

## Learnings
* Using the Simple Office Assets to build a maze
* Interactors, Interactables
* ProGrids alignment
* ProBuilder extruding
* Layers vs Interaction Layers Masks, how they combine
* XR Direct Interacter
* XR Ray Interactos
* Using Triggers and Tags to open doors
* Normals on walls
* Teleportion Areas
* Logging Interactions to the console
