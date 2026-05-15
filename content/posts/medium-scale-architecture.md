+++
date = '2026-04-15T13:48:00-05:00'
draft = false
title = 'Medium Scale Architecture'
+++

## Medium Scale Architecture

![scene based architecture](/CSC324-Portfolio/images/architecture_scenes.png)

![asset architecture](/CSC324-Portfolio/images/architecture_assets.png)

I co-designed the front-end portion of GrinnSim. The architectural pattern that our program employs is a scene-based architecture. This works by switching through our "scenes" to activate different displays/options on the screen. In particular, I focused mainly on the character design and main menu scenes, which had a lot more assets in comparision to submenu screnes (that were mostly text based gameplay). The components that result from this are the scenes modules themselves, along with the components that comprise each scene. The components in the character design screen, for example, are the asset management (how I organized the assets into different categories to be used and drawn at different stages) and the ui layout system (how everything was drawn on the screen). For most components, we used the love.graphics library to load assets into the front-end and create shapes using Love2D as needed. 

The example of architectural pattern can be found in the GrinnSim repository, specifically in the character design and main menu files. I used ChatGPT to help me with some formatting issues in the main menu scene, but not with the implementation of scenes overall. This demonstrates completion of this compentency because I was able to employ a architectural pattern (scene management) as a blueprint for the structure of GrinnSim's code.