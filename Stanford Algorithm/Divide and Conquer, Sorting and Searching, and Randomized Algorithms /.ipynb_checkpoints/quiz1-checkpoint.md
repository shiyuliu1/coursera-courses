Coursera

Explore
What do you want to learn?

0


Shiyu Liu
Divide and Conquer, Sorting and Searching, and Randomized Algorithms
Week 1
Problem Set #1
Prev
Next

I. INTRODUCTION
Reading: Welcome and Week 1 Overview
. Duration:10 min
Reading: Overview, Resources, and Policies
. Duration:10 min
Reading: Lecture slides
. Duration:10 min
Video: LectureWhy Study Algorithms?
. Duration:4 min
Video: LectureInteger Multiplication
. Duration:8 min
Video: LectureKaratsuba Multiplication
. Duration:12 min
Video: LectureAbout the Course
. Duration:17 min
Video: LectureMerge Sort: Motivation and Example
. Duration:8 min
Video: LectureMerge Sort: Pseudocode
. Duration:12 min
Video: LectureMerge Sort: Analysis
. Duration:9 min
Video: LectureGuiding Principles for Analysis of Algorithms
. Duration:15 min

II. ASYMPTOTIC ANALYSIS
Video: LectureThe Gist
. Duration:14 min
Video: LectureBig-Oh Notation
. Duration:4 min
Video: LectureBasic Examples
. Duration:7 min
Video: LectureBig Omega and Theta
. Duration:7 min
Video: LectureAdditional Examples [Review - Optional]
. Duration:7 min

Problem Set #1
Quiz: Problem Set #1
5 questions

Programming Assignment #1
Quiz: Programming Assignment #1
1 question
QUIZ • 30 MIN
Problem Set #1
Get closer to your goal
You are 45% more likely to complete the course if you finish the assignment

Submit your assignment
DUE DATESep 13, 11:59 PM PDT
ATTEMPTS2 every 12 hours
Receive grade
TO PASS80% or higher
Grade
100%
We keep your highest score



Problem Set #1
Graded Quiz • 30 min
Due Sep 13, 11:59 PM PDT

Congratulations! You passed!
TO PASS 80% or higher
GRADE
100%
Problem Set #1
LATEST SUBMISSION GRADE
100%
1.
Question 1
3-way-Merge Sort : Suppose that instead of dividing in half at each step of Merge Sort, you divide into thirds, sort each third, and finally combine all of them using a three-way merge subroutine. What is the overall asymptotic running time of this algorithm? (Hint: Note that the merge step can still be implemented in O(n)O(n) time.)

1 / 1 point

nn


n ( \log(n))^2n(log(n)) 
2
 


n^2\log(n)n 
2
 log(n)


n \log(n)nlog(n)

Correct
That's correct! There is still a logarithmic number of levels, and the overall amount of work at each level is still linear.

2.
Question 2
You are given functions ff and gg such that f(n)=O(g(n))f(n)=O(g(n)). Is f(n)*log_2(f(n)^c) = O(g(n)*log_2(g(n)))f(n)∗log 
2
​	
 (f(n) 
c
 )=O(g(n)∗log 
2
​	
 (g(n))) ? (Here cc is some positive constant.) You should assume that ff and gg are nondecreasing and always bigger than 1.

1 / 1 point

Sometimes yes, sometimes no, depending on the constant cc


True


False


Sometimes yes, sometimes no, depending on the functions ff and gg

Correct
That's correct! Roughly, because the constant c in the exponent is inside a logarithm, it becomes part of the leading constant and gets suppressed by the big-Oh notation.

3.
Question 3
Assume again two (positive) nondecreasing functions ff and gg such that f(n)=O(g(n))f(n)=O(g(n)). Is 2^{f(n)}=O(2^{g(n)})2 
f(n)
 =O(2 
g(n)
 ) ? (Multiple answers may be correct, you should check all of those that apply.)

1 / 1 point

Never


Sometimes yes, sometimes no (depending on ff and gg)

Correct

Yes if f(n) \le g(n)f(n)≤g(n) for all sufficiently large nn

Correct

Always

4.
Question 4
k-way-Merge Sort. Suppose you are given kk sorted arrays, each with nn elements, and you want to combine them into a single array of knkn elements. Consider the following approach. Using the merge subroutine taught in lecture, you merge the first 2 arrays, then merge the 3^{rd}3 
rd
  given array with this merged version of the first two arrays, then merge the 4^{th}4 
th
  given array with the merged version of the first three arrays, and so on until you merge in the final (k^{th}k 
th
 ) input array. What is the running time taken by this successive merging algorithm, as a function of kk and nn? (Optional: can you think of a faster way to do the k-way merge procedure ?)

1 / 1 point

\theta(n^2k)θ(n 
2
 k)


\theta(n \log(k))θ(nlog(k))


\theta(nk)θ(nk)


\theta(nk^2)θ(nk 
2
 )

Correct
That's correct! For the upper bound, the merged list size is always O(kn)O(kn), merging is linear in the size of the larger array, and there are kk iterations. For the lower bound, each of the last k/2k/2 merges takes \Omega(kn)Ω(kn) time.

5.
Question 5
Arrange the following functions in increasing order of growth rate (with g(n)g(n) following f(n)f(n) in your list if and only if f(n)=O(g(n))f(n)=O(g(n))).

a)n^2 \log(n)n 
2
 log(n)

b)2^n2 
n
 

c)2^{2^n}2 
2 
n
 
 

d)n^{log(n)}n 
log(n)
 

e)n^2n 
2
 

Write your 5-letter answer, i.e., the sequence in lower case letters in the space provided. For example, if you feel that the answer is a->b->c->d->e (from smallest to largest), then type abcde in the space provided without any spaces before / after / in between the string.

You can assume that all logarithms are base 2 (though it actually doesn't matter).

WARNING: this question has multiple versions, you might see different ones on different attempts!

1 / 1 point
eadbceadbc
Please note: Each of the following will be interpreted as a single variable, not as a product of variables: eadbc. To multiply variables, please use * (e.g. enter x*y to multiply variables x and y).
eadbc
Correct
One approach is to graph these functions for large values of n. Once in a while this can be misleading, however. Another useful trick is to take logarithms and see what happens (though again be careful, as in Question 3).

