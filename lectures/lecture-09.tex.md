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

Prove that, for each integer $n \geq 3$, the sum of the angles of a convex
_n_-sided polygon is $180n - 360$ degrees.

**Polygon:** A 2D shape with straight sides.

**Convex:** Any line between two corners is completely inside the shape.

The sum of the angles of a convex 3-sided polygon is 180 degrees so the
statement is true for $n=3$.

The sum of the angles of a convex 4-sided polygon is 460 degrees so the
statement is true for $n=4$.

The sum of the angles of a convex 5-sided polygon is 540 degrees so the
statement is true for $n=5$.
