# CoderDojo

Lovely Lucy and Magnificent Maddy have spent the day creating a naughts and crosses game in Python. 
As they are about to save their game Naughty Nic delete the winning positions. Unfortunately, 
Lovely Lucy nor Magnificent Maddy can remember what the code was. They need your help!

You goal, is to help the girls out by writing the correct winning positions. 

Step 1:
  a) Go to the following website:
        https://raw.githubusercontent.com/jackleekopij/CoderDojo/master/Naughts_and_crosses.py
  b) Open up "Notepad" and paste the above file in. 

  c) Save this file in "C:/"


Step 2:
  Now it is your time to help write the code! Look at the first line of code that reads:
  "Wins = [ '' '' ''
    ]"

  This says if the player has won the game. 
  The second line says the player has won by get 3 in a column i.e.

  x|o|-
  x|o|- is checked by the line '100 100 100'
  x|-|- 

  o|x|-
  o|x|- is checked by the line '010 010 010'
  o|x|- 

  -|-|x
  -|o|x is checked by the line '001 001 001'
  o|-|x 

  Your job is to write in the code that will check:
  x|x|x
  o|-|-
  o|-|-
  
  -|o|-
  x|x|x
  o|-|-

  -|0|-
  -|o|-
  x|x|x

  What do you have to write inside the quotes so Lovely Lucy and Magnificent Maddy can fix their code?
  
Step 3:
  Once you have finished the code it is time to play the game!
  a) First open the command prompt. Open the start menu and search for 'command prompt'. 
    (This should open a black window that looks like the following.)

  b) In the black box write the following:
        `pip install pygame`

  c) Now, save the "mememory_game.py" file in the C:/ directory***Subject to the default folder***. 

  d) Now type the following into the command prompt:
      "python memory_game.py"

    This should start the memory_game. Now please spend some time playing and enjoying your game!
