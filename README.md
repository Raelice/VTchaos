# VTchaos
A youtube chat bot that sends commands to Vtube Studio.

This is public version 1.1 of the VTchaos chat program. You can use it to read chat from youtube and have that activate commands in Vtube Studio. Example : someone types in !big in chat, it scales your avatar size to 100 (the max). When run for the first time it will generate a file name vtube studio config, DO NOT put this in the same folder as vtube studio, not sure if it will interfere with anything but better safe than sorry. The buttons are slightly laggy while it attempts to read chat, do not worry the commands will execute.

| Chat Command List |
- !flip - rotates model 180 degress
- !reset - returns model to position size and rotation set by the "set reset" button
- !bigger - increases model size by 5% up to max
- !smaller - decreases model size by 5% down to min
- !spin - makes the model spin for a few seconds
- !center - returns model to center of screen
- !rainbow - applys a rainbow effect to character in quick succession
- !tiny - scales model to minimum size
- !huge - scales model to maximum size
- !up - moves model up a small amount
- !down - moves model down a small amount
- !right - moves model right a small amount
- !left - moves model left a small amount
- !tiltR - rotates model 45 degrees clockwise
- !tiltL - rotates model 45 degrees counterclockwise

| UI Commands | 
- Authentication - can only be run while Vtube studio is open and will request plugin access, once accepted you shouldn't need to use this again unless you move onto a new computer.
- Livestream ID- input a youtube livestream ID such as "SlWqbzg2F-I" that you want to connect to
- Set Reset - saves the current model position, rotation and size, and when you use the !reset command it will return it to that state, can be set multiple times.
- Set Model - saves the current model for the 'custom avatar' button which will load the specified model.
- Set Slow Mode - input a time in seconds that will prevent chat commands from executing, ex 20 means a new command can only be executed by chat every 20 seconds, button commands are not stopped.

This program likely only works on Windows, this version does have a console running so if you encounter an error please post the log here.

Follow me on twitter for me updates @theraelice or join our discord where I'll talk about what updates I'm bringing to this. (https://twitter.com/theRaelice) Discord: https://discord.gg/QvP8hwS
