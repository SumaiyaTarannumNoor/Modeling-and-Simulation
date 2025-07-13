# Bertrand Paradox
## Book reference 
- **Papoulis,Page 8-9, Example 1-3**
- The Bertrand paradox refers to a problem in probability where different, seemingly reasonable methods for randomly selecting a chord within a circle lead to different probabilities for the chord being longer than the side of an inscribed equilateral triangle.
- This highlights how the method of generating random variables is crucial for well-defined probability problems.
- In economics, the Bertrand paradox describes a situation in Nash equilibrium where two firms, competing on price, end up setting prices equal to marginal cost, a result counterintuitive to the typical expectation of price above marginal cost in a duopoly.

## In Probability

- Bertrand's paradox in probability arises when trying to determine the probability that a randomly selected chord in a circle is longer than the side of an inscribed equilateral triangle.
- The paradox lies in the fact that different, equally valid-seeming methods for defining "randomly selected chord" lead to different probabilities (1/2, 1/3, or 1/4).
- One method selects a random point on the radius and draws a perpendicular chord.
- Another method selects two random points on the circle and connects them.
- A third method chooses a random midpoint within the circle.
- These different methods highlight that the probability result is sensitive to the random selection process.

## In Economics

- The Bertrand paradox in economics refers to a duopoly (two-firm market) where firms compete on price.
- It is a "paradox" because, in a duopoly, one might expect firms to collude or set prices above marginal cost.
- However, the Bertrand model shows that in equilibrium, both firms will set their price equal to marginal cost, leading to the same outcome as perfect competition.
- This result assumes that firms can perfectly meet demand at any price, and that consumers will always buy from the firm with the lower price.
- The paradox highlights the extreme sensitivity of the Bertrand model to its assumptions, particularly concerning demand and the ability to meet it.

[Reference:](https://web.mit.edu/tee/www/bertrand/problem.html) <br>
## The Problem
Determine the probability that a random chord of a circle of unit radius has a length greater than the square root of 3, the side of an inscribed equilateral triangle.

## The Solution

### Solution for 1/2

![1/2](https://web.mit.edu/tee/www/bertrand/onehalf.gif)

- Answer : 1/2 <br>
    -By symmetry, we can reduce the problem to examining only the chord with a chosen direction.
    
    Then, the factor which decides whether the chord is smaller or greater than the square root of 3 is the distance to the center of the circle.
    The chord is greater than the square root of 3 if and only if its distance to the center of the circle is smaller than 1/2.
    
    So, the probability is 1/2 .
    
    Here is an animation that explains the way we can get to this answer:
     ![1/2 Proof Image](https://web.mit.edu/tee/www/bertrand/onehalfmath.gif)

  ### Solution for 1/3

  ![1/3](https://web.mit.edu/tee/www/bertrand/onethird.gif)

  - Answer : 1/3
     - We generate the random chord by randomly choosing its end on the circle.

      By symmetry, we can fix one of the ends. The moving end generates a chord with a length greater than the square root of 3 when it's on the portion away from the fixed end, with length one third of the circle length.
      
      So, the probability that the random chord has a length greater than the square root of 3 is 1/3.
      
      Here is an animation that explains the way we can get to this answer:
        ![1/3 Proof Image](https://web.mit.edu/tee/www/bertrand/onethirdmath.gif)

  ### Solution for 1/4

  ![1/4](https://web.mit.edu/tee/www/bertrand/onefourth.gif)

  


  
