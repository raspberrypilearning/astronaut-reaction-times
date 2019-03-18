## Add a random pause

You don't want the game to start straight away, or for the start of the game to be predictable.

--- task ---
Add in some blocks to your program so that it waits for a random number of seconds before starting and then make the sprite shout "GO!".

--- hints --- --- hint ---
You will need to add in a `wait 1 seconds`{:class="block3control"} block and inside it place a `pick random 1 to 10`{:class="block3operators"} block
--- /hint --- --- hint ---
Here are the two blocks you will need

```blocks3
say [Hello!]

pick random (1) to (10)

wait (1) seconds
```
--- /hint --- --- hint ---
Here's the two blocks added into the program
```blocks3
when flag clicked
say [Hello, British ESA Astronaut Tim Peake here. Let's test your reaction times?] for (2) seconds
wait (1) seconds
say [Press the Space key when I say "GO!"]
+ wait (pick random (1) to (10)) seconds
+ say [GO!]
```
--- /hint --- --- /hints ---
--- /task ---


