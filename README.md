# The Space Race

My first full coding project, written in Grade 11 (June 2023) in Java with Swing.

You fly a rocket through space with the arrow keys while dodging asteroids.

## What's in it

- `Runner.java` is the entry point and opens the game window.
- `SpaceGameGUI.java` builds the 500×700 window: a space background, the player's rocket, asteroid panels, and a game-over screen.
- `ShipMovement.java` is a `KeyListener` that moves the rocket with the arrow keys and keeps it inside the window.

## Running it

It's a NetBeans project. Open the folder in NetBeans and run `Runner`, or:

```bash
javac -d out src/*.java
java -cp out Runner
```

## Looking back

This is where I learned the basics: event listeners, Swing layouts, and how a game loop fits together. The code is kept as it was, unfinished parts included, as a record of where I started.
