# Lecture 20: Pascal's triangle and the binomial theorem

## Patterns

Choosing <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> elements from a set of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements to be in a combination is
equivalent to choosing <img src="/lectures/tex/bdc4fe24ac8ca702834e1744502f09d9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.83102344999999pt height=19.1781018pt/> elements from the same set to not be in the
combination. So:

<p align="center"><img src="/lectures/tex/0d3d28e87cd91ed432017a15106a23b7.svg?invert_in_darkmode&sanitize=true" align=middle width=218.45116754999998pt height=39.452455349999994pt/></p>

Let <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> be the set of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements and <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> is a fixed element of <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/>. For any <img src="/lectures/tex/12f5d867d4197d7f82644a5d84238a54.svg?invert_in_darkmode&sanitize=true" align=middle width=99.01801304999998pt height=24.65753399999998pt/>, there are <img src="/lectures/tex/eb631c86075f4ec9f0a342fb6bb50567.svg?invert_in_darkmode&sanitize=true" align=middle width=40.021136099999985pt height=29.419440600000005pt/> combinations of <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> elements of
<img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> that do not contain <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> and there are <img src="/lectures/tex/f2fe1727b676632825e0be2202b17c62.svg?invert_in_darkmode&sanitize=true" align=middle width=40.021136099999985pt height=29.419440600000005pt/> combinations of <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/>
elements of <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> that do contain <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/>. So:

<p align="center"><img src="/lectures/tex/83dfe42c2448bb2e07a340228851c42f.svg?invert_in_darkmode&sanitize=true" align=middle width=301.26691815pt height=39.452455349999994pt/></p>

**Question** The binomial coefficient <img src="/lectures/tex/55345afebb1bfd523bc03fa4f60ed4b1.svg?invert_in_darkmode&sanitize=true" align=middle width=21.621118199999987pt height=29.419440600000005pt/> is the number of ways to
choose zero things from the empty set. The value of <img src="/lectures/tex/55345afebb1bfd523bc03fa4f60ed4b1.svg?invert_in_darkmode&sanitize=true" align=middle width=21.621118199999987pt height=29.419440600000005pt/> is:

1. 0
2. 1
3. Undefined
4. None of the above

**Answer** **2** It is the top entry in Pascal's triangle.

## Binomial Theorem

<p align="center"><img src="/lectures/tex/bfbe6319bf27d2e0a42e46f69d29ae5d.svg?invert_in_darkmode&sanitize=true" align=middle width=589.59726045pt height=39.452455349999994pt/></p>
