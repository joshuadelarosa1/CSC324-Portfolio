+++
date = '2026-04-15T13:47:06-05:00'
draft = false
title = 'Testing Strategies'
+++

## Testing Strategies

![testing strategy snippet](/CSC324-Portfolio/images/testing_strategy_snippet.png)

![testing strategy snippet 2](/CSC324-Portfolio/images/testing_strategy_snippet2.png)

I was responsible for testing the circle nav, character creation, and academics stats. I also helped with testing if they academic options updated stats correctly. The components that were covered in these tests were the generation of the buttons themselves (making sure that they can be drawn by love2d), the "cycling" of the character creation (so users can actually switch between options), and that stats were updated correctly when choosing different options in the academics submenu. These were unit tests, which tested specific portions of each file we were looking to test. This worked best to ensure proper functionality of our functions/tools. The code that was not able to be covered by tests was the general formatting/look of the UI. It's difficult to create tests that will "look" at the screen and see if things allign nicely, etc. Instead of coding these tests, visual testing had to be done manually.

These tests are located in the GrinnSim repository under the tests folder. They can be seen in pull request 84. I used Connor's tests as examples of how to write lua tests. I also brainstormed with my other team mates to see what should be tested. Tests that I added include: test_character_creation, test_circle_nav, and test_stats_academics. I used ChatGPT to help write the tests themselves. I udpated the code produced from ChatGPT as needed.

This demonstrates that I have completed this competency because I identified (1) components (button generation, cycling, and stats) (2) types of tests (unit tests) and (3) why I did not cover the code related to actual formatting/the look of the UI. 