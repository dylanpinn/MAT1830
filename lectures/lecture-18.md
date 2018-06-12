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
