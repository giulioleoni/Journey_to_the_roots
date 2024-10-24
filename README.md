# Journey to the roots

For Global Game Jam 2023 we made a team of 15 students and developed a platform using Unreal Engine 4.27.

The particularity is that the player can only jump so he must calibrate the force carefully. 

Normally the game has a side-view camera but there are parts of the level where the view will be top-down.

## Camera System

At the time I did not know much about Unreal so it was complicated to implement the camera switch system.

In the end I decided to use boxes placed at the spots in the level where there needed to be a camera switch. When they were overlapped by the player they passed him the position of the new camera and then the camera switch was made.


https://github.com/user-attachments/assets/e1f5ac76-3b38-4f0f-92cb-97b6243eab96





## Checkpoints

To make checkpoints, I created boxes to be placed in the level that, if overlapped by the player, would save in the gamemode the respawn position

![image](https://github.com/user-attachments/assets/36cb464b-7990-47cd-b59a-b7a1dc826fa6)






































