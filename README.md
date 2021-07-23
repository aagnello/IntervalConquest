Interval Conquest
=======

This repo gives code to arress numerically a probem with N players, that play in sequence, to each grab as much as they can from a common interval.
The problem is quite classical when there are three players, but I haven't found a lot of discussion of the gernal N>3 case.
I have, however, found an analytical solution that seems to be confirmed numerically by my code.

Anyways, here's the problem:
Three queens stand before me: Adore, Bianca and Courtney. Adore chooses a number on the interval between 0 and 1 (included), then Bianca chooses another number in the same interval, and then C chooses.
I then draw a random number X uniformly over [0;1], and the player that lies closer to X wins. Where should Adore and Bianca place their choices?
When there are four players (Adore, Bianca, Courtney and Dela), what is Adore's best choice?