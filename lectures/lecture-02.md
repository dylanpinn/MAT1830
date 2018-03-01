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

## 2.3 Finding divisors

This algorithm also finds a prime divisor of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>. Either the least <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/acd2c745e074d1e7b747918849ab19d7.svg?invert_in_darkmode" align=middle width=54.17247pt height=24.99551999999999pt/> which divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>, or, if we do not find a divisor among the <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/acd2c745e074d1e7b747918849ab19d7.svg?invert_in_darkmode" align=middle width=54.17247pt height=24.99551999999999pt/>, <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> itself is prime.

