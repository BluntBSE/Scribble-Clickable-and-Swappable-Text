The script you probably want is locate_substring().

This project is not really ready for 'human' consumption, so please excuse the clutter.

If the current version does not run it automatically, press "0" on game start to active locate_substring.

# Scribble-Clickable-and-Swappable-Text
This is a sample of how to create hitboxes around text generated by JuJuAdams' "Scribble" for Game Maker. It also includes a mechanism for swapping words in a string. 


Screen displayed on the screen is stored in obj_dialoguemanager
Actual printing and calling of the function you're interested in, locate_substring, is done obj_textbox in the Draw_GUI and Draw_GUI_End events
The variables that locate_substring looks for in the text are temporarily stored in obj_textbox in the Create event.

You can see a demonstration of this mechanic by simply starting the game.

I am a terrible programmer, so please feel free to make suggestions and improvements here.
