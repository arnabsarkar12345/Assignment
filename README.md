# Assignment
These rules, which compare the behavior of the automaton to real life, can be condensed into the following:

### Any live cell with two or three live neighbours survives.
### Any dead cell with three live neighbours becomes a live cell.
### All other live cells die in the next generation. Similarly, all other dead cells stay dead.



The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed; births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick. Each generation is a pure function of the preceding one. The rules continue to be applied repeatedly to create further generations.
