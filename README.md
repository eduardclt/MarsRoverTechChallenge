# MarsRoverTechChallenge

My soution for the google marsrovertechchallenge. 
See the challenge here: 
https://code.google.com/archive/p/marsrovertechchallenge/ 

## Instalation 

There are nothing that needs to be installed. Simply clone or download the project files and open index.html in your browser.
Optionally, visit: https://eduardclt.github.io/ where the project is hosted.

## Usage

1. Enter the size of the plateau on the first screen. (eg 10, 10)
2. You'll now see two forms. One for generating a rover and the second one is to control a rover.
3. Insert the an x and y coordinate and the orientation of a rover you would like to add. (eg 3, 4, N)
4. In the table that's now generated you can find the rovers ID that is used to select and control it.
5. In the bottom form type the ID of the rover you which to move and the commands that it should follow. (eg MRRLM)
(Please note, if the commands will be excuted until the rover goes out of bounds. This will stop the exucution) 

## Assumptions I made about the problem

1. I can use HTML to get user input rather than hardcoded or automated input.
2. It will be nice to be able to add a bunch of rovers and make them move whenever you want.
3. The rovers must not be able to go out of the plateau.
