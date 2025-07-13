# Interactive_adventure_game_Python  

Text Adventure Game: The Grand Palace Quest
A simple text-based adventure game written in Python where you explore rooms, collect items, and solve a puzzle to unlock a hidden treasure.

**How to Play**  
You start at the entrance of a mysterious palace and must explore connected rooms, pick up useful items, combine parts of a key, and unlock a hidden chamber to find the treasure.

Use simple commands to move, interact with items, and solve puzzles.

**Available Commands**  
go [direction] — Move north, south, east, or west (e.g., go north)  
pick [item] — Pick up an item in the current room (e.g., pick knife)  
use [item] — Use an item from your inventory (e.g., use key)  
combine [item1] [item2] — Combine two items (e.g., combine key_part1 key_part2) 
inventory — See what you're carrying  
look — Look around your current room again  
help — Show all available commands  
quit — Exit the game

**Puzzle**
To unlock the Locked Room:  
Collect key_part1 from the Library  
Collect key_part2 from the Kitchen  
Use combine key_part1 key_part2 to create the full key  
Use the key in the Hallway to unlock the door to the treasure

**Rooms in the Game**
Entrance — Starting point of the game  
Hallway — Central room with access to other areas  
Library — Contains a part of the key  
Kitchen — Contains the other part of the key  
Locked Room — Hidden chamber with the treasure (must be unlocked)  


**Learning Goals**
This project helps practice:  
Python dictionaries and lists  
Control flow (if/else, loops)  
String handling  
State management (inventory, rooms)  
Functions and modular design

**Win Condition**  
The game ends when you successfully unlock the Locked Room and pick up the treasure.
