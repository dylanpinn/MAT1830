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

**Example** Let <img src="/lectures/tex/892a37aa017271610e33589d33f2b1b7.svg?invert_in_darkmode&sanitize=true" align=middle width=238.12752479999995pt height=24.65753399999998pt/> be defined by
<img src="/lectures/tex/1c9d6807786d5d3d1c49ccb5c3b6556f.svg?invert_in_darkmode&sanitize=true" align=middle width=71.52966314999999pt height=24.65753399999998pt/>.

| <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> | <img src="/lectures/tex/7997339883ac20f551e7f35efff0a2b9.svg?invert_in_darkmode&sanitize=true" align=middle width=31.99783454999999pt height=24.65753399999998pt/> |
|-----|--------|
|  0  |    0   |
|  1  |    2   |
|  2  |    4   |
|  3  |    6   |

<p align="center"><img src="/lectures/tex/6246fad45b00070836afada3c2f7cff3.svg?invert_in_darkmode&sanitize=true" align=middle width=184.4750094pt height=16.438356pt/></p>

**Example** Let <img src="/lectures/tex/b279a1f7296f643186b7be3760225978.svg?invert_in_darkmode&sanitize=true" align=middle width=72.83079209999998pt height=22.831056599999986pt/> be defined by <img src="/lectures/tex/d6f38fe1ad2efcb79c9f06a2b815210a.svg?invert_in_darkmode&sanitize=true" align=middle width=71.52966314999999pt height=24.65753399999998pt/>.

<p align="center"><img src="/lectures/tex/833a815f2530ddbd8dacd26490fdbfd9.svg?invert_in_darkmode&sanitize=true" align=middle width=118.59564749999998pt height=16.438356pt/></p>

## Arrow Diagrams

**Example** Let <img src="/lectures/tex/892a37aa017271610e33589d33f2b1b7.svg?invert_in_darkmode&sanitize=true" align=middle width=238.12752479999995pt height=24.65753399999998pt/> be defined by
<img src="/lectures/tex/1c9d6807786d5d3d1c49ccb5c3b6556f.svg?invert_in_darkmode&sanitize=true" align=middle width=71.52966314999999pt height=24.65753399999998pt/>.

![](images/L13-P50.png)

The image of <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> is <img src="/lectures/tex/3e862163e16e68fe852987cc26bcbb8e.svg?invert_in_darkmode&sanitize=true" align=middle width=71.23290569999999pt height=24.65753399999998pt/>. (So <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> is not onto.)

**Question**

Why don't we always set the codomain equal to the image?

Think about <img src="/lectures/tex/b279a1f7296f643186b7be3760225978.svg?invert_in_darkmode&sanitize=true" align=middle width=72.83079209999998pt height=22.831056599999986pt/> defined by <img src="/lectures/tex/ec35dacf7066b6b48f5edb4675cc3ab9.svg?invert_in_darkmode&sanitize=true" align=middle width=313.0362938999999pt height=26.76175259999998pt/>.

We've set the codomain to <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/> and that's fine - certainly <img src="/lectures/tex/e774126540b7b1263a6bc317a0aacb87.svg?invert_in_darkmode&sanitize=true" align=middle width=63.96115109999998pt height=24.65753399999998pt/>.

What is the image of <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/>? Hard to find and probably ugly.

Another reason is that "<img src="/lectures/tex/1023c6ff6aeb2536ae58d75211c2c6fa.svg?invert_in_darkmode&sanitize=true" align=middle width=49.314959099999996pt height=22.648391699999998pt/> functions", for
example, make a nice class to consider.

**Question** What set of ordered pairs does <img src="/lectures/tex/a7a0af87a865b67ae3c11fdc6dbc5893.svg?invert_in_darkmode&sanitize=true" align=middle width=132.19152044999998pt height=24.65753399999998pt/> defined by <img src="/lectures/tex/45d56c128bbdcd4414f84c155351f718.svg?invert_in_darkmode&sanitize=true" align=middle width=69.86299979999998pt height=26.76175259999998pt/> correspond to?

<p align="center"><img src="/lectures/tex/bddaaf43bbdfb86ff8e84aa281afafb6.svg?invert_in_darkmode&sanitize=true" align=middle width=184.4750094pt height=16.438356pt/></p>

**Question** Which of the following sets of ordered pairs correspond to
functions from <img src="/lectures/tex/3f4efc607a90eb7ad1e9c1db443d0a13.svg?invert_in_darkmode&sanitize=true" align=middle width=55.70781314999999pt height=24.65753399999998pt/> to <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>?

<p align="center"><img src="/lectures/tex/11408117bb12fd1f77b02a6c7b0d122f.svg?invert_in_darkmode&sanitize=true" align=middle width=131.4896649pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/1d49d15e0f23b01ca8f927476b342258.svg?invert_in_darkmode&sanitize=true" align=middle width=176.1872112pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/0a404eeb747898148e4b4be711f89bb9.svg?invert_in_darkmode&sanitize=true" align=middle width=221.14945875pt height=16.438356pt/></p>

- **A.** Just T
- **B.** S and T
- **C.** T and U
- **D.** All of them

**Answer** Not **S** - it doesn't have an ordered pair with coordinate 1. Not
**U** - it has two ordered pairs with first coordinate 2. But **T** is fine. So
**A**.

## Square: <img src="/lectures/tex/1023c6ff6aeb2536ae58d75211c2c6fa.svg?invert_in_darkmode&sanitize=true" align=middle width=49.314959099999996pt height=22.648391699999998pt/>

**Examples.**

The squaring functions square <img src="/lectures/tex/560e6a06958749f60c6766986c0d9557.svg?invert_in_darkmode&sanitize=true" align=middle width=60.04558724999999pt height=26.76175259999998pt/> with domain <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>, codomain
<img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>, and pairs

<p align="center"><img src="/lectures/tex/8197a8f2c7f612dee5fabb513aeb0894.svg?invert_in_darkmode&sanitize=true" align=middle width=117.750897pt height=18.312383099999998pt/></p>

which form what we usually call the _plot_ of the squaring function.

The image of this function (the set of _y_ values) is the set
<img src="/lectures/tex/5b86d9e34af75573e30b3476fa54e0f7.svg?invert_in_darkmode&sanitize=true" align=middle width=28.698746999999987pt height=27.705869399999983pt/> of real numbers <img src="/lectures/tex/97724efe1d61e77783b76251d3ae68dc.svg?invert_in_darkmode&sanitize=true" align=middle width=25.570741349999988pt height=21.18721440000001pt/>.

## sqrt: <img src="/lectures/tex/7090bd21ba30b4ea6d6d2ef5a8c33889.svg?invert_in_darkmode&sanitize=true" align=middle width=66.96341684999999pt height=27.705869399999983pt/>

The square root function sqrt <img src="/lectures/tex/af4e2c5c66a242a3cf6d446a28206d59.svg?invert_in_darkmode&sanitize=true" align=middle width=67.1917125pt height=24.995338500000003pt/> with domain <img src="/lectures/tex/83384b0778f2b99b99ec51e21c52a786.svg?invert_in_darkmode&sanitize=true" align=middle width=28.698746999999987pt height=27.705869399999983pt/>, codomain <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>, and pairs

<p align="center"><img src="/lectures/tex/b0f1ef01f61e92232f1654858e28495d.svg?invert_in_darkmode&sanitize=true" align=middle width=201.04990125pt height=17.4097869pt/></p>

The image of this function (the set of <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> values) is the set <img src="/lectures/tex/83384b0778f2b99b99ec51e21c52a786.svg?invert_in_darkmode&sanitize=true" align=middle width=28.698746999999987pt height=27.705869399999983pt/>.

## cube: <img src="/lectures/tex/1023c6ff6aeb2536ae58d75211c2c6fa.svg?invert_in_darkmode&sanitize=true" align=middle width=49.314959099999996pt height=22.648391699999998pt/>

The cubing function cube <img src="/lectures/tex/8acb1ceffc413f625fcb8f21a19cf8fe.svg?invert_in_darkmode&sanitize=true" align=middle width=60.04558724999999pt height=26.76175259999998pt/> with domain <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>, codomain
<img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>, and pairs

<p align="center"><img src="/lectures/tex/1f7d0a96e2aaf22606d121520465f049.svg?invert_in_darkmode&sanitize=true" align=middle width=117.750897pt height=18.312383099999998pt/></p>

The image of this function is the whole of the codomain <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>, so it is
onto.

## Question 13.1

Which of the following rules define functions?

- For each non-empty set <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/> of natural numbers, let <img src="/lectures/tex/a74295660f0f66b340fbf614a573656f.svg?invert_in_darkmode&sanitize=true" align=middle width=33.63022904999998pt height=24.65753399999998pt/> be the least member
  of <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/>.
  - Yes
- For each set <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> of real numbers between 0 and 1, let <img src="/lectures/tex/889ff6fa193255b40c2616db0e8ec14f.svg?invert_in_darkmode&sanitize=true" align=middle width=36.12445814999999pt height=24.65753399999998pt/> be the least
  member of <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/>.
  - No - <img src="/lectures/tex/7888ba85a39432e0ea44939415edb116.svg?invert_in_darkmode&sanitize=true" align=middle width=211.49610735pt height=27.77565449999998pt/> is not
    defined.
- For each circle <img src="/lectures/tex/9b325b9e31e85137d1de765f43c0f8bc.svg?invert_in_darkmode&sanitize=true" align=middle width=12.92464304999999pt height=22.465723500000017pt/> in the <img src="/lectures/tex/7392a8cd69b275fa1798ef94c839d2e0.svg?invert_in_darkmode&sanitize=true" align=middle width=38.135511149999985pt height=24.65753399999998pt/> plane, let <img src="/lectures/tex/1f0fa7f228a3fb21e110b4ec8e98cf50.svg?invert_in_darkmode&sanitize=true" align=middle width=35.18118614999999pt height=24.65753399999998pt/> be the minimum distance
  from <img src="/lectures/tex/9b325b9e31e85137d1de765f43c0f8bc.svg?invert_in_darkmode&sanitize=true" align=middle width=12.92464304999999pt height=22.465723500000017pt/> to the x axis.
  - Yes
- For a pair <img src="/lectures/tex/b9ebfc5473fcab62450e73397e4d098b.svg?invert_in_darkmode&sanitize=true" align=middle width=32.92809134999999pt height=22.465723500000017pt/> of sets of real numbers let <img src="/lectures/tex/8f9fd6afd1f0938554507f13d279d3af.svg?invert_in_darkmode&sanitize=true" align=middle width=53.418997499999996pt height=24.65753399999998pt/> be the smallest set
  which has both <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> and <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> as subsets.
  - Yes (depending on your interpretation of "smallest").
  - <img src="/lectures/tex/0963ab8b11419f30877d1473450f8e77.svg?invert_in_darkmode&sanitize=true" align=middle width=119.22353519999999pt height=24.65753399999998pt/>.
- For a pair <img src="/lectures/tex/91daf49251530f97b200e0d037770c11.svg?invert_in_darkmode&sanitize=true" align=middle width=32.92809134999999pt height=22.465723500000017pt/> of sets of real numbers let <img src="/lectures/tex/fc03a4bfe7b2b0596f882fcf8551539e.svg?invert_in_darkmode&sanitize=true" align=middle width=51.64961669999999pt height=24.65753399999998pt/> be the largest set which
  is a subset of both <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> and <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/>.
  - Yes (depending on your interpretation of "largest").
  - <img src="/lectures/tex/901e596f03626ad34269cf7be6d68aac.svg?invert_in_darkmode&sanitize=true" align=middle width=117.45415439999998pt height=24.65753399999998pt/>.

## 13.2 Arrow notation

If <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> is a function with domain <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> and codomain <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> we write:

<p align="center"><img src="/lectures/tex/12e56f867353753c65849f53a3a8b4ee.svg?invert_in_darkmode&sanitize=true" align=middle width=74.70864225pt height=14.611878599999999pt/></p>

and we say that <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> is from <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> to <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/>.

**Question 13.2** Which of the following functions can be defined on the whole
of <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>, so that the function values also lie in <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>? (In other
words, which can be <img src="/lectures/tex/1023c6ff6aeb2536ae58d75211c2c6fa.svg?invert_in_darkmode&sanitize=true" align=middle width=49.314959099999996pt height=22.648391699999998pt/> functions?)

- <img src="/lectures/tex/6177db6fc70d94fdb9dbe1907695fce6.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=26.76175259999998pt/> - Yes
- <img src="/lectures/tex/f6de2147c9c203a34732c0a74515a98c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.454371649999997pt height=27.77565449999998pt/> - No undefined for <img src="/lectures/tex/2f3c8b04b987706450f80c5b0c2619d4.svg?invert_in_darkmode&sanitize=true" align=middle width=39.53182859999999pt height=21.18721440000001pt/>
- <img src="/lectures/tex/38f816ed8d9782e71ecfd164e77c5150.svg?invert_in_darkmode&sanitize=true" align=middle width=43.41333149999999pt height=24.65753399999998pt/> - No - undefined for <img src="/lectures/tex/4ffda6d041407624a670ed82e95de8c8.svg?invert_in_darkmode&sanitize=true" align=middle width=39.53182859999999pt height=21.18721440000001pt/> (because <img src="/lectures/tex/42c302b7b723c671fd35a91bd18d0c62.svg?invert_in_darkmode&sanitize=true" align=middle width=46.067244299999984pt height=21.839370299999988pt/> for all <img src="/lectures/tex/f037e157fa0f871ed85ce6ac327e7201.svg?invert_in_darkmode&sanitize=true" align=middle width=41.35830434999999pt height=22.648391699999998pt/>.
- <img src="/lectures/tex/dd14e4011870d961fb4f5097866d9009.svg?invert_in_darkmode&sanitize=true" align=middle width=23.09366069999999pt height=24.995338500000003pt/> - No - undefined for <img src="/lectures/tex/949d3fe7fc31d082be4b1fbe3eb4ac89.svg?invert_in_darkmode&sanitize=true" align=middle width=39.53182859999999pt height=21.18721440000001pt/>
- <img src="/lectures/tex/ab581c2338e8b905c9c8076866561329.svg?invert_in_darkmode&sanitize=true" align=middle width=23.09365905pt height=24.995338500000003pt/> - Yes

## 13.3 One-to-one functions

A function <img src="/lectures/tex/8dd51bd31b996f66d97db221486b70a5.svg?invert_in_darkmode&sanitize=true" align=middle width=77.19148799999999pt height=22.831056599999986pt/> is _one-to-one_ if for each <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> in the range of
<img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> there is only one <img src="/lectures/tex/ef2a9dc0d2e528efe607b65aaed55845.svg?invert_in_darkmode&sanitize=true" align=middle width=44.39481419999999pt height=22.465723500000017pt/> such that <img src="/lectures/tex/1058016037635271ffc2e170bf1e40de.svg?invert_in_darkmode&sanitize=true" align=middle width=62.564690099999986pt height=24.65753399999998pt/>.

For example, the function cube(x) is one-to-one because each real number <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> is
the cube of exactly one real number <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/>.

The function square: <img src="/lectures/tex/1023c6ff6aeb2536ae58d75211c2c6fa.svg?invert_in_darkmode&sanitize=true" align=middle width=49.314959099999996pt height=22.648391699999998pt/> is _not_ one-to-one
because the real number 1 is the square of two different real numbers, 1 and -1.
(In fact each real <img src="/lectures/tex/1160cbd2c82a490a8f9f6fd9ef657806.svg?invert_in_darkmode&sanitize=true" align=middle width=38.78604674999999pt height=21.18721440000001pt/> is the square of two different real numbers,
<img src="/lectures/tex/f9e91f01119bbc22d42cb9c4d73a3e56.svg?invert_in_darkmode&sanitize=true" align=middle width=22.34789699999999pt height=21.79901790000001pt/> and <img src="/lectures/tex/df76aa85a92d9c1edb5053582d8b53a9.svg?invert_in_darkmode&sanitize=true" align=middle width=35.133331199999986pt height=21.79901790000001pt/>)

On the other hand, square: <img src="/lectures/tex/7090bd21ba30b4ea6d6d2ef5a8c33889.svg?invert_in_darkmode&sanitize=true" align=middle width=66.96341684999999pt height=27.705869399999983pt/> _is_
one-to-one because each real number <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> in <img src="/lectures/tex/5b86d9e34af75573e30b3476fa54e0f7.svg?invert_in_darkmode&sanitize=true" align=middle width=28.698746999999987pt height=27.705869399999983pt/> is the square
of only one real number in <img src="/lectures/tex/5b86d9e34af75573e30b3476fa54e0f7.svg?invert_in_darkmode&sanitize=true" align=middle width=28.698746999999987pt height=27.705869399999983pt/>, namely <img src="/lectures/tex/f9e91f01119bbc22d42cb9c4d73a3e56.svg?invert_in_darkmode&sanitize=true" align=middle width=22.34789699999999pt height=21.79901790000001pt/>.

The last example shows that the domain of a function is an important part of its
description, because changing the domain can change the properties of the
function.

**Question** Is the function pictured below one-to-one?

![](images/L13-P100.png)

Yes

**Question** Is the function pictured below one-to-one?

![](images/L13-P101.png)

No. <img src="/lectures/tex/2b2e09aa15ed7d1e2ba808bbcb63c1b1.svg?invert_in_darkmode&sanitize=true" align=middle width=100.66221824999998pt height=24.65753399999998pt/>.

## 13.4 Proving a function is one-to-one

There is an equivalent way of phrasing the definition of one-to-one: a function
<img src="/lectures/tex/8dd51bd31b996f66d97db221486b70a5.svg?invert_in_darkmode&sanitize=true" align=middle width=77.19148799999999pt height=22.831056599999986pt/> is one-to-one when, for all <img src="/lectures/tex/13779be22d85173e4d1ff498bf53cf38.svg?invert_in_darkmode&sanitize=true" align=middle width=75.84460619999999pt height=22.465723500000017pt/>,

<p align="center"><img src="/lectures/tex/74c7c3f7f19ec09b3836a4a0c93e2c11.svg?invert_in_darkmode&sanitize=true" align=middle width=180.86743289999998pt height=16.438356pt/></p>

This can be useful for proving that some functions are or are not one-to-one.

**Example.** The function <img src="/lectures/tex/b279a1f7296f643186b7be3760225978.svg?invert_in_darkmode&sanitize=true" align=middle width=72.83079209999998pt height=22.831056599999986pt/> given by <img src="/lectures/tex/2ec31cc76dbabda99d2c26345318b7ac.svg?invert_in_darkmode&sanitize=true" align=middle width=99.84006285pt height=24.65753399999998pt/> is one-to-one because:

<p align="center"><img src="/lectures/tex/462332e13ce51040a2ce2f3b2ce79228.svg?invert_in_darkmode&sanitize=true" align=middle width=100.66221825pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/b84b17cbf1bed854321194039e0a1262.svg?invert_in_darkmode&sanitize=true" align=middle width=149.5202478pt height=13.059335849999998pt/></p>
<p align="center"><img src="/lectures/tex/81fd44e659abb66bcd03feb5b14d9d11.svg?invert_in_darkmode&sanitize=true" align=middle width=92.07753389999999pt height=13.059335849999998pt/></p>
<p align="center"><img src="/lectures/tex/92b159c894777b6c297ea162622f6ba4.svg?invert_in_darkmode&sanitize=true" align=middle width=75.63911519999999pt height=9.54335085pt/></p>

**Example.** The function <img src="/lectures/tex/b279a1f7296f643186b7be3760225978.svg?invert_in_darkmode&sanitize=true" align=middle width=72.83079209999998pt height=22.831056599999986pt/> given by <img src="/lectures/tex/dc13dd657f2526f2ad0d1a3b63307511.svg?invert_in_darkmode&sanitize=true" align=middle width=98.99531399999998pt height=26.76175259999998pt/> is not one-to-one because <img src="/lectures/tex/6f44fa9c3c20190c656dae2457c4c0ef.svg?invert_in_darkmode&sanitize=true" align=middle width=73.74432944999998pt height=24.65753399999998pt/> and <img src="/lectures/tex/671bdb51c88878bef02eea8fd1d54964.svg?invert_in_darkmode&sanitize=true" align=middle width=60.95889524999999pt height=24.65753399999998pt/> and so

<p align="center"><img src="/lectures/tex/79359937d4af8982a7eec8c25a0e6afb.svg?invert_in_darkmode&sanitize=true" align=middle width=96.34717619999999pt height=16.438356pt/></p>

**Question** Which of the following functions are one-to-one?

<img src="/lectures/tex/533e8cb6a5543f381cc3baf9a77108f4.svg?invert_in_darkmode&sanitize=true" align=middle width=71.91755504999998pt height=22.831056599999986pt/> defined by <img src="/lectures/tex/1058016037635271ffc2e170bf1e40de.svg?invert_in_darkmode&sanitize=true" align=middle width=62.564690099999986pt height=24.65753399999998pt/> where <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> is the
least even integer greater than <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/>.

<img src="/lectures/tex/f8d223a437accd5c3b9579ea4685d855.svg?invert_in_darkmode&sanitize=true" align=middle width=70.53049904999999pt height=22.648391699999998pt/> defined by <img src="/lectures/tex/a17143cb0af27e53a35c12eec430ae48.svg?invert_in_darkmode&sanitize=true" align=middle width=138.70409189999998pt height=26.76175259999998pt/>.

- **A.** Neither
- **B.** Just _f_
- **C.** Just _g_
- **D.** Both

**Examples for _f_**: <img src="/lectures/tex/7a512827e8807f99e15dcf784a410152.svg?invert_in_darkmode&sanitize=true" align=middle width=402.2827908pt height=24.65753399999998pt/>

**Examples for _g_**: <img src="/lectures/tex/40aa1b3960794dd9971a8021cb07127e.svg?invert_in_darkmode&sanitize=true" align=middle width=376.39799175pt height=24.65753399999998pt/>

**Answer:** _f_ isn't one-to-one because <img src="/lectures/tex/7daacf31e94b15c1ad603b0f1faf6a0a.svg?invert_in_darkmode&sanitize=true" align=middle width=83.561742pt height=24.65753399999998pt/>. _g_ is one-to-one. So
**C**.

**Example** Show <img src="/lectures/tex/f8d223a437accd5c3b9579ea4685d855.svg?invert_in_darkmode&sanitize=true" align=middle width=70.53049904999999pt height=22.648391699999998pt/> defined by <img src="/lectures/tex/5f87327375af7b8f7464a5a854b49187.svg?invert_in_darkmode&sanitize=true" align=middle width=138.70409189999998pt height=26.76175259999998pt/> is one-to-one?

Suppose that

<p align="center"><img src="/lectures/tex/00cc9129025a641df7a697f845802c35.svg?invert_in_darkmode&sanitize=true" align=middle width=97.8881079pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/8cafd59f79e1296b2935cfd8704d9ad6.svg?invert_in_darkmode&sanitize=true" align=middle width=209.0179146pt height=18.312383099999998pt/></p>
<p align="center"><img src="/lectures/tex/64d3a7a1e99aca81ebbcb1a107ff3fce.svg?invert_in_darkmode&sanitize=true" align=middle width=151.5752007pt height=18.312383099999998pt/></p>
<p align="center"><img src="/lectures/tex/1539a76928b8f635ac1274bc977f6617.svg?invert_in_darkmode&sanitize=true" align=middle width=112.07732744999998pt height=13.059335849999998pt/></p>
<p align="center"><img src="/lectures/tex/a893e1a316d29c1cc327f2ca154c0a6f.svg?invert_in_darkmode&sanitize=true" align=middle width=54.634613550000005pt height=9.54335085pt/></p>

This shows that _g_ is one-to-one.
