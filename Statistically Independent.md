# Statistically Independent Events

## Definition

Two events A and B are **statistically independent** if the occurrence of one does not affect the probability of the occurrence of the other.  
Mathematically, A and B are independent if:  
P(A ∩ B) = P(A) × P(B)

This concept can be extended to more than two events. A set of events {A1, A2, ..., An} are mutually independent if every subset of these events is independent.

---

## Properties

1. **Symmetry:**  
   If A and B are independent, so are B and A.

2. **Conditional Probability:**  
   If A and B are independent and P(B) > 0, then P(A | B) = P(A)

3. **Complement:**  
   If A and B are independent, then A and B-complement are also independent.

4. **Extension to Multiple Events:**  
   For three events A, B, C to be mutually independent:  
   - P(A ∩ B) = P(A) × P(B)  
   - P(A ∩ C) = P(A) × P(C)  
   - P(B ∩ C) = P(B) × P(C)  
   - P(A ∩ B ∩ C) = P(A) × P(B) × P(C)

---

## Example

Suppose you toss a fair coin and roll a fair die.

Let event A: "Coin shows heads"  
Let event B: "Die shows a 4"

- P(A) = 1/2 (two possible coin outcomes)
- P(B) = 1/6 (six possible die outcomes)
- P(A ∩ B): The probability of both A and B occurring is (1/2) × (1/6) = 1/12

Since P(A ∩ B) = P(A) × P(B), the events A and B are independent.

---

## Proof

Let us prove that for independent events, P(A | B) = P(A):

By definition:  
P(A | B) = P(A ∩ B) / P(B)  
If A and B are independent, then P(A ∩ B) = P(A) × P(B), so:  
P(A | B) = [P(A) × P(B)] / P(B) = P(A)

This shows that knowing B occurred does not change the probability of A.

---

## Popular Mathematical Questions and Solutions

### 1. Question: If P(A) = 0.5, P(B) = 0.4, and A and B are independent, what is P(A ∩ B)?

**Solution:**  
P(A ∩ B) = P(A) × P(B) = 0.5 × 0.4 = 0.2

---

### 2. Question: If A and B are independent and P(A) = 0.6, P(B) = 0.3, what is the probability that at least one occurs?

**Solution:**  
P(A ∪ B) = P(A) + P(B) - P(A ∩ B)  
P(A ∩ B) = P(A) × P(B) = 0.6 × 0.3 = 0.18  
P(A ∪ B) = 0.6 + 0.3 - 0.18 = 0.72

---

### 3. Question: If A and B are independent and P(A) = 0.7, what is P(B | A)?

**Solution:**  
P(B | A) = P(A ∩ B) / P(A) = [P(A) × P(B)] / P(A) = P(B)

---

### 4. Question: Suppose you draw one card from a deck. Let A be the event "card is a heart," B be "card is a king." Are A and B independent?

**Solution:**  
- P(A) = 13/52 = 1/4 (hearts)
- P(B) = 4/52 = 1/13 (kings)
- P(A ∩ B) = 1/52 (king of hearts)
- P(A) × P(B) = (1/4) × (1/13) = 1/52

Since P(A ∩ B) = P(A) × P(B), events are independent.

---

**Summary:**  
Statistical independence means the occurrence of one event does not affect the probability of another. This property is critical in many areas of probability and statistics.
