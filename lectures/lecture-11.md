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
- <img src="/lectures/tex/f21a321fb872de33723aaddf4d7c121a.svg?invert_in_darkmode&sanitize=true" align=middle width=10.045686749999991pt height=22.648391699999998pt/> empty set <img src="/lectures/tex/4ff29620e88188582cae13f73fcb04b2.svg?invert_in_darkmode&sanitize=true" align=middle width=16.438418699999993pt height=24.65753399999998pt/>
