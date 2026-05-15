+++
date = '2026-04-15T13:47:34-05:00'
draft = false
title = 'Medium Scale Abstraction'
+++

## Medium Scale Abstraction

![abstraction snippet](/CSC324-Portfolio/images/abstraction_snippet)
![abstraction snippet 2](/CSC324-Portfolio/images/abstraction_snippet2)

A portion of the project that I co-wrote and employs medium-scale abstraction is the CircleNav functionality to create the circle buttons on the main menu screen. This code "abstracts away" the need to create new circle buttons and calculating their position on the screen each time they need to be placed/implemented. This works mechanically by obtaining the dimensions of the screen (which can be updated as needed) to calculate the positions of the buttons. Then the buttons, labels, and targets are created/loaded themselves based on the calculate_position function. This abstraction serves the larger program by successfully implementing a navigation system in our UI that can be reused as needed in other scenes besides the main menu. I was originally thinking it would also be applied for the character creation scene, but this didn't end up making as much sense.

This code is in the CircleNav.lua file in the style/widgets folder of the GrinnSim repository. I used what Gabi & Marina started for this file as a base, and then updated when implementing assets (instead of only using love2d to draw circles). This was especially relevant for updating the calculate_position and get/draw button functions. I used ChatGPT to debug some of the positioning on the screen.

This demonstrates that I completed the abstraction competency because I abstracted away the need to load and position our circle buttons every time, which was especially relevant for our circle navigation system that was essential for users to play the game. 