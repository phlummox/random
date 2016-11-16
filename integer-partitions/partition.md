
Code in Haskell to find the count of [integer partitions](https://en.wikipedia.org/wiki/Partition_(number_theory)) of a number *n*: [gist](https://gist.github.com/phlummox/31560c074168863ba8a4441faf8eb4b8#file-part-hs)

There's no doubt a way of doing it without using state internally that's just as fast, but this worked for me - calculates p(6*10^4) in about 8 seconds on my machine.

Any suggestions on faster ways happily accepted.

