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
<img src="/lectures/tex/bb13ebf60d342c9e474fdde6c7b7e422.svg?invert_in_darkmode&sanitize=true" align=middle width=21.621118199999987pt height=29.419440600000005pt/> such strings and so <img src="/lectures/tex/f09bc419c02de86b5d2aa177ffa6c76c.svg?invert_in_darkmode&sanitize=true" align=middle width=132.6084474pt height=29.419440600000005pt/>.
