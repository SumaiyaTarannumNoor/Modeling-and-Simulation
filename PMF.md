# PMF, Countable Sample Space, and Proofs for Discrete Distributions

## Definitions

### Probability Mass Function (PMF)

A **probability mass function (PMF)** is a function p(x) defined for a discrete random variable X such that:

1. p(x) ≥ 0 for all x ∈ S  
2. Σₓ p(x) = 1, where the sum is over all x in the sample space S  
3. p(x) = P(X = x)

---

### Countable Sample Space

A **countable sample space** S is a set of possible outcomes that is either finite or countably infinite (can be listed as s₁, s₂, s₃, ...).  
Example: S = {0, 1, 2, ...} or S = {heads, tails}

---

## Proofs That Discrete Distributions Are PMFs

For each distribution, we show:

- p(x) ≥ 0 for all x  
- Σₓ p(x) = 1

---

### 1. Binomial Distribution

Let X ~ Binomial(n, p), n ∈ ℕ, 0 < p < 1

**PMF:**  
p(x) = C(n, x) p^x (1-p)^(n-x), for x = 0, 1, ..., n

- p(x) ≥ 0 since all terms are non-negative
- Σₓ=0ⁿ C(n, x) p^x (1-p)^(n-x) = (p + 1 - p)^n = 1^n = 1

Thus, the binomial is a valid PMF.

---

### 2. Poisson Distribution

Let X ~ Poisson(λ), λ > 0

**PMF:**  
p(x) = (λ^x e^(-λ)) / x!, for x = 0, 1, 2, ...

- p(x) ≥ 0 for all x
- Σₓ=0^∞ (λ^x e^(-λ)) / x! = e^(-λ) Σₓ=0^∞ (λ^x / x!) = e^(-λ) e^λ = 1

Thus, the Poisson is a valid PMF.

---

### 3. Geometric Distribution

Let X ~ Geometric(p), 0 < p < 1

**PMF:**  
p(x) = (1-p)^(x-1) p, for x = 1, 2, 3, ...

- p(x) ≥ 0 for all x
- Σₓ=1^∞ (1-p)^(x-1) p = p Σₖ=0^∞ (1-p)^k = p × 1/(1-(1-p)) = p/p = 1

Thus, the geometric is a valid PMF.

---

### 4. Discrete Uniform Distribution

Let X be uniformly distributed on {a, a+1, ..., b}, where b ≥ a

**PMF:**  
p(x) = 1 / (b - a + 1), for x = a, a+1, ..., b

- p(x) ≥ 0 for all x
- Number of possible values = (b - a + 1)  
  Σₓ=a^b [1 / (b - a + 1)] = (b - a + 1) × [1 / (b - a + 1)] = 1

Thus, the discrete uniform is a valid PMF.

---
**Summary:**  
All four distributions satisfy the PMF properties: non-negativity and sum to 1 over a countable sample space.
