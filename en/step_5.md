## Calculating reaction times

To calculate the reaction time of the player, you can use Scratch's inbuilt timer.

--- task ---
Add a `reset timer`{:class="block3sensing"} to your script

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times?] for (2) seconds
wait (1) seconds
say [Press the Space key when I say "GO!"]
wait (pick random (1) to (10)) seconds
say [GO!]
+ reset timer
```
--- /task ---

The timer will now start counting, starting from zero seconds.
The timer needs to stop when the player presses the spacebar.

--- task ---
Use a `wait until`{:class="block3control"} and a `key space pressed?`{:class="block3sensing"} block to start the next part of the program.

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
Then you can tell the player how long it took them to press the timer. Use `join`{:class="block3operators"} blocks report the number or seconds it took them.

--- hints --- --- hint ---
You want the astronaut to say something like "Your reaction time was 4 seconds".
You will need to use a `say`{:class="block3looks"} block, two `join`{:class="block3operators"} blocks and the `timer`{:class="block3sensing"} block
--- /hint --- --- hint ---
Here are all the block you need

```blocks3
say []
join () ()
join () ()
timer
```
--- /hint --- --- hint ---
Here's what your script should look like

![astronaut sprite](images/astro-sprite.png)

```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times?] for (2) seconds
wait (1) seconds
say [Press the Space key when I say "GO!"]
wait (pick random (1) to (10)) seconds
say [GO!]
reset timer
+ say (join [Your reaction time was ] (join (timer) [seconds]))
```
--- /hint --- --- /hints ---
--- /task ---
