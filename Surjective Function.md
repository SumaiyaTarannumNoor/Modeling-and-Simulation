# Concept of Surjective Function/ onto both

An onto function, also known as a surjective function, is a special type of mathematical rule that connects two sets, let's call them Set A and Set B. In an onto function, every element in Set B has a partner in Set A. This means that the function covers all the elements in Set B and there are no leftovers in Set B without a matching element in Set A.

[Reference: GeeksforGeeks – Surjective Function](https://www.geeksforgeeks.org/bijective-function/) <br>

## Onto Function Definition

```
function f: A →B to be onto, for every y in the codomain B, there exists an x in the domain A such that: f(x) = y
```

## Representation for Onto Function

The following illustration provides the representation of an example of a onto function.

![Surjective Function Diagram](https://media.geeksforgeeks.org/wp-content/uploads/20231017191730/Onto-Function-1.png) <br>

In the figure, you can see that every element in Set B connects with an element in Set A. There's no element in Set B that is left unmatched in Set A.

## Examples of Onto Function
Some examples of Onto functions are:

- Linear Functions: f(x) = 2x, g(x) = 5x + 5, etc.
- Quadratic Functions: f(x) = x2
- Polynomial Functions: f(x) = x3 - x
- Exponential Functions: f(x) = ex, g(x) = 2x, etc.
- Absolute Value Function: f(x) = |x|

**Note:** Onto Functions are codomain dependent, as the above functions are onto if codomain is R i.e., Real Numbers. 

## Properties of Onto Function

An **onto function** (also known as a *surjective function*) ensures that **every element in the codomain (set B)** is mapped to by **at least one element in the domain (set A)**.

---

### Key Concept

> In an onto function, **every element in Set B must be used at least once**.

---

### Example 1: Simple Codomain Mapping

Suppose Set B = `{1, 2, 3}`.

An onto function from Set A to Set B guarantees that **each of 1, 2, and 3 is matched** with at least one element from Set A.

---

### Example 2: Doubling Function

Consider a function:

```
f(x) = 2x
```

Let Set B = `{2, 4, 6}`.

To determine whether this function is onto, check if every element in Set B can be reached by doubling a value from Set A.

- 2 → came from `2 / 2 = 1`
- 4 → came from `4 / 2 = 2`
- 6 → came from `6 / 2 = 3`

This function is onto because **every element in Set B** is the image of some element in Set A.

You can define the right inverse of this function as:

```
f⁻¹(x) = x / 2
```

---

### Example 3: Students and Subjects

Imagine:

- Set A = Students
- Set B = Favourite Subjects

Let Set B = `{Math, Science, English}`.

If each subject is liked by **at least one student**, then the function mapping students to their favorite subjects is onto.

> We only need to describe the actual subjects liked by students — not all possible subjects — to define the codomain.

---

## Summary

- An **onto function** uses every element in the **codomain**.
- It's okay if **multiple elements from the domain** map to the same element in the codomain.
- To check if a function is onto, verify that **every codomain value has at least one pre-image** in the domain.


## Composition of Onto Function

In terms of composition, if you have two functions f: A → B and g: B → C, and both functions are onto (surjective), then their composition (g∘f): A → C will also be onto. <br>

This is because the composition of two onto functions ensures that every element in the codomain of the second function has a pre-image in the domain of the first function, and then in the codomain of the second function.

**Note:** If either of the two functions in the composition is not onto, the composition may or may not be onto. 

### Onto Function Graph
As all the elements in the codomain of a onto function have a pre-image in the domain, the graph of the onto function covers the entire codomain without leaving any gaps. Let's see some graphs of onto functions in the following illustration:

![Surjective Function Graph](https://media.geeksforgeeks.org/wp-content/uploads/20231017191729/Onto-Function-3.png) <br>

# Number of Onto Functions

Sometimes, we want to know how many functions we can create between two sets, A and B. Both sets have some elements in common. Set A has |A| elements and Set B has |B| elements. We can find the number of **onto functions** from A to B using this formula:

> **Number of onto functions** = (Total number of functions) - (Number of functions that are not onto)

### How it Works:

- The total number of functions from A to B amounts to `|B|^|A|` because each element in A can be paired with any element in B.
- To find the number of functions that aren't onto, we use the **inclusion-exclusion principle**.

---

## One-to-One and Onto Functions

Let's clear up the difference between one-to-one (injective) and onto (surjective) functions:

### One-to-One (Injective) Function

An injective function is like a careful matchmaker. It ensures that no element in Set B has more than one corresponding element in Set A. However, it does not necessarily cover all of Set B.

### Onto (Surjective) Function

A surjective function ensures that every element in Set B has a corresponding element in Set A. It **covers the entire codomain**.

For more details, refer to: [One-to-One Functions](https://www.geeksforgeeks.org/one-to-one-functions/)

---

## Onto vs Into Functions

There are several differences between onto and into functions, which are summarized in the table below:

| Property           | Onto (Surjective) Function | Into Function |
|--------------------|-----------------------------|---------------|
| **Definition**     | A function `f: A → B` is onto if for every element `b` in set B, there exists an element `a` in A such that `f(a) = b`. | A function `f: A → B` is into if there exists at least one element in B that is not an image of any element in A. |
| **Symbol**         | `↠` or `↪`                  | `↣` or `↩`    |
| **Example**        | `f: {1, 2, 3} → {a, b, c}`<br>`f(1) = a`, `f(2) = b`, `f(3) = c`<br>**f is onto** because all elements in codomain have a pre-image. | `g: {1, 2, 3} → {a, b, c, d}`<br>`g(1) = a`, `g(2) = b`, `g(3) = c`<br>**g is into** as `d` in codomain has no pre-image. |
| **Not Example**    | `h: {1, 2} → {a, b, c}`<br>`h(1) = a`, `h(2) = b`<br>**h is not onto** because `c` has no pre-image. | `k: {1, 2, 3} → {a, b, c}`<br>`k(1) = a`, `k(2) = b`, `k(3) = c`<br>**k is not into** if multiple elements in A map to the same element in B. |



# Solved Examples on Onto Functions

## Example 1: 
Consider the function f that turns numbers from {1, 2, 3} into numbers from {2, 4, 6} by doubling them, defined as f(x) = 2x. Is this an onto function?

**Solution:**

To prove that f(x) = 2x is an onto function, we need to show that for every number in {2, 4, 6}, there's a number in {1, 2, 3} that, when doubled, gives the number in question. For each number in the set {2, 4, 6}, we can easily find a number in {1, 2, 3} that works. For instance, if we take 4, we can choose 2 from {1, 2, 3} and when we double 2, we get 4. This holds true for all numbers in {2, 4, 6}, so the function is indeed onto because it covers the entire set {2, 4, 6}.

---

## Example 2: 
Let's examine the function f(x) = 2x, where x can be any real number. Is this function onto?

**Solution:**

To show that f(x) = 2x is onto, we must demonstrate that for any real number y, there exists a real number x such that f(x) = y. In this case, for any real number y, selecting x = y/2 satisfies the condition. Therefore, the function is indeed onto because it covers all real numbers.

---

## Example 3: 
Consider the function g(x) = x², where x can be any integer. Is this an onto function?

**Solution:**

No, the function g(x) = x² is not onto because it doesn't cover the entire range of integers in the codomain. For example, there is no integer x that results in g(x) = -1 because the square of any integer is non-negative. This means that some values in the codomain, like -1, are not covered by this function, so it's not onto.

---

## Example 4: 
Imagine we have the numbers 1, 2, and 3 in Set A and the numbers 2, 4, and 6 in Set B. We have a magic rule that says we double the number in Set A to get a number in Set B. So, is this magic rule an onto function? (f(x) = 2x)

**Solution:**

Yes, it sure is! We can see in the figure that every number in Set B (2, 4, and 6) has a corresponding number in Set A (1, 2, and 3). So, this is an onto function.

---

## Example 5: 
Let's take Set A as a set of shapes (Circle, Square, Triangle) and Set B as a set of colors (Red, Blue, Yellow, Green). We have a rule that links each shape in Set A with a color in Set B, such that Circle maps to Red, Square maps to Blue, and Triangle maps to Yellow. Is this rule an onto function?

**Solution:**

No, it is not an onto function. While all shapes in Set A (Circle, Square, Triangle) are associated with colors in Set B (Red, Blue, Yellow), the color Green (from Set B) has no corresponding shape in Set A. In an onto function, every element in the codomain (Set B) should have a pre-image in the domain (Set A), which is not the case here.

---

## Example 6: 
Consider Set A as a set of animal names (Lion, Tiger, Bear) and Set B as a set of sounds (Roar, Growl). We have a rule that assigns animal names in Set A to the sounds they make in Set B, such that Lion maps to Roar, Tiger maps to Growl, and Bear maps to Roar. Is this rule an onto function?

**Solution:**

Yes, it is! All the sounds in Set B (Roar, Growl) have corresponding animal names in Set A (Lion, Tiger, Bear). Therefore, this rule is an onto function.

---

# Practice Problems on Onto Functions

## Problem 1: 
Determine whether the function f: ℝ → ℝ defined by f(x) = 2x - 3 is onto.

---

## Problem 2: 
Let g: ℤ → ℤ be defined by g(n) = 3n. Is the function g onto?

---

## Problem 3: 
Consider the function h: {1, 2, 3, 4} → {5, 6, 7, 8} defined by h(1) = 5, h(2) = 6, h(3) = 7, and h(4) = 8. Is the function h onto?

---

## Problem 4: 
Determine whether the function k: ℝ → ℝ defined by k(x) = x² is onto.

---

## Problem 5: 
Let m: ℕ → ℕ be defined by m(n) = n + 1. Is the function m onto?

---

## Problem 6: 
Consider the function p: {a, b, c, d, e} → {1, 2, 3} defined by p(a) = 1, p(b) = 1, p(c) = 2, p(d) = 2, and p(e) = 3. Is the function p onto?

