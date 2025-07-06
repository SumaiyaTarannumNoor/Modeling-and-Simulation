## Definitions

**Sample Space (S):**  
The set of all possible outcomes of a random experiment.

**Event (A):**  
A subset of the sample space, representing a specific outcome or set of outcomes.

**Probability Measure (P):**  
A function that assigns a probability value to each event, such that:
- The probability of any event is between 0 and 1 (inclusive).
- The probability of the entire sample space is 1.

## Example

Imagine flipping a fair coin.

- **Sample Space (S):**  
  {Heads (H), Tails (T)}

- **Event (A):**  
  Getting Heads. This is a subset of the sample space:  
  A = {H}

- **Probability Measure (P):**
  - P(H) = 1/2 (probability of getting heads)
  - P(T) = 1/2 (probability of getting tails)
  - P(S) = P(H) + P(T) = 1/2 + 1/2 = 1

In this example, the probability measure assigns a probability of 1/2 to both the event of getting heads and the event of getting tails, and the sum of probabilities for all possible outcomes (the sample space) is 1.

## Definition

The **power set** of a given set is the set of all possible subsets of that set, including the empty set and the set itself.

Given a set \( A \), its power set, denoted as \( P(A) \) or \( \mathcal{P}(A) \), is the set of all possible subsets of \( A \).
- This includes:
  - The empty set (also known as the null set)
  - The set \( A \) itself
- **Subsets** are sets that contain only elements from the original set \( A \).

## Example 1

Let’s say we have a set \( A = \{1, 2\} \).  
The subsets of \( A \) are:
- The empty set: \( \{\} \) or \( \varnothing \)
- The singleton sets: \( \{1\} \) and \( \{2\} \)
- The set itself: \( \{1, 2\} \)

Therefore, the power set of \( A \) is:  
\( P(A) = \{\ \{\},\ \{1\},\ \{2\},\ \{1, 2\}\ \} \)

## Example 2

If set \( B = \{a, b, c\} \), then its power set \( P(B) \) would be:  
\( P(B) = \{\ \{\},\ \{a\},\ \{b\},\ \{c\},\ \{a, b\},\ \{a, c\},\ \{b, c\},\ \{a, b, c\}\ \} \)

## Cardinality

The **number of elements** in the power set (its cardinality) is \( 2^n \), where \( n \) is the number of elements in the original set.

- For example, if set \( A \) has 3 elements, its power set will have \( 2^3 = 8 \) elements.
- If set \( B \) has 5 elements, its power set will have \( 2^5 = 32 \) elements.

# Definitions: PMF and PDF

## Probability Mass Function (PMF)

A **Probability Mass Function (PMF)** describes the probability that a discrete random variable takes a specific value. The PMF gives the probability for each possible value.

**Mathematical definition:**  
For a discrete random variable X,  
P(X = x) = p(x), where  
- p(x) ≥ 0 for all x  
- The sum over all x of p(x) = 1

**Example:**  
Let X be the outcome when rolling a fair six-sided die.  
Possible values: 1, 2, 3, 4, 5, 6  
p(x) = 1/6 for each x in {1, 2, 3, 4, 5, 6}

---

## Probability Density Function (PDF)

A **Probability Density Function (PDF)** describes the relative likelihood for a continuous random variable to take on a value. The PDF itself is not a probability, but the area under the curve over an interval gives the probability for that interval.

**Mathematical definition:**  
For a continuous random variable X,  
P(a ≤ X ≤ b) = ∫ from a to b of f(x) dx, where  
- f(x) ≥ 0 for all x  
- The integral from -∞ to ∞ of f(x) dx = 1

**Example:**  
Let X be a random variable with a uniform distribution on the interval [0, 1].  
f(x) = 1 for 0 ≤ x ≤ 1  
f(x) = 0 otherwise  
Probability that X is between 0.2 and 0.5:  
P(0.2 ≤ X ≤ 0.5) = ∫ from 0.2 to 0.5 of 1 dx = 0.5 - 0.2 = 0.3


