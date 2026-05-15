+++
date = '2026-04-15T13:46:51-05:00'
draft = false
title = 'Collaboration'
+++

## Collaboration

# Instance 1

![instance 1](/CSC324-Portfolio/images/instance1.png)

![instance 1 code snippet](/CSC324-Portfolio/images/instance1_codesnippet.png)

(1) filing and/or resolving a bug, (2) filing a pull request

In this instance, I began the implementation of the button assets onto the main screen of GrinnSim. When attempting to do a pull request, we noticed that I committed a lot of unnecessary libraries which I had not noticed before. This was causing problems (a blue screen) with running and testing the new button assets. I did not enconter difficultes collaborating in this pull request, Gabi and I worked together to identify the issue, reverse what I had committed, and recommit only what was necessary and properly working.

This is located in the GrinnSim repository under pull request 43, which is attached to issue 33. The related files included main_menu.lua and circle_nav.lua. The code I worked off of for both the main_menu.lua and circle_nav.lua came from Gabi and Marina's work. Once implementing the actual assets, I needed to make changes to how the buttons were created along with their positioning on the screen. Instead of drawing the buttons directly using Love2D (like originally in circle_nav.lua), I subsituted with the creation of assets and implementation in the code. This also meant making small changes in main_menu.lua in loading the images properly.

This instance demonstrates collaboration because I used Gabi's feedback to rework my pull request and change portions of my code to only include necessary functions. This helped make the pull request cleaner overall and (actually) functional. 

# Instance 2

(2) filing a pull request

![instance 2](/CSC324-Portfolio/images/instance2.png)

In this instance, I filed a pull request which implemented the character creation scene and the necessary assets associated with that scene. This was an instance where I authored some piece of code that was then needed to be worked on by Gabi, which meant we had to be in communication regarding what my code was actually doing and how it worked. In order to do this, Gabi and I did a code review where we went through the file. I also added documentation to the code towards the end. We did not necessarily enconter any difficulties in this instance in specific, but it was important that we weren't "stepping on each others toes" especially since we were updating the same files.

This is located in the GrinnSim repository under pull request 47, which is attached to issue 42. The related files included character_creation.lua in the scenes folder, as well as all the assets in the "character folder". I used ChatGPT to create the base for the scene, and updated code based on what I actually needed/was looking for.

This instance demonstrates collaboration because (1) I filed a pull request, (2) had to explain my code to Gabi so she could work off of it, and, finally, gained a clearer understanding of both of our work. 

# Instance 3

(3) performing a code review of a pull request

![instance 3 snippet 1](/CSC324-Portfolio/images/instance3_snippet1.png)

![instance 3 snippet 2](/CSC324-Portfolio/images/instance3_snippet2.png)

In this instance, I reviewed a pull request that Connor made to look for any potential bugs or conflicts that could arrise from what he added. The changes being added were to the styling of the stats features on the main_menu screen. I was able to do this review because Connor added to code that I worked on and knew well. When going through the code, we needed to discuss the reasoning behind some portions of what he had written, so we went through the files together. After doing the review, I better understood his changes and realized it was only affecting the stats portion of the screen rather than the other assets that I had worked on originally. One difficulty that we encountered was not knowing that we were both updating the same file at the same time, which caused some conflicts between ideas. When we realized, however, that we were working on different portions of the same file, we were able to not overlap or mesh too much while still having the same understanding of the overarching code.

This is located in the GrinnSim repository under pull request 81, associated with Connor's branch. The related files included main_menu.lua and main_menu_view.lua. I did not use AI in the process of reviewing this code.

This instance demonstrates collaboration because (1) I helped review Connor's code which used portions of what I had written before, (2) spoke with him about his changes and any potential issues and, finally, successfully was able to collaborate on the same file together. 

# Instance 4

![instance 4](/CSC324-Portfolio/images/instance4.png)

(1) filing and/or resolving a bug

This is a case where something I pushed cause an error in the code. I accidentally hard coded my own path into some of the files, which was causing problems from Connor's end. Originally, Gabi and I came up with a temporary solution to hard code my path into the files so I can run it on my computer, and then we could update the pathing later when necessary. When the pathing issue came up again, I realized I had forgotten about the issue, and then communicated with Connor what was going on. The difficulty that arrose from this was not triple checking my code before pushing it onto the respository, I should have had someone review it before so we could have avoided the issue all together.

This is located in the GrinnSim repository under pull request 83, associated with Connor's branch. The related files included love_game/stats/stats_back.lua and love_game/stats/setup_data_files/setup_family.lua. No AI was used in this process

This demonstrates collaboration because Connor was having issues with code I had written, spoke to me about it, and then we came up with a solution for what was happening. We realized together that it was the path problem which I had forgotten about.