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
