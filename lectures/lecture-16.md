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
