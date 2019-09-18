# MarsRoverTechChallenge

My solution for the google marsrovertechchallenge. 
See the challenge here: 
https://code.google.com/archive/p/marsrovertechchallenge/ 

## General Notes

There are two 'versions' of the project. The one is simply with unit testing and the other without.

## Installation 

There are nothing that needs to be installed. Simply clone or download the project files and open index.html in your browser.
Optionally, visit: https://eduardclt.github.io/ where the project is hosted.
(Please note version on the link above does not have unit testing)

## Usage

1. Select the version without testing.
2. Enter the size of the plateau on the first screen. (eg 10, 10)
3. You'll now see two forms. One for generating a rover and the second one is to control a rover.
4. Insert the an x and y coordinate and the orientation of a rover you would like to add. (eg 3, 4, N)
5. In the table that's now generated you can find the rovers ID that is used to select and control it.
6. In the bottom form type the ID of the rover you which to move and the commands that it should follow. (eg MRRLM)
(Please note, if the commands will be executed until the rover goes out of bounds. This will stop the execution) 

## Assumptions I made about the problem

1. I can use HTML to get user input rather than hardcoded or automated input.
2. It will be nice to be able to add a bunch of rovers and make them move whenever you want.
3. The rovers must not be able to go out of the plateau.

## Difficulties I had

I have yet to learn unit testing. I tried to add it to my project but had some struggles. I added 2 basic tests to a separate version of the project just to show what I tried doing with unit testing. 
