# COC-Project-1st-year-
In this it includes my COC project of C with the Titile: The "Ludo" Dice distribution analyzer

This C program simulates rolling *two six sided dice* a large number of times (default:1,000,000) to calculate and display the *probability distribution* of heir sums.

---
## FEATURES
(a) Simulates two dice rolls using random numbers.
(b) Counts the frequency of each possible sum(2-12).
(c) Calculates and displays the probability for each sum.
(d) Uses 'rand()' and 'srand(time(NULL))' for randomness.

---
## How it works
1. Each die rol gives a random number from *1 to 6*.
2. The program repeats this process *1,000,000 times*.
3. It record how many times each sum (2-12) appears.
4. Finally, it prints the *count and probability* for each sum.

---

## Sample output

Sum   Count   Probability
2    27696     2.77%
3    55431     5.54%
4    83477     8.35%
5    111230    11.12%
6    139015    13.90%
7    167047    16.70%
8    138926    13.89%
9    110974    11.10%
10   84501      8.35%
11   1155569    5.56%
12   27734      2.77%
