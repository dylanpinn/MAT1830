# Lecture 13: Functions

**Functions - why should you care?**

The concept of a function is extremely important in both computer science and
maths.

- Functions (subroutines) in programming are closely related to functions in the
  mathematical sense.
- In the case of functional programming languages (e.g. Lisp, Haskell, Rust)
  they are exactly functions in the mathematical sense.
- Functions are used to define a lot of important concepts in maths and
  theoretical computer science.

A function can be thought of as a "black box" which accepts inputs and, for each
input, produces a single output.

- Each input produces exactly one output. (Always the same output for a given
  input).
- Input = Domain
- Output = Codomain

**Remember:** The domain and codomain are part of the function and must always
be defined.

## 13.1 Defining functions via sets

Formally we represent a function <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> as a set <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> of possible inputs, a set <img src="/lectures/tex/91aac9730317276af725abd8cef04ca9.svg?invert_in_darkmode&sanitize=true" align=middle width=13.19638649999999pt height=22.465723500000017pt/>
so that every output of <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> is guaranteed to be in <img src="/lectures/tex/91aac9730317276af725abd8cef04ca9.svg?invert_in_darkmode&sanitize=true" align=middle width=13.19638649999999pt height=22.465723500000017pt/>, and a set of (input,
output) pairs from <img src="/lectures/tex/973dfebc244ccaeeae26a8e1d1a6b1fc.svg?invert_in_darkmode&sanitize=true" align=middle width=48.196244249999985pt height=22.465723500000017pt/>. The vital property of a function is that each
input gives exactly one output.

A function <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> consists of a _domain_ <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/>, a _codomain_ <img src="/lectures/tex/91aac9730317276af725abd8cef04ca9.svg?invert_in_darkmode&sanitize=true" align=middle width=13.19638649999999pt height=22.465723500000017pt/>, and a set of
ordered pairs from <img src="/lectures/tex/973dfebc244ccaeeae26a8e1d1a6b1fc.svg?invert_in_darkmode&sanitize=true" align=middle width=48.196244249999985pt height=22.465723500000017pt/> which has exactly one ordered pair <img src="/lectures/tex/7392a8cd69b275fa1798ef94c839d2e0.svg?invert_in_darkmode&sanitize=true" align=middle width=38.135511149999985pt height=24.65753399999998pt/> for
each <img src="/lectures/tex/ef2a9dc0d2e528efe607b65aaed55845.svg?invert_in_darkmode&sanitize=true" align=middle width=44.39481419999999pt height=22.465723500000017pt/>.

When <img src="/lectures/tex/0cd27d4708cd735f6ea469dc3debed0e.svg?invert_in_darkmode&sanitize=true" align=middle width=35.83526759999999pt height=24.65753399999998pt/> is in this set we write <img src="/lectures/tex/4b0486af10b11c8d72996ffd69db4416.svg?invert_in_darkmode&sanitize=true" align=middle width=60.264428399999986pt height=24.65753399999998pt/>.

The set of <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> values occurring in these pairs in the _image_ of <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/>.

Note that the image of a function is always a subset of its codomain but they
may or may not be equal.

If the image of a function is equal to its codomain, we say that the function is
_onto_.

Formally, a function consists of a domain <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/>, a codomain <img src="/lectures/tex/91aac9730317276af725abd8cef04ca9.svg?invert_in_darkmode&sanitize=true" align=middle width=13.19638649999999pt height=22.465723500000017pt/>, and a set of
ordered pairs from <img src="/lectures/tex/973dfebc244ccaeeae26a8e1d1a6b1fc.svg?invert_in_darkmode&sanitize=true" align=middle width=48.196244249999985pt height=22.465723500000017pt/> which has exactly one ordered pair <img src="/lectures/tex/7392a8cd69b275fa1798ef94c839d2e0.svg?invert_in_darkmode&sanitize=true" align=middle width=38.135511149999985pt height=24.65753399999998pt/> for
each <img src="/lectures/tex/ef2a9dc0d2e528efe607b65aaed55845.svg?invert_in_darkmode&sanitize=true" align=middle width=44.39481419999999pt height=22.465723500000017pt/>.

The set of <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> values occurring in these ordered pairs is called the _image_ of
the function.

The image is always a subset of the codomain but they may not be equal. If they
are equal we say the function is _onto_.

"<img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> is a function with domain <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> and codomain <img src="/lectures/tex/91aac9730317276af725abd8cef04ca9.svg?invert_in_darkmode&sanitize=true" align=middle width=13.19638649999999pt height=22.465723500000017pt/>" is shortened to <img src="/lectures/tex/137b3a92c7aec21e4297abdb43e89c89.svg?invert_in_darkmode&sanitize=true" align=middle width=77.19148799999999pt height=22.831056599999986pt/>.
