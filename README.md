# GI-Jam-2015-Pong-Linux-
The Linux version of a rough game called GI Jam 2015 Pong, built entirely on Unity 5 and programmed with C#.

University of Waterloo
DIY or Die Trying Event Archive Folder

(sponsored by The Games Institute, recommended by the UW Game Development Club [Brook Jensen])

Programmed by Gregory Desrosiers, October 17-18, 2015

This folder holds the files for a game I put together in the duration of the event. It was my first time putting together a playable game using Unity 5 as the editor, engine, and codebase. The game was entirely programmed in C#, with resources from Unity's own API the engine uses throughout game execution.

The game I put together is roughly a Pong clone, with a 3D aspect to it. This was accomplished by using basic 3D solids and polygons Unity Provides - a plane, two capsules, two rectangular prisms, and one sphere. One light source was used to draw
shadows on the board, and simple collision and physics models were used as integrated into the shapes.

The important aspect I somehow implemented was camera tilting based on the ball's vertical position with respect to the origin. When the ball is at the top or bottom of the board, the camera tilts at maximum 5 degrees.


~ How to use the files ~

The game is available for use on Windows (the x86 architecture, compatible with both 32-bit and 64-bit OS; does run on Windows 8.1 perfectly!), Linux (Universal, for both x86 and x64 architectures), and Mac OS X (x86 architecture). Be warned: the game has not been tested on Mac OS X and Linux, so use them at your own risk.

Right now, there is no way to download all the files directly in a ZIP file or a compressed folder. You need to actually clone this repository from the Git Shell, or the GitHub application, including the files from other folders in it, in order to access the game files and the executable you need to play.

Since this game uses the Unity engine, you must download the Web version of the Unity player. Once you have the player installed, you may click on the executable file, set your settings, and run the game.



~ How to play ~
You are controlling the red paddle on the left side. Your goal is to simply get 5 points before your opponent, which holds the blue paddle, does. Use the up and down arrow keys on your keyboard to move the red paddle.

For optimization, play the game at windowed 800x600 resolution.



Have fun taking a look at this small project I got! Updates will come soon!
