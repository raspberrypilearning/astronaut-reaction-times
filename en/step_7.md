## Finish the game

Now, the astronaut sprite needs to tell the player how far they would have travelled on the ISS.

To make your calculation a bit easier to read, you can use a `round`{:class="block3operators"} block. This will round the number up or down so that it is a whole number.

--- task ---
Use `say`{:class="block3looks"}, `join`{:class="block3operators"}, and `join`{:class="block3operators"} blocks to tell the player the value of the `kilometres`{:class="block3variables"} variable.

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
say (join [Your reaction time was ] (join (timer) [seconds]))
set [kilometres v] to ((timer) * (7.66))
wait (2) seconds
say (join (join [In that time, the ISS travels about] (round (kilometres)))[ kilometres]
```
--- /task ---



