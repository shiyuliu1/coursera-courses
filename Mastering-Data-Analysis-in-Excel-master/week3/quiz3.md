1.Question 1
Suppose we have two coins: one “fair” coin, where p(head) = p(tails) = .5; and an “unfair” coin where p(heads) does not equal p(tails). Which coin has a larger entropy prior to observing the outcome?
1 / 1 point


The fair coin *


The unfair coin

Correct
Correct. A uniform distribution is the maximum entropy distribution for a discrete number of outcomes. Any other distribution must have lower entropy.
2.Question 2
If you roll one fair dice (6-sided), what is its entropy before the result is observed?
1 / 1 point


2.58 bits *


0.43 bits


2.32 bits


0.46 bits

Correct
For a uniform distribution across "n" things, the entropy is always equal to log(n) - here we are using log to the base 2. 1/6 * log2(6) * 6 = log2(6) = 2.58 bits

3.Question 3
If your friend picks one number between 1001 to 5000, under the strategy used in video Entropy of a Guessing Game, what is the maximum number of questions you need to ask to find out that number?
1 / 1 point


13


12 *


11


10


4.Question 4
Use the “Information Gain Calculator” spreadsheet to calculate the "Conditional Entropy" H(X|Y) given a = 0.4, c = 0.5, e = 0.11.

Information Gain Calculator.xlsx
1 / 1 point


0.97 bits


0.90 bits


1.87 bits


0.87 bits *

Correct
We want the "conditional entropy" which is the expected entropy of X, given that Y is known. The spreadsheet should do the work. Input the three Confusion Matrix values manually and the answer will be calculated automatically.
5.Question 5
On the “Information Gain Calculator” spreadsheet, given a = 0.3, c = 0.2, suppose now we also know that H(X,Y) = H(X) + H(Y). What is the joint probability e?

Information Gain Calculator.xlsx
1 / 1 point


0.06 *


0.5


0.3


0.04

Correct
H(X,Y) = H(X) + H(Y) implies independence, therefore e = a*c
6.Question 6
Given a = 0.2, c = 0.5 on the Information Gain Calculator Spreadsheet suppose now we also know the true positive rate is 0.18. What is the Mutual Information?

Information Gain Calculator.xlsx
1 / 1 point


0.13 bits


1.64 bits


0.08 bits *


0.72 bits

Correct
Great job!
7.Question 7
Consider the Monty Hall problem, but instead of the usual 3 doors, assume there are 5 doors to choose from. You first choose door #1. Monty opens doors #2 and #3. What is the new probability that there is a prize behind door #4?
1 / 1 point


0.4 *


0.67


0.5


0.2


8.Question 8
Again, consider the Monty Hall problem, but with 5 doors to choose from instead of 3. You pick door #1, and Monty opens 2 of the other 4 doors. How many bits of information are communicated to you by Monty when you observe which two doors he opens?
1 / 1 point


1.52 bits


2.32 bits


0.80 bits *


0.67 bits

Correct
Initial entropy: 1/5*log(2.5/1) * 5 = 2.32

After opened 2 doors: 1/5*log(2,5/1) + 2/5*log(2,5/2) * 2 = 1.52

Information gain = 2.32 - 1.52 = 0.8
9.Question 9
B stands for “the coin is fair”, ~B stands for “the coin is crooked”. The p(heads | B) = 0.5, and p(heads | ~B) = 0.4. Your friend tells you that he often tests people to see if they can guess whether he is using the fair coin or the crooked coin, but that he is careful to use the crooked coin 70% of the time. He tosses the coin once and it comes up heads.

What is your new best estimate of the probability that the coin he just tossed is fair?
1 / 1 point


0.15


0.35 *


0.40


0.43

Correct
Great job!
10.Question 10
Suppose you are given either a fair dice or an unfair dice (6-sided). You have no basis for considering either dice more likely before you roll it and observe an outcome. For the fair dice, the chance of observing “3” is 1/6. For the unfair dice, the chance of observing “3” is 1/3. After rolling the unknown dice, you observe the outcome to be 3.

What is the new probability that the die you rolled is fair?
1 / 1 point


0.08


0.23


0.33 *


0.36

