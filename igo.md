igo Language
-------------------

A language for GoEngine to setup rules, which usually hard to be defined.
For example, player 1 couldn't play higher than third line in the first 20 steps but place two stones each round. Here is the pseudocode:

```
player 1:
      if current steps < 20:
        above third line are unavailible to put stone
        place 2 stones
      else:
        normal
player 2:
      normal 
```

Could be more complex, like include how many step the player could place for each round, and other rules.
