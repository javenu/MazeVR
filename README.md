# MazeVR
 Maze VR project demonstrating the XR Interaction Toolkit

## Instructions
Find the golden key and unlock the door to the red room

## Screenshots
<img src="https://github.com/javenu/MazeVR/blob/development/.github/Screenshots.jpg" width="800">

## Notes
* As the Snap office resources were discontinued, I bought the [Simple Office Interiors Package](https://assetstore.unity.com/packages/3d/props/interior/simple-office-interiors-cartoon-assets-38028) for $9.99. 
* The most challenging part of working with this package was the walls only had normals on one side, which required duplicating and reversing the walls to avoid seeing through them. 
* Another challenge was making sure users couldn't peek through walls by leaning into them which would defeat a maze. By setting the teleportation grid far enough away from walls, if a user leans forward, the guardian switches to pass-through. However, this work around could be defeated by changing the guardian boundary and wouldn't work if locomotion included continuous move.
* To make the maze more challenging, the key could disappear after use, requiring the user to go back and retrieve another key if they used it on the wrong door. But this could be annoying for a demo level.
