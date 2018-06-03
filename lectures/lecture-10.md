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

<p align="center"><img src="/lectures/tex/b6f70806def41a13c90719d26c3bc1c3.svg?invert_in_darkmode&sanitize=true" align=middle width=246.03859334999996pt height=16.438356pt/></p> by <img src="/lectures/tex/4aea7d03cb3afc4a3d2c5963d5d5d280.svg?invert_in_darkmode&sanitize=true" align=middle width=34.69756784999999pt height=24.65753399999998pt/>.

<p align="center"><img src="/lectures/tex/bb68fc4f2d7bf217d1761f2bf00af51f.svg?invert_in_darkmode&sanitize=true" align=middle width=233.25315915000002pt height=12.9680562pt/></p>

So <img src="/lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode&sanitize=true" align=middle width=63.00796754999999pt height=24.65753399999998pt/> is true.

This proves that <img src="/lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode&sanitize=true" align=middle width=35.489081099999986pt height=24.65753399999998pt/> is true for each integer <img src="/lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>.
