---
name: RoBob The Builder
img: ../imgs/robob.png
img_size: 300px
links:
 - name: Code
   value: https://github.com/bri25yu/robob-the-builder
 - name: Website
   value: https://sites.google.com/berkeley.edu/robobthebuilder/
   last: true
ordering: 2
---
Built a robotic simulation upon the idea that a user can specify a unique structure composed of blocks and a robot will process
the structure and attempt to recreate it autonomously. We used the PAL Robotics TiAGo robot model to perform 2 primary tasks: 
(1) in an initial world with a desired structure created by a user, use TiAGo's frontal cameras to capture the structure and extract
the 3D coordinate points of the blocks that make up the structure, and (2) autonomously navigate to and pick up randomly placed blocks in a new world, and place them in in a way that replicates the desired structure.
For this project, we used OpenCV to process the strutural images and extract coordinates, and used ROSPy and ArUco to actuate TiAGo autonomously to perform pick up/place down actions. 
