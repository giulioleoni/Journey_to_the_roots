# Journey to the roots
Roots

For Global Game Jam 2023 we made a team of 15 students and developed a platform using Unreal Engine 4.27.

The particularity is that the player can only jump so he must calibrate the force carefully. 

Normally the game has a side-view camera but there are parts of the level where the view will be top-down.

## Camera System

At the time I did not know much about Unreal so it was complicated to implement the camera switch system.

In the end I decided to use boxes placed at the spots in the level where there needed to be a camera switch. When they were overlapped by the player they passed him the position of the new camera and then the camera switch was made.

















































