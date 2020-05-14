## Work out distances

Now that the program knows the player's reaction time, write some code to calculate how far the ISS would have travelled in that time.

--- task ---
Create a new variable called `kilometres`{:class="block3variables"}.
--- /task ---

The ISS travels at about 7.66 kilometres per second.

--- task ---
Add blocks to your code so that the `kilometres`{:class="block3variables"} variable is set to the distance that the ISS would have travelled.

--- hints --- --- hint ---
You can use a `*`{:class="block3operators"} multiplier block to work out the distance travelled and set this as the variable's value.
--- /hint --- --- hint ---
Here are the blocks that you will need:

```blocks3
set [kilometres v] to ()

timer

() * ()
```
--- /hint --- --- hint ---
Here is what your completed script should look like:

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times!] for (2) seconds
wait (1) seconds
say [Press the Space key when I say "GO!"]
wait (pick random (1) to (10)) seconds
say [GO!]
reset timer
say (join [Your reaction time was ] (join (timer) [seconds]))
+ set [kilometres v] to ((timer) * (7.66))
```
--- /hint --- --- /hints ---
--- /task ---
	
