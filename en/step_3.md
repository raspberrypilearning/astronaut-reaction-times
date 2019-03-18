## Starting the test

You can start the game by having the Astronaut give and introduction and some basic instructions.

--- task ---
Click on the Astronaut sprite and then add a `when flag clicked`{:class="block3events"} and a `say Hello! for 2 seconds`{:class="block3looks"}

![astronaut sprite](images/astro-sprite.png)
```blocks3
when flag clicked
say (Hello!) for (2) seconds
```
--- /task ---

--- task ---
Now change the "Hello!" text to a different greeting. You can use the one below or make something up yourself.
![astronaut sprite](images/astro-sprite.png)
```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times?] for (2) seconds
```
--- /task ---

--- task ---
Now add a `wait 1 seconds`{:class="block3control"} block and then give the player some instructions for what they need to do.

![astronaut sprite](images/astro-sprite.png)
```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times?] for (2) seconds
+ wait (1) seconds
+ say [Press the Space key when I say "GO!"]
```
--- /task --

--- task ---
Click the green flag to test your game and make sure it all works
--- /task ---

