# Max Data Storage Datapack
Adds a list with easy access to numbered entries.

The purpose of this datapack is to cover the shortcoming of minecraft lists that you can't access a specific number entry -for instance, the third one in  list- without hardcoding each number you may want. This datapack allows you to access any entry with a number you can manipulate.
  
  
You can interact with the datapack with three commands:

/function mm.data:api/init destroys and requires sole control over a chunk in the middle your world, and is required for the datapack to work. You can do this in other dimensions, though.

/scoreboard players set destination mm.data # sets the position in the list that will be accessed. # can only be a number between 0 and 98303.

/function mm.data:api/goto updates the position in the list that is being accessed. It requires that you use the previous command first.

To access the set, you can execute at @e[type=marker,tag=mm.data.librarian] and the barrel corresponding to the position in the list you wanted will be ~ ~ ~.

The idea for this datapack was directly stolen in its entirety from NuclearInferno, but he never released his version and I wrote this all myself. If he wants me to take this down, I will.
