## From INTRO TO PROBABILITY FOR DATA SCIENCE (Chapter 3)
- How do we convert a statement to a number? The answer is the
  concept of random variables.
- Key Concept 1: What are random variables?
Random variables are mappings from events to numbers.
- Now, suppose that we have constructed a random variable that translates statements to
numbers. The next task is to endow the random variable with probabilities. More precisely,
we need to assign probabilities to the random variable so that we can perform computations.
This is done using the concept called probability mass function (PMF).
- Key Concept 2: What are probability mass functions (PMFs)?
Probability mass functions are the ideal histograms of random variables.
- The best way to think about a PMF is a histogram, something we are familiar with.
A histogram has two axes: The x-axis denotes the set of states and the y-axis denotes
the probability. For each of the states that the random variable possesses, the histogram
tells us the probability of getting a particular state. The PMF is the ideal histogram of a
random variable. It provides a complete characterization of the random variable. If you have
a random variable, you must specify its PMF. Vice versa, if you tell us the PMF, you have
specified a random variable.
-   A random variable X is a function X : Ω → R that maps an outcome
ξ ∈ Ω to a number X(ξ) on the real line. (Page 105)
- Consider an experiment with 4 outcomes Ω = {♣, ♢, ♡, ♠}. 
- othing wrong with his motivation because
all of us want efficiency. How can we help him? Well, the easiest solution is to encode each
symbol with a number, for example, ♣ ← 1, ♢ ← 2, ♡ ← 3, ♠ ← 4
- e can express this more formally by defining
a function X : Ω → R with
X(♣) = 1, X(♢) = 2, X(♡) = 3, X(♠) = 4.

- Ω sample space = the set containing ♣, ♢, ♡, ♠
ξ an element in the sample space, which is one of ♣, ♢, ♡, ♠
X a function that maps ♣ to the number 1, ♢ to the number 2, etc
X(ξ) a number on the real line, e.g., X(♣) = 1

- The probability mass function (PMF) of a random variable X is a
function which specifies the probability of obtaining a number X(ξ) = x. We denote a
PMF as
pX (x) = P[X = x]. (3.1)
The set of all possible states of X is denoted as X(Ω).


- Key Concept 2: What are probability mass functions (PMFs)?
PMFs are the ideal histograms of random variables.

### CDF (Discrete)
- Page 121
- A CDF is essentially the cumulative sum of a PMF from −∞ to x, where the variable x′ in
the sum is a dummy variable.

