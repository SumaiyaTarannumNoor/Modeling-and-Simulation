# Concept of Injective Function/ one to one function
An injective function (also known as a one-to-one function or injection) is a function where each element in the domain (the input set) is mapped to a unique element in the codomain (the output set). In other words, if f(x) = f(y), then x = y. 

### More Detailed Explanation

**Domain:** The set of all possible inputs for the function. <br>

**Codomain:** The set of all possible outputs of the function. <br>

**Injective Property:** An injective function ensures that no two distinct elements in the domain are mapped to the same element in the codomain. Each element in the codomain has, at most, one element in the domain that maps to it. <br>

In essence, an injective function is a function that preserves the uniqueness of elements in the domain. <br>

**Examples of Injective Functions:**
- f(x) = x + 5: (for real numbers).
- A function that maps students to their roll numbers.
- The function f = {(1, 6), (2, 7), (3, 8), (4, 9), (5, 10)}.

**Key Properties of Injective Functions:**

- **Distinct Input, Distinct Output:** If x1 ≠ x2, then f(x1) ≠ f(x2). 
- **Horizontal Line Test:** If a function's graph passes the horizontal line test (meaning any horizontal line intersects the graph at most once), then the function is injective. 
- **Left-invertible:** An injective function can be inverted from the left (meaning there exists a function g such that g(f(x)) = x).

- In mathematics, an injective function (also known as injection, or one-to-one function[1] ) is a function f that maps distinct elements of its domain to distinct elements of its codomain; that is, x1 ≠ x2 implies f(x1) ≠ f(x2) (equivalently by contraposition, f(x1) = f(x2) implies x1 = x2).
- 
- **In other words, every element of the function's codomain is the image of at most one element of its domain. The term one-to-one function must not be confused with one-to-one correspondence that refers to bijective functions, which are functions such that each element in the codomain is an image of exactly one element in the domain.**

[Reference: GeeksforGeeks – Injective Function](https://www.geeksforgeeks.org/injective-functions/) <br>

**Injective Function Definition**
Formally, a function f: A → B is said to be injective if, for all elements a1 and a2 in the domain A, such that<br>



```
 f(a1) = f(a2) implies that a1 = a2
    
    OR
    
 f(a1) ≠ f(a2) implies that a1 ≠ a2
```

**Injective Function Example**
Some more examples of Injective functions are:


  ```
    - Linear Functions: f(x) = 2x, f(x) = 5x + 5
    - Polynomial Functions: f(x) = x3 + 2x
    - Absolute Value Function: f(x) = |x|, where x in R+
  ```

![Injective Function](https://media.geeksforgeeks.org/wp-content/uploads/20231016183536/Injective-Function-1.png)

### Properties of Injective Function
There are various properties of Injecive functions, some of those are listed as follows: <br>

- For every input element in the domain of the function, there is a unique output element in the codomain.
- Injective functions are often monotonic i.e., function is either strictly increases or strictly decreases as you move along the real number line.
- An injective function does not have any critical points (i.e., points where the derivative is zero or undefined) within its domain.
- An injective function that is also surjective (onto) is called a bijective function.
- Some more properties of Injective function include:

- The composition of two injective functions is also an injective function.
   - If f: A → B and g: B → C are both injective functions, then their composition g(f(x)) is also injective.
- Two sets A and B have the same cardinality if and only if there exists an injective function from A to B and an injective function from B to A.
- If you have a function f: A → B and a subset A' of A, you can restrict the domain of f to A' to create a new function. This restricted function is still injective if f is injective on A'.

# Graph of Injective Function

One such example of an Injective Function is `f(x) = x³`, and the graph of the injective function `f(x)` is shown below:
![Injective Function Graph](https://media.geeksforgeeks.org/wp-content/uploads/20231016183534/Injective-Function-3.png)

**Graph of Injective Function**

## Horizontal Line Test

For any injective function plotted on a coordinate plane, no horizontal line can intersect the graph more than once. In other words, the graph of an injective function never has horizontal line segments that cross it more than once.

![Injective Function Horizontal Line Test](https://media.geeksforgeeks.org/wp-content/uploads/20231016183534/Injective-Function-3.png)

## Injective, Surjective and Bijective Function

The key differences between Injective, Surjective and Bijective Functions are listed in the following table:

| Property | Injective Function (One-to-One) | Surjective Function (Onto) | Bijective Function (One-to-One and Onto) |
|----------|----------------------------------|-----------------------------|------------------------------------------|
| Definition | A function where each element in the domain maps to a unique element in the codomain. | A function where the codomain is completely covered by the elements in the domain. | A function that is both injective and surjective. |
| Symbol | `f: A ↣ B` | `f: A ↠ B` | `f: A ⤖ B` |
| Unique Mapping | Each element in the domain maps to a unique element in the codomain. | Multiple elements in the domain may map to the same element in the codomain. | Each element in the domain maps to a unique element in the codomain. |
| All Elements in Domain Mapped | Yes | Not necessarily | Yes |
| All Elements in Codomain Covered | Not necessarily | Yes | Yes |
| Example | `f(x) = 2x`, `f: ℝ → ℝ` | `f(x) = x²`, `f: ℝ → ℝ⁺` | `f(x) = x`, `f: ℝ → ℝ` |

**Illustration showing Injective, Surjective and Bijective Functions**
![Difference among all three functions](https://media.geeksforgeeks.org/wp-content/uploads/20231016183533/Injective-Function-5.png)

## Solved Example on Injective Function

**Example 1:** Let's take a simple function, `f(x) = 2x`. Is this function injective?

**Solution:**  
Yes, `f(x) = 2x` is an injective function. For every distinct input, you get a distinct output.
![Injective Function Example 1](https://media.geeksforgeeks.org/wp-content/uploads/20231016183535/Injective-Function-2.png)

**Example 2:** Consider the function `f: ℝ → ℝ` defined as `f(x) = x²`. Is this function injective?

**Solution:**  
No, `f(x) = x²` is not an injective function because different inputs (e.g., `x = 2` and `x = -2`) result in the same output (`f(2) = 4`, `f(-2) = 4`).

---

**Example 3:** Consider the function `f: ℝ → ℝ` defined as `f(x) = x³`. Is this function injective?

**Solution:**  
Yes, `f(x) = x³` is an injective function. Every unique input results in a unique output.

---

## Practice Problems on Injective Function

1. Determine whether the following functions are injective:
   - `f(x) = 2x + 3`
   - `g(x) = x² - 4x + 4`
   - `k(x) = e^x`
   - `q(x) = x³ + 2x² - x`
   - `u(x) = 3x - 2`

2. Determine whether the function `h(x) = sin(x)` is injective on the interval `[0, π]`.

3. Consider the function `p(x) = 1/x` for `x ≠ 0`: Is `p(x)` an injective function?

4. Given the function `r(x) = |x|`, where `x` is a real number, is `r(x)` an injective function?

5. Consider the function `s(x) = √x` for `x ≥ 0`: Is `s(x)` injective?

6. Determine whether the function `t(x) = cos(x)` is injective on the interval `[0, 2π]`.

---

  



