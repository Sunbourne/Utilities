#Blender Batch Render + GUI

This is a simple script that I've developed the past year.
I had to model and render 400 pack-shots, so I was modeling during the day and run the script overnight.

I must make clear that I'm not much of a programmer and maybe you'll find some sloppy code here,
I'm sure it can be optimized so if you find any mistakes or you have any suggestions please point them out.

The script renders all "blend" files inside a folder, saves the renders in a specified location, displays notifications when necessary and finally creates a statistics text file in the same folder.

Basically the script is running blender console commands and sets variables with the help of zenity dialogues.

Before running the script you must prepare you files accordingly (eg. select your rendered engine, rendering quality, animation frames etc) 

1. Select the render executable in case you have more than one blender versions in your machine.

2. Select the folder that needs to be rendered

3. Select the folder where the renders should be saved

4. Select Image Format

5. Select what action to take after the renders have finished. If shutdown or suspend is selected then you're prompted for your password

6. Select if you want to render a single frame or an animation

7. A progress bar displays the total progress of rendering jobs

8. Notifications are displayed for successful rendering (or not) and total rendering time.

The script can also be modified to play a sounds on render finish or in render error, so you can leave the room.

I'm planning also to implement an SMS functionality so you can leave the office/house and be notified if something went wrong or everything run well.

On the other hand maybe I could use this script as an excuse to learn python and re-write it over again.
I hope it will be helpful for you as it was for me.

