# Tetris23

how to use your program (e.g., what the command line arguments are, if any);
- you'll be prompted to enter a gridsize (an integer between 10 and 50. So 10, 20, 30, 40, 50)
- once the first piece appears on the screen you can move it using 'a' and 'd' keys on your computer.


there are a couple remaining bugs.
- I've just noticed this when playing with a gridsize of 10, but sometimes the shapes
 will leave a little one square "trace" behind if you move it left/right
- if you move a shape to the right or left right before it "lands"/arrives in its final position the incrementation of how many
pieces are in each column of the grid might be a little funky and result in some pieces going through others/stopping before they need to
(but this is only really a problem if the user changes the direction right before the piece lands).
