## Work out reaction times

To calculate the player's reaction time, you can use Scratch's inbuilt timer.

--- task ---
Add a `reset timer`{:class="block3sensing"} block to your script.

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times!] for (2) seconds
wait (1) seconds
say [Press the Space key when I say "GO!"]
wait (pick random (1) to (10)) seconds
say [GO!]
+ reset timer
```
--- /task ---

The timer will start counting from zero seconds.
The timer needs to stop when the player presses the space bar.

--- task ---
Use a `wait until`{:class="block3control"} block and a `key space pressed?`{:class="block3sensing"} block to start the next part of the program.

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times?] for (2) seconds
wait (1) seconds
say [Press the Space key when I say "GO!"]
wait (pick random (1) to (10)) seconds
say [GO!]
reset timer
+ wait until <key [space v] pressed?>
```
--- /task ---

--- task ---
Then, tell the player how long it took them to press the space bar. Use `join`{:class="block3operators"} blocks to report the number of seconds it took them.

--- hints --- --- hint ---
The astronaut should say something like "Your reaction time was 4 seconds".
Use a `say`{:class="block3looks"} block, two `join`{:class="block3operators"} blocks, and the `timer`{:class="block3sensing"} block.
--- /hint --- --- hint ---
Here are all the blocks that you need:

```blocks3
say []
join () ()
join () ()
timer
```
--- /hint --- --- hint ---
Here is what your script should look like:

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times!] for (2) seconds
wait (1) seconds
say [Press the Space key when I say "GO!"]
wait (pick random (1) to (10)) seconds
say [GO!]
reset timer
wait until <key [space v] pressed?>
+ say (join [Your reaction time was ] (join (timer) [seconds]))
```
--- /hint --- --- /hints ---
--- /task ---
