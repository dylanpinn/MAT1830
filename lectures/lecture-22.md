# Lecture 22: Conditional probability and Bayes' theorem

## Conditional probability

Conditional probabilities measure the likelihood of an event, given that some
other event occurs.

For events _A_ and _B_, the _conditional probability of A given B_ is

<p align="center"><img src="/lectures/tex/e2a7af74439812f95f0d982d1bb1c0ee.svg?invert_in_darkmode&sanitize=true" align=middle width=158.78763615pt height=38.83491479999999pt/></p>

This definition also implies that <img src="/lectures/tex/5860fd7aa37e7846276de471c1e73221.svg?invert_in_darkmode&sanitize=true" align=middle width=203.25914235pt height=24.65753399999998pt/>.

**Example** A spinner is spun. Let _A_ be the event that the result was at least
3 and _B_ be the event that the result was even. What is <img src="/lectures/tex/55fc1799f50d66462cc650ec731dc094.svg?invert_in_darkmode&sanitize=true" align=middle width=60.59946749999999pt height=24.65753399999998pt/>?

- <img src="/lectures/tex/0e343ab47260a10a7a1aa578ae459819.svg?invert_in_darkmode&sanitize=true" align=middle width=165.28859654999997pt height=27.77565449999998pt/>
- <img src="/lectures/tex/33fa8b89d05880f001355f1b00ad4095.svg?invert_in_darkmode&sanitize=true" align=middle width=256.4208372pt height=27.77565449999998pt/>
- Thus, <img src="/lectures/tex/33cf43c44f88cb083eeb182b58c89ae3.svg?invert_in_darkmode&sanitize=true" align=middle width=205.79041394999996pt height=37.54198139999998pt/>.

**Example** A binary string of length 6 is generated uniformly at random. Let
_A_ be the event that is the first bit is a 1 and _B_ be the event that the
string contains two 1s. What is <img src="/lectures/tex/55fc1799f50d66462cc650ec731dc094.svg?invert_in_darkmode&sanitize=true" align=middle width=60.59946749999999pt height=24.65753399999998pt/>?

There are <img src="/lectures/tex/c3a4aa729873ec54312d9af87608014d.svg?invert_in_darkmode&sanitize=true" align=middle width=14.771756999999988pt height=26.76175259999998pt/> strings in our sample space. Now <img src="/lectures/tex/b0c1a78bbd8d865698d311abad4d5d92.svg?invert_in_darkmode&sanitize=true" align=middle width=43.88690624999999pt height=22.465723500000017pt/> occurs when the
first bit is a 1 and the rest of the string contains one 1. There are
<img src="/lectures/tex/bb13ebf60d342c9e474fdde6c7b7e422.svg?invert_in_darkmode&sanitize=true" align=middle width=21.621118199999987pt height=29.419440600000005pt/> such strings and so <img src="/lectures/tex/a4ab93c2ac3d07b6a7744ad664cb66f0.svg?invert_in_darkmode&sanitize=true" align=middle width=116.56729589999999pt height=43.068412200000004pt/>.
Also, there are <img src="/lectures/tex/cce20003de73186579b665e0a0cdce0f.svg?invert_in_darkmode&sanitize=true" align=middle width=21.621118199999987pt height=29.419440600000005pt/> strings containing two 1s and so <img src="/lectures/tex/d55866b63b168d385532761ccb0f5f94.svg?invert_in_darkmode&sanitize=true" align=middle width=85.97379944999999pt height=43.068412200000004pt/>. Thus,

<p align="center"><img src="/lectures/tex/939af30e0be5c81bda5857bd2e496f51.svg?invert_in_darkmode&sanitize=true" align=middle width=240.35357775pt height=45.528984599999994pt/></p>.

**Exercise** A normal die is rolled. Let _A_ be the event that the result is an
odd number. Let _B_ be the event that the result is a square number.

- **A:** <img src="/lectures/tex/305470adb8ae7a49e1f58a418dfcab14.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/ee337f7160622a3b2a96bdaaaa9d5f6d.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>
- **B:** <img src="/lectures/tex/305470adb8ae7a49e1f58a418dfcab14.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/da76a6832f25f6f26a36a40734d3a2d2.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>
- **C:** <img src="/lectures/tex/5443b7403614410d29d8cf88d066e473.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/6e6c73f707c99eeac6fe5d344c296bc7.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>
- **D:** <img src="/lectures/tex/32405c6978e4b4a9750a08bd29701121.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/> and <img src="/lectures/tex/ee337f7160622a3b2a96bdaaaa9d5f6d.svg?invert_in_darkmode&sanitize=true" align=middle width=91.04224139999998pt height=27.77565449999998pt/>

**ANS: B:** Since <img src="/lectures/tex/c74f8d51bd5e63b0732f4d8b00a59cff.svg?invert_in_darkmode&sanitize=true" align=middle width=90.46215914999999pt height=24.65753399999998pt/> we see that <img src="/lectures/tex/714d73b92779626634bdaeede1500980.svg?invert_in_darkmode&sanitize=true" align=middle width=104.74071629999999pt height=27.77565449999998pt/>.
So

<p align="center"><img src="/lectures/tex/85a4e1706b50c55f8ba00bef2691feb6.svg?invert_in_darkmode&sanitize=true" align=middle width=229.2301968pt height=43.715357399999995pt/></p>

<p align="center"><img src="/lectures/tex/6edf12e0b00d973677d169ad6c0555a7.svg?invert_in_darkmode&sanitize=true" align=middle width=229.2301968pt height=43.715357399999995pt/></p>