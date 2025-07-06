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

Given a set A, its power set, denoted as P(A), is the set of all possible subsets of A.

- This includes:
  - The empty set (also known as the null set)
  - The set A itself

**Subsets** are sets that contain only elements from the original set A.


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

# Probability Theory

## Definition

**Probability theory** is the branch of mathematics that deals with the analysis of random phenomena. It provides a systematic way to quantify uncertainty, describing how likely an event is to occur. Probability values range from 0 (the event never happens) to 1 (the event always happens).

## Example

Suppose you toss a fair coin. There are two possible outcomes: heads (H) or tails (T).

- The probability of getting heads, P(H), is 1/2.
- The probability of getting tails, P(T), is also 1/2.

This means each outcome is equally likely.

## Properties of Probability

1. **Non-negativity:**  
   For any event A, the probability is always greater than or equal to 0.  
   P(A) ≥ 0

2. **Normalization (Total Probability):**  
   The probability of the sample space (the set of all possible outcomes) is 1.  
   P(S) = 1

3. **Additivity (For mutually exclusive events):**  
   If two events A and B cannot both happen at the same time, then  
   P(A or B) = P(A) + P(B)

4. **Complementary Rule:**  
   The probability that an event A does not occur is 1 minus the probability that it does occur.  
   P(not A) = 1 - P(A)

5. **Range:**  
   For any event A, the probability is between 0 and 1.  
   0 ≤ P(A) ≤ 1

---
**Summary:**  
Probability theory provides rules and tools to model and analyze situations involving uncertainty and randomness. It is foundational in statistics, science, engineering, and everyday decision-making.

# Difference Between Set Theory and Probability Theory

## Set Theory

- Set theory is the branch of mathematics that studies sets, which are collections of distinct objects.
- The objects in a set are called elements or members.
- Set theory focuses on the relationships between sets, such as union, intersection, and complement.
- It forms the foundation for various mathematical concepts, including probability, logic, and functions.

**Example:**  
Let A = {1, 2, 3}, B = {2, 3, 4}  
- The union of A and B (A ∪ B) = {1, 2, 3, 4}  
- The intersection of A and B (A ∩ B) = {2, 3}

---

## Probability Theory

- Probability theory is the branch of mathematics concerned with quantifying uncertainty and analyzing random phenomena.
- It uses the language of set theory to describe events, but assigns a probability value (between 0 and 1) to the likelihood of those events.
- Probability theory introduces the concept of a probability measure, which assigns probabilities to sets (events) within a sample space.

**Example:**  
When rolling a standard die, the sample space S = {1, 2, 3, 4, 5, 6}  
- The event "rolling an even number" is E = {2, 4, 6}  
- The probability of event E is P(E) = 3/6 = 1/2

---

## Summary Table

| Aspect            | Set Theory                          | Probability Theory                          |
|-------------------|-------------------------------------|---------------------------------------------|
| Focus             | Relationships between sets          | Quantifying likelihood of events            |
| Main Concept      | Sets and their operations           | Probability measure on sets (events)        |
| Example Question  | What is A ∩ B?                      | What is the probability of event E?         |
| Application       | Foundations of mathematics, logic   | Statistics, risk analysis, decision making  |

---
Set theory provides the basic language and structure, while probability theory builds on it to measure uncertainty and chance.

# Bertrand Paradox

## Definition

The **Bertrand Paradox** is a famous problem in probability theory that shows how the probability of an event can depend on the method used to define randomness. Specifically, the paradox arises when calculating the probability that a random chord in a circle is longer than the side of an equilateral triangle inscribed in that circle. The paradox demonstrates that "random" can have different meanings, leading to different answers depending on how randomness is defined.

## Example

Suppose you want to find the probability that a randomly chosen chord in a circle is longer than the side of an inscribed equilateral triangle.

Depending on how you define "random chord," you can get different probabilities:

- **Method 1:** Fix one endpoint of the chord and choose the other endpoint uniformly at random on the circle.  
  Probability = 1/3

- **Method 2:** Choose a random point inside the circle and draw a chord with that point as its midpoint.  
  Probability = 1/2

- **Method 3:** Choose a random radius, then pick a random point on that radius and draw the chord perpendicular to the radius at that point.  
  Probability = 1/4

Each method is valid, but leads to a different answer. This is the essence of the Bertrand Paradox: the outcome depends on the definition of randomness.

---
**Summary:**  
The Bertrand Paradox highlights the importance of specifying how randomness is defined in probability problems, as different interpretations can yield different probabilities.

# How Do We Measure the Countability of an Infinite Set?

## Definition

A set is called **countable** (or countably infinite) if its elements can be put into a one-to-one correspondence with the set of natural numbers N = {1, 2, 3, ...}. In other words, a set S is countable if we can list its elements as s₁, s₂, s₃, ... such that every element of S appears exactly once in this list.

If such a listing is not possible, the set is called **uncountable**.

## Mathematical Proof Example: The Set of Integers is Countable

Let's prove that the set of all integers Z = {..., -3, -2, -1, 0, 1, 2, 3, ...} is countable.

### Proof

1. We need to show a one-to-one correspondence (bijection) between the set of natural numbers N and the set of integers Z.
2. We can construct a function f: N → Z that "lists" all the integers.

Define the function as follows:

- f(1) = 0
- f(2) = 1
- f(3) = -1
- f(4) = 2
- f(5) = -2
- f(6) = 3
- f(7) = -3
- ... and so on.

More generally:
- For even n: f(n) = n/2
- For odd n > 1: f(n) = -[(n-1)/2]

This function assigns a unique natural number to each integer and vice versa. Thus, we have created a one-to-one correspondence between N and Z.

**Conclusion:**  
Z is countably infinite.

---

## Uncountable Example: The Real Numbers

The set of real numbers between 0 and 1 is **uncountable**. This can be shown by Cantor's diagonal argument, which proves that no listing of all real numbers in (0, 1) is possible.

**Summary:**  
- An infinite set is **countable** if its elements can be listed in a sequence indexed by natural numbers.
- If this is not possible, the set is **uncountable**.


# Equicardinality and the "Measure" of Infinite Sets

## Equicardinality (by Georg Cantor)

**Equicardinality** is a concept introduced by Georg Cantor to compare the sizes (cardinalities) of sets, including infinite sets. Two sets A and B are **equicardinal** (or have the same cardinality) if there exists a one-to-one correspondence (bijection) between the elements of A and the elements of B.

- If such a correspondence exists, we write |A| = |B|, meaning the sets have the same cardinality.
- This idea allows us to rigorously compare the "sizes" of infinite sets, even when both are infinite.

**Example:**  
- The set of natural numbers N = {1, 2, 3, ...}  
- The set of even numbers E = {2, 4, 6, ...}

There is a bijection f: N → E defined by f(n) = 2n.  
Therefore, |N| = |E|, even though E is a proper subset of N.

---

## "Measure" of Infinite Sets

While **cardinality** compares the "size" of infinite sets via one-to-one correspondence, the concept of **measure** deals with assigning a "length," "area," or "volume" to sets, particularly in real analysis.

- For finite sets, measure is just the count of elements.
- For infinite sets, measure is more subtle.

**Key points:**
- Some infinite sets, like the set of real numbers between 0 and 1, have infinite cardinality (specifically, uncountable).
- In measure theory, the set of all real numbers between 0 and 1 has a measure (length) of 1.
- A countable set (like the natural numbers or the rationals in [0, 1]) has measure zero, even though it is infinite in cardinality.

**Example:**
- The interval (0, 1) has uncountable cardinality and measure 1.
- The set of rational numbers in (0, 1) is countably infinite, but its measure is 0.

---

**Summary:**  
- **Equicardinality** (Cantor): Two sets are the same "size" if there is a bijection between them, even if infinite.
- **Measure of infinite sets:** Assigns a notion of "size" (like length or area) to sets; some infinite sets have measure zero, while others have positive measure.

# Proof that the Set of Integers (Z) is Countable Using Bijective Mapping

## Statement

The set of all integers Z = {..., -3, -2, -1, 0, 1, 2, 3, ...} is **countable**.  
A set is countable if there exists a bijection (one-to-one and onto mapping) between the set and the set of natural numbers N = {1, 2, 3, ...}.

---

## Proof by Constructing a Bijection

We need to define a function f: N → Z that pairs every natural number with exactly one integer, and every integer with exactly one natural number.

**Construction of the bijection:**

Define the function f as follows:

- f(1) = 0  
- f(2) = 1  
- f(3) = -1  
- f(4) = 2  
- f(5) = -2  
- f(6) = 3  
- f(7) = -3  
- ... and so on.

**In general:**
- For even n:  f(n) = n / 2  
- For odd n > 1: f(n) = -((n-1)/2)

This mapping lists the integers in the order: 0, 1, -1, 2, -2, 3, -3, ...

---

## Why This is a Bijection

- **Injective (One-to-One):**  
  Every natural number n maps to a unique integer f(n), and no two different n map to the same integer.

- **Surjective (Onto):**  
  Every integer z will appear as f(n) for some n. For example:
  - If z = 0, then n = 1.
  - If z > 0, then n = 2z.
  - If z < 0, then n = -2z + 1.

So, every integer is paired with exactly one natural number, and vice versa.

---

## Conclusion

Since we have constructed an explicit bijection between the natural numbers N and the integers Z, the set of integers is **countable**.

# Probability: Closure Properties, Axioms, and Key Theorems

## Closure Properties

### Event Space

Let S be a sample space.  
An **event space** (also called an algebra or field of sets) F is a collection of subsets of S (events) such that:

1. **Closure under Complement:**  
   If A ∈ F, then Aᶜ ∈ F.

2. **Closure under Union:**  
   If A, B ∈ F, then (A ∪ B) ∈ F.

3. **Closure under Intersection:**  
   If A, B ∈ F, then (A ∩ B) ∈ F.  
   (Follows from De Morgan's laws and the other properties.)

4. **Contains S and ∅:**  
   S ∈ F, ∅ ∈ F.

---

### Field

A **field** (or algebra) of sets over S is a non-empty collection F of subsets of S such that:

- **A ∈ F ⇒ Aᶜ ∈ F**
- **A, B ∈ F ⇒ (A ∪ B) ∈ F**
- **A, B ∈ F ⇒ (A ∩ B) ∈ F** (by De Morgan's laws)

---

### Sigma Field (σ-field)

A **sigma field** (σ-field) is a field with the additional property:

- **Closure under Countable Unions:**  
  If A₁, A₂, A₃, ... ∈ F, then (⋃ₙ Aₙ) ∈ F.

- **Closure under Countable Intersections:**  
  If A₁, A₂, A₃, ... ∈ F, then (⋂ₙ Aₙ) ∈ F.
  
---

## Axioms of Probability

Given a sample space S and a σ-field F of events, a **probability measure** P satisfies:

1. **Non-negativity:**  
   For all A ∈ F, P(A) ≥ 0

2. **Normalization:**  
   P(S) = 1

3. **Countable Additivity:**  
   For any countable sequence of mutually exclusive events {A₁, A₂, ...} (Aᵢ ∩ Aⱼ = ∅ for i ≠ j),  
   P(⋃ₙ Aₙ) = Σₙ P(Aₙ)

---

## Conditional Probability

The **conditional probability** of event A given event B (with P(B) > 0) is:

P(A | B) = P(A ∩ B) / P(B)

**Example:**  
If a card is drawn from a standard deck, let A = "card is a heart", B = "card is red".  
P(A) = 13/52, P(B) = 26/52, P(A ∩ B) = 13/52  
P(A | B) = (13/52) / (26/52) = 1/2

---

## Bayes' Theorem

Bayes' Theorem relates conditional probabilities:

P(A | B) = [P(B | A) × P(A)] / P(B)

**Example:**  
Suppose 1% of a population has a disease (A), and a test is 99% accurate (P(B | A) = 0.99, P(B | Aᶜ) = 0.01).  
If a person tests positive (B), what is the probability they actually have the disease?

P(A) = 0.01,  
P(B | A) = 0.99,  
P(B | Aᶜ) = 0.01,  
P(Aᶜ) = 0.99

P(B) = P(B | A)P(A) + P(B | Aᶜ)P(Aᶜ)  
= (0.99)(0.01) + (0.01)(0.99) = 0.0198

P(A | B) = (0.99 × 0.01) / 0.0198 ≈ 0.5

---

## Law of Total Probability

If {B₁, B₂, ..., Bₙ} is a partition of S (mutually exclusive and exhaustive), then for any event A:

P(A) = Σₖ P(A | Bₖ) × P(Bₖ)

**Example:**  
Suppose a factory has 2 machines:  
- Machine 1 produces 60% of items (P(B₁) = 0.6), defect rate 2% (P(A | B₁) = 0.02)
- Machine 2 produces 40% (P(B₂) = 0.4), defect rate 5% (P(A | B₂) = 0.05)

Total probability an item is defective:  
P(A) = P(A | B₁)P(B₁) + P(A | B₂)P(B₂)  
= (0.02)(0.6) + (0.05)(0.4)  
= 0.012 + 0.02 = 0.032

---

**Summary Table**

| Concept               | Symbolic Property                                  |
|-----------------------|----------------------------------------------------|
| Closure (union)       | A, B ∈ F ⇒ (A ∪ B) ∈ F                            |
| Closure (complement)  | A ∈ F ⇒ Aᶜ ∈ F                                    |
| Sigma field           | {A₁, A₂, ...} ⊆ F ⇒ (⋃ₙ Aₙ) ∈ F                   |
| Axiom (non-negativity)| P(A) ≥ 0                                           |
| Axiom (normalization) | P(S) = 1                                           |
| Additivity            | P(⋃ₙ Aₙ) = Σₙ P(Aₙ) for disjoint events            |
| Conditional Prob.     | P(A | B) = P(A ∩ B) / P(B)                         |
| Bayes' Theorem        | P(A | B) = [P(B | A) × P(A)] / P(B)                |
| Total Probability     | P(A) = Σₖ P(A | Bₖ) × P(Bₖ)                        |
