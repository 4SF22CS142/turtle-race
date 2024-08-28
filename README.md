# turtle-race
This Python script simulates a simple turtle race using the turtle module. Here's a summary of how it works:

Screen Setup:

A screen is created with a black background and a title "Turtle Race".
Turtles Creation:

Five turtles are created, each with a different color from a predefined list (red, yellow, white, sky blue, green).
The turtles are positioned at the starting line on the left side of the screen at different Y-coordinates.
Race Track:

A white turtle draws a vertical finish line at the X-coordinate of 300.
User Bet:

The user is prompted to bet on which colored turtle they think will win the race.
Race Logic:

The turtles move forward by a random amount in each iteration of the loop.
The race continues until one of the turtles crosses the finish line (X-coordinate > 300).
If the turtle that crosses the line first matches the user's bet, a message "You won" is displayed; otherwise, "You lost" is shown.
End of Program:

The screen waits for a click to exit.
This script is an interactive way to engage with the turtle module and learn about loops, randomization, and user interaction in Python.
