# vrc_dolly_osc_controller
A OSC Blender controller for the dolly camera in VRChat

ABOUT
This will allow you to send a camera's position in real time to Vrchat's waypoint system on their new dolly camera.
This is acheived by using Vrchat's dolly camera paramaters listed here https://wiki.vrchat.com/wiki/Camera_Dolly#OSC_integration

IMPORT / SEND
it comes with a import and send function so you can creat keyframes and import then send directly to the dolly in game

REALTIME 
The real time option isn't quite real time as Vrchat's dolly is super limited right now, instead it spams the /import and the /play to the osc system 
acting almost realtime, (Unfortunetly this won't work wit hKeyframed camera's in blender)

VIDEO SHOWCASE
https://youtu.be/nX6TZgmYgIc



INSTALATION
Download from the code button, Extract the zip within the folder Install the zip by going to blender / Prefrences / install addon from zip / select the download.


USAGE
In the addon (Located in the scene options in blender) Start OSC, Select your camera, then either import and send your keyframes or hit real time view, there are also overides for the 
FOV, Apature, and focus, aswell as the timing options (these acan be keyframed aswell)


PLANS / NOTICE
First off, I wrote this with Gemini's new 2.5 model, it does better with code thatn i've seen most LLM do, I KNOW NOW PYTHON CODING. as far as plans for updates, i'd like Vrchat to update and add more than 100 waypoints, that way we could get fluid
Motion tracking from blender into VRC, if that happend i'll plan to update a better Realtime option for this project.
