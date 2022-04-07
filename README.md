
# Text-based-game-engine-thing
Goal: To create a reasonably simple basis to create a text based game with a degree of modularity. 
Doing this mostly blind.

initial ideas:
stats as an item in a hashmap.
player object has "inventory" object
payer has "equipment" object which is subclass of "inventory" which could be a subclass of abstract "storage"
-equipment is a type of inventory so it will use all it's functions

enemies and chests has "loot" subclass of "storage" abstract
simple xp and combat
simplified dnd Initial complete version will just roll to hit and roll damage.

Mobs and chests/room_loot basically the same, so ill create a parent class maybe? I may or may not include player under it becuase to complex to make sense perhaps?
-same roll to do something
-might have a finese or brute option

events as either an interface or abstract class.
-can contain other events to form a  "story arc"
-specific type of events "shop", "fight", "explore" with preset methods, not compulsory to use (maybe interface for shop?)

Inventory management.
-list items function
  1.
  2.
  3.
 typing rearrage will allow u to switch item locations from 4<->6 for example
-drop 1. will drop item 1


Ascii images.
-maybe a way to read them from text files?
-or just store them as objects in an instance

Music and sound
-last to be implemented, probably for sound effects and music for ambeince depending what enviroment.

ORDER OF DEVELEPMENT:
Player class and main class first, followed by inventory, basic event(combat) along with mobs, rest afterward
