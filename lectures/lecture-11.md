# Lecture 11: Sets

**Sets - why should you care?**

- Sets are an important data structure when programming.
- Sets are very important concepts CS and maths.
- Set notation is used a lot in writing about CS and maths.
- The standard approach to building maths up from logic is based on sets.

Sets are vital in expressing mathematics formally and are also very important
data structures in computer science.

A set is basically just an unordered collection of distinct objects, which we
call its _elements_ or _members_. Note that there is no notion of order for a
set, even though we often write down its elements in some order for convenience.
Also, there is no notion of multiplicity: an object is either in a set or not -
it cannot be in the set multiple times.

Sets _A_ and _B_ are equal when every element of _A_ is an element of _B_ and
vice-versa.

## 11.1 Set notation

- <img src="/lectures/tex/f6df514422dc78ee1050d56402d63ef9.svg?invert_in_darkmode&sanitize=true" align=middle width=40.513527449999984pt height=22.465723500000017pt/> means that _x_ is an element of set _S_.
- <img src="/lectures/tex/1f0baa1f7eae73d789419b02f13a70ea.svg?invert_in_darkmode&sanitize=true" align=middle width=110.58206114999999pt height=24.65753399999998pt/> is the set with elements <img src="/lectures/tex/d5c9279a24b113348b150b31b3e4f0e9.svg?invert_in_darkmode&sanitize=true" align=middle width=91.40398244999999pt height=14.15524440000002pt/>
- <img src="/lectures/tex/9945ec71be114e1aa39e8cf726f4648c.svg?invert_in_darkmode&sanitize=true" align=middle width=74.54902125pt height=24.65753399999998pt/> is the set of all _x_ with property _P_.

**Example.**

<p align="center"><img src="/lectures/tex/0831bd557c17a9083d545f27679e6bc9.svg?invert_in_darkmode&sanitize=true" align=middle width=323.9492586pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/c61353f4d79a18be78a2d1f393a628fb.svg?invert_in_darkmode&sanitize=true" align=middle width=133.33325775pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/91c26afa6786e50f00a847e05659c4eb.svg?invert_in_darkmode&sanitize=true" align=middle width=100.45663319999998pt height=16.438356pt/></p>

For a finite set <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/>, we write <img src="/lectures/tex/65840c883e7323ab67192c3db4729de1.svg?invert_in_darkmode&sanitize=true" align=middle width=20.159830349999993pt height=24.65753399999998pt/> for the number of elements of <img src="/lectures/tex/e257acd1ccbe7fcb654708f1a866bfe9.svg?invert_in_darkmode&sanitize=true" align=middle width=11.027402099999989pt height=22.465723500000017pt/>.
