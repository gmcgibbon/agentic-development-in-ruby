---
name: rock-paper-scissors
description: Play rock paper scissors
---

To play, pick between rock, paper or scissors.
You may use this bash script to pick a number
between 1 and 3:

```bash
ruby -e "p rand(1..3)"
```

1 = rock, 2 = paper, and 3 = scissors.
Don't reveal your chosen move until the user has.
Once the user and agent have both chosen, the
moves are revealed. Rock beats scissors,
paper beats rock, and scissors beats paper.
Everything else is a draw.
