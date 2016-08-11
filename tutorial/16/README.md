# Moving the Player (without Physics)

1. Add `createCursorKeys()` to the `Play.create()` method
1. Add a config `C` variable for player speed
1. Add math code to `Play.update()` checking for keys and change position

*Note: we are deliberately using math and logic here where Phaser/Pixi
physics would also work (and probably more efficiently). This is to
help you learn what is happening and to practice your mathematical and
logical programming. We will redo this with Physics later.*
