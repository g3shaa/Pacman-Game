**How to Play**

 On welcome screen, press E to start the game, unless you press G, then you enter DEV mode.
 Use arrow keys or WASD to move, Q to pause, E to resume, and R to restart.
 Gaming mechanics is just like the original Pacman.

 Scoring is as follows:
 - 10 pts for each pellet
 - 50 pts for each power pellet
 - 200 for the first ghost eaten in freight mode, double the previous score for
   each additional ghost eaten in the same occurance of freight mode (i.e. 200
   for the 1st, 400 for the 2nd, 800 for the 3rd, resets for every freight mode).

![image](https://user-images.githubusercontent.com/64840882/202746761-45153887-87e4-48f9-bb45-ae0510e42cd9.png)


**Explanation of the JS source code**

 - Function callbacks
   setInterval() used to refresh game, setTimeOut() used to pause screen 
   shortly during countdown to start.

 - Anonymous function
   Used with setTimeOut during countdown.

 - Optional parameters
   Run() takes an optional parameter of isGodMode to determine whether or not
   to enter god mode.

 - Arrays
   Used for constructing game board grids (2-D array), keeping record of ghosts
   and lives left, and an assortment of other various elements.

 - Objects
   Pacman, ghosts, and grids are all objects. 
   They have constructors, properties, parameters, prototypes, overridden 
   toString() methods, etc.
