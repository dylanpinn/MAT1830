# Lecture 10: Induction and well-ordering

In the previous lecture we were able to prove a property _P_ holds for
<img src="/lectures/tex/fe43dff12772ed4c9d2593ad6b2ba6c1.svg?invert_in_darkmode&sanitize=true" align=middle width=65.75326724999998pt height=21.18721440000001pt/> as follows:

**Base step.** Prove <img src="/lectures/tex/c94461c42a545e128f875c4c5b07f994.svg?invert_in_darkmode&sanitize=true" align=middle width=33.84141419999999pt height=24.65753399999998pt/>

**Induction step.** Prove <img src="/lectures/tex/8d964ff95bb74502bce8da917cfee26f.svg?invert_in_darkmode&sanitize=true" align=middle width=123.27613649999998pt height=24.65753399999998pt/> for each natural number <img src="/lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode&sanitize=true" align=middle width=9.075367949999992pt height=22.831056599999986pt/>.

This is sufficient to prove that <img src="/lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode&sanitize=true" align=middle width=35.489081099999986pt height=24.65753399999998pt/> holds for all natural numbers <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>, but
it may be difficult to prove that <img src="/lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode&sanitize=true" align=middle width=63.00796754999999pt height=24.65753399999998pt/> follows from <img src="/lectures/tex/4aea7d03cb3afc4a3d2c5963d5d5d280.svg?invert_in_darkmode&sanitize=true" align=middle width=34.69756784999999pt height=24.65753399999998pt/>. It may in fact
be easier to prove the induction step

<p align="center"><img src="/lectures/tex/05a45a135d2511e0c2696d52d0124eb8.svg?invert_in_darkmode&sanitize=true" align=middle width=264.93105045pt height=16.438356pt/></p>

That is, it may help to assume _P_ holds for _all_ numbers before <img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/>.
Induction with this style of induction step is sometimes called the _strong
form_ of mathematical induction.

### Example 1

Prove that, for each integer <img src="/lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>, <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> has a prime factorisation.

**Solution** Let <img src="/lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode&sanitize=true" align=middle width=35.489081099999986pt height=24.65753399999998pt/> be the statement "_n_ has a prime factorisation".

**Base step.** 2 is prime. So just '2' is a prime factorisation for 2.

**Induction step.** Suppose that <img src="/lectures/tex/e6538594d90f0bbf79f17ccac088c5fc.svg?invert_in_darkmode&sanitize=true" align=middle width=146.21569545pt height=24.65753399999998pt/> are true for some
integer <img src="/lectures/tex/93b0cc42af701f8d26df07765ffc4627.svg?invert_in_darkmode&sanitize=true" align=middle width=39.21220214999999pt height=22.831056599999986pt/>. This means that <img src="/lectures/tex/85cee8732265bbf3ae3fd7c4249bbc0c.svg?invert_in_darkmode&sanitize=true" align=middle width=61.13010914999999pt height=22.831056599999986pt/> all have prime
factorisations.

We want to prove that <img src="/lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode&sanitize=true" align=middle width=63.00796754999999pt height=24.65753399999998pt/> is true. We need to show that <img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/> has a prime
factorisation.

If <img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/> is prime, then just '<img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/>' is a prime factorisation for <img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/>.

If <img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/> is not prime, then <img src="/lectures/tex/3f528536e5a20b7972602504e6e06f0a.svg?invert_in_darkmode&sanitize=true" align=middle width=92.76822884999999pt height=22.831056599999986pt/> for integers <img src="/lectures/tex/4fe48dde86ac2d37419f0b35d57ac460.svg?invert_in_darkmode&sanitize=true" align=middle width=20.679527549999985pt height=21.68300969999999pt/> such that <img src="/lectures/tex/e65a6ad6d055e6d89ced4144c5055e47.svg?invert_in_darkmode&sanitize=true" align=middle width=80.70230519999998pt height=22.831056599999986pt/>.

Because <img src="/lectures/tex/02e5e81fd8ab521241a88f4d502b53e6.svg?invert_in_darkmode&sanitize=true" align=middle width=31.28543219999999pt height=24.65753399999998pt/> is true <img src="/lectures/tex/77a3b857d53fb44e33b53e4c8b68351a.svg?invert_in_darkmode&sanitize=true" align=middle width=5.663225699999989pt height=21.68300969999999pt/> has a prime factorisation.

Because <img src="/lectures/tex/1aadac9df964729662a76d442fca2190.svg?invert_in_darkmode&sanitize=true" align=middle width=33.33262349999999pt height=24.65753399999998pt/> is true <img src="/lectures/tex/36b5afebdba34564d884d347484ac0c7.svg?invert_in_darkmode&sanitize=true" align=middle width=7.710416999999989pt height=21.68300969999999pt/> has a prime factorisation.

So <img src="/lectures/tex/a238dda0a11c8a4443e2f0f31f3d5e03.svg?invert_in_darkmode&sanitize=true" align=middle width=33.46483469999999pt height=21.68300969999999pt/> has a prime factorisation. (Just combine the prime
factorisations of _i_ and _j_.)

So <img src="/lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode&sanitize=true" align=middle width=63.00796754999999pt height=24.65753399999998pt/> is true.

This proves that <img src="/lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode&sanitize=true" align=middle width=35.489081099999986pt height=24.65753399999998pt/> is true for each integer <img src="/lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>.

### Question

Which of the following is likely to require strong induction for its proof?

1. <img src="/lectures/tex/785b452e7e1671a824e4d37390e10cfa.svg?invert_in_darkmode&sanitize=true" align=middle width=221.71935719999996pt height=26.76175259999998pt/> for all <img src="/lectures/tex/8fa66d8b80ce643977d63a6f345785b9.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>.
2. <img src="/lectures/tex/9ad498a8243f912af9dae4314006479b.svg?invert_in_darkmode&sanitize=true" align=middle width=316.28548215pt height=24.65753399999998pt/> for all $n \geq 2$.
3. <img src="/lectures/tex/6512cbd0d448700a036bf3a691c37acc.svg?invert_in_darkmode&sanitize=true" align=middle width=16.81517804999999pt height=14.15524440000002pt/> is divisible by <img src="/lectures/tex/5dc642f297e291cfdde8982599601d7e.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=21.18721440000001pt/> for all <img src="/lectures/tex/685dff572c54cd51cfe7b54bddb98380.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>, where <img src="/lectures/tex/577fcfe243d3ebd16fde487572ee9fb3.svg?invert_in_darkmode&sanitize=true" align=middle width=112.65597914999998pt height=14.15524440000002pt/> is the sequence defined by $a_0 = 3, a_1 = 12,$ and $a_i = a_{i-1} +
   2a_{a-2}$ for $i \geq 2$.
4. Both 2 & 3.

**Answer:**

For 1., split <img src="/lectures/tex/6ae048b06eb9e9989603a8174226944e.svg?invert_in_darkmode&sanitize=true" align=middle width=182.59078859999997pt height=24.65753399999998pt/> as <img src="/lectures/tex/6b12a0afe0936399c25a6a09e0afe94a.svg?invert_in_darkmode&sanitize=true" align=middle width=261.0723852pt height=24.65753399999998pt/> and use
normal induction.

For 2., split <img src="/lectures/tex/ccc59ab4c2acd6a61457f3889e862bca.svg?invert_in_darkmode&sanitize=true" align=middle width=139.01038634999998pt height=24.65753399999998pt/>

For 3., the definition of <img src="/lectures/tex/1f7616939fc449b9941b7e7d44995d30.svg?invert_in_darkmode&sanitize=true" align=middle width=32.599104449999984pt height=14.15524440000002pt/> uses both <img src="/lectures/tex/888b6c2a06fc366952ac84a80c43f5f7.svg?invert_in_darkmode&sanitize=true" align=middle width=15.95518319999999pt height=14.15524440000002pt/> and <img src="/lectures/tex/15d36598a2a6c5d8544d093f4652e1a1.svg?invert_in_darkmode&sanitize=true" align=middle width=32.781751199999995pt height=14.15524440000002pt/> so strong
induction will be useful.

So 3.

### Normal Induction Proof of 2.

Prove that <img src="/lectures/tex/dcc420291f81d2a87777b98f2000c545.svg?invert_in_darkmode&sanitize=true" align=middle width=316.28548215pt height=24.65753399999998pt/> for all <img src="/lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>.

#### Solution

Let <img src="/lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode&sanitize=true" align=middle width=35.489081099999986pt height=24.65753399999998pt/> be the statement "<img src="/lectures/tex/5c32b32771ba3b609d367231d80921ea.svg?invert_in_darkmode&sanitize=true" align=middle width=316.28548215pt height=24.65753399999998pt/>".

**Base Step.** <img src="/lectures/tex/80cf2a320983d550f5666d11b9632b78.svg?invert_in_darkmode&sanitize=true" align=middle width=33.84141419999999pt height=24.65753399999998pt/> says "<img src="/lectures/tex/fd00a2320c2b5e65d9c3f5f5ee47d227.svg?invert_in_darkmode&sanitize=true" align=middle width=142.0205853pt height=24.65753399999998pt/>" which is just DeMorgan's law.

**Induction step.** Suppose that <img src="/lectures/tex/4aea7d03cb3afc4a3d2c5963d5d5d280.svg?invert_in_darkmode&sanitize=true" align=middle width=34.69756784999999pt height=24.65753399999998pt/> is true for some integer <img src="/lectures/tex/93b0cc42af701f8d26df07765ffc4627.svg?invert_in_darkmode&sanitize=true" align=middle width=39.21220214999999pt height=22.831056599999986pt/>. So
<img src="/lectures/tex/90f10cf31f3ec8a68ccd820ab55a2002.svg?invert_in_darkmode&sanitize=true" align=middle width=309.9992709pt height=24.65753399999998pt/>.

We want to prove that <img src="/lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode&sanitize=true" align=middle width=63.00796754999999pt height=24.65753399999998pt/> is true. We need to show that <img src="/lectures/tex/d1cd2a644b8ccda251c75ed90ce88484.svg?invert_in_darkmode&sanitize=true" align=middle width=347.85332504999997pt height=24.65753399999998pt/>.

<p align="center"><img src="/lectures/tex/f00a0280bcd4e1d4797b9ce1c8df53ee.svg?invert_in_darkmode&sanitize=true" align=middle width=189.41752169999998pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/2641c20ad30148bd2bde76c9b62b0615.svg?invert_in_darkmode&sanitize=true" align=middle width=187.3971792pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/3e8d836fb0f378a9e36839c3cdfd3f93.svg?invert_in_darkmode&sanitize=true" align=middle width=211.28404605pt height=16.438356pt/></p> by
DeMorgan's law.

<p align="center"><img src="/lectures/tex/b6f70806def41a13c90719d26c3bc1c3.svg?invert_in_darkmode&sanitize=true" align=middle width=246.03859334999996pt height=16.438356pt/></p>

by <img src="/lectures/tex/4aea7d03cb3afc4a3d2c5963d5d5d280.svg?invert_in_darkmode&sanitize=true" align=middle width=34.69756784999999pt height=24.65753399999998pt/>

<p align="center"><img src="/lectures/tex/bb68fc4f2d7bf217d1761f2bf00af51f.svg?invert_in_darkmode&sanitize=true" align=middle width=233.25315915000002pt height=12.9680562pt/></p>

So <img src="/lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode&sanitize=true" align=middle width=63.00796754999999pt height=24.65753399999998pt/> is true.

This proves that <img src="/lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode&sanitize=true" align=middle width=35.489081099999986pt height=24.65753399999998pt/> is true for each integer <img src="/lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>.

## Example 2

Prove that every integer is a sum of distinct powers of 2. (Just a power of two
by itself counts as a "sum".)

The idea behind this proof is to repeatedly subtract the largest possible power
of 2. We illustrate with the number 27.

27 - largest power of 2 less than 27 <img src="/lectures/tex/56524519d55f4f6ab84cb92218b77c2e.svg?invert_in_darkmode&sanitize=true" align=middle width=108.67560989999997pt height=21.18721440000001pt/>

11 - largest power of 2 less than 11 <img src="/lectures/tex/9b4132c19c06970415e6e829e1b7ef65.svg?invert_in_darkmode&sanitize=true" align=middle width=92.23719119999998pt height=21.18721440000001pt/>

3 - largest power of 2 less than 3 <img src="/lectures/tex/98db8266990efcbff9f9307dd9133322.svg?invert_in_darkmode&sanitize=true" align=middle width=84.01798184999998pt height=21.18721440000001pt/>

Hence <img src="/lectures/tex/537176ac78502e5c7860dd250adf6ca1.svg?invert_in_darkmode&sanitize=true" align=middle width=283.46963865pt height=26.76175259999998pt/>. (It is only interesting to
find _distinct_ powers of 2, because of course each integer <img src="/lectures/tex/33fc3e3d5a5ca99d5ac200178cc7c25a.svg?invert_in_darkmode&sanitize=true" align=middle width=25.570741349999988pt height=21.18721440000001pt/> is a sum of
1s, and <img src="/lectures/tex/b8f06769d0123f7ead8b61af7ad09f75.svg?invert_in_darkmode&sanitize=true" align=middle width=44.90859614999999pt height=26.76175259999998pt/>.)


### Solution

Let <img src="/lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode&sanitize=true" align=middle width=35.489081099999986pt height=24.65753399999998pt/> be the statement "_n_ can be written as a sum of distinct powers of
2".

**Base step.** <img src="/lectures/tex/b8f06769d0123f7ead8b61af7ad09f75.svg?invert_in_darkmode&sanitize=true" align=middle width=44.90859614999999pt height=26.76175259999998pt/>, so 1 is a sum of (one) power of 2.

**Induction step.** Suppose that <img src="/lectures/tex/a15640b42ace9ee59de2bfa481625e75.svg?invert_in_darkmode&sanitize=true" align=middle width=137.99671874999999pt height=24.65753399999998pt/> are true for some
integer <img src="/lectures/tex/4e5227ce11270fec063cddcfb92c3417.svg?invert_in_darkmode&sanitize=true" align=middle width=40.06836074999999pt height=22.831056599999986pt/>. This means that <img src="/lectures/tex/0b54ec654d26fb072b0da2c417d30183.svg?invert_in_darkmode&sanitize=true" align=middle width=61.13010914999999pt height=22.831056599999986pt/> can be written as a sum of
distinct powers of 2.

We want to prove that <img src="/lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode&sanitize=true" align=middle width=63.00796754999999pt height=24.65753399999998pt/> is true. We need to show that <img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/> can be
written as a sum of distinct powers of 2.

If <img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/> is a power of 2, then we are finished.

If not, let <img src="/lectures/tex/b483d63dd412dda7d6fa3ebd72211fff.svg?invert_in_darkmode&sanitize=true" align=middle width=14.32371929999999pt height=27.15900329999998pt/> be the greatest power of 2 less than <img src="/lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.38576269999999pt height=22.831056599999986pt/>.

(This means that <img src="/lectures/tex/3199b78aae22096ea6852755cc111a8d.svg?invert_in_darkmode&sanitize=true" align=middle width=97.73217795pt height=27.77565449999998pt/>.)

Let <img src="/lectures/tex/1776f87e8322aebc32e49a20a53157e4.svg?invert_in_darkmode&sanitize=true" align=middle width=112.16696369999997pt height=27.15900329999998pt/>. Note that <img src="/lectures/tex/dc72d7f2ace76420cb56531034a20833.svg?invert_in_darkmode&sanitize=true" align=middle width=72.0414156pt height=27.15900329999998pt/>.

Because <img src="/lectures/tex/02e5e81fd8ab521241a88f4d502b53e6.svg?invert_in_darkmode&sanitize=true" align=middle width=31.28543219999999pt height=24.65753399999998pt/> is true, <img src="/lectures/tex/77a3b857d53fb44e33b53e4c8b68351a.svg?invert_in_darkmode&sanitize=true" align=middle width=5.663225699999989pt height=21.68300969999999pt/> can be written as a sum of distinct powers of 2.
(Note that each power of 2 in this sum is smaller than <img src="/lectures/tex/b483d63dd412dda7d6fa3ebd72211fff.svg?invert_in_darkmode&sanitize=true" align=middle width=14.32371929999999pt height=27.15900329999998pt/> because <img src="/lectures/tex/808df385bb3e16e54831b12945be04b8.svg?invert_in_darkmode&sanitize=true" align=middle width=41.904574799999985pt height=27.15900329999998pt/>).

So <img src="/lectures/tex/83c0292f08488727b21486ab60d85ac3.svg?invert_in_darkmode&sanitize=true" align=middle width=100.20342419999997pt height=27.15900329999998pt/> can be written as a sum of distinct powers of 2.

So <img src="/lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode&sanitize=true" align=middle width=63.00796754999999pt height=24.65753399999998pt/> is true.

This proves that <img src="/lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode&sanitize=true" align=middle width=35.489081099999986pt height=24.65753399999998pt/> is true for each integer <img src="/lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>.

## Question 10.2

What else tells you every integer is a sum of distinct powers of 2?

The fact that every integer can be written as binary is equivalent to saying
every integer is a sum of distinct powers of 2.

## Question 10.3

Is every integer <img src="/lectures/tex/53b5365e05f26de6bd81b9c8fc76defe.svg?invert_in_darkmode&sanitize=true" align=middle width=32.23179299999999pt height=21.18721440000001pt/> a sum of distinct powers of 3?

No. The powers of three are <img src="/lectures/tex/4dd4940f154a092f91a5e5c7674e66a3.svg?invert_in_darkmode&sanitize=true" align=middle width=84.01825244999998pt height=21.18721440000001pt/> So, for example, 2 is not and 7
is not.

We can write every integer <img src="/lectures/tex/33fc3e3d5a5ca99d5ac200178cc7c25a.svg?invert_in_darkmode&sanitize=true" align=middle width=25.570741349999988pt height=21.18721440000001pt/> as
<p align="center"><img src="/lectures/tex/810d4fd38171b429a494e9365230131a.svg?invert_in_darkmode&sanitize=true" align=middle width=226.17188714999998pt height=16.66852275pt/></p>

Where <img src="/lectures/tex/e86a7f3439fd74936abfbdda8c73fbad.svg?invert_in_darkmode&sanitize=true" align=middle width=112.65597914999998pt height=14.15524440000002pt/> are all in {0,1,2}, however.

## 10.2 Well-ordering and descent

Induction expresses the fact that each natural number <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> can be reached by
starting at 0 and going upwards (e.g. adding 1) a finite number of times.

Equivalent facts are that it is only a finite number of steps, _downwards_ from
any natural number to 0, that _any descending sequence of natural numbers is
finite_, and that _any set of natural numbers has a least element._

This property is called _well-ordering_ of the natural numbers. It is often
convenient to arrange a proof to "work downwards" and appeal to well-ordering by
saying that the process of working downwards must eventually stop.

Such proofs are equivalent to induction, though they are sometimes called
"infinite descent" or similar.

## 10.3 Proofs by descent

**Example 1.** Prove that any integer <img src="/lectures/tex/a5029d6fb2d56f3b58c48da8dd19230d.svg?invert_in_darkmode&sanitize=true" align=middle width=25.570741349999988pt height=21.18721440000001pt/> has a prime divisor.

If <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> is prime, then it is a prime divisor of itself. If not, let <img src="/lectures/tex/620d96fc37814cef4788068ba5130b68.svg?invert_in_darkmode&sanitize=true" align=middle width=49.025842799999985pt height=17.723762100000005pt/> be
a divisor of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>.

If <img src="/lectures/tex/3c7e3568fa1625fede3ff436bfec732d.svg?invert_in_darkmode&sanitize=true" align=middle width=16.41942389999999pt height=14.15524440000002pt/> is prime, it is a prime divisor of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>. If not, let <img src="/lectures/tex/5699ab9c9c338283e921c23160be2416.svg?invert_in_darkmode&sanitize=true" align=middle width=55.57839044999998pt height=17.723762100000005pt/> be a
divisor of <img src="/lectures/tex/3c7e3568fa1625fede3ff436bfec732d.svg?invert_in_darkmode&sanitize=true" align=middle width=16.41942389999999pt height=14.15524440000002pt/> (and hence of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>).

If <img src="/lectures/tex/3ff44da77b122337fa0f84a268ccf932.svg?invert_in_darkmode&sanitize=true" align=middle width=16.41942389999999pt height=14.15524440000002pt/> is prime, it is a prime divisor of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>. If not, let <img src="/lectures/tex/9783f4176aa82acd6b8b3c1ade305d6f.svg?invert_in_darkmode&sanitize=true" align=middle width=55.57839044999998pt height=17.723762100000005pt/> be a
divisor of <img src="/lectures/tex/3ff44da77b122337fa0f84a268ccf932.svg?invert_in_darkmode&sanitize=true" align=middle width=16.41942389999999pt height=14.15524440000002pt/>, etc.

The sequence <img src="/lectures/tex/462db7af62c412d1a607e5cb03286e35.svg?invert_in_darkmode&sanitize=true" align=middle width=168.43939859999998pt height=17.723762100000005pt/> must eventually terminate, and this
means we find a prime divisor of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>.

### Question

Is every descending sequence of positive rational numbers finite?

No. For example <img src="/lectures/tex/f475889224ee056aeabda44f1daa6ca1.svg?invert_in_darkmode&sanitize=true" align=middle width=106.22349539999998pt height=27.77565449999998pt/> is an infinite sequence.

### Example 2

Prove that <img src="/lectures/tex/71486f265f83bc1e3d2b6f67704bcc23.svg?invert_in_darkmode&sanitize=true" align=middle width=21.91788224999999pt height=28.511366399999982pt/> is irrational.

Suppose that <img src="/lectures/tex/7395f0e10aa95efcec5872eba8199bbc.svg?invert_in_darkmode&sanitize=true" align=middle width=57.472953449999984pt height=28.511366399999982pt/> for all natural numbers <img src="/lectures/tex/0e51a2dede42189d77627c4d742822c3.svg?invert_in_darkmode&sanitize=true" align=middle width=14.433101099999991pt height=14.15524440000002pt/> and <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>. We
will show this is impossible. Since the square of an odd number is odd, we can
argue as follows.

<p align="center"><img src="/lectures/tex/bd25a79f89cfc5e5e4ae76034f9ce8e6.svg?invert_in_darkmode&sanitize=true" align=middle width=60.24120465pt height=29.47417935pt/></p>
<p align="center"><img src="/lectures/tex/e79540a25b6daef4af8b773e9fac5f43.svg?invert_in_darkmode&sanitize=true" align=middle width=221.50635044999999pt height=35.77743345pt/></p>
<p align="center"><img src="/lectures/tex/e13070620546f5618b81274111797f07.svg?invert_in_darkmode&sanitize=true" align=middle width=89.36832464999999pt height=14.202794099999998pt/></p>
<p align="center"><img src="/lectures/tex/4f3f4be0944a2a8e2ff8bde371e1dbc0.svg?invert_in_darkmode&sanitize=true" align=middle width=96.784776pt height=14.202794099999998pt/></p>
<p align="center"><img src="/lectures/tex/a24b31ab7d61b876bdd5bfca834f9004.svg?invert_in_darkmode&sanitize=true" align=middle width=397.08229769999997pt height=14.611878599999999pt/></p>
<p align="center"><img src="/lectures/tex/807adeac8bfb0f374f2258b88487db0a.svg?invert_in_darkmode&sanitize=true" align=middle width=116.01220124999999pt height=13.789957499999998pt/></p>
<p align="center"><img src="/lectures/tex/5b44d7ab66b6e433e05a19925ceb8161.svg?invert_in_darkmode&sanitize=true" align=middle width=141.31272539999998pt height=18.2666319pt/></p>
<p align="center"><img src="/lectures/tex/05633b45e2f20cd499d9e6cb505bcdb8.svg?invert_in_darkmode&sanitize=true" align=middle width=89.36832464999999pt height=18.2666319pt/></p>
<p align="center"><img src="/lectures/tex/58418651c5047cfb40476229e19aed36.svg?invert_in_darkmode&sanitize=true" align=middle width=185.50995705pt height=14.174856299999998pt/></p>

But then <img src="/lectures/tex/4f6eadc57d126f1c09b41ecdd5358342.svg?invert_in_darkmode&sanitize=true" align=middle width=63.88856429999999pt height=28.511366399999982pt/>, and we can repeat the argument to show
that <img src="/lectures/tex/0429e3dd940669f4c728ca27fe915301.svg?invert_in_darkmode&sanitize=true" align=middle width=20.985647099999987pt height=14.15524440000002pt/> and <img src="/lectures/tex/3c7e3568fa1625fede3ff436bfec732d.svg?invert_in_darkmode&sanitize=true" align=middle width=16.41942389999999pt height=14.15524440000002pt/> are both even, so <img src="/lectures/tex/1d915c18a76bdec4bd1c16e98d16eaf8.svg?invert_in_darkmode&sanitize=true" align=middle width=72.93004784999998pt height=21.18721440000001pt/> and <img src="/lectures/tex/e27c0c4b33d473407b3addf9be3d643b.svg?invert_in_darkmode&sanitize=true" align=middle width=63.79759979999999pt height=21.18721440000001pt/>, and so on.

Since the argument can be repeated indefinitely, we get an _infinite_ descending
sequence of natural numbers <p align="center"><img src="/lectures/tex/550520667bc1c49bf81b62f2d5043c15.svg?invert_in_darkmode&sanitize=true" align=middle width=142.9791033pt height=11.327609699999998pt/></p> which is impossible.

Hence there are no natural numbers <img src="/lectures/tex/0e51a2dede42189d77627c4d742822c3.svg?invert_in_darkmode&sanitize=true" align=middle width=14.433101099999991pt height=14.15524440000002pt/> and <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> with <img src="/lectures/tex/7395f0e10aa95efcec5872eba8199bbc.svg?invert_in_darkmode&sanitize=true" align=middle width=57.472953449999984pt height=28.511366399999982pt/>.
