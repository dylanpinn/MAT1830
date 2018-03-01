# Lecture 2 - Divisors and Primes

**Definitiion:** An _integer_ is a "whole number". It may be positive or
negative or zero.

## 2.1 Primes

A positive integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/85d11c1326adcab7f42dd2e11a15feb6.svg?invert_in_darkmode" align=middle width=38.407545000000006pt height=21.18732pt/> is a prime if its only positive integer divisors are
1 and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/>.

**Fundamental Theorem of Arithmetic:**

_Each integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2e0be7ab9f7f002587464f2558250bdb.svg?invert_in_darkmode" align=middle width=25.570875pt height=21.18732pt/> can be expressed in exactly one way, up to order, as a
product of primes._

**Example:**

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a4e21697bfbb92d03862cdfdd7df937f.svg?invert_in_darkmode" align=middle width=139.72563pt height=11.9634735pt/></p>

and this is the only product of primes which equals <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/505b66e1b09c0768b24d75a07ca0b389.svg?invert_in_darkmode" align=middle width=24.657765pt height=21.18732pt/>.

## 2.2 Recognising primes

If an integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/64a72b8c9c5b8f75fec2f7108bae6bc2.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/> has a divisor, it has a divisor <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8997bc199c09dda0023c357ca8445b7f.svg?invert_in_darkmode" align=middle width=40.917195pt height=24.99551999999999pt/>, because
for any divisor <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ba08ddb1d5bf689d2aee11f0a495022e.svg?invert_in_darkmode" align=middle width=54.17247pt height=24.99551999999999pt/> we also have the divisor <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/1af293634edec3587edb297c499394d2.svg?invert_in_darkmode" align=middle width=26.775375000000004pt height=24.65759999999998pt/>, which is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/28dc3cc94458a926eac7587d57d0ea4b.svg?invert_in_darkmode" align=middle width=40.917195pt height=24.99551999999999pt/>.

```
assign a the value 2.
assign prime the value T.
while a <= sqrt{n} and prime = T
  if a divides n
    give prime the value F
  else
    increase the value of a by 1.
```

## 2.3 Finding divisors

This algorithm also finds a prime divisor of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>. Either the least <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/acd2c745e074d1e7b747918849ab19d7.svg?invert_in_darkmode" align=middle width=54.17247pt height=24.99551999999999pt/> which divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>, or, if we do not find a divisor among the <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/acd2c745e074d1e7b747918849ab19d7.svg?invert_in_darkmode" align=middle width=54.17247pt height=24.99551999999999pt/>, <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> itself is prime.

## 2.4 The greatest common divisor of two numbers

We can find the greatest common divisor of positive integers _m_ and _n_,
<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/9c21a952d94f32aafa47e371e5a8b444.svg?invert_in_darkmode" align=middle width=68.4915pt height=24.65759999999998pt/>, without finding their prime divisors.

**Euclidean Algorithm**


```
Input: positive integers m and n with m >= n
Output: gcd(m,n)

a := m, b := n
r := remainder when a is divided by b
while r != 0 do
  a := b
  b := r
  r := remainder when a is divided by b
end
return b
```

**Example:**

Find <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/444ed9cc50b4342a394a737c70a75c20.svg?invert_in_darkmode" align=middle width=93.50681999999999pt height=24.65759999999998pt/>.

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44c27e96b18678f5e2b9792492fa6881.svg?invert_in_darkmode" align=middle width=136.07286pt height=11.9634735pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ce74d2c5c9ee868fdebc6835cbdf2e22.svg?invert_in_darkmode" align=middle width=127.853715pt height=11.9634735pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/c1b7495ff513cb5def6e51583a059e1d.svg?invert_in_darkmode" align=middle width=119.634405pt height=11.9634735pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/0c1e96bfb3799bda71c0125a452dfdb6.svg?invert_in_darkmode" align=middle width=111.41525999999999pt height=11.9634735pt/></p>

So <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/10c90c4f4474999131b6bb4bc63b7779.svg?invert_in_darkmode" align=middle width=131.86288499999998pt height=24.65759999999998pt/>.

**Definition:** Suppose _m_ and _n_ are positive integers. Then a _common
divisor_ of _m_ and _n_ is an integer which divides both _m_ and _n_.

**Example:** The common divisors of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/08f4ed92f27cec32cdd7a6ecd580f9e7.svg?invert_in_darkmode" align=middle width=16.438455000000005pt height=21.18732pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f2ebeadd36ad2620cbe7f02c861c9da3.svg?invert_in_darkmode" align=middle width=16.438455000000005pt height=21.18732pt/> are <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/71d29c6eff9b1337eaff85f73d5d2b5f.svg?invert_in_darkmode" align=middle width=63.013830000000006pt height=21.18732pt/> (and their
negatives).

**Definition:** Suppose _m_ and _n_ are positive integer. Then the _greatest
common divisor_ (or gcd) of _m_ and _n_ is the greatest integer which is a
common divisor of _m_ and _n_.

**Examples:**

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8a3fef690b507c336d998adac3cc2efd.svg?invert_in_darkmode" align=middle width=115.42426499999999pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7a3ee183028f2f6a95729d66a77d0bc7.svg?invert_in_darkmode" align=middle width=107.20512000000001pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/aa087f0e6d21a73fbfd9b70cbf76caa3.svg?invert_in_darkmode" align=middle width=107.20512000000001pt height=16.438356pt/></p>

**Fact:** <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/063bad8b6b3a7be4823146865c74f077.svg?invert_in_darkmode" align=middle width=178.009755pt height=24.65759999999998pt/> for any positive integers <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/88436bff22acdecd04360a591e1773dc.svg?invert_in_darkmode" align=middle width=39.431205000000006pt height=22.831379999999992pt/>.

**Proof:** If _d_ is a common divisor of _a_ and _b_ then _d_ is a common
divisor of _a_ - _kb_ and _b_.

If _e_ is a common divisor of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ed0cc78203bce1b0bf4e800991d5be8e.svg?invert_in_darkmode" align=middle width=44.91052500000001pt height=22.831379999999992pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/> then <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8cd34385ed61aca950a6b06d09fb50ac.svg?invert_in_darkmode" align=middle width=7.6542015000000045pt height=14.155350000000013pt/> is a common divisor of
<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode" align=middle width=8.689230000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/> (note <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/3d569890f736388f0579e2cbcc49841c.svg?invert_in_darkmode" align=middle width=130.916775pt height=24.65759999999998pt/>.

So the list of common divisors of is exactly the same as the list of common
divisors of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode" align=middle width=8.689230000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/>.

So the greatest common divisor of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ed0cc78203bce1b0bf4e800991d5be8e.svg?invert_in_darkmode" align=middle width=44.91052500000001pt height=22.831379999999992pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/> is equal to the greatest
common divisor of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode" align=middle width=8.689230000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/>.

## 2.5 The Euclidean algorithm works!

We start with the precondition <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7d9c97a3a0144e296e4b658bf23497e7.svg?invert_in_darkmode" align=middle width=76.354575pt height=21.18732pt/>. Then the division theorem tells
us there is a remainder <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/c7eddd374c961b8b9d243b17714ca99a.svg?invert_in_darkmode" align=middle width=36.845490000000005pt height=22.831379999999992pt/> when <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/93594010be750c2d9eaa53cbccbcd512.svg?invert_in_darkmode" align=middle width=45.039885pt height=14.155350000000013pt/> is divided by <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/b0e0695f1ff82c71419f123f0599bd6b.svg?invert_in_darkmode" align=middle width=38.83935pt height=22.831379999999992pt/>. Repeating
the process gives successively smaller remainders, and hence the algorithm
eventually returns a value.

## 2.6 Extended Euclidean algorithm

If we have used the Euclidean algorithm to find that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e5c488b4a50b7df7d20a4f1abc117472.svg?invert_in_darkmode" align=middle width=98.96502pt height=24.65759999999998pt/>, we can
"work backwards" through its steps to find integers <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode" align=middle width=8.689230000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/> such that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/b3d59374676b6751de3ac28fa881cf3e.svg?invert_in_darkmode" align=middle width=90.60875999999999pt height=22.831379999999992pt/>.

**Example:**
