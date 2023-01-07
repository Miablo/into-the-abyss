# into-the-abyss

### Required
Install: http://courses.missouristate.edu/kenvollmar/mars/

Text-based adventure game in MIPS using MARS

 Author: Mio Diaz
 Purpose: Final Project
 Text based choose your adventure game

 Important: 
 the Bitmap Display tool must be connected to MARS and set to:
   unit width in pixels: 1
   unit height in pixels: 1
   display width in pixels: 1024
   display height in pixels: 1024
   base address for display: 0x10040000 (heap)

 all characters entered must be UPPERCASE

################################
##------ GAME MECHANICS ------##
################################

 Enter the letter in brackets to make that selection
 game will determine your fate based on your selection
 each game play won't be the same as the last
 winning or losing is all based on your actions

 stretch goals:
 1) inventory
 2) normal or nightmare mode
 3) hope or death picker
 random gen will pick between 0-1
 0 will be hope and 1 will be death
 based on your response some will lead to hope
 other responses are based on chance
 the fate of certain paths - if the end of a path is reached -
 will be predetermined
 
 Sample Scenes
 ![Scene 1](/scene1.PNG)
 
 ![Scene 2](/scene2.PNG)
  
 ![Tutorial](/tutorial.PNG)
