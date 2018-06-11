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
