# Lecture 16: Relations

**Relations - why should you care?**

- Relations are used heavily in database theory in computer science.
- They are also used in theories of object orientation in programming.
- Relations can be thought of as a generalisation of functions.
- Like there is a functional programming paradigm there's a relational
  programming paradigm.

Roughly speaking, a binary relation on a set is something that tells us, for
any two things in the set, that they are related or they are not related. (Order
_is_ important.)

We could make a set <img src="/lectures/tex/02ceba8b20e861d7fbbc2466a15c0ed1.svg?invert_in_darkmode&sanitize=true" align=middle width=150.79154309999998pt height=24.65753399999998pt/>.

Mathematical objects can be related in various ways, and any particular way of
relating objects is called a _relation_ on the set of objects in question.

(This also applies to relations in the everyday sense. For example, "parent of"
is a relation on the set of people.)

A _binary relation_ <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> on a set <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> consists of <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> and a set of ordered pairs
from <img src="/lectures/tex/d1a4c3cb9c2223868a1d086d2c818240.svg?invert_in_darkmode&sanitize=true" align=middle width=44.748788699999984pt height=22.465723500000017pt/>. When <img src="/lectures/tex/0cd27d4708cd735f6ea469dc3debed0e.svg?invert_in_darkmode&sanitize=true" align=middle width=35.83526759999999pt height=24.65753399999998pt/> is in this set we write <img src="/lectures/tex/b3b3425b4ba9f5f69882ea9d0c802c3f.svg?invert_in_darkmode&sanitize=true" align=middle width=28.35242024999999pt height=22.831056599999986pt/>.

Similarly, a _ternary_ relation on <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> would be defined by a set of ordered
triples from <img src="/lectures/tex/c0cb8f82644fd059377834979d745f6d.svg?invert_in_darkmode&sanitize=true" align=middle width=77.16877739999998pt height=22.465723500000017pt/>, and so on. (A _unary_ relation on <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> is
just a subset of <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/>.)

A binary relation <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> on a set <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> consists of the set <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> together with a set
of ordered pairs from <img src="/lectures/tex/d1a4c3cb9c2223868a1d086d2c818240.svg?invert_in_darkmode&sanitize=true" align=middle width=44.748788699999984pt height=22.465723500000017pt/>.

If <img src="/lectures/tex/7392a8cd69b275fa1798ef94c839d2e0.svg?invert_in_darkmode&sanitize=true" align=middle width=38.135511149999985pt height=24.65753399999998pt/> is in the set then we write <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> and say "x is R-related to y".

If <img src="/lectures/tex/7392a8cd69b275fa1798ef94c839d2e0.svg?invert_in_darkmode&sanitize=true" align=middle width=38.135511149999985pt height=24.65753399999998pt/> is not in the set then we write <img src="/lectures/tex/d20fbc173b5876c674d4dd27be842599.svg?invert_in_darkmode&sanitize=true" align=middle width=39.78488084999999pt height=22.831056599999986pt/>.

Order matters. It might be that <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> but <img src="/lectures/tex/1a32e44da613c81dafd31706353e2003.svg?invert_in_darkmode&sanitize=true" align=middle width=39.78486104999999pt height=22.831056599999986pt/>.

**Arrow diagrams**

**Example** Let <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> be the relation on <img src="/lectures/tex/59855cc9c63715a8bed6834ce6651a79.svg?invert_in_darkmode&sanitize=true" align=middle width=146.4222078pt height=24.65753399999998pt/> given by the set
<img src="/lectures/tex/dd8ebf3be7a4968df2609137da5e17a2.svg?invert_in_darkmode&sanitize=true" align=middle width=264.5532483pt height=24.65753399999998pt/>.

![](images/L16-P9.png)

- Is <img src="/lectures/tex/38c431708856b993858482ba375992fb.svg?invert_in_darkmode&sanitize=true" align=middle width=26.777071199999988pt height=22.831056599999986pt/>? **Yes**
- Is <img src="/lectures/tex/ad0fb7c3cb3e73936e96693165eb8bcb.svg?invert_in_darkmode&sanitize=true" align=middle width=30.08002469999999pt height=22.831056599999986pt/>? **No**
- Is <img src="/lectures/tex/971822f2806bf66535aec9c2f4a0d223.svg?invert_in_darkmode&sanitize=true" align=middle width=28.411429199999986pt height=22.465723500000017pt/>? **No**
- Is <img src="/lectures/tex/0581c18d937e07ab0e316a8411087271.svg?invert_in_darkmode&sanitize=true" align=middle width=28.818571649999992pt height=22.831056599999986pt/>? **Yes**
- Is <img src="/lectures/tex/5f57ca0200c31a8d7c7afbde528e10dc.svg?invert_in_darkmode&sanitize=true" align=middle width=23.93492309999999pt height=22.465723500000017pt/>? **Yes**

## 16.1 Relations and functions

Any function <img src="/lectures/tex/8dd51bd31b996f66d97db221486b70a5.svg?invert_in_darkmode&sanitize=true" align=middle width=77.19148799999999pt height=22.831056599999986pt/> can be viewed as a relation <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> on <img src="/lectures/tex/eb6fc4bcc0521cca43308ec259cd83bc.svg?invert_in_darkmode&sanitize=true" align=middle width=46.369751999999984pt height=22.465723500000017pt/>. The relation is defined by <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> if and only if <img src="/lectures/tex/0e241c321e18ed6141f9a47d8095bebd.svg?invert_in_darkmode&sanitize=true" align=middle width=62.56467194999998pt height=24.65753399999998pt/>.

However, not every relation is a function. Remember that a function must have
exactly one output <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> for each input <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> in its domain. In a relation, on the
other hand, and element <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> may be related to many elements <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/>, or to none at
all.

## 16.2 Examples

**Question** Give the set of ordered pairs for the relation "=" on
<img src="/lectures/tex/7dad423fb8faaf679b9ba94be368f183.svg?invert_in_darkmode&sanitize=true" align=middle width=102.28309079999998pt height=24.65753399999998pt/> and draw an arrow diagram of it.

![](images/L16-P12.png)

**Question** Give the set of orders pairs for the relation <img src="/lectures/tex/0942af8a2264d9a80424b3c08dfc1bd3.svg?invert_in_darkmode&sanitize=true" align=middle width=38.35605014999999pt height=22.831056599999986pt/> on
<img src="/lectures/tex/7dad423fb8faaf679b9ba94be368f183.svg?invert_in_darkmode&sanitize=true" align=middle width=102.28309079999998pt height=24.65753399999998pt/> and draw an arrow diagram of it.

![](images/L16-P14.png)

**Question** Which of the following binary relations <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> satisfy <img src="/lectures/tex/3059f60df5fd7ff245f23ef9c027b071.svg?invert_in_darkmode&sanitize=true" align=middle width=85.26086744999999pt height=24.65753399999998pt/>?

1. <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> defined on <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/> by <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> if and only if <img src="/lectures/tex/27d75453d3c4eccd494155e51a9736d6.svg?invert_in_darkmode&sanitize=true" align=middle width=70.11583754999998pt height=22.465723500000017pt/>
2. <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> defined on <img src="/lectures/tex/bbab0050918154dbcd19efcc0141b225.svg?invert_in_darkmode&sanitize=true" align=middle width=47.72843129999998pt height=24.65753399999998pt/> by <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> if and only if <img src="/lectures/tex/df2d3542b5af158a43c0ec6c512e4a38.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96184334999999pt height=20.908638300000003pt/>
3. <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> defined on <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/> by <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> if and only if <img src="/lectures/tex/78bdc28b55ffcf72965ced5360da934b.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96184334999999pt height=17.723762100000005pt/>
4. <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> defined on <img src="/lectures/tex/4fd661cfefdf4318d1aa35fb483796b2.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/> by <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> if and only if <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> divides <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/>

- **A** (1), (2) and (3) but not (4)
- **B** (2), (3) and (4) but not (1)
- **C** (2) and (3) but not (1) and (4)
- **D** None of them

**Hint** <img src="/lectures/tex/1ce420c9fd5b5549516d7c0286406746.svg?invert_in_darkmode&sanitize=true" align=middle width=79.74718784999999pt height=24.65753399999998pt/> means roughly "everything is R-related to
something".

**Answer**

- To show <img src="/lectures/tex/1ce420c9fd5b5549516d7c0286406746.svg?invert_in_darkmode&sanitize=true" align=middle width=79.74718784999999pt height=24.65753399999998pt/> is true we must find, for each x, a y such
  that <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/>.
- To show <img src="/lectures/tex/1ce420c9fd5b5549516d7c0286406746.svg?invert_in_darkmode&sanitize=true" align=middle width=79.74718784999999pt height=24.65753399999998pt/> is false we must find one specific x such
  that <img src="/lectures/tex/d20fbc173b5876c674d4dd27be842599.svg?invert_in_darkmode&sanitize=true" align=middle width=39.78488084999999pt height=22.831056599999986pt/> for all <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/>.
- False for (1). If <img src="/lectures/tex/c3c01522aec26c044a392f697d1fb936.svg?invert_in_darkmode&sanitize=true" align=middle width=44.16654329999999pt height=22.465723500000017pt/> then <img src="/lectures/tex/d20fbc173b5876c674d4dd27be842599.svg?invert_in_darkmode&sanitize=true" align=middle width=39.78488084999999pt height=22.831056599999986pt/> for all <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/>.
- True for (2). For each <img src="/lectures/tex/8f2d4bef5e5414945cc2ce944147b231.svg?invert_in_darkmode&sanitize=true" align=middle width=48.09931664999999pt height=22.465723500000017pt/> for example.
- True for (3). For each <img src="/lectures/tex/3c8e47ae8fad180b8a50a5bdbf371cbb.svg?invert_in_darkmode&sanitize=true" align=middle width=89.19515055pt height=24.65753399999998pt/> for example.
- True for (4). For each <img src="/lectures/tex/4fdac3cf3f1bba0236934847b8aaec09.svg?invert_in_darkmode&sanitize=true" align=middle width=69.10396019999999pt height=24.65753399999998pt/> for example.
- So **B**.

**Question 16.2** Use logic symbols and the <img src="/lectures/tex/a27bd5e00db840936296ead0783388e7.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=20.908638300000003pt/> relation to write a relation
between real numbers <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> and <img src="/lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.649225749999989pt height=14.15524440000002pt/> which says that the point <img src="/lectures/tex/7392a8cd69b275fa1798ef94c839d2e0.svg?invert_in_darkmode&sanitize=true" align=middle width=38.135511149999985pt height=24.65753399999998pt/> lies in the
square with the corners <img src="/lectures/tex/5e53850ff2f5ca0f27d4f2329433be1f.svg?invert_in_darkmode&sanitize=true" align=middle width=124.20097304999997pt height=24.65753399999998pt/> and <img src="/lectures/tex/345bb27c06bd6ce90e57ba2433f718bb.svg?invert_in_darkmode&sanitize=true" align=middle width=36.52973609999999pt height=24.65753399999998pt/>.

![](images/L16-P17.png)

**Answer**

<p align="center"><img src="/lectures/tex/acc24c89eae588115eb97b07e9bdd37a.svg?invert_in_darkmode&sanitize=true" align=middle width=262.57157685pt height=16.438356pt/></p>

### 3. Algebraic curves

An algebraic curve consists of the points <img src="/lectures/tex/7392a8cd69b275fa1798ef94c839d2e0.svg?invert_in_darkmode&sanitize=true" align=middle width=38.135511149999985pt height=24.65753399999998pt/> satisfying an equation <img src="/lectures/tex/f5f31dfc3531d204839050016da37ed5.svg?invert_in_darkmode&sanitize=true" align=middle width=76.54291754999998pt height=24.65753399999998pt/> where <img src="/lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode&sanitize=true" align=middle width=8.270567249999992pt height=14.15524440000002pt/> is a polynomial.

E.g. unit circle <img src="/lectures/tex/b1e5384decefdd050656339a78591627.svg?invert_in_darkmode&sanitize=true" align=middle width=111.3315456pt height=26.76175259999998pt/>. Notice that this relation is not a
function, because there are two pairs with the same <img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/>, e.g. <img src="/lectures/tex/1e5ba49ae6981862f61b4d510dcf29af.svg?invert_in_darkmode&sanitize=true" align=middle width=36.52973609999999pt height=24.65753399999998pt/> and
<img src="/lectures/tex/ea75b46d38ac4f1a9e9357d605df114a.svg?invert_in_darkmode&sanitize=true" align=middle width=49.31516864999999pt height=24.65753399999998pt/>.

Likewise, the curve <img src="/lectures/tex/bb6c04a0e2e0bd4bbb5a20b8296140d4.svg?invert_in_darkmode&sanitize=true" align=middle width=105.20156624999998pt height=26.76175259999998pt/> is not a function.

### 4. The subset relation <img src="/lectures/tex/2e0145a5b0e7374cba1158796ba774c0.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=20.908638300000003pt/>.

This consists of the ordered pairs of sets <img src="/lectures/tex/0ed7b9f99b267c62dd2db0eb0241c40f.svg?invert_in_darkmode&sanitize=true" align=middle width=45.71351894999999pt height=24.65753399999998pt/> such that <img src="/lectures/tex/3c8b983d929a7dc3bcb427bbf20e86d6.svg?invert_in_darkmode&sanitize=true" align=middle width=47.539839599999986pt height=22.465723500000017pt/>.
<img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> and <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> must be subsets of some universal set <img src="/lectures/tex/6bac6ec50c01592407695ef84f457232.svg?invert_in_darkmode&sanitize=true" align=middle width=13.01596064999999pt height=22.465723500000017pt/>.

**Question** Give the set of ordered pairs for the relation <img src="/lectures/tex/e0990e04e807dbb309998a6dc3aa3f37.svg?invert_in_darkmode&sanitize=true" align=middle width=38.35605014999999pt height=22.831056599999986pt/> on
<img src="/lectures/tex/64ec31d8aa3de54f297ba4c28b44c6cf.svg?invert_in_darkmode&sanitize=true" align=middle width=63.43049954999999pt height=24.65753399999998pt/> and draw an arrow diagram for it.

Remember <img src="/lectures/tex/40bffec850facaaf3e88a118dfc4fc54.svg?invert_in_darkmode&sanitize=true" align=middle width=221.42138534999995pt height=24.65753399999998pt/>.

![](images/L16-P20.png)

**Question** How many possible relations are there on a set <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> with <img src="/lectures/tex/b983eb66dd4d9c6d4ed67a6a0e10f6a8.svg?invert_in_darkmode&sanitize=true" align=middle width=55.82562149999999pt height=24.65753399999998pt/>?

- **A** <img src="/lectures/tex/021273d50c6ff03efebda428e9e42d77.svg?invert_in_darkmode&sanitize=true" align=middle width=16.41942389999999pt height=26.76175259999998pt/>
- **B** <img src="/lectures/tex/f5ac8bc1b354a334d65fc81e65f0adcc.svg?invert_in_darkmode&sanitize=true" align=middle width=33.03487934999999pt height=32.44583099999998pt/>
- **C** <img src="/lectures/tex/f8f25e4580c418a51dc556db0d8d2b93.svg?invert_in_darkmode&sanitize=true" align=middle width=16.34523329999999pt height=21.839370299999988pt/>
- **D** <img src="/lectures/tex/56f3577693c38f185d7e9f0173375ebd.svg?invert_in_darkmode&sanitize=true" align=middle width=33.10714439999999pt height=29.190975000000005pt/>

**Hint** Think of the relation as a set of ordered pairs. How many possible
ordered pairs are there? So how many possible relations?

**Answer**

- A relation on <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> can be thought of as a subset of <img src="/lectures/tex/2cfbede980e22a2122e4e9c3258b799e.svg?invert_in_darkmode&sanitize=true" align=middle width=49.90854659999999pt height=22.465723500000017pt/>.
- Every subset of <img src="/lectures/tex/2cfbede980e22a2122e4e9c3258b799e.svg?invert_in_darkmode&sanitize=true" align=middle width=49.90854659999999pt height=22.465723500000017pt/> corresponds to a unique relation (and vice
  versa).
- So the number of possible relations on <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> is the same as the number of
  subsets of <img src="/lectures/tex/2cfbede980e22a2122e4e9c3258b799e.svg?invert_in_darkmode&sanitize=true" align=middle width=49.90854659999999pt height=22.465723500000017pt/>.
- <img src="/lectures/tex/80ee660918fc47508458750b36e5b977.svg?invert_in_darkmode&sanitize=true" align=middle width=97.3780269pt height=26.76175259999998pt/>. So the number of subsets of <img src="/lectures/tex/2cfbede980e22a2122e4e9c3258b799e.svg?invert_in_darkmode&sanitize=true" align=middle width=49.90854659999999pt height=22.465723500000017pt/> is <img src="/lectures/tex/f5ac8bc1b354a334d65fc81e65f0adcc.svg?invert_in_darkmode&sanitize=true" align=middle width=33.03487934999999pt height=32.44583099999998pt/>.
- So **B**.

### 5. Congruence modulo n

For a fixed <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>, congruence modulo <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> is a binary relation. It consists of the
ordered pairs of integers <img src="/lectures/tex/0cd27d4708cd735f6ea469dc3debed0e.svg?invert_in_darkmode&sanitize=true" align=middle width=35.83526759999999pt height=24.65753399999998pt/> such that <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> divides <img src="/lectures/tex/3db94e1f2989d6890a93270f166723f6.svg?invert_in_darkmode&sanitize=true" align=middle width=35.83514219999999pt height=22.831056599999986pt/>.

**Congruence modulo _n_**

Remember <img src="/lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode&sanitize=true" align=middle width=37.66158164999999pt height=22.831056599999986pt/> (mod n) means that _a_ and _b_ have the same remainder
when you divide them by _n_.

**Definition** We say <img src="/lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode&sanitize=true" align=middle width=37.66158164999999pt height=22.831056599999986pt/> (mod n) if _n_ divides <img src="/lectures/tex/3db94e1f2989d6890a93270f166723f6.svg?invert_in_darkmode&sanitize=true" align=middle width=35.83514219999999pt height=22.831056599999986pt/>.

For a fixed integer <img src="/lectures/tex/e4fa18f24ed41ec42105ccc667ea4f17.svg?invert_in_darkmode&sanitize=true" align=middle width=40.00371704999999pt height=21.18721440000001pt/>, congruence modulo _n_ is a binary relation.

**Question** Which integers are congruent to 1 modulo 7?

Integers in the set <img src="/lectures/tex/cfe8d070d7f6f5a0a424aded99a9b3ea.svg?invert_in_darkmode&sanitize=true" align=middle width=247.48838729999994pt height=24.65753399999998pt/>. This is
the set <img src="/lectures/tex/3f645d0e15eab8aef7477f21939b570b.svg?invert_in_darkmode&sanitize=true" align=middle width=115.86725369999999pt height=24.65753399999998pt/>.

**Question** Which integers are congruent to 2 modulo 5?

Integers in the set <img src="/lectures/tex/5ada4cecec234404b9c1efc15cb428fa.svg?invert_in_darkmode&sanitize=true" align=middle width=239.26917794999997pt height=24.65753399999998pt/>.

This is the set <img src="/lectures/tex/73c0f0b4782edc662088cbbcc56e8fbe.svg?invert_in_darkmode&sanitize=true" align=middle width=115.86725369999999pt height=24.65753399999998pt/>.

## 16.3 Properties of congruence

As the symbol <img src="/lectures/tex/ebf45b23c8b2fe7cb8bf20cb8bbd565d.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=15.24650820000002pt/> suggests, congruence mod <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> is a lot like equality.
Numbers <img src="/lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode&sanitize=true" align=middle width=8.68915409999999pt height=14.15524440000002pt/> and <img src="/lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode&sanitize=true" align=middle width=7.054796099999991pt height=22.831056599999986pt/> which are congruent mod <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> are not necessarily equal, but
they are "equal up to multiples of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>," because they have equal remainders when
divided by <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>.

Because congruence is like equality, congruence <img src="/lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode&sanitize=true" align=middle width=37.66158164999999pt height=22.831056599999986pt/> (mod _n_) behave a
lot like equations. In particular, they have the following three properties.

1. Reflexive property: <img src="/lectures/tex/97b4b2884947bc33647e51fc8688d4f0.svg?invert_in_darkmode&sanitize=true" align=middle width=39.29593799999999pt height=15.24650820000002pt/> (mod <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>) for any number <img src="/lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode&sanitize=true" align=middle width=8.68915409999999pt height=14.15524440000002pt/>.
2. Symmetric property: <img src="/lectures/tex/734fa34f6bcae1e3e0d79917792eefcb.svg?invert_in_darkmode&sanitize=true" align=middle width=225.65062904999994pt height=24.65753399999998pt/> for any numbers _a_ and _b_.
3. Transitive property: <img src="/lectures/tex/fe2451800e3e323d89f42caa9b61bb9f.svg?invert_in_darkmode&sanitize=true" align=middle width=359.50546169999996pt height=24.65753399999998pt/> for any numbers _a,b_ and
   _c_.

These properties are clear if one remembers that <img src="/lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode&sanitize=true" align=middle width=37.66158164999999pt height=22.831056599999986pt/> (mod n) means that
a and b have the same remainder on division by n.

**Question** Let _R_ be the binary relation on <img src="/lectures/tex/b9477ea14234215f4d516bad55d011b8.svg?invert_in_darkmode&sanitize=true" align=middle width=10.95894029999999pt height=22.648391699999998pt/> defined by <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> if
and if <img src="/lectures/tex/ee7e4d9ca61da271efaf35f9cd10d96d.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96184334999999pt height=15.24650820000002pt/> (mod 3). Roughly, what would an arrow diagram for _R_ look
like?

![](images/L16-P27.png)
