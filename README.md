# Bot Fighter
## This page servers as documentation for Bryce Olivier's final project for LSU CSC 2463, Bot Fighter.

This project is a culmination of programming art and sound while incorporating physical computing along with it. The project is a simple, two-player fighting game, where one player uses the keyboard and the other uses an arduino that functions as a controller. Winning the game means the oponent has reached zero health, which is visible via health bars at the top of the screen, and can be done by punching the oponent to deplete their health or by knocking them off the side of the screen. Inspiration was taken from classic fighter games, such as Street Fighter and Super Smash Bros. All sound and music was made by me, as well as the Arduino controller.

![game](https://github.com/Brythe40/Brythe40.github.io/assets/113539993/3fbcb3a3-1ae4-4880-bb2f-a33b59be1ac2)


For the game controls, I thought it would be interesting to mix keyboard with controller. The keyboard controls the blue character using the "a" and "d" keys to move left and right and by using the spacebar to punch. The red character uses the joystick from the Arduino controller to move left and right and uses a physical button to punch. This was done by parsing the JSON file that was created to read the Arduino's output and adding velocity to the red character if the stick is pushed to the left or right. The button works as a boolean, only activating the punch action if it is pressed or held down. I also added an external LED to the controller that lights up when the blue player loses.


![Arduino controller](https://github.com/Brythe40/Brythe40.github.io/assets/113539993/9c4d6e48-4d19-4c38-9ea1-611384db0b3f)



While my early goal for this project was to make a fighter game, the project took on many different forms over the few weeks of making it. The picture below is the first concept for the game, which actually looks pretty similar to the final game. However, the game was almost a survival-fighter style game, where the player had to defeat waves of enemies that would randomly spawn on the left and right of the screen. This is still an idea that I am fond of and may alter the project at a later date to achieve this goal. The game also was not intended to be multiplayer until half way through developement. I realized that I have the most fun playing games when I do it with my friends, so I made it for us to play together instead of me playing alone.

![first sketch](https://github.com/Brythe40/Brythe40.github.io/assets/113539993/53c18823-7e51-45e2-917a-ab1ebabafb43)


The game turned out to be a great success. Before starting this project, the scope of what I was aiming to do seemed overwhelming. However, once I began developement, it turned out to be quite easy. While there are things that I wish I had time to fix, such as player hitboxes and animation canceling, I am proud of how it turned out. This project has opened the door for future projects as well as a deeper dive on this one in the future. Below is a video of the final product.

[a link](https://youtu.be/nqqEKcxeS_Q)
