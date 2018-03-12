# Lecture 5: Tautologies and logical equivalence

## 5.1 Tautologies and contradictions

A sentence in propositional logic:

* a _tautology_ if it has value **T** under all interpretations;
* a _contradiction_ if it has value **F** under all interpretations.

### Example

"If Morne Morkel is limping and AB de Villiers is looking grumpy, then South
Africa are losing the test match."

_p_: "Morne Morkel is limping."

_q_: "AB de Villiers is looking grumpy."

_r_: "South Africa are losing the test match."

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/58ea668c2e08d2ed57b3689fa87b83a2.svg?invert_in_darkmode" align=middle width=80.69226pt height=16.438356pt/></p>

_p_ could be **T** or **F**, _q_ could be **T** or **F**, and _r_ could be **T**
or **F**.

So there are <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/3250fc6b3ffe5a19821621be77cb8325.svg?invert_in_darkmode" align=middle width=94.97697000000001pt height=21.18732pt/> ways to assign truth values to this
statement.

That's why there would be eight rows in the truth table.

### Question

How many ways are there to assign truth values to the following statement?

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/71a519ce7e771f681cfa583137b773a7.svg?invert_in_darkmode" align=middle width=323.21355pt height=16.438356pt/></p>

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/38fb1a02f4196214db6430a00e492f5d.svg?invert_in_darkmode" align=middle width=159.81685499999998pt height=11.9634735pt/></p>

### Question 5.1

There are two possibilities for each of the variables and this gives a total of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/dad699c3115a5a0d58164c0f910a56e9.svg?invert_in_darkmode" align=middle width=142.372065pt height=21.839399999999983pt/> possibilities.

## 5.2 Logical equivalence

Why should <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2857c19c3ea1f88d3e6309be566b7046.svg?invert_in_darkmode" align=middle width=41.769420000000004pt height=14.155350000000013pt/> mean the same as <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/346c404d6b9937eed5e0180470ae431b.svg?invert_in_darkmode" align=middle width=27.157680000000003pt height=14.155350000000013pt/>?

"If you train hard, then you'll finish the marathon."

"You won't train hard or you'll finish the marathon."

"If that's a lion, then we're dead."

"That's not a lion or we're dead."

The expression:

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/05e948bc1ee6b5ba467f4558ed78077f.svg?invert_in_darkmode" align=middle width=198.15675pt height=39.8871pt/></p>

is actually the same as the expression <p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/911121f44fb86cab5f5ba8e45e25a5d7.svg?invert_in_darkmode" align=middle width=120.662025pt height=16.438356pt/></p>, but
the second expression is nicer.

Similarly <p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/af57f530016787cb4467a16356be6578.svg?invert_in_darkmode" align=middle width=259.60605pt height=16.438356pt/></p>
is logically equivalent to <p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/cf9ba349ce9223c81132dd7536d119dc.svg?invert_in_darkmode" align=middle width=18.887055pt height=10.2739725pt/></p>

## Useful equivalences

The following equivalences are the most frequently used in this "algebra of
logic".

### Equivalence law

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/aeb6975cde084274d82842a4e5f691a5.svg?invert_in_darkmode" align=middle width=191.06175pt height=16.438356pt/></p>

### Implication law

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a1479b48ea1f45f94733d62b0264cff3.svg?invert_in_darkmode" align=middle width=121.894575pt height=16.438356pt/></p>

### Double Negation law

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/24ab40837e08e2315e0d9504feabe51f.svg?invert_in_darkmode" align=middle width=60.376635pt height=10.819611pt/></p>

### Idempotent laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6933bd24f2c4992891eb5b1f7f2b570c.svg?invert_in_darkmode" align=middle width=64.993995pt height=12.3288pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/acb2ef2a0b4f306a6d95ac0f6252d2d5.svg?invert_in_darkmode" align=middle width=64.993995pt height=12.3288pt/></p>

### Commutative laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/c6a162e8f636a5b2ef434fe810a1699c.svg?invert_in_darkmode" align=middle width=90.84438pt height=12.3288pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/09b400121795ba111198d4b90bee5a66.svg?invert_in_darkmode" align=middle width=90.84438pt height=12.3288pt/></p>

### Associative laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/c5870688cb178c7552f0739380964b76.svg?invert_in_darkmode" align=middle width=168.69105pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e76068caf6d67b264c70b0cea3bea6eb.svg?invert_in_darkmode" align=middle width=168.69105pt height=16.438356pt/></p>

### Distributive laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/730f71b85090502d898026ba393cb0ad.svg?invert_in_darkmode" align=middle width=208.01054999999997pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4af3447d8ef158142b0a3f15dca2b7a8.svg?invert_in_darkmode" align=middle width=208.01054999999997pt height=16.438356pt/></p>

### De Morgans's laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/763744e054b67e0fd90e25a8cfa97c76.svg?invert_in_darkmode" align=middle width=162.07752pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/3319787d90b2e4ae4fe9a47769157225.svg?invert_in_darkmode" align=middle width=162.07752pt height=16.438356pt/></p>

### Identity laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e679b1dd1caa4250242d6bc426b19305.svg?invert_in_darkmode" align=middle width=68.612775pt height=14.429217pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8bf1e29289492e541a9ff46d5b5ebc98.svg?invert_in_darkmode" align=middle width=69.577365pt height=14.429217pt/></p>

### Annihilation laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8b281df2ff37c059451dc4951b7869fb.svg?invert_in_darkmode" align=middle width=74.160735pt height=14.429217pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/51d6c3275c0b26df727a82a534b4a095.svg?invert_in_darkmode" align=middle width=72.231555pt height=14.429217pt/></p>

### Inverse laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f1b956ea1bb30f0f84edd0ae1885e364.svg?invert_in_darkmode" align=middle width=93.32168999999999pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/1e9478c12ee8d150e7677413bac9acce.svg?invert_in_darkmode" align=middle width=92.35709999999999pt height=16.438356pt/></p>

### Absorption laws

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2f5d6887caa69c6ea1a87e2a5faa3e47.svg?invert_in_darkmode" align=middle width=82.054665pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a086c78223b65e9771b70e7ffebdc50c.svg?invert_in_darkmode" align=middle width=82.054665pt height=16.438356pt/></p>
