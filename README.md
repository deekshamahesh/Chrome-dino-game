# Chrome-dino-game
Python code to automate chrome dino game

A bot that plays the boring chrome dinosaur game that appears when no internet available.
***
You will need to install **pyautogui** to make the bot run
```
pip install pyautogui
```
Use this link **chrome://dino/** to access the game even when you have internet (*use chrome*).
***
# Theory
I capture a screenshot every frame to look for obstacles to avoid.

There are 2 search ranges to find obstacles:

1- To look for the ground obstacles (**Cactus**).

2- To look for the upper obstacles (**Birds**).

#### How to identify obstacle?
An obstacle is considered any pixel in the search area that is different than the background colour.
If the bot finds an obstacle it uses the python **keyboard** library to press space and let the Dino jump.
***

Any recommendations are welcomed
