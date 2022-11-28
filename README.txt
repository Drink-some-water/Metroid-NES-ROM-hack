This is a very basic rom manipulation to change the color of the main character sprite.
I also added my name to the start menu. 

To run the file I would suggest using 
Mesen: 
OR
FCEUX: 


A brief description of my work:
downloaded fceux, loaded up the rom, opened the hex editor from the debug tools, switched 
to editing the rom, found the memory address containing the color values, 16 19 27. 
Long process of trial and error until changing the proper 27(orange) to 23(purple). 
Used monkey moore to edit the text. typed the text "push to start" to generate a table 
of the text found in main menu. Then loaded the table file into fceux and edited bytecode
according to table.
