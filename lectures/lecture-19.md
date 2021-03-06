# Lecture 19: Selections and Arrangements

## Ordered selections without repetition

The number of ordered selections without repetition of <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> elements from a set
of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements <img src="/lectures/tex/659a9643eddf51cc290c19c87cf33314.svg?invert_in_darkmode&sanitize=true" align=middle width=82.57973624999998pt height=24.65753399999998pt/> is:

<p align="center"><img src="/lectures/tex/451f7da1a1669ff6cc0777dcda4a9364.svg?invert_in_darkmode&sanitize=true" align=middle width=243.48666045000002pt height=37.9216761pt/></p>

When <img src="/lectures/tex/880574c17268de1fe3aacbbd9c5ba596.svg?invert_in_darkmode&sanitize=true" align=middle width=39.65746289999999pt height=14.15524440000002pt/> and all the elements of a set <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/> are ordered, we just say that this
is a _permutation_ of <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/>. Our formula tells us there are <img src="/lectures/tex/50c0357224674ab662b8ea5e5ca3eb8a.svg?invert_in_darkmode&sanitize=true" align=middle width=14.433101099999991pt height=22.831056599999986pt/> such
permutations. For example, there are <img src="/lectures/tex/85913a56dd00b08a2a4c65184b3d106f.svg?invert_in_darkmode&sanitize=true" align=middle width=42.92227334999999pt height=22.831056599999986pt/> permutations of the set
<img src="/lectures/tex/b5935d2873e269fe97955fa45c8ee5a6.svg?invert_in_darkmode&sanitize=true" align=middle width=53.90794035pt height=24.65753399999998pt/>.

## Unordered selections without repetition

A _combination_ of <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> elements from a set <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/> is a subset of <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/> with <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/>
elements.

The number of combinations of <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> elements from a set of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements <img src="/lectures/tex/4d1f4471f3505b6f640aa18a4dbed3d5.svg?invert_in_darkmode&sanitize=true" align=middle width=82.57973624999998pt height=24.65753399999998pt/> is

<p align="center"><img src="/lectures/tex/e8bfddd2decc41cc4261a6ad4720646d.svg?invert_in_darkmode&sanitize=true" align=middle width=315.8564442pt height=39.452455349999994pt/></p>

## Ordered selections with repetition

The number of sequences of <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> terms, each from some set of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements, is

<p align="center"><img src="/lectures/tex/71c1a27040d5806e4bf178b0d3d41554.svg?invert_in_darkmode&sanitize=true" align=middle width=147.29414865pt height=13.1114775pt/></p>

**Questions**

**19.1** A bank requires a PIN that this is a string of four decimal digits. How
many such PINs are there? How many are made of four different digits?

A PIN is an ordered selection with repetition of four elements from the set
<img src="/lectures/tex/6090d842ab3a28d61c4d311fa3c575d7.svg?invert_in_darkmode&sanitize=true" align=middle width=69.40625339999998pt height=24.65753399999998pt/>. So there are <img src="/lectures/tex/2a15b76747e110fd0af39e7335c40457.svg?invert_in_darkmode&sanitize=true" align=middle width=86.82655574999998pt height=26.76175259999998pt/> possible PINs.

A PIN with four _different_ digits is a permutation of four elements from the
set <img src="/lectures/tex/6090d842ab3a28d61c4d311fa3c575d7.svg?invert_in_darkmode&sanitize=true" align=middle width=69.40625339999998pt height=24.65753399999998pt/>. So there are <img src="/lectures/tex/606c628a97353f8ce07aae8524894d7f.svg?invert_in_darkmode&sanitize=true" align=middle width=73.59362999999999pt height=28.92634470000001pt/> possible PINs with
four different digits.

**19.2** How many binary strings of length 5 are there? How many of these
contain exactly two 1s?

There are <img src="/lectures/tex/95de08ccc1e1b5f3ce14ed748478354c.svg?invert_in_darkmode&sanitize=true" align=middle width=53.94971834999998pt height=26.76175259999998pt/> binary strings of length 5.

There are <img src="/lectures/tex/689ed70c96a7d7e9c6d639d2253e4fb8.svg?invert_in_darkmode&sanitize=true" align=middle width=59.97716834999999pt height=29.419440600000005pt/> that contain exactly two 1s.

## Unordered selections with repetition

A **multiset** is like a set, except we allow elements to appear more than once
and we keep track of how many times they occur.

An ordered selection of <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> elements, with repetition allowed, from a set <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> of
<img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements can be thought of a multiset with <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> elements, each in <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/>.

The number of multisets of <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> elements, each from a set of <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements, is

<p align="center"><img src="/lectures/tex/1282081078e3db64ada8efbcb06ec6aa.svg?invert_in_darkmode&sanitize=true" align=middle width=198.0719862pt height=39.452455349999994pt/></p>

**Question**

Elodie orders a pizza from a shop that allows any 4 toppings to be chosen from a
list of 11 options. Is this choice

1. ordered without repetition
2. unordered without repetition
3. ordered with repetition
4. unordered with repetition

**Answer** **2** It's reasonable to assume that Elodie doesn't care about the
order in which the toppings are put on the pizza, and that she doesn't want to
repeat toppings.

<p align="center"><img src="/lectures/tex/8c81742616d35b7c161bb483f13dc6f6.svg?invert_in_darkmode&sanitize=true" align=middle width=222.66628889999998pt height=39.452455349999994pt/></p>

**Question**

Sam orders 3 pizzas from a shop that sells 7 different pizzas. Is his choice

1. ordered without repetition
2. unordered without repetition
3. ordered with repetition
4. unordered with repetition

**Answer** **4** The same pizza may be picked more than once, but the order
doesn't matter.

<p align="center"><img src="/lectures/tex/1d14b9ff80b232ba9a3c8124e85f71ee.svg?invert_in_darkmode&sanitize=true" align=middle width=263.30526914999996pt height=39.452455349999994pt/></p>

## The pigeonhole principle

If <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> items are placed in <img src="/lectures/tex/0e51a2dede42189d77627c4d742822c3.svg?invert_in_darkmode&sanitize=true" align=middle width=14.433101099999991pt height=14.15524440000002pt/> containers with <img src="/lectures/tex/d934387e8f739ff0602a0df914fe7b4a.svg?invert_in_darkmode&sanitize=true" align=middle width=46.21760714999999pt height=17.723762100000005pt/>, then at least one
container has at least two items.

**Example**

If a drawer contains only blue, black and white socks and you take out four
socks without looking at them, then you are guaranteed to have two of the same
colour.

**Questions**

**19.3** In a game, each of 10 players holds a red, blue and green marbles, and
places one marble in a bag. How many possibilities are there for for the colours
of the marbles in the bag? If each player chooses their colour at random are all
of these possibilities equally likely?

There are <img src="/lectures/tex/052e9ca541abd49b588da10377bdf54c.svg?invert_in_darkmode&sanitize=true" align=middle width=281.542404pt height=29.419440600000005pt/> possibilities.

These are _not_ equally likely. For example, the "all red" case is less likely
than having 3 red, 3 blue and 4 green.

**19.4** How many ways are there to partition a set with 10 elements into one
class of 5 elements, one class of 3 elements and one class of 2 elements? How
many ways are there to partition a set with 10 elements into one class of 6
elements and two classes of 2 elements each?

In the first case, there are <img src="/lectures/tex/b0dc6eb9335ae4c75e74cb3d7d3e6a38.svg?invert_in_darkmode&sanitize=true" align=middle width=187.69411649999998pt height=29.419440600000005pt/>
ways.

In the second case, there are <img src="/lectures/tex/5145fdcad0066cb8e8b7379e242063e0.svg?invert_in_darkmode&sanitize=true" align=middle width=171.95889809999997pt height=43.068412200000004pt/> ways.
