# Lecture 18: Order Relations

## 18.1 Partial order relations

A _partial order relation R_ on a set _A_ is a binary relation with the
following three properties.

1. Reflexivity. <img src="/lectures/tex/7ce734238de3a1df28eef503cc25155c.svg?invert_in_darkmode&sanitize=true" align=middle width=29.98677824999999pt height=22.465723500000017pt/> for all <img src="/lectures/tex/093389674502221e9d1394082bbabd6f.svg?invert_in_darkmode&sanitize=true" align=middle width=41.10908999999999pt height=22.465723500000017pt/>.
2. Antisymmetry. <img src="/lectures/tex/b3b3425b4ba9f5f69882ea9d0c802c3f.svg?invert_in_darkmode&sanitize=true" align=middle width=28.35242024999999pt height=22.831056599999986pt/> and <img src="/lectures/tex/462ad26b0a66af148b8baa93bef3d285.svg?invert_in_darkmode&sanitize=true" align=middle width=91.58460299999999pt height=22.831056599999986pt/> for all <img src="/lectures/tex/b62c2586b691b315f9b440ae4358ed02.svg?invert_in_darkmode&sanitize=true" align=middle width=55.46977094999998pt height=22.831056599999986pt/>.
3. Transitivity. <img src="/lectures/tex/b3b3425b4ba9f5f69882ea9d0c802c3f.svg?invert_in_darkmode&sanitize=true" align=middle width=28.35242024999999pt height=22.831056599999986pt/> and <img src="/lectures/tex/58b4ec2477394924e2151ae5a91db8c7.svg?invert_in_darkmode&sanitize=true" align=middle width=80.75909984999998pt height=22.831056599999986pt/> for all <img src="/lectures/tex/5d22b101a8e05a8b7a3f72eff1d3e90a.svg?invert_in_darkmode&sanitize=true" align=middle width=69.88945754999999pt height=22.831056599999986pt/>.

For a binary relation <img src="/lectures/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> on a set <img src="/lectures/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/>.

**Antisymmetry:** For all <img src="/lectures/tex/9311deac98c2602d33194f450b01649b.svg?invert_in_darkmode&sanitize=true" align=middle width=57.77001449999998pt height=22.465723500000017pt/>, if <img src="/lectures/tex/53712d99bae21b47e7c2bb25e64c6f5a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65266379999999pt height=22.465723500000017pt/> then <img src="/lectures/tex/b1185cf9f05b29c99b55c0cde01294f5.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96184334999999pt height=14.15524440000002pt/>.

This definition is useful for proofs but I think the contrapositive is more
intuitive.

**Antisymmetry (equivalent dfn):** For all <img src="/lectures/tex/9311deac98c2602d33194f450b01649b.svg?invert_in_darkmode&sanitize=true" align=middle width=57.77001449999998pt height=22.465723500000017pt/>, if <img src="/lectures/tex/fefeb2f61cc8685177b0a576d3e3cb95.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96184334999999pt height=22.831056599999986pt/> then it
is not the case that <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> and <img src="/lectures/tex/53712d99bae21b47e7c2bb25e64c6f5a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65266379999999pt height=22.465723500000017pt/>.

**Antisymmetry** (For a binary relation _R_ on a set _A_)

![](images/L18-P5.png)

To prove _R_ is antisymmetric, show that; For all <img src="/lectures/tex/9311deac98c2602d33194f450b01649b.svg?invert_in_darkmode&sanitize=true" align=middle width=57.77001449999998pt height=22.465723500000017pt/>, if <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> and
<img src="/lectures/tex/53712d99bae21b47e7c2bb25e64c6f5a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65266379999999pt height=22.465723500000017pt/> then <img src="/lectures/tex/b1185cf9f05b29c99b55c0cde01294f5.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96184334999999pt height=14.15524440000002pt/>.

To prove _R_ is not antisymmetric, show that; There is some <img src="/lectures/tex/9311deac98c2602d33194f450b01649b.svg?invert_in_darkmode&sanitize=true" align=middle width=57.77001449999998pt height=22.465723500000017pt/> such
that <img src="/lectures/tex/9cbb1b17ffb8fb4bdca2437258ddf640.svg?invert_in_darkmode&sanitize=true" align=middle width=77.92039199999998pt height=22.831056599999986pt/> and <img src="/lectures/tex/53712d99bae21b47e7c2bb25e64c6f5a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65266379999999pt height=22.465723500000017pt/>.

**Warning** Antisymmetric does not mean "not symmetric"!

**Question** Let _R_ be the relation _A_ pictured below. Is _R_ antisymmetric?

![](images/L18-P7-1.png)

Yes. For all <img src="/lectures/tex/9311deac98c2602d33194f450b01649b.svg?invert_in_darkmode&sanitize=true" align=middle width=57.77001449999998pt height=22.465723500000017pt/>, if <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> and <img src="/lectures/tex/53712d99bae21b47e7c2bb25e64c6f5a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65266379999999pt height=22.465723500000017pt/> then <img src="/lectures/tex/b1185cf9f05b29c99b55c0cde01294f5.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96184334999999pt height=14.15524440000002pt/>.

**Question** Let _S_ be the relation _A_ pictured below. Is _S_ antisymmetric?

![](images/L18-P7-2.png)

No. <img src="/lectures/tex/2d04e61cb98f6800037724871672eaaf.svg?invert_in_darkmode&sanitize=true" align=middle width=27.465800999999992pt height=22.465723500000017pt/> and <img src="/lectures/tex/4a29d640a7b86177b2f8fa0f4071af0a.svg?invert_in_darkmode&sanitize=true" align=middle width=27.465800999999992pt height=22.465723500000017pt/> (and <img src="/lectures/tex/ad1e0669a5d35368751260719af7dbff.svg?invert_in_darkmode&sanitize=true" align=middle width=44.748765599999984pt height=24.65753399999998pt/>.

**Examples.**

1. <img src="/lectures/tex/c85a67d18322c7784f40a29a9fd19c86.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=20.908638300000003pt/> on <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>
  Reflexive: <img src="/lectures/tex/c9f09401fe3eb3d79a8b6d19802264ab.svg?invert_in_darkmode&sanitize=true" align=middle width=39.29593799999999pt height=20.908638300000003pt/> for all <img src="/lectures/tex/3fdcf825afb8e2bee68b6e9fa814c29a.svg?invert_in_darkmode&sanitize=true" align=middle width=40.65247064999999pt height=22.648391699999998pt/>.
  Antisymmetric: <img src="/lectures/tex/ba7b0048fb01eb2791ba2ac6d678eade.svg?invert_in_darkmode&sanitize=true" align=middle width=37.66158164999999pt height=22.831056599999986pt/> and <img src="/lectures/tex/9647a82caadc981595d330fb91385e86.svg?invert_in_darkmode&sanitize=true" align=middle width=100.89376275pt height=22.831056599999986pt/> for all, <img src="/lectures/tex/a7339e6d81b4a0fcd2e53025c2eea2e5.svg?invert_in_darkmode&sanitize=true" align=middle width=55.013151599999986pt height=22.831056599999986pt/>.
  Transitive: <img src="/lectures/tex/ba7b0048fb01eb2791ba2ac6d678eade.svg?invert_in_darkmode&sanitize=true" align=middle width=37.66158164999999pt height=22.831056599999986pt/> and <img src="/lectures/tex/ecb43070eb29ed1df702ca095a1cadbb.svg?invert_in_darkmode&sanitize=true" align=middle width=99.37742099999997pt height=22.831056599999986pt/> for all <img src="/lectures/tex/c082e7a027ffb0e0e7ce6306c59de452.svg?invert_in_darkmode&sanitize=true" align=middle width=69.43283819999999pt height=22.831056599999986pt/>.
2. <img src="/lectures/tex/2e0145a5b0e7374cba1158796ba774c0.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=20.908638300000003pt/> on <img src="/lectures/tex/20c9d513a800b81d0cff408acaf23139.svg?invert_in_darkmode&sanitize=true" align=middle width=35.11995794999999pt height=24.65753399999998pt/>.
  Reflexive: <img src="/lectures/tex/2696e0a27aac15c721a172604f213ccc.svg?invert_in_darkmode&sanitize=true" align=middle width=46.575228149999994pt height=22.465723500000017pt/> for all <img src="/lectures/tex/e8578091b2399f04bec68fe254b4c1c4.svg?invert_in_darkmode&sanitize=true" align=middle width=63.90024959999998pt height=24.65753399999998pt/>.
  Antisymmetric: <img src="/lectures/tex/3c8b983d929a7dc3bcb427bbf20e86d6.svg?invert_in_darkmode&sanitize=true" align=middle width=47.539839599999986pt height=22.465723500000017pt/> and <img src="/lectures/tex/65f60b9e9d35b23b4dfe86c8dc5a9421.svg?invert_in_darkmode&sanitize=true" align=middle width=120.65027204999998pt height=22.465723500000017pt/> for all
  <img src="/lectures/tex/43817159ba5b94273c3eeceb0dc0c324.svg?invert_in_darkmode&sanitize=true" align=middle width=77.67683549999998pt height=24.65753399999998pt/>.
  Transitive: <img src="/lectures/tex/3c8b983d929a7dc3bcb427bbf20e86d6.svg?invert_in_darkmode&sanitize=true" align=middle width=47.539839599999986pt height=22.465723500000017pt/> and <img src="/lectures/tex/dc49ca2084cfb10a10c083e60d3030a8.svg?invert_in_darkmode&sanitize=true" align=middle width=120.87734504999999pt height=22.465723500000017pt/> for
  all <img src="/lectures/tex/7719a7890072057ed4ff861de545af9b.svg?invert_in_darkmode&sanitize=true" align=middle width=108.36970154999999pt height=24.65753399999998pt/>.
3. Divisibility on <img src="/lectures/tex/4fd661cfefdf4318d1aa35fb483796b2.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>.
  The relation "_a_ divides _b_" on natural numbers is reflexive, antisymmetric
  and transitive.
4. Alphabetical order of words.
  Words on the English alphabet are alphabetically ordered by comparing the
  leftmost letter at which they differ.

**Definition** A binary relation _R_ on a set _A_ is a _total order relation_
if:

- it is a partial order relation; and
- for any <img src="/lectures/tex/9311deac98c2602d33194f450b01649b.svg?invert_in_darkmode&sanitize=true" align=middle width=57.77001449999998pt height=22.465723500000017pt/> we have <img src="/lectures/tex/cd545545658252896318babb6260cb4a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65268359999999pt height=22.465723500000017pt/> or <img src="/lectures/tex/53712d99bae21b47e7c2bb25e64c6f5a.svg?invert_in_darkmode&sanitize=true" align=middle width=30.65266379999999pt height=22.465723500000017pt/>.

![](images/L18-P9.png)

**Example** <img src="/lectures/tex/c85a67d18322c7784f40a29a9fd19c86.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=20.908638300000003pt/> on <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/> is a total order relation (because for any
<img src="/lectures/tex/5de81020d9195d45c724e07c5f78636a.svg?invert_in_darkmode&sanitize=true" align=middle width=57.313395149999984pt height=22.648391699999998pt/> we have that <img src="/lectures/tex/cdfb20e63b6a1d9e6315da9104a271e9.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96184334999999pt height=20.908638300000003pt/> or <img src="/lectures/tex/ae34727a0b1c0584abd914efe4294a26.svg?invert_in_darkmode&sanitize=true" align=middle width=39.96182519999999pt height=20.908638300000003pt/>).

**Example** <img src="/lectures/tex/2e0145a5b0e7374cba1158796ba774c0.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=20.908638300000003pt/> on <img src="/lectures/tex/4b7a9696f7ae0fe4556882e908fe1e20.svg?invert_in_darkmode&sanitize=true" align=middle width=78.95559209999999pt height=24.65753399999998pt/> is not a total order relation (for
example, <img src="/lectures/tex/a3f06086efb289f29dbb02b66f700af3.svg?invert_in_darkmode&sanitize=true" align=middle width=86.7579801pt height=24.65753399999998pt/> and <img src="/lectures/tex/d461b96d777f12ca8f1c2a9343815960.svg?invert_in_darkmode&sanitize=true" align=middle width=86.7579801pt height=24.65753399999998pt/>).

## 18.2 Total order relations

A total order relation is a special kind of partial order relation that "puts
everything in order".

A _total order relation R_ on a set _A_ is a partial order relation that also
has the property <img src="/lectures/tex/b3b3425b4ba9f5f69882ea9d0c802c3f.svg?invert_in_darkmode&sanitize=true" align=middle width=28.35242024999999pt height=22.831056599999986pt/> or <img src="/lectures/tex/2549cc2462a00bf6823b401cd651d088.svg?invert_in_darkmode&sanitize=true" align=middle width=28.35242024999999pt height=22.831056599999986pt/> for all <img src="/lectures/tex/b62c2586b691b315f9b440ae4358ed02.svg?invert_in_darkmode&sanitize=true" align=middle width=55.46977094999998pt height=22.831056599999986pt/>.

**Examples.**

1. <img src="/lectures/tex/1af17265e819031033c1ab7d26c362d8.svg?invert_in_darkmode&sanitize=true" align=middle width=66.66669734999999pt height=22.831056599999986pt/>.
  This is a total order relation because for all real numbers _a_ and _b_ we
  have <img src="/lectures/tex/ba7b0048fb01eb2791ba2ac6d678eade.svg?invert_in_darkmode&sanitize=true" align=middle width=37.66158164999999pt height=22.831056599999986pt/> or <img src="/lectures/tex/307059ed570a9ed96829de9a48229299.svg?invert_in_darkmode&sanitize=true" align=middle width=37.66158164999999pt height=22.831056599999986pt/>.
2. <img src="/lectures/tex/2e0145a5b0e7374cba1158796ba774c0.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=20.908638300000003pt/> on <img src="/lectures/tex/20c9d513a800b81d0cff408acaf23139.svg?invert_in_darkmode&sanitize=true" align=middle width=35.11995794999999pt height=24.65753399999998pt/>.
  This is not a total order because, for example, <img src="/lectures/tex/656b2ff0ea36487397cb387d66f178e6.svg?invert_in_darkmode&sanitize=true" align=middle width=102.28307264999998pt height=24.65753399999998pt/> and <img src="/lectures/tex/2e9fd10f1fce4a3a386b069064ec56f1.svg?invert_in_darkmode&sanitize=true" align=middle width=102.28307264999998pt height=24.65753399999998pt/>.
3. Divisibility on <img src="/lectures/tex/4fd661cfefdf4318d1aa35fb483796b2.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>.
  This is not a total order because, for example, 2 does not divide 3 and 3 does
  not divide 2.
4. Alphabetical order of words.
  This is a total order because given any two different words, one will appear
  before the other in alphabetical order.
