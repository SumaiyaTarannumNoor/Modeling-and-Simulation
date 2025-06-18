# Class Notes From Lecture 02

## Sample Space
    |
    S

List of all possible outcomes of an experiment
```
                                     |
                         Flip a coin or Roll a die
```

```
S1 = {H, T}         // S1: Sample space for flipping a coin
S2 = {HH, HT, TH, TT} // S2: Sample space for flipping two coins
S3 = {1, 2, 3, 4, 5, 6} // S3: Sample space for rolling a die
```

## Event Space
Event Space - Set of all possible subsets of the sample space.
```
        |                     |
   Power of set "S"      Power Set P(S)
```

S = {H, T}, P(S) = {{H}, {T}, {H, T}, Φ}
```
             |      |
P({H, T}) = P({H}) + P({T})          P(H) = 1/2 P({H})
                  = 1
```

p(.): Ƒ(S) -> [0, 1] 
      --------------
      ```
      |
      ```
Function: Relation between sets -> but with some special "Traits"

P({H}), P({T})
```
   |
 Singleton Set -> Set with only one element
```         
# Set Theory vs Probability Theory

| Set Theory                        | Probability Theory                   |
|----------------------------------|--------------------------------------|
|  Fundamental element: Set        | Fundamental element: event           |
|   Set ⊂ Universal set            |     Event ⊂ Sample Space            |
|           Element                 |          Outcome                   |


**Sample Space:** Depending on the Sample Space, the same problem can have multiple correct answers. 
This is called the **Bartrand Paradox**.


### What is the probability that a randomly drawn chord has a length larger than the side of the equlateral  triangle? 

### Probability of a Random Chord Longer Than the Side of an Equilateral Triangle

### Question:

**What is the probability that a randomly drawn chord in a circle has a length greater than the side of an inscribed equilateral triangle?**

---

### Understanding the Setup

An equilateral triangle is inscribed in a circle.  
We want to know the probability that a randomly drawn chord in the circle is **longer than a side** of that triangle.

Let the radius of the circle be **r**.  
Then the side of the inscribed equilateral triangle is:

\[
s = r\sqrt{3}
\]

So, a chord is **longer than the side of the triangle** if its length is **greater than** \( r\sqrt{3} \).

---

### Methods of Drawing Chords

This problem is famous for being **ambiguous** unless the method of choosing a random chord is specified. There are three common methods:

### 1. Random Endpoints on Circle
The "random endpoints" method: Choose two random points on the circumference of the circle and draw the chord joining them. To calculate the probability in question imagine the triangle rotated so its vertex coincides with one of the chord endpoints. Observe that only if the other chord endpoint lies on the arc between the endpoints of the triangle side opposite the first point, the chord is longer than a side of the triangle. The length of that arc is one third of the circumference of the circle, therefore the probability that a random chord is longer than a side of the inscribed triangle is ⁠
1
/
3
⁠. <br>

(π/3)/π = (π/3) * (1/π) = 1/3  <br>

Draw two points at random on the circle’s circumference and connect them.

![Method 1: Random Endpoints](https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/Bertrand1-figure.svg/250px-Bertrand1-figure.svg.png)

- **Probability:** 1/3

---

### 2. Random Radius and Midpoint on It

The "random radial point" method: Choose a radius of the circle, choose a point on the radius and construct the chord through this point and perpendicular to the radius. To calculate the probability in question imagine the triangle rotated so a side is perpendicular to the radius. The chord is longer than a side of the triangle if the chosen point is nearer the center of the circle than the point where the side of the triangle intersects the radius. The side of the triangle bisects the radius, therefore the probability a random chord is longer than a side of the inscribed triangle is ⁠
1
/
2
⁠. <br>

(π(r/2)) / πr = πr/2 * 1/πr = 1/2 <br>

Choose a random radius. Then select a random point along that radius as the **midpoint** of the chord.

![Method 2: Random Midpoint on Radius](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Bertrand2-figure.svg/161px-Bertrand2-figure.svg.png)

- **Probability:** 1/2

---

### 3. Random Midpoint Inside Circle

The "random midpoint" method: Choose a point anywhere within the circle and construct a chord with the chosen point as its midpoint. The chord is longer than a side of the inscribed triangle if the chosen point falls within a concentric circle of radius ⁠
1
/
2
⁠ the radius of the larger circle. The area of the smaller circle is one fourth the area of the larger circle, therefore the probability a random chord is longer than a side of the inscribed triangle is ⁠
1
/
4
⁠. <br>

(π(r/2)^2)/πr^2 = ((πr^2)/4) * (1/πr) = 1/4

Select a point **uniformly at random** inside the circle. This point becomes the **midpoint** of the chord.

![Method 3: Random Midpoint in Circle](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8b/Bertrand3-figure.svg/161px-Bertrand3-figure.svg.png)

- **Probability:** 1/4

---

### Conclusion

The answer **depends on how you define a "random chord."**  
This is known as the **Bertrand Paradox**.

| Method                             | Probability (Chord > Triangle Side) |
|------------------------------------|-------------------------------------|
| Random endpoints on circle         | 1/3                                 |
| Random midpoint on a radius        | 1/2                                 |
| Random midpoint inside the circle  | 1/4                                 |

---

### References

- [Bertrand Paradox – Wikipedia](https://en.wikipedia.org/wiki/Bertrand_paradox_(probability))

### Here 1/3, 1/2, 1/4 are all correct answers, but the "Sample spaces" are different

