## Concept of Bijective Function/mapping -> one to one correspondence -> One to one and onto both
A bijective function, also known as a bijection or one-to-one correspondence, is a function where every element in the second set (codomain) is the image of exactly one element from 
the first set (domain). In simpler terms, a bijective function establishes a perfect pairing between the two sets, ensuring that each element in the first set is paired with a unique 
element in the second set, and vice versa. 

[Reference: GeeksforGeeks – Bijective Function](https://www.geeksforgeeks.org/bijective-function/) <br>
<br>
  Bijective Function is a special type of function that represents the relationship between two sets in such a way that all elements in the domain have an image in the codomain and each
  element in the codomain has a pre-image in the domain. <br>

  Bijective Function is also called one-to-one correspondence due to the relationship between domain and codomain i.e., each element of the domain is mapped to a unique element of codomain,
  and no element of codomain remains left without pre-image. In real life, the concept of bijective functions is used in various places such as shuffling of cards, cryptography, biometrics,
  physical lock and keys, language translation, etc. In this article, we have provided a well-detailed description of the concept of the Bijective Function, including all the subtopics.

  - **What is Bijective Function?** <br>
    A bijective function also known as bijection, ensures a perfect match between two sets, typically referred to as Set A and Set B. To be considered bijective, a function must satisfy these
    two properties:

    - Injectivity: This means that each element from Set A must connect with a distinct element in Set B. In simpler terms, no two different elements from Set A can connect with the same element
      in Set B.
    - Surjectivity: The function should cover the entire Set B. This means that for every element in Set B, there should be at least one element in Set A that connects with it through the function.
      
    When a function satisfies both injectivity and surjectivity, it is classified as a bijective function, establishing a perfect one-to-one correspondence between the elements of Set A and Set B. <br>

    ![Bijective Function Diagram](https://media.geeksforgeeks.org/wp-content/uploads/20231019170642/Bijective-Function-2.png) <br>

  - **Bijective Function Examples** <br>
    Some examples of Bijective functions are:

      - **Linear Functions**:  
        `f(x) = x`, `g(x) = x + 10`, `h(x) = 5x - 5`

      - **Polynomial Functions**:  
        `f(x) = x³`, `g(x) = x³ - 1`

      - **Exponential Functions**:  
        `f(x) = e^x` where `f: ℝ → (0, ∞)`

      - **Absolute Value Function**:  
        `f(x) = x|x|`

  - **Properties of Bijective Function** <br>
    Other than subjectivity and injectivity, there are some more properties of bijective function that are listed as follows: <br>

      - **Inverse Exists**: A bijective function has an inverse function that undoes the mapping, taking an element from the codomain back to an element in the domain.
      - **Unique Inverse**: The inverse of a bijective function is unique, meaning there is only one function that reverses the mapping.
      - **Preservation of Composition**: If you compose a bijective function with another function, the composition is also bijective.
        
  - **How to Identify a Bijective Functions?**
    
## Concept of Bijective Function/mapping -> one to one correspondence -> One to one and onto both

A bijective function, also known as a bijection or one-to-one correspondence, is a function where every element in the second set (codomain) is the image of exactly one element from the first set (domain). In simpler terms, a bijective function establishes a perfect pairing between the two sets, ensuring that each element in the first set is paired with a unique element in the second set, and vice versa.

- https://www.geeksforgeeks.org/bijective-function/  
  
Bijective Function is a special type of function that represents the relationship between two sets in such a way that all elements in the domain have an image in the codomain and each element in the codomain has a pre-image in the domain.  

Bijective Function is also called one-to-one correspondence due to the relationship between domain and codomain i.e., each element of the domain is mapped to a unique element of codomain, and no element of codomain remains left without pre-image. In real life, the concept of bijective functions is used in various places such as shuffling of cards, cryptography, biometrics, physical lock and keys, language translation, etc. In this article, we have provided a well-detailed description of the concept of the Bijective Function, including all the subtopics.

### What is Bijective Function?

A bijective function also known as bijection, ensures a perfect match between two sets, typically referred to as Set A and Set B. To be considered bijective, a function must satisfy these two properties:

- **Injectivity**: This means that each element from Set A must connect with a distinct element in Set B. In simpler terms, no two different elements from Set A can connect with the same element in Set B.
- **Surjectivity**: The function should cover the entire Set B. This means that for every element in Set B, there should be at least one element in Set A that connects with it through the function.

When a function satisfies both injectivity and surjectivity, it is classified as a bijective function, establishing a perfect one-to-one correspondence between the elements of Set A and Set B.  

![Bijective Function](https://media.geeksforgeeks.org/wp-content/uploads/20231019170642/Bijective-Function-2.png)

### Bijective Function Examples

Some examples of Bijective functions are:

- Linear Functions: `f(x) = x`, `g(x) = x + 10`, `h(x) = 5x - 5`, etc.
- Polynomial Functions: `f(x) = x^3`, `g(x) = x^3 - 1`
- Exponential Functions: `f(x) = e^x`, where `f : R → (0, ∞)`
- Absolute Value Function: `f(x) = x|x|`

### Properties of Bijective Function

Other than subjectivity and injectivity, there are some more properties of bijective function that are listed as follows:

- **Inverse Exists**: A bijective function has an inverse function that undoes the mapping, taking an element from the codomain back to an element in the domain.
- **Unique Inverse**: The inverse of a bijective function is unique, meaning there is only one function that reverses the mapping.
- **Preservation of Composition**: If you compose a bijective function with another function, the composition is also bijective.

### How to Identify a Bijective Function?

To figure out if a function is bijective, there is a 2-step process:

- Injectivity  
- Surjectivity  

Let's understand these steps in brief.

---

### Step 1: Check for Injectivity

Start by imagining you have two different sets: Set A and Set B.  
In Set A, we have some elements, and in Set B, we have some other elements.

A function is injective if:

```
f(x₁) = f(x₂) ⇒ x₁ = x₂
```

Let's consider an example to understand the check for injectivity.

- **Set A**: `{1, 2, 3}`  
- **Set B**: `{a, b, c}`

Now, consider a function, which we'll call `f`, that connects elements from Set A to Set B:

```
f(1) = a  
f(2) = b  
f(3) = c
```

In the injectivity step, what you want to make sure of is that no two different items from Set A (let's say, `x₁` and `x₂`) point to the same item in Set B through the function `f`.  
So, if `f(x₁) = f(x₂)`, you must prove that `x₁ = x₂`.

In our example, since each element from Set A maps to a distinct element in Set B (like 1 → a, 2 → b, and 3 → c), there is no duplication.  

**Therefore, the function passes the injectivity test.**

---

### Step 2: Check for Surjectivity

Next, we want to ensure that no element in Set B is left without a connection from Set A.

Example:

- **Set A**: `{1, 2, 3}`  
- **Set B**: `{a, b, c}`

With the same function `f`:

```
f(1) = a  
f(2) = b  
f(3) = c
```

In the surjectivity step, we confirm that for every item `y` in Set B (like a, b, or c), there is a corresponding item `x` in Set A (1, 2, or 3) such that `f(x) = y`.  
This ensures that every item in Set B has a connection in Set A through the function `f`.

In our example, since each element in Set B (a, b, and c) has a connection to an element in Set A (1, 2, and 3), the function `f` passes the surjectivity test.

---

### Conclusion

When a function passes both the **injectivity** and **surjectivity** tests, like in our example, it's classified as a **bijective function**.

It establishes a **one-to-one relationship** between elements of Set A and Set B, without any duplication or missing connections.

- **Graph of Bijective Function** <br>
### Bijective Function: f(x) = x

As there are various different bijective functions, we can consider one such function i.e., f(x) = x. This is a linear function with slope equal to 1. Let's see its graph as following illustration.

**Graph of Bijective Function [f(x) = x]**

---

### Injective, Surjective and Bijective Function

The key differences between Injective, Surjective and Bijective Function are listed in the following table:

| Property        | Injective Function                                | Surjective Function                                               | Bijective Function                                 |
|----------------|---------------------------------------------------|-------------------------------------------------------------------|----------------------------------------------------|
| Injectivity     | Each x₁ ≠ x₂ maps to distinct f(x)               | Multiple x can map to the same f(x)                              | Each x₁ ≠ x₂ maps to distinct f(x)                |
| Surjectivity    | Not necessarily every element in codomain is covered | Every element in codomain is covered but not necessarily distinctively | Every element in codomain is covered distinctly    |
| Bijectivity     | No                                                | No                                                                | Yes                                                |
| Symbol          | ↣                                                 | ↠                                                                 | ⤖                                                 |
| Inverse Function| May not have an inverse                           | May not have an inverse                                           | Has a unique inverse                               |
| Example         | f(x) = 5x + 5 for x ∈ ℝ                           | f(x) = x³ for x ∈ ℝ                                               | f(x) = x for x ∈ ℝ                                 |

**Following illustration shows the difference between all three functions:**

---

### Read More

- Relation and Function  
- Types of Functions  
- Trigonometric Functions  

---

### Solved Examples of Bijective Functions

#### Example 1: f(x) = x (Number to Itself)

**Solution:**

Let's consider the set of natural numbers (positive whole numbers) as both Set A and Set B. In this case, you can define a bijective function like this:

```
f(1) = 1  
f(2) = 2  
f(3) = 3  
...
```

In this function, every number in Set A (natural numbers) maps to the exact same number in Set B. It's a straightforward example of a bijective function because it meets both criteria:
- Each element in Set A matches a distinct element in Set B (injectivity)
- No elements in Set B are left unmatched (surjectivity)

---

#### Example 2: Matching Students and ID Numbers

**Solution:**

Suppose you have a set of students (Set A) and a set of student ID numbers (Set B). You want to create a bijective function to pair each student with a unique student ID number. Let's say your sets look like this:

```
Set A (Students): {Alice, Bob, Carol, David}  
Set B (Student ID Numbers): {101, 102, 103, 104}
```

You can define a bijective function f as follows:

```
f(Alice) = 101  
f(Bob) = 102  
f(Carol) = 103  
f(David) = 104
```

In this example:
- Each student in Set A is matched with a distinct student ID number in Set B (injectivity)
- Every student ID number in Set B has a corresponding student in Set A (surjectivity)

---

#### Example 3: Consider the function f: ℝ → ℝ defined as f(x) = 2x + 1. Is this function bijective?

**Solution:**

- **Injectivity:**  
  Assume f(x₁) = f(x₂).  
  ⇒ 2x₁ + 1 = 2x₂ + 1  
  ⇒ x₁ = x₂  
  Therefore, the function is injective.

- **Surjectivity:**  
  For any y ∈ ℝ,  
  ⇒ y = 2x + 1 ⇒ x = (y - 1) / 2  
  Thus, every real number y has a corresponding x.

Since both injectivity and surjectivity are satisfied, the function is bijective.

---

#### Example 4: Let g: {1, 2, 3} → {a, b, c} be defined as g(1) = a, g(2) = b, and g(3) = c. Is g a bijective function?

**Solution:**

- **Injectivity:**  
  Each element in domain (1, 2, 3) maps to a distinct element in codomain (a, b, c)

- **Surjectivity:**  
  Every element in codomain is mapped from domain

Thus, g is a bijective function.

---

### Practice Problems on Bijective Function

**Problem 1:** Determine whether the following functions are Bijective:

- f(x) = 2x + 5  
- g(x) = x² + 1  
- k(x) = 5x - 2  

**Problem 2:** Consider the function f(x) = 1 / (x - 10) for x ≠ 10  
Is f(x) a bijective function?




    
    
