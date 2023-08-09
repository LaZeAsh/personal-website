---
title: "Rubiks Logs"
---
## 07-17-2023

Today I am in San Francisco sitting next to Mr.Steven Gong himself, and he's assisting me with what I could do better for my personal project RubiksCube-AI along with general habits like note taking

I am thinking of currently starting off with an OpenCV application which scans each face of the Rubiks Cube and then stores them somewhere eventually eventually shutting off the OpenCV screen. After that I want to make it so a 3D Render of the current stage of the Rubiks Cube is generated from which it'll give you visuals of turning to certain faces, and giving instructions to follow on what to do next.

To execute this I am going to start by making the CV portion first

Update: I asked Nathan for advice and he suggested for me to make a box in the middle of the screen where user can position their rubiks cube and on the click of a button the cube will be analyzed

## 07/27/2023

I am sitting in Calgary, Alberta today. Pretty tired to be honest but I realized how much of a failure I would be if I didn't do any work today. I just made a box on the RubiksCube-AI GUI. I am working on the process of scanning each side of the cube. I eventually want to implement a proper GUI similar to [Motional](http://github.com/LaZeAsh/Motional), until then I will figure out janky ways to make this application work. 

Heading back to hotel...

No matter how the cube is jumbled up the side is always surrounded by the same sides, now the problem is when user what if they are holding the cube in different orientations: eg the cube is rotated to the left of what we were looking for and that messes up the calculations

Possible Solutions:
1. When scanning the different sides ask for the color of the side on the top
2. Tell the user to scan the rubiks cube with set movements
3. 