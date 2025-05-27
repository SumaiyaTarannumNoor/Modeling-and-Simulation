## Probability, Set and Event (Class Notes)
- Flipa Coin <br>
  S1 = {H, T} <- Flip once <br>
  Flip Twice <br>
  S2 = {HH, HT, TH, TT} <- Probable outcomes <br>

|     | H   | T   |
|-----|-----|-----|
| H   | HH  | HT  |
| T   | TH  | TT  |


  
- To list the outcome of any probabilistic problem you need to borrow the idea from set theory.
- Die
  S = {1, 2, 3, 4, 5, 6}
  Want to see **an even** number once you roll a die
  - {2, 4, 6} <- event
  - 3/6 or 1/2 = Probability of this event
 
  Event: Seeing 3
  - {3} <- Event
  - 1/6 = Probability of this event
  
- In Probabilistic theory, we have 3 fundamental points
  - Set of Probable outcomes (Sample space)
  - Set of all possible events (Event space)
  - Set of Probability measure
- An event is nothing but a set, and it is a subset of the initial set.

   {1, 3, 5} ⊂ S = {1, 2, 3, 4, 5, 6}

   {3} ⊂ S = {1, 2, 3, 4, 5, 6}

   Roll a die to see any number

    {1, 2, 3, 4, 5, 6} ⊆ {1, 2, 3, 4, 5, 6}
  
- Event space is a subset of sample space.
- **We never calculate the probability of outcome, we calculate the probability of event.**
- All possible events = 2^cardinal of S where S = {1,2, 3, 4, 5, 6} <br>
                      = 2^6 for S <br>
                      = 64 possible outcomes for S <br>
- Coin flip once S = {H, T}  
```
F(S) = {{H}, {T}, {H, T}, ∅}
                    |     |
                 Certain  Impossible
                  Event    Event
```


-  P(w) = P({w}) <-- Probability of an event 

- By definition P(Φ) = 0
- **Power set is only possible for smaller sample space.**
- **In real-world it is not possible, because it will be too big.**
- Cardinality: number of elements in a set.
- Set of Integer, Real number and Float all are infinite.

  S ⊆ [0, 1] ∈ ℝ <br>
```
Countable              Uncountable
ℕ                       ℝ
ℤ                        
|                       | 
Discrete PMF            Continuous PDF
```

<br>
<br>

**PMF** - Probability Mass Function 

**PDF** - Probability Density Function 
<br>
<br>
ℕ - Set of Natural Numbers (All positive Integers) {0, 1, 2, 3, .....} <br>
ℤ - Set of Integers (Both Positive and Negative) {....-3, -2, -1, 0, 1, 2, 3,....} <br>
ℝ - Set of Real Numbers (Positive, Negative, Integer and Float) {..., -2, -1.5, 1, 0.5, 0, 0.5, 1, 1.5, 2, ...} <br>

- Rational Number : Countable
    Q = {p/q, where p, q ∈ ℤ, and q != 0} <br>

- **Important Proves**
  - Prove that rational number is countable. <br>
  - Prove that irrational number is uncountable.<br>

- **For Countability**
  - Concept of Bijective Function/mapping -> one to one correspondence -> One to one and onto both
  - Concept of Injective Function/ one to one function
  - Concept of Subjective Function/ onto both
  

  
