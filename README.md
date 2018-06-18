# Pentomino tiling

Solve pentomino exact cover problem recursively.

A pentomino is a polyomino that consists of 5 squares. There are 12 pentomino shapes, if you don't count rotations and reflections. 
Most pentominoes can form their own mirror image through rotation, but some of them have to be flipped over.

```        I                                                                        
        I     L       N                                                 Y        
 FF     I     L      NN     PP     TTT              V       W     X    YY      ZZ
FF      I     L      N      PP      T     U U       V      WW    XXX    Y      Z 
 F      I     LL     N      P       T     UUU     VVV     WW      X     Y     ZZ
```
A Pentomino tiling is an example of an exact cover problem and can take on many forms. A traditional tiling presents an 8 by 8 grid, where 4 cells are left uncovered. The other cells are covered by the 12 pentomino shapes, without overlaps, with every shape only used once.

The 4 uncovered cells should be chosen at random. Note that not all configurations are solvable.

Example:
```
F I I I I I L N
F F F L L L L N
W F - X Z Z N N
W W X X X Z N V
T W W X - Z Z V
T T T P P V V V
T Y - P P U U U
Y Y Y Y P U - U
```
(text used when creating the RosettaCode task)
