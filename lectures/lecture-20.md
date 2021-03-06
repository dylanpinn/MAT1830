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

<p align="center"><img src="/lectures/tex/85b86511c68bf8844dd1b1fc8878bf23.svg?invert_in_darkmode&sanitize=true" align=middle width=605.5790763pt height=39.452455349999994pt/></p>

**Questions**

**20.1** Substitute <img src="/lectures/tex/f41f51aeb9528548f1409a3a0ec61640.svg?invert_in_darkmode&sanitize=true" align=middle width=39.53182859999999pt height=21.18721440000001pt/> and <img src="/lectures/tex/1bff0e95fdc5dc5190c88c0a706c22ac.svg?invert_in_darkmode&sanitize=true" align=middle width=51.571479299999986pt height=21.18721440000001pt/> into the statement of the binomial theorem.
What does this tell you about the rows of Pascal's triangle?

<p align="center"><img src="/lectures/tex/596f81897bdb3bff69864934259a1ddc.svg?invert_in_darkmode&sanitize=true" align=middle width=328.78040415pt height=39.452455349999994pt/></p>

The alternating sum of the terms in each row is zero except the first row.

**20.2** Find a pattern in the sums of the rows in Pascal's triangle. Prove your
pattern holds using the binomial theorem. Also prove it holds by considering the
powerset of a set.

Substitute <img src="/lectures/tex/c0b1d0f5f29d8b5366ed5e02cd7e21ac.svg?invert_in_darkmode&sanitize=true" align=middle width=85.62375689999999pt height=21.18721440000001pt/> into the binomial theorem to get

<p align="center"><img src="/lectures/tex/e4c364ca347182f51adb8122b43ccbfd.svg?invert_in_darkmode&sanitize=true" align=middle width=354.2578347pt height=39.452455349999994pt/></p>

If <img src="/lectures/tex/b983eb66dd4d9c6d4ed67a6a0e10f6a8.svg?invert_in_darkmode&sanitize=true" align=middle width=55.82562149999999pt height=24.65753399999998pt/> then <img src="/lectures/tex/26e3c37d8fad22cf96e666136d358211.svg?invert_in_darkmode&sanitize=true" align=middle width=85.55175749999998pt height=24.65753399999998pt/>. We count all subsets by counting those with
0 elements, then those with 1 element, then those with 2 elements and so on, up
to those with <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements.

**Question** The number of terms that I would get if I expanded <img src="/lectures/tex/bbb3ccb1acd21aea9cb1cf8272b7ebe1.svg?invert_in_darkmode&sanitize=true" align=middle width=77.1310056pt height=26.76175259999998pt/>
using the binomial theorem is:

1. 2016
2. 2017
3. 2018
4. 2019

**Answer** **4** There are terms for every power of <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> from <img src="/lectures/tex/3c58ce81e368ae900ae3b6ec3ac03351.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=26.76175259999998pt/> to
<img src="/lectures/tex/bf063ec04552dfced0fc285f3ed1e8f2.svg?invert_in_darkmode&sanitize=true" align=middle width=35.60517509999999pt height=26.76175259999998pt/>. There are 2019 numbers in <img src="/lectures/tex/982ac470071289a94d1dd3ad5fa95e80.svg?invert_in_darkmode&sanitize=true" align=middle width=125.11406654999999pt height=24.65753399999998pt/>.

## Inclusion-exclusion

In general, if <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> and <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> are finite sets then we have:

<p align="center"><img src="/lectures/tex/8a5e71a83673acae6196054ef8432407.svg?invert_in_darkmode&sanitize=true" align=middle width=212.0258085pt height=16.438356pt/></p>

We can also set that if <img src="/lectures/tex/b9ebfc5473fcab62450e73397e4d098b.svg?invert_in_darkmode&sanitize=true" align=middle width=32.92809134999999pt height=22.465723500000017pt/> and <img src="/lectures/tex/9b325b9e31e85137d1de765f43c0f8bc.svg?invert_in_darkmode&sanitize=true" align=middle width=12.92464304999999pt height=22.465723500000017pt/> are sets then we have

<p align="center"><img src="/lectures/tex/73dd6a01bc659ea9ab6d99ed99f6eab2.svg?invert_in_darkmode&sanitize=true" align=middle width=536.11144785pt height=16.438356pt/></p>

**Question**

**20.3** Use inclusion-exclusion to work out how many numbers in the set <img src="/lectures/tex/a453c9b2acdd093c0f7e1db7584b4a7e.svg?invert_in_darkmode&sanitize=true" align=middle width=85.84467209999998pt height=24.65753399999998pt/> are divisible by 2 or 3 or 5.

Let <img src="/lectures/tex/f6fac43e354f1b2ca85658091df26df1.svg?invert_in_darkmode&sanitize=true" align=middle width=20.17129784999999pt height=22.465723500000017pt/> be the set of numbers in <img src="/lectures/tex/606c2bbcb7b3a60bf2da1295368a3f72.svg?invert_in_darkmode&sanitize=true" align=middle width=85.84467209999998pt height=24.65753399999998pt/> that are divisible by 2.

Let <img src="/lectures/tex/1baf02c4f56309cbe1b8eb8152c8a0c3.svg?invert_in_darkmode&sanitize=true" align=middle width=20.17129784999999pt height=22.465723500000017pt/> be the set of numbers in <img src="/lectures/tex/606c2bbcb7b3a60bf2da1295368a3f72.svg?invert_in_darkmode&sanitize=true" align=middle width=85.84467209999998pt height=24.65753399999998pt/> that are divisible by 3.

Let <img src="/lectures/tex/0a1a10f401bdabe662baedc9639fffc7.svg?invert_in_darkmode&sanitize=true" align=middle width=20.17129784999999pt height=22.465723500000017pt/> be the set of numbers in <img src="/lectures/tex/606c2bbcb7b3a60bf2da1295368a3f72.svg?invert_in_darkmode&sanitize=true" align=middle width=85.84467209999998pt height=24.65753399999998pt/> that are divisible by 5.

We want <img src="/lectures/tex/31507cb836ce5fb488426f804e414067.svg?invert_in_darkmode&sanitize=true" align=middle width=108.64147799999998pt height=24.65753399999998pt/> which is

<p align="center"><img src="/lectures/tex/2b690371dd77b95000772351f44a8a1d.svg?invert_in_darkmode&sanitize=true" align=middle width=527.7163105499999pt height=16.438356pt/></p>

These are much easier sets to count. For example, <img src="/lectures/tex/4615e6129c350835418469f33718ec5d.svg?invert_in_darkmode&sanitize=true" align=middle width=69.38356919999998pt height=24.65753399999998pt/> counts the
numbers that are divisible by 10 (of which there are 10)

So <img src="/lectures/tex/fb13a002e31b208fa5807c8b132bc588.svg?invert_in_darkmode&sanitize=true" align=middle width=388.09281884999996pt height=24.65753399999998pt/>.
