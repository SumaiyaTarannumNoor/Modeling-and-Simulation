# PDF, Uncountable Sample Space, and Proofs for Continuous Distributions

## Definitions

### Probability Density Function (PDF)

A probability density function (PDF) for a continuous random variable X is a function f(x) with these properties:
1. f(x) ≥ 0 for all x in the sample space S  
2. The total area under f(x) is 1: ∫ f(x) dx over all x = 1  
3. The probability that X is between a and b is: P(a ≤ X ≤ b) = ∫ from a to b of f(x) dx

---

### Uncountable Sample Space

An uncountable sample space is a set of possible outcomes that cannot be listed in a sequence.  
Example: All real numbers between 0 and 1, written as (0, 1).

---

## Proofs That Continuous Distributions Are PDFs

For each distribution, we show:
- f(x) ≥ 0 for all x  
- The total area under f(x) is 1  

---

### 1. Uniform Distribution

Let X be uniformly distributed on [a, b] (where a < b).

PDF:  
f(x) = 1 / (b - a) for a ≤ x ≤ b  
f(x) = 0 otherwise

- f(x) is always non-negative  
- The total area: ∫ from a to b of 1 / (b - a) dx = (b - a) × [1 / (b - a)] = 1  

---

### 2. Gaussian (Normal) Distribution

Let X have mean μ and standard deviation σ > 0.

PDF:  
f(x) = 1 / (σ √(2π)) × exp( - (x - μ)² / (2σ²) ) for all x

- f(x) is always non-negative  
- The total area under f(x) for all x is known to be 1 (property of the normal distribution)

---

### 3. Exponential Distribution

Let X have rate λ > 0.

PDF:  
f(x) = λ × exp( -λx ) for x ≥ 0  
f(x) = 0 for x < 0

- f(x) is always non-negative  
- The total area: ∫ from 0 to ∞ of λ × exp( -λx ) dx = 1

---

### 4. Beta Distribution

Let X be on (0, 1) with parameters α > 0, β > 0.

PDF:  
f(x) = x^(α - 1) × (1 - x)^(β - 1) / B(α, β) for 0 < x < 1  
f(x) = 0 otherwise  
where B(α, β) is the beta function (a normalizing constant)

- f(x) is always non-negative for valid α, β  
- The total area: ∫ from 0 to 1 of f(x) dx = 1 (by definition of B(α, β))

---

### 5. Nakagami Distribution

Let X ≥ 0 follow the Nakagami distribution with shape m ≥ 0.5 and spread Ω > 0.

PDF:  
f(x) = (2 m^m / Γ(m) Ω^m) × x^(2m - 1) × exp( - (m / Ω) × x² ) for x ≥ 0  
f(x) = 0 for x < 0  
where Γ(m) is the gamma function

- f(x) is always non-negative for x ≥ 0  
- The total area: ∫ from 0 to ∞ of f(x) dx = 1 (due to the normalizing constant)

---

**Summary:**  
All five distributions above are valid probability density functions.  
They satisfy both conditions:  
1. f(x) ≥ 0 for all x in the domain  
2. ∫ f(x) dx over the entire domain equals 1
