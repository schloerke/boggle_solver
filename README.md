# [boggle_solver](http://schloerke.github.io/boggle_solver)

Approach

Due to rapidly increasing complexity by checking if a word exists in in the dictionary,
it is faster to check if each dictionary word exists instead.

For every word... Once a starting position is found, the nearest 8 neighbors are checked (if valid)
for the next letter. Repeat this checking until the word is found or not able to be found.
