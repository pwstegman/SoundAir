# SoundAir
A magic floating piano made with index cards and a Leap Motion

This is the code from our project submitted to CrimsonHacks 2017. It can be found on Devpost at https://devpost.com/software/soundair.

### Video demo
<p><a href="http://www.youtube.com/watch?feature=player_embedded&v=HQzYNQv8p90
" target="_blank"><img src="http://img.youtube.com/vi/HQzYNQv8p90/0.jpg" 
alt="SoundAir Demo | CrimsonHacks 2017" width="240" height="180" border="10" /></a></p>

### Usage

Open index.html to try it out. Position the Leap Motion over the table facing down. (We used a cardboard box to hold it up.) The Leap Motion Controller software needs to be running on your computer for this to work. Only one hand can be tracked at a time (multiple hands will confuse the code).
The index finger is tracked to determine which card to play, and the height of the center of your hand is tracked to determine when to play the note.
An open flat hand with spread fingers where the tip of the index finger is centered over the card you wish to play and you play it by moving your hand up and down over the card works best.

When you click "Add Card", the card is added at the current position of the tip of your index finger, seen as a blue dot on the screen.

If you don't have a Leap Motion, you can type `mode = "mouse"` in the console to use mouse-enabled mode. Double click to add a card at the location of the mouse. Mouse-enabled mode is not fully functional, and was intended for quick debugging.

The code was rushed at times, and some values (such as the y distance of the Leap Motion from the table) are hardcoded. You may have to change these values when testing it.

The code was tested on Chrome 56 and is currently not designed to be cross browser compatible.

https://github.com/keithwhor/audiosynth was used to produce the notes and sounds.
