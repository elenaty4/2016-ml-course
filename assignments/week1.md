Week 1 Homework
--
Due Monday, August 27 at 11:55pm.

* Exercise 2.2
* Write the following program.
 * The program will output 100 letters per line, on 10 lines. 
 * The first letter is always "I".
 * The subsequent letters will be generated with the following probabilities:
 * P(_ | I) = 1
 * P(a | _) = 0.5
 * P(l | _) = 0.5
 * P(m | a) = 0.4
 * P(l | a) = 0.6
 * P(v | i) = 0.95
 * P(n | i) = 0.05
 * P(! | e) = 1
 * P(_ | !) = 0.7
 * P(I | !) = 0.2
 * P(! | !) = 0.1
 
Hint: You need to sample from a distribution here, i.e., "roll the dice."  