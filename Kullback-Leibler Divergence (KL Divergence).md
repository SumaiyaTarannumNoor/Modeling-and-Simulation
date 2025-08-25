# KL Divergence (Kullback-Leibler Divergence)

KL Divergence is a statistical measure of how one probability distribution, **Q**, diverges from a reference distribution, **P**. Also known as *relative entropy*, it quantifies the "information loss" or "extra surprise" incurred when using the model's distribution (Q) to approximate the true distribution (P).

**Key properties include:**
- **Non-negativity:** KL divergence is always zero or positive, with zero divergence only when the distributions are identical.
- **Non-symmetry:** The order of P and Q matters; KL divergence is not symmetric.

---

## What it Represents

- **Information Loss:** KL divergence measures how many additional bits are needed to encode data using the approximate distribution (Q) instead of the true distribution (P).
- **Model Evaluation:** In machine learning, it helps evaluate how well a model's predicted distribution matches the actual data distribution.
- **Statistical Difference:** It quantifies the difference between two probability distributions, indicating how dissimilar they are.

> _See also: [Understanding KL Divergence | TDS Archive - Medium](https://medium.com)_

---

## Key Properties

- **Non-Negativity:** KL divergence is always zero or positive. It is zero if and only if the two distributions are identical.
- **Asymmetry:** The Kullback-Leibler divergence is not symmetric; D(P||Q) is not necessarily equal to D(Q||P). The "cost" of using Q instead of P is different from using P instead of Q.

> _Reference: [Kullback-Leibler Divergence - GeeksforGeeks](https://www.geeksforgeeks.org)_


---

## Formula

The KL divergence from P to Q is given by the formula:

\[
D_{KL}(P||Q) = \sum P(x)\log \left(\frac{P(x)}{Q(x)}\right)
\]

Where:
- **P(x):** Probability of outcome x in the true distribution
- **Q(x):** Probability of outcome x in the approximated distribution
- The summation is over all possible outcomes.

> _Reference: [Kullback-Leibler divergence - University of Iowa](https://myweb.uiowa.edu)_

---

## Applications

- **Machine Learning:** Used in model evaluation, regularization (e.g., in neural networks), and Bayesian updates.
- **Data Science:** Helps in understanding how different models or hypotheses deviate from observed data.
- **Information Theory:** Used in data compression and efficient message transmission.
- **Computer Vision:** Applied to measure the distortion between images in steganography and for tasks like knowledge distillation.
