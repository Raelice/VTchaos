# VTchaos
A youtube chat bot that sends commands to Vtube Studio
This is public version .1 of the VTchaos chat program. You can use it to read chat from youtube and have that activate commands in Vtube Studio. Example : someone types in !big in chat, it scales your avatar size to 100 (the max). When run for the first time it will generate a file name vtube studio config, DO NOT put this in the same folder as vtube studio, not sure if it will interfere with anything but better safe than sorry. The buttons are slightly laggy while it attempts to read chat, do not worry the commands will execute.

Current list of commands
!flip - rotates model 180 degress
!reset returns model to position size and rotation set by the "set reset" button
!big - scales model size to 100
!small - scales model size to -80
!spin - makes the model spin for a few seconds
!center -returns model to center of screen
!rainbow - aplys a rainbow effect to character in quick succession

UI buttons - 
Authentication - Can only be run while Vtube studio is open and will request plugin access, once accepted you shouldn't need to use this again unless you move onto a new computer.

Livestream ID- input a youtube livestream ID such as "SlWqbzg2F-I" that you want to connect to
Set Reset - saves the current model position, rotation and size, and when you use the !reset command it will return it to that state, can be set multiple times.
Set Model - Saves the current model for the 'custom avatar' button which will load the specified model.

This program likely only works on Windows, this version does have a console running so if you encounter an error please post the log here.

Follow me on twitter for me updates @theraelice or join our discord where I'll talk about what updates I'm bringing to this. (https://twitter.com/theRaelice) Discord: https://discord.gg/QvP8hwS
