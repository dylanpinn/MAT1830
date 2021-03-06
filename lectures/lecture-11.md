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

**Question:** Let <img src="/lectures/tex/6c4428fe578b3435e53c1acd6a6d030b.svg?invert_in_darkmode&sanitize=true" align=middle width=182.51896409999998pt height=24.65753399999998pt/>.

Is <img src="/lectures/tex/f2327da2f28224c690e81d27baf85f74.svg?invert_in_darkmode&sanitize=true" align=middle width=39.807693749999984pt height=22.465723500000017pt/>? Yes

Is <img src="/lectures/tex/af8562d7be650ceb0abd32e1c31104a2.svg?invert_in_darkmode&sanitize=true" align=middle width=38.173335749999985pt height=22.831056599999986pt/>? No

**Question:** Is <img src="/lectures/tex/3e3bbc408c616bb1d2909c5a57f7efeb.svg?invert_in_darkmode&sanitize=true" align=middle width=56.24611244999999pt height=24.65753399999998pt/>? Is <img src="/lectures/tex/e3501d225d4caf98a243c3e088b02fab.svg?invert_in_darkmode&sanitize=true" align=middle width=70.60679174999999pt height=24.65753399999998pt/>?

Answer: Yes, No.

**Question:**

Let <img src="/lectures/tex/8cdfdca660369c4088f26a103cff8cd9.svg?invert_in_darkmode&sanitize=true" align=middle width=88.43404019999998pt height=24.65753399999998pt/>. What is <img src="/lectures/tex/b131ee40f802f4941063a6a8351c97d5.svg?invert_in_darkmode&sanitize=true" align=middle width=21.74091809999999pt height=24.65753399999998pt/>? **3**

Let <img src="/lectures/tex/5c7a680f371832cf155e80cc0eea4411.svg?invert_in_darkmode&sanitize=true" align=middle width=182.51896409999998pt height=24.65753399999998pt/>. What is <img src="/lectures/tex/65840c883e7323ab67192c3db4729de1.svg?invert_in_darkmode&sanitize=true" align=middle width=20.159830349999993pt height=24.65753399999998pt/>? **4**

Let <img src="/lectures/tex/abbfcd889a362deba9a7101429f6adbc.svg?invert_in_darkmode&sanitize=true" align=middle width=150.7017996pt height=24.65753399999998pt/>. What is <img src="/lectures/tex/64d5b62235f6fbfef0ee9c4ec7f7624e.svg?invert_in_darkmode&sanitize=true" align=middle width=21.021758999999992pt height=24.65753399999998pt/>? **101**

What is <img src="/lectures/tex/53ad727ba87ae15d58f31805f1f26432.svg?invert_in_darkmode&sanitize=true" align=middle width=25.57086674999999pt height=24.65753399999998pt/>? **0**

### Question 11.1

<img src="/lectures/tex/9558402e4701b4901b73fda0b34173be.svg?invert_in_darkmode&sanitize=true" align=middle width=44.39492144999999pt height=24.65753399999998pt/> "x is even"

<img src="/lectures/tex/717a497105a214f1c655cd26cfd8e001.svg?invert_in_darkmode&sanitize=true" align=middle width=44.16666704999999pt height=24.65753399999998pt/> "5 divides x" (Assume we're working in the integers <img src="/lectures/tex/97724efe1d61e77783b76251d3ae68dc.svg?invert_in_darkmode&sanitize=true" align=middle width=25.570741349999988pt height=21.18721440000001pt/>).

What is the set <img src="/lectures/tex/ea7ee7e9becffadaef1942b97975e3b7.svg?invert_in_darkmode&sanitize=true" align=middle width=128.09346824999997pt height=24.65753399999998pt/>?

The set containing all multiples of 10, that is <img src="/lectures/tex/193a538e58aada3f09c221e1c9d06279.svg?invert_in_darkmode&sanitize=true" align=middle width=125.11406654999999pt height=24.65753399999998pt/>.

Write a formula for the set <img src="/lectures/tex/95bbeb3ff6f126f4f90b12125a8e3bea.svg?invert_in_darkmode&sanitize=true" align=middle width=125.11406654999999pt height=24.65753399999998pt/>.

<img src="/lectures/tex/25e82f2d09e70e00054f3166bedbda86.svg?invert_in_darkmode&sanitize=true" align=middle width=139.0524102pt height=24.65753399999998pt/>

## 11.2 Universal set

The idea of a "set of all sets" leads to logical difficulties. Difficulties are
avoided by always working within a local "universal set" which includes only
those objects under consideration.

For example, when discussing arithmetic it might be sufficient to work just with
numbers <img src="/lectures/tex/5a1c15190d207b036ba70588a3a3b15a.svg?invert_in_darkmode&sanitize=true" align=middle width=81.27835979999999pt height=21.18721440000001pt/>. Our universal set could then be taken as

<p align="center"><img src="/lectures/tex/821944705ea61bde1bf97d240809b162.svg?invert_in_darkmode&sanitize=true" align=middle width=134.24624895pt height=16.438356pt/></p>

, and other sets of interest, e.g. <img src="/lectures/tex/327ec78623d1a3d9e7668ebd5b0022b7.svg?invert_in_darkmode&sanitize=true" align=middle width=117.55702859999997pt height=24.65753399999998pt/>, are parts of
<img src="/lectures/tex/4fd661cfefdf4318d1aa35fb483796b2.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>.

### Important sets

- <img src="/lectures/tex/4fd661cfefdf4318d1aa35fb483796b2.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/> natural numbers <img src="/lectures/tex/23ab5f88fff6bc77e39976f07a64ad20.svg?invert_in_darkmode&sanitize=true" align=middle width=84.93134594999998pt height=24.65753399999998pt/>.
- <img src="/lectures/tex/b9477ea14234215f4d516bad55d011b8.svg?invert_in_darkmode&sanitize=true" align=middle width=10.95894029999999pt height=22.648391699999998pt/> integers <img src="/lectures/tex/f9308236d569f86005633f85db36d673.svg?invert_in_darkmode&sanitize=true" align=middle width=170.77593059999998pt height=24.65753399999998pt/>
- <img src="/lectures/tex/0f452ec0bcf578fa387e4857f80f03f4.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=22.648391699999998pt/> rational numbers <img src="/lectures/tex/36cbdba2d529a6aafad364c8c4c3befd.svg?invert_in_darkmode&sanitize=true" align=middle width=139.809846pt height=24.65753399999998pt/>
- <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/> real numbers
- <img src="/lectures/tex/53fe7f87db69e0ed1312d865111c131f.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=24.65753399999998pt/> empty set <img src="/lectures/tex/4ff29620e88188582cae13f73fcb04b2.svg?invert_in_darkmode&sanitize=true" align=middle width=16.438418699999993pt height=24.65753399999998pt/>

## 11.3 Subsets

We say that <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> is a _subset_ of <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> and write <img src="/lectures/tex/3c8b983d929a7dc3bcb427bbf20e86d6.svg?invert_in_darkmode&sanitize=true" align=middle width=47.539839599999986pt height=22.465723500000017pt/> when each element
of <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> is an element of <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/>.

**Example.** The set of primes forms a _subset_ of <img src="/lectures/tex/4fd661cfefdf4318d1aa35fb483796b2.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>, that is <img src="/lectures/tex/f8237436d95f7b6e9d9b5d71579ef238.svg?invert_in_darkmode&sanitize=true" align=middle width=151.34683739999997pt height=24.65753399999998pt/>.

![](images/L10-P16.png)

Formally, <img src="/lectures/tex/3c8b983d929a7dc3bcb427bbf20e86d6.svg?invert_in_darkmode&sanitize=true" align=middle width=47.539839599999986pt height=22.465723500000017pt/> if <img src="/lectures/tex/ca9e4bc485ba76efbfb1eeca0add5a5f.svg?invert_in_darkmode&sanitize=true" align=middle width=141.47792339999998pt height=24.65753399999998pt/>.

That is, <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> is a subset of <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> if every element of <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> is also an element of
<img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/>.

**Notes:** Every set is a subset of itself. <img src="/lectures/tex/4ff29620e88188582cae13f73fcb04b2.svg?invert_in_darkmode&sanitize=true" align=middle width=16.438418699999993pt height=24.65753399999998pt/> is a subset of every set.

**Question:** Let <img src="/lectures/tex/6c4428fe578b3435e53c1acd6a6d030b.svg?invert_in_darkmode&sanitize=true" align=middle width=182.51896409999998pt height=24.65753399999998pt/>.

Is <img src="/lectures/tex/4f59846a3287403b6fc42ed9de7e52a6.svg?invert_in_darkmode&sanitize=true" align=middle width=56.43824834999999pt height=24.65753399999998pt/>? No, because <img src="/lectures/tex/089abefb2a541f5b395e299786d321ff.svg?invert_in_darkmode&sanitize=true" align=middle width=38.173335749999985pt height=22.831056599999986pt/>.

Is <img src="/lectures/tex/dcf794618dc2183737ca6838a00a2f2f.svg?invert_in_darkmode&sanitize=true" align=middle width=126.59231144999998pt height=24.65753399999998pt/>? Yes, because <img src="/lectures/tex/f2327da2f28224c690e81d27baf85f74.svg?invert_in_darkmode&sanitize=true" align=middle width=39.807693749999984pt height=22.465723500000017pt/> and <img src="/lectures/tex/745c257a5c617c8a8cbcb3d84b944276.svg?invert_in_darkmode&sanitize=true" align=middle width=85.02647999999998pt height=24.65753399999998pt/>.

**Question:** Is <img src="/lectures/tex/5f63d107bacd2c99a2bea4bcb2f26186.svg?invert_in_darkmode&sanitize=true" align=middle width=72.43328399999999pt height=24.65753399999998pt/>? Is <img src="/lectures/tex/38b12de86257840f2d9ebbc28d7d7850.svg?invert_in_darkmode&sanitize=true" align=middle width=105.31012304999999pt height=24.65753399999998pt/>?

- A: Yes, yes
- B: Yes, no
- C: No, yes
- D: No, no

**Answer:**

<img src="/lectures/tex/60f17e6b0647db012bdd49b296037039.svg?invert_in_darkmode&sanitize=true" align=middle width=72.43328399999999pt height=24.65753399999998pt/> because <img src="/lectures/tex/089abefb2a541f5b395e299786d321ff.svg?invert_in_darkmode&sanitize=true" align=middle width=38.173335749999985pt height=22.831056599999986pt/>.

<img src="/lectures/tex/2a6617c09aff68cee9a883c86302ba95.svg?invert_in_darkmode&sanitize=true" align=middle width=105.31012304999999pt height=24.65753399999998pt/> because <img src="/lectures/tex/3e3bbc408c616bb1d2909c5a57f7efeb.svg?invert_in_darkmode&sanitize=true" align=middle width=56.24611244999999pt height=24.65753399999998pt/> and <img src="/lectures/tex/0524c3660841104ac89587f2fb27a64a.svg?invert_in_darkmode&sanitize=true" align=middle width=54.611754449999985pt height=24.65753399999998pt/>.

So C.

## 11.4 Characteristic functions

A subset <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> of <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> can be specified by its _characteristic function_ <img src="/lectures/tex/116b5dfc1436d5c53775b6cf36dc3c9d.svg?invert_in_darkmode&sanitize=true" align=middle width=22.614152549999993pt height=22.465723500000017pt/>,
which tells which elements of <img src="/lectures/tex/61e84f854bc6258d4108d08d4c4a0852.svg?invert_in_darkmode&sanitize=true" align=middle width=13.29340979999999pt height=22.465723500000017pt/> are in <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> and which are not.

<p align="center"><img src="/lectures/tex/2d33dc70b770b5f066845ad95da06fa7.svg?invert_in_darkmode&sanitize=true" align=middle width=166.26891104999999pt height=49.315569599999996pt/></p>

**Example.** The subset <img src="/lectures/tex/c6113301d0cb68b238b9a3d55966af7b.svg?invert_in_darkmode&sanitize=true" align=middle width=73.79368919999999pt height=24.65753399999998pt/> of <img src="/lectures/tex/c20d5daf394618a6e0e0161de3de1549.svg?invert_in_darkmode&sanitize=true" align=middle width=89.11897499999998pt height=24.65753399999998pt/> has the characteristic
function <img src="/lectures/tex/9740dbd219e0391bb4595149ed2ef6a6.svg?invert_in_darkmode&sanitize=true" align=middle width=20.171264849999986pt height=14.15524440000002pt/> with

<p align="center"><img src="/lectures/tex/15ac5672ca1d99d3f80be39827991f62.svg?invert_in_darkmode&sanitize=true" align=middle width=229.21582529999998pt height=16.438356pt/></p>

We also write this function more simply as

- a b c
- 1 0 1

In fact we can list all characteristic functions on <img src="/lectures/tex/b5935d2873e269fe97955fa45c8ee5a6.svg?invert_in_darkmode&sanitize=true" align=middle width=53.90794035pt height=24.65753399999998pt/>, and hence all
subsets of <img src="/lectures/tex/b5935d2873e269fe97955fa45c8ee5a6.svg?invert_in_darkmode&sanitize=true" align=middle width=53.90794035pt height=24.65753399999998pt/>, by listing all sequences of three binary digits:

| characteristic function | subset |
|-------------------------|--------|
| a b c                   |        |
| 0 0 0                   | <img src="/lectures/tex/4ff29620e88188582cae13f73fcb04b2.svg?invert_in_darkmode&sanitize=true" align=middle width=16.438418699999993pt height=24.65753399999998pt/> |
| 0 0 1                   | <img src="/lectures/tex/54503bfb2865a3ed5bb8f924c557ab22.svg?invert_in_darkmode&sanitize=true" align=middle width=23.552223749999985pt height=24.65753399999998pt/> |
| 0 1 0                   | <img src="/lectures/tex/3f119c53287d45650d843885ff6ee115.svg?invert_in_darkmode&sanitize=true" align=middle width=23.493214799999986pt height=24.65753399999998pt/> |
| 0 1 1                   | <img src="/lectures/tex/6ac258419e7ab63fb46fa353dc2fc36d.svg?invert_in_darkmode&sanitize=true" align=middle width=37.91290304999999pt height=24.65753399999998pt/> |
| 1 0 0                   | <img src="/lectures/tex/c3e2cf59ab52ddb82646528b31dc523a.svg?invert_in_darkmode&sanitize=true" align=middle width=25.12757279999999pt height=24.65753399999998pt/> |
| 1 0 1                   | <img src="/lectures/tex/c5e9578fb772b0ecd601fbaefaf9f1c2.svg?invert_in_darkmode&sanitize=true" align=middle width=39.54726104999999pt height=24.65753399999998pt/> |
| 1 1 0                   | <img src="/lectures/tex/862d66bb688d01a807467833e7a64042.svg?invert_in_darkmode&sanitize=true" align=middle width=39.48825209999999pt height=24.65753399999998pt/> |
| 1 1 1                   | <img src="/lectures/tex/b5935d2873e269fe97955fa45c8ee5a6.svg?invert_in_darkmode&sanitize=true" align=middle width=53.90794035pt height=24.65753399999998pt/> |

We could similarly list all the subsets of a four-element set, and there would
be <img src="/lectures/tex/49db0ca540e68dc1e939eaf219ad8c35.svg?invert_in_darkmode&sanitize=true" align=middle width=53.94971834999998pt height=26.76175259999998pt/> of them, corresponding to the <img src="/lectures/tex/812eddc94b3c44a52699e8da08d64dd6.svg?invert_in_darkmode&sanitize=true" align=middle width=14.771756999999988pt height=26.76175259999998pt/> sequences of 0s and 1s.

In the same way, we find that an n-element set has <img src="/lectures/tex/f8f25e4580c418a51dc556db0d8d2b93.svg?invert_in_darkmode&sanitize=true" align=middle width=16.34523329999999pt height=21.839370299999988pt/> subsets, because there
are <img src="/lectures/tex/f8f25e4580c418a51dc556db0d8d2b93.svg?invert_in_darkmode&sanitize=true" align=middle width=16.34523329999999pt height=21.839370299999988pt/> binary sequences of length <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/>. (Each of the <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> places in the
sequences can be filled in two ways.)

## 11.5 Power set

The set of all subsets of a set <img src="/lectures/tex/6bac6ec50c01592407695ef84f457232.svg?invert_in_darkmode&sanitize=true" align=middle width=13.01596064999999pt height=22.465723500000017pt/> is called the _power set_ <img src="/lectures/tex/9fda00268f20291ca7188a0a602fd929.svg?invert_in_darkmode&sanitize=true" align=middle width=36.26371814999999pt height=24.65753399999998pt/> of
<img src="/lectures/tex/6bac6ec50c01592407695ef84f457232.svg?invert_in_darkmode&sanitize=true" align=middle width=13.01596064999999pt height=22.465723500000017pt/>.

**Example.** We see from the previous table that <img src="/lectures/tex/be5b3ab41f9ea2228586505bd75f9249.svg?invert_in_darkmode&sanitize=true" align=middle width=85.84487339999998pt height=24.65753399999998pt/> is the
set

<p align="center"><img src="/lectures/tex/03e0fbf81cdc5b06cd2b18ee90781da0.svg?invert_in_darkmode&sanitize=true" align=middle width=331.61361089999997pt height=16.438356pt/></p>

If <img src="/lectures/tex/6bac6ec50c01592407695ef84f457232.svg?invert_in_darkmode&sanitize=true" align=middle width=13.01596064999999pt height=22.465723500000017pt/> has <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> elements, then <img src="/lectures/tex/9fda00268f20291ca7188a0a602fd929.svg?invert_in_darkmode&sanitize=true" align=middle width=36.26371814999999pt height=24.65753399999998pt/> has <img src="/lectures/tex/f8f25e4580c418a51dc556db0d8d2b93.svg?invert_in_darkmode&sanitize=true" align=middle width=16.34523329999999pt height=21.839370299999988pt/> elements.

**Questions:**

How many subsets does <img src="/lectures/tex/d2bd286081002058b5306c1d2c5af908.svg?invert_in_darkmode&sanitize=true" align=middle width=87.67132439999999pt height=24.65753399999998pt/> have? <img src="/lectures/tex/49db0ca540e68dc1e939eaf219ad8c35.svg?invert_in_darkmode&sanitize=true" align=middle width=53.94971834999998pt height=26.76175259999998pt/>

**Question:**

What is <img src="/lectures/tex/51e2c123aa8de712f82a7ea0802cb6e6.svg?invert_in_darkmode&sanitize=true" align=middle width=110.91910334999999pt height=24.65753399999998pt/>?

<img src="/lectures/tex/9b4552a5696eb6defb0a38a4d9ed1b35.svg?invert_in_darkmode&sanitize=true" align=middle width=907.7634340499998pt height=24.65753399999998pt/>

## 11.6 Sets and properties

We mentioned at the beginning that <img src="/lectures/tex/83f1c4f904aae11b5d136390b1659bbb.svg?invert_in_darkmode&sanitize=true" align=middle width=74.54902125pt height=24.65753399999998pt/> stands for the set of objects
<img src="/lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode&sanitize=true" align=middle width=9.39498779999999pt height=14.15524440000002pt/> with property <img src="/lectures/tex/df5a289587a2f0247a5b97c1e8ac58ca.svg?invert_in_darkmode&sanitize=true" align=middle width=12.83677559999999pt height=22.465723500000017pt/>. Thus sets correspond to properties.

Properties of the natural numbers <img src="/lectures/tex/12069d2c8fd405e0321f158983089448.svg?invert_in_darkmode&sanitize=true" align=middle width=88.58424299999999pt height=21.18721440000001pt/> for example, correspond to
subsets of the set <img src="/lectures/tex/c73a7487724c0a68b6d85f1a7669f555.svg?invert_in_darkmode&sanitize=true" align=middle width=134.24624895pt height=24.65753399999998pt/>. Thus the subset

<p align="center"><img src="/lectures/tex/fefef07803d0b4b203a111cfba72b50e.svg?invert_in_darkmode&sanitize=true" align=middle width=268.22629185pt height=16.438356pt/></p>

corresponds to the property of being even. Similarly, the set

<p align="center"><img src="/lectures/tex/66babcc63ab8084550a1035627fabe8b.svg?invert_in_darkmode&sanitize=true" align=middle width=266.6665518pt height=16.438356pt/></p>

corresponds to the property of being prime. The power set <img src="/lectures/tex/4d69a69860667da9feda4f7a4f8b785a.svg?invert_in_darkmode&sanitize=true" align=middle width=38.247747449999984pt height=24.65753399999998pt/> corresponds
to all possible properties of natural numbers.

**Question 11.3** Consider the sets

<p align="center"><img src="/lectures/tex/8afa695b7e4642b65139acc6d0b8d389.svg?invert_in_darkmode&sanitize=true" align=middle width=109.20049635pt height=16.438356pt/></p>
<p align="center"><img src="/lectures/tex/0f985deb7cb51ae916575a1ae913b095.svg?invert_in_darkmode&sanitize=true" align=middle width=113.1456843pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/a686708f8ba16435bc7f97dfe66bdeea.svg?invert_in_darkmode&sanitize=true" align=middle width=113.1456843pt height=32.990165999999995pt/></p>
<p align="center"><img src="/lectures/tex/356f5fa84917fb215beba65ec09687d8.svg?invert_in_darkmode&sanitize=true" align=middle width=113.1456843pt height=32.990165999999995pt/></p>

Do they have an element in common?

No. Suppose they had <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> in common. Then <img src="/lectures/tex/ac4347acd383a6b21d3794b0b621326e.svg?invert_in_darkmode&sanitize=true" align=middle width=38.009795999999994pt height=21.18721440000001pt/>, so there is a (big) natural
number <img src="/lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode&sanitize=true" align=middle width=9.86687624999999pt height=14.15524440000002pt/> such that <img src="/lectures/tex/08316d6d59ba59aef094254b1c67a785.svg?invert_in_darkmode&sanitize=true" align=middle width=39.88920704999999pt height=27.77565449999998pt/>. But then <img src="/lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> is not in the set <img src="/lectures/tex/813fa296531d5310e29c4a5bf50e9cee.svg?invert_in_darkmode&sanitize=true" align=middle width=113.05250219999999pt height=27.77565449999998pt/>. Contradiction.
