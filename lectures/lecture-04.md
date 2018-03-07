# Lecture 4 - Logic

## Question 4.1

Which of the following are propositions?

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/fe38cd50ce053e4d42c61e3274903966.svg?invert_in_darkmode" align=middle width=152.237415pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6b5b444e8c773bb701dfcc280d02839f.svg?invert_in_darkmode" align=middle width=62.55711pt height=12.602732999999999pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e547b88bb92debf1a2f66447e5b41395.svg?invert_in_darkmode" align=middle width=160.50259499999999pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/deb28fedbdb5470d49cb87f7e79a1b6d.svg?invert_in_darkmode" align=middle width=62.55711pt height=12.602732999999999pt/></p>

## 4.1 Connectives ∧, ∨ and ¬

Define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/0b6832fb78c570edf56af766820951ee.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=18.265169999999976pt/> by the following _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/cb78b0cacb6c794f10bfd9e6761398ac.svg?invert_in_darkmode" align=middle width=34.463385pt height=18.265169999999976pt/> |
|-----|-----|-------------|
|  T  |  T  |     T       |
|  T  |  F  |     F       |
|  F  |  T  |     F       |
|  F  |  F  |     F       |

Define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6007a29527e0ec27309d7829f5754d08.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=18.265169999999976pt/> by the _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/82385103bdbbacdc2e6ac03827c9e3e1.svg?invert_in_darkmode" align=middle width=34.463385pt height=18.265169999999976pt/> |
|-----|-----|------------|
|  T  |  T  |     T      |
|  T  |  F  |     T      |
|  F  |  T  |     T      |
|  F  |  F  |     F      |

Define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/23bf728170c10d0449b90561f827623a.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=14.155350000000013pt/> by the _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/eea93f3519d9141e9e02f11439b4588d.svg?invert_in_darkmode" align=middle width=19.229595000000003pt height=14.155350000000013pt/> |
|-----|----------|
|  T  |  F       |
|  F  |  T       |

### Notation

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/47b61b8ae5cc2531c99faa80efb9d429.svg?invert_in_darkmode" align=middle width=59.360895pt height=11.415524999999999pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4f65d921512dd7f5ca052dd36d71b665.svg?invert_in_darkmode" align=middle width=127.07804999999999pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/057ed779a82f90fbcefdc229d6a994b4.svg?invert_in_darkmode" align=middle width=56.621235pt height=11.415524999999999pt/></p>

### Order of precedence

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/23bf728170c10d0449b90561f827623a.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=14.155350000000013pt/> has precedence over the other connectives.

For example, <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8aedfee9c431ef7507b4706570dfad7f.svg?invert_in_darkmode" align=middle width=45.422354999999996pt height=18.265169999999976pt/> means <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/51e44209e800e5c2fe7deec52d7ee52f.svg?invert_in_darkmode" align=middle width=58.207875pt height=24.65759999999998pt/>.

### Example

Find the truth tables for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e0f736f33ed56c4985d37ee5f4270bb9.svg?invert_in_darkmode" align=middle width=73.386555pt height=24.65759999999998pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/9c613ce6e53ed8a3e3fef0fee2f7a473.svg?invert_in_darkmode" align=middle width=112.70720999999999pt height=24.65759999999998pt/>

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode" align=middle width=7.873024500000003pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/81c2563ebeefaddb896d1a3bb032ed9c.svg?invert_in_darkmode" align=middle width=34.065735pt height=18.265169999999976pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e0f736f33ed56c4985d37ee5f4270bb9.svg?invert_in_darkmode" align=middle width=73.386555pt height=24.65759999999998pt/> |
|-----|-----|-----|------------|----------------------|
|  T  |  T  |  T  |     T      |     T                |
|  T  |  T  |  F  |     T      |     T                |
|  T  |  F  |  T  |     T      |     T                |
|  T  |  F  |  F  |     F      |     F                |
|  F  |  T  |  T  |     T      |     F                |
|  F  |  T  |  F  |     T      |     F                |
|  F  |  F  |  T  |     T      |     F                |
|  F  |  F  |  F  |     F      |     F                |

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/cb78b0cacb6c794f10bfd9e6761398ac.svg?invert_in_darkmode" align=middle width=34.463385pt height=18.265169999999976pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/fe2c89613a52d32d41c1e538565c74d6.svg?invert_in_darkmode" align=middle width=34.408275pt height=18.265169999999976pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/3598d0808113f23ad5732168d6f9d2c7.svg?invert_in_darkmode" align=middle width=112.36467000000002pt height=24.65759999999998pt/> |
|-------------|-------------|---------------------------------|
|     T       |     T       |     T                           |
|     T       |     F       |     T                           |
|     F       |     T       |     T                           |
|     F       |     F       |     F                           |
|     F       |     F       |     F                           |
|     F       |     F       |     F                           |
|     F       |     F       |     F                           |
|     F       |     F       |     F                           |

### Question

What must the truth values of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> be to make <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8aea9d21cb9999c106a25c324ea10ef6.svg?invert_in_darkmode" align=middle width=95.70198pt height=24.65759999999998pt/> true?

#### Answer

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> mus be T because otherwise the expression would evaluate to F.

The expression is then <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e94a1c158ac42fbbb39b3d99d1809c27.svg?invert_in_darkmode" align=middle width=96.598095pt height=24.65759999999998pt/>.

To make the bracketed part evaluate to T we need <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7c601dca1d618f40701705fccce94d94.svg?invert_in_darkmode" align=middle width=33.879615pt height=14.155350000000013pt/> to be T.

Or in other words we need <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> to be F.

## 4.2 Implication

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/326cc2e6a08a4500d254abe8364ed5fd.svg?invert_in_darkmode" align=middle width=93.24215999999998pt height=14.611871999999998pt/></p>

We define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/777d001ea1ec5971b67bb546ed760f97.svg?invert_in_darkmode" align=middle width=16.438455000000005pt height=14.155350000000013pt/> by the _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/1bb32e35386650ec2cb2c08b31689d4a.svg?invert_in_darkmode" align=middle width=41.769420000000004pt height=14.155350000000013pt/> |
|-----|-----|------------|
|  T  |  T  |     T      |
|  T  |  F  |     F      |
|  F  |  T  |     T      |
|  F  |  F  |     T      |

### Question 4.2

f: "foo"

b: "bar"

"if foo, then bar" <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5a6381a07ead798b73e5313a8f8c1c33.svg?invert_in_darkmode" align=middle width=42.44295pt height=22.831379999999992pt/>

"bar if foo" <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5a6381a07ead798b73e5313a8f8c1c33.svg?invert_in_darkmode" align=middle width=42.44295pt height=22.831379999999992pt/>

"bar only if foo" <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/435ef8bab55f81e4a243dcd9e97e861b.svg?invert_in_darkmode" align=middle width=42.44295pt height=22.831379999999992pt/>

"foo implies not bar" <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/42a8b64dba15fc20d7f20ad8d8e1d039.svg?invert_in_darkmode" align=middle width=53.401754999999994pt height=22.831379999999992pt/>

"foo is sufficient for bar" <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5a6381a07ead798b73e5313a8f8c1c33.svg?invert_in_darkmode" align=middle width=42.44295pt height=22.831379999999992pt/>

"foo is necessary for bar" <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/435ef8bab55f81e4a243dcd9e97e861b.svg?invert_in_darkmode" align=middle width=42.44295pt height=22.831379999999992pt/>

## 4.3 Other connectives

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/dc206a20a3b0a9f67233d896ee4464fc.svg?invert_in_darkmode" align=middle width=153.881475pt height=14.611871999999998pt/></p>

We define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/b58782f9626978f96019fe94cf45b6d6.svg?invert_in_darkmode" align=middle width=30.137250000000005pt height=14.155350000000013pt/> by the _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/15be2f2cfc73b7b58e1f1da086ae9188.svg?invert_in_darkmode" align=middle width=64.600305pt height=14.155350000000013pt/> |
|-----|-----|------------|
|  T  |  T  |     T      |
|  T  |  F  |     F      |
|  F  |  T  |     F      |
|  F  |  F  |     T      |

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/306c79e8ba7717d65ca87df0824dcf48.svg?invert_in_darkmode" align=middle width=115.66235999999999pt height=14.611855499999999pt/></p>

We define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/779c14dfccad801470c7c47650e3816d.svg?invert_in_darkmode" align=middle width=10.045695000000002pt height=22.758779999999973pt/> by the _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a307d6949671b53a202e506ce2a35ef1.svg?invert_in_darkmode" align=middle width=33.55011pt height=22.758779999999973pt/> |
|-----|-----|------------|
|  T  |  T  |     F      |
|  T  |  F  |     T      |
|  F  |  T  |     T      |
|  F  |  F  |     F      |

### Question 4.3

"Would you like coffee or tea?" - exclusive

"Oranges or lemons are a good source of vitamin C." - inclusive

"He will arrive in a minute or two." - exclusive

### Question

What must the truth values of _p_ and _q_ be to make <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/cf5f802d9c39d1ab63ce172f2bbbe7d8.svg?invert_in_darkmode" align=middle width=79.83426pt height=24.65759999999998pt/> false?

#### Answer

For <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a85cfb9815e34e839e29c28d1e967ffa.svg?invert_in_darkmode" align=middle width=79.83426pt height=24.65759999999998pt/> to be F we need <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> to be T and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a307d6949671b53a202e506ce2a35ef1.svg?invert_in_darkmode" align=middle width=33.55011pt height=22.758779999999973pt/>
to be F.

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> must be T and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/91182d725456845783e9a1b90f9ddfd0.svg?invert_in_darkmode" align=middle width=37.51143pt height=22.758779999999973pt/> must be F.

This means that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> must be T (checking both cases for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/>).

## 4.4 Remarks

1. The symbols <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/0b6832fb78c570edf56af766820951ee.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=18.265169999999976pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6007a29527e0ec27309d7829f5754d08.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=18.265169999999976pt/> are intentionally similar to the symbols <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7ab28e3f02aa13bfc8dd97fe3b995ecb.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=18.265169999999976pt/>
   and $\cup$ for set intersection and union because
   $$x \in A \cap B  \Leftrightarrow (x \in A) \land (x \in B)$$
   $$x \in A \cup B  \Leftrightarrow (x \in A) \lor (x \in B)$$
2. The "exclusive or" function <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/779c14dfccad801470c7c47650e3816d.svg?invert_in_darkmode" align=middle width=10.045695000000002pt height=22.758779999999973pt/> is written XOR in some programming
   languages.
3. If we write 0 for F and 1 for T then <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/779c14dfccad801470c7c47650e3816d.svg?invert_in_darkmode" align=middle width=10.045695000000002pt height=22.758779999999973pt/> becomes the function:

  | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a307d6949671b53a202e506ce2a35ef1.svg?invert_in_darkmode" align=middle width=33.55011pt height=22.758779999999973pt/> |
  |-----|-----|------------|
  |  1  |  1  |     0      |
  |  1  |  0  |     1      |
  |  0  |  1  |     1      |
  |  0  |  0  |     0      |

  This is known as the "mod 2 sum", because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4df4b8eb78fe163016659638ef3e0990.svg?invert_in_darkmode" align=middle width=96.803355pt height=21.18732pt/> (mod 2)
