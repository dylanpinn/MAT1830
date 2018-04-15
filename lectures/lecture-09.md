# Lecture 9: Mathematical Induction

## Induction - why should you care?

- Induction is vital technique for proofs in CS and maths.
- It's particularly useful for proving things about:
  - algorithms that involve recursion (loops)
  - strings and similar data structures
  - trees and similar data structures.
- Understanding induction can help you better understand these recursive
  algorithms and recursive data structures.

### Question

Prove that, for each integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/84872ff6fed071721ce0bdbc5e6a80be.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>, the sum of the angles of a convex
_n_-sided polygon is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5059c99d14044330c0aeb90b0cbb5b79.svg?invert_in_darkmode" align=middle width=79.27342499999999pt height=21.18732pt/> degrees.

**Polygon:** A 2D shape with straight sides.

**Convex:** Any line between two corners is completely inside the shape.

The sum of the angles of a convex 3-sided polygon is 180 degrees so the
statement is true for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/aa6905d780872f0007f642420d7a2d9c.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>.

The sum of the angles of a convex 4-sided polygon is 460 degrees so the
statement is true for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/180bde3f581b83f9e0205ff90404a62d.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>.

The sum of the angles of a convex 5-sided polygon is 540 degrees so the
statement is true for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/1527cca23083db7049d5be6e93eb2b93.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>.
