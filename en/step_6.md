## Calculating distances

Now that the program knows the player's reaction time, you can use it to calculate how far the ISS would have traveled in that time.

--- task ---
Create a new variable called `kilometers`{:class="block3data"}
--- /task ---

The ISS travels at about 7.66 kilometers a second.
--- task ---
Add blocks to your code so that the `kilometers`{:class="block3data"} variable is set to the distance the ISS would have traveled

--- hints --- --- hint ---
You can use a `*`{:class="block3operators"} block to work out the distance traveled and set this as the variable's value.
--- /hint --- --- hint ---
Here are the blocks you will need

```blocks3
set [kilometersv] to ()

timer

() * ()
--- /hint --- --- hint ---
Here's what your completed script should look like

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times?] for (2) seconds
wait (1) seconds
say [Press the Space key when I say "GO!"]
wait (pick random (1) to (10)) seconds
say [GO!]
reset timer
say (join [Your reaction time was ] (join (timer) [seconds]))
+ set [kilometers v] to ((timer) * (7.66))
```
--- /hint --- --- /hints ---
--- /task ---
	
