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

The sum of the angles of a convex 6-sided polygon is 720 degrees so the
statement is true for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/600979b5b6b2bf60cc96e3ebb182b871.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>.

**Solution:** Let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode" align=middle width=35.48919pt height=24.65759999999998pt/> be the statement "the sum of the angles of a convex
_n_-sided polygon is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5059c99d14044330c0aeb90b0cbb5b79.svg?invert_in_darkmode" align=middle width=79.27342499999999pt height=21.18732pt/> degrees.

_First we show that the statement is true for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/aa6905d780872f0007f642420d7a2d9c.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>_

**Base Step.** The sum of the angles of a convex 3-sided polygon is 180 degrees
so _P(3)_ is true.

_Now we should that **if** P(k) is true for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/06fd55f23448993b291b8cbd005d3ba5.svg?invert_in_darkmode" align=middle width=39.212250000000004pt height=22.831379999999992pt/>, **then**
<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode" align=middle width=63.008055pt height=24.65759999999998pt/> is also true._

**Induction step.**

- Suppose that _P(k)_ is true.
- Any convex _(k+1)_-sided polygon can be "split" into a _k_-sided polygon and a
  triangle.
- The sum of the angles of a triangle is 180 degrees.
- The sum of the angles of a _k_-sided polygon is 180_k_ - 360 degrees (by
  P(k)).
- So the sum of the angles of a <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8efe9ff4209e9ab5e98c62cd39393f0e.svg?invert_in_darkmode" align=middle width=50.171220000000005pt height=24.65759999999998pt/>-sided polygon is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2a26d47ce7679c39100cd4b9b300c152.svg?invert_in_darkmode" align=middle width=277.511355pt height=24.65759999999998pt/> degrees. So <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode" align=middle width=63.008055pt height=24.65759999999998pt/> is true.

_This proves the original statement!_
