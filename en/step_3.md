## Start the game

Set up the game so that the astronaut gives an introduction and some basic instructions to the player at the start of the game.

--- task ---
Click on the astronaut sprite, and then drag and drop a `when flag clicked`{:class="block3events"} block and a `say Hello! for 2 seconds`{:class="block3looks"} block.

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say (Hello!) for (2) seconds
```
--- /task ---

--- task ---
Now, change the `Hello!` text to a different greeting. You can use the one below or make something up.

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times!] for (2) seconds
```
--- /task ---

--- task ---
Add a `wait 1 seconds`{:class="block3control"} block and then write some code to tell the player what they need to do.

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times!] for (2) seconds
+ wait (1) seconds
+ say [Press the Space key when I say "GO!"]
```
--- /task ---

--- task ---
Click on the green flag to test your game and make sure it all works.
--- /task ---

