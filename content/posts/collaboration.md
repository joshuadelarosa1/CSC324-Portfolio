+++
date = '2026-04-15T13:46:51-05:00'
draft = false
title = 'Collaboration'
+++

## Collaboration

Identify three different instances where you participated in collaborative work with your team as identified by specific commits, pull requests, and/or issue numbers on Github. These instances should not simply be "committing code" but situations that required back and forth with your peers, e.g., a substantial bug or a code review:
* Identify the work you did in each of these instances.
* Describe the difficulties that necessitated communication with your peers in each instance.
* Did you encounter any difficulties in collaboration with team during these instances? If so, how did you resolve those difficulties?

Evidence that I have completed this competency:
* A statement of where the sample is located in your project, i.e., the specific repository, files, and line numbers (when applicable).
You should also include relevant code snippets and/or screenshots/images in your write-up.
* A statement of your specific contributions to the sample, in particular, if the sample is drawn from group work and/or generative AI was used to build portions of the sample. You should state what parts of the sample you built yourself and what parts you relied on others (teammates or AI) to build.
* A short description (1–2 paragraphs) of how the sample demonstrates mastery of the given development competency. This description is competency-specific, guided by a set of questions you should answer in your description. Each question should be addressed in a few (2–3 sentences) in your description.

# Instance 1

![instance 1](/CSC324-Portfolio/images/instance1.png)
![instance 1 code snippet](/CSC324-Portfolio/images/instance1_codesnippet.png)

In this instance, I began the implementation of the button assets onto the main screen of GrinnSim. When attempting to do a pull request, we noticed that I committed a lot of unnecessary libraries which I had not noticed before. This was causing problems (a blue screen) with running and testing the new button assets. I did not enconter difficultes collaborating in this pull request, Gabi and I worked together to identify the issue, reverse what I had committed, and recommit only what was necessary and properly working.

This is located in the GrinnSim repository under the pull request attached to issue 43. The related files included main_menu.lua and circle_nav.lua. The code I worked off of for both the main_menu.lua and circle_nav.lua came from Gabi and Marina's work. Once implementing the actual assets, I needed to make changes to how the buttons were created along with their positioning on the screen. Instead of drawing the buttons directly using Love2D (like originally in circle_nav.lua), I subsituted with the creation of assets and implementation in the code. This also meant making small changes in main_menu.lua in loading the images properly.

This instance demonstrates collaboration because I used Gabi's feedback to rework my pull request and change portions of my code to only include necessary functions. This helped make the pull request cleaner overall and (actually) functional. 

# Instance 2

![instance 2](/CSC324-Portfolio/images/instance2.png)

# Instance 3

![image]()

# Instance 4