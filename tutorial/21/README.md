# Add Math to Keep All of Dodge Always on the Screen

1. Calculate how many pixels are in half the scaled `dodge` sprite
1. Calculate the `max` x value by subtracting from `game.width`
1. Calculate the `min` x value by adding to 0
1. Adjust `randInt(max)` and the result to use `max` and `min`

* Note: yes there is an easier way, but do it this way first to
  understand all the math that is happening.
