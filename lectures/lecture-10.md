# Lecture 10: Induction and well-ordering

In the previous lecture we were able to prove a property _P_ holds for
<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/fe43dff12772ed4c9d2593ad6b2ba6c1.svg?invert_in_darkmode" align=middle width=65.753325pt height=21.18732pt/> as follows:

**Base step.** Prove <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/c94461c42a545e128f875c4c5b07f994.svg?invert_in_darkmode" align=middle width=33.8415pt height=24.65759999999998pt/>

**Induction step.** Prove <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8d964ff95bb74502bce8da917cfee26f.svg?invert_in_darkmode" align=middle width=123.27612000000002pt height=24.65759999999998pt/> for each natural number <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>.

This is sufficient to prove that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode" align=middle width=35.48919pt height=24.65759999999998pt/> holds for all natural numbers <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>, but
it may be difficult to prove that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode" align=middle width=63.008055pt height=24.65759999999998pt/> follows from <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4aea7d03cb3afc4a3d2c5963d5d5d280.svg?invert_in_darkmode" align=middle width=34.69768500000001pt height=24.65759999999998pt/>. It may in fact
be easier to prove the induction step

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/05a45a135d2511e0c2696d52d0124eb8.svg?invert_in_darkmode" align=middle width=264.93059999999997pt height=16.438356pt/></p>

That is, it may help to assume _P_ holds for _all_ numbers before <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode" align=middle width=37.385865pt height=22.831379999999992pt/>.
Induction with this style of induction step is sometimes called the _strong
form_ of mathematical induction.

### Example 1

Prove that, for each integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>, <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> has a prime factorisation.

**Solution** Let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode" align=middle width=35.48919pt height=24.65759999999998pt/> be the statement "_n_ has a prime factorisation".

**Base step.** 2 is prime. So just '2' is a prime factorisation for 2.

**Induction step.** Suppose that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e6538594d90f0bbf79f17ccac088c5fc.svg?invert_in_darkmode" align=middle width=146.21573999999998pt height=24.65759999999998pt/> are true for some
integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/93b0cc42af701f8d26df07765ffc4627.svg?invert_in_darkmode" align=middle width=39.212250000000004pt height=22.831379999999992pt/>. This means that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/85cee8732265bbf3ae3fd7c4249bbc0c.svg?invert_in_darkmode" align=middle width=61.13019pt height=22.831379999999992pt/> all have prime
factorisations.

We want to prove that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode" align=middle width=63.008055pt height=24.65759999999998pt/> is true. We need to show that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode" align=middle width=37.385865pt height=22.831379999999992pt/> has a prime
factorisation.

If <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode" align=middle width=37.385865pt height=22.831379999999992pt/> is prime, then just '<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode" align=middle width=37.385865pt height=22.831379999999992pt/>' is a prime factorisation for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode" align=middle width=37.385865pt height=22.831379999999992pt/>.

If <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode" align=middle width=37.385865pt height=22.831379999999992pt/> is not prime, then <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/3f528536e5a20b7972602504e6e06f0a.svg?invert_in_darkmode" align=middle width=92.76828pt height=22.831379999999992pt/> for integers <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4fe48dde86ac2d37419f0b35d57ac460.svg?invert_in_darkmode" align=middle width=20.679615000000002pt height=21.683310000000006pt/> such that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e65a6ad6d055e6d89ced4144c5055e47.svg?invert_in_darkmode" align=middle width=80.702325pt height=22.831379999999992pt/>.

Because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/02e5e81fd8ab521241a88f4d502b53e6.svg?invert_in_darkmode" align=middle width=31.285485pt height=24.65759999999998pt/> is true <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/77a3b857d53fb44e33b53e4c8b68351a.svg?invert_in_darkmode" align=middle width=5.663295000000005pt height=21.683310000000006pt/> has a prime factorisation.

Because <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/1aadac9df964729662a76d442fca2190.svg?invert_in_darkmode" align=middle width=33.332640000000005pt height=24.65759999999998pt/> is true <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/36b5afebdba34564d884d347484ac0c7.svg?invert_in_darkmode" align=middle width=7.710483000000004pt height=21.683310000000006pt/> has a prime factorisation.

So <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/a238dda0a11c8a4443e2f0f31f3d5e03.svg?invert_in_darkmode" align=middle width=33.46497000000001pt height=21.683310000000006pt/> has a prime factorisation. (Just combine the prime
factorisations of _i_ and _j_.)

So <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode" align=middle width=63.008055pt height=24.65759999999998pt/> is true.

This proves that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode" align=middle width=35.48919pt height=24.65759999999998pt/> is true for each integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>.

### Question

Which of the following is likely to require strong induction for its proof?

1. <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/785b452e7e1671a824e4d37390e10cfa.svg?invert_in_darkmode" align=middle width=221.71990499999998pt height=26.76201000000001pt/> for all <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8fa66d8b80ce643977d63a6f345785b9.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>.
2. <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/9ad498a8243f912af9dae4314006479b.svg?invert_in_darkmode" align=middle width=316.28635499999996pt height=24.65759999999998pt/> for all $n \geq 2$.
3. <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6512cbd0d448700a036bf3a691c37acc.svg?invert_in_darkmode" align=middle width=16.815315000000002pt height=14.155350000000013pt/> is divisible by <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/5dc642f297e291cfdde8982599601d7e.svg?invert_in_darkmode" align=middle width=8.219277000000005pt height=21.18732pt/> for all <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/685dff572c54cd51cfe7b54bddb98380.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>, where <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/577fcfe243d3ebd16fde487572ee9fb3.svg?invert_in_darkmode" align=middle width=112.65605999999998pt height=14.155350000000013pt/> is the sequence defined by $a_0 = 3, a_1 = 12,$ and $a_i = a_{i-1} +
   2a_{a-2}$ for $i \geq 2$.
4. Both 2 & 3.
