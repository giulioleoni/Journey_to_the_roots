# Journey to the roots

For Global Game Jam 2023 we made a team of 15 students and developed a platformer using Unreal Engine 4.27.

The particularity is that the player can only jump so he must calibrate the force carefully. 

Normally the game has a side-view camera but there are parts of the level where the view will be top-down.

## Camera System

At the time I did not know much about Unreal so it was complicated to implement the camera switch system.

In the end I decided to use boxes placed at the spots in the level where there needed to be a camera switch. When they were overlapped by the player they passed him the position of the new camera and then the camera switch was made.




https://github.com/user-attachments/assets/50d1a97c-c572-4d99-a02c-12a9821410d6



## Checkpoints

To make checkpoints, I created boxes to be placed in the level that, if overlapped by the player, would save in the gamemode the respawn position

![image](https://github.com/user-attachments/assets/36cb464b-7990-47cd-b59a-b7a1dc826fa6)




## Hazards and collectibles

I also worked on an hazard and the collectibles system.

The hazard is a static mesh of a caterpillar with a sphere collision volume and a rotating movement component. When the volume is overlapped by the player it will deal damage:

![photo_2024-10-31_09-44-13](https://github.com/user-attachments/assets/6426a9e4-eca3-40a7-a7a7-cf68ed875e63)



The collectible is very similar but calls an interface method when it is collected that will update the number of collectables saved in the gamemode:



![photo_2024-10-31_09-49-51](https://github.com/user-attachments/assets/bdfdd0d1-1077-4361-a4b6-b4bbc5e990d2)










https://github.com/user-attachments/assets/dc5fead4-2905-4511-b78b-7857c87c8381












