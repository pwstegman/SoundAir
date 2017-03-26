# SoundAir
A magic floating piano made with index cards and a Leap Motion

This is the code from our project submitted to CrimsonHacks 2017. It can be found on Devpost at https://devpost.com/software/soundair.

Open index.html to try it out. Position the Leap Motion over the table facing down. (We used a cardboard box to hold it up.) The Leap Motion Controller software needs to be running on your computer for this to work. Only one hand can be tracked at a time (multiple hands will confuse the code).
The index finger is tracked to determine which card to play, and the height of the center of your hand is tracked to determine when to play the note.
An open flat hand with spread fingers where the tip of the index finger is centered over the card you wish to play and you play it by moving your hand up and down over the card works best.

The code was rushed at times, and some values (such as the y distance of the Leap Motion from the table) are hardcoded. You may have to change these values when testing it.
