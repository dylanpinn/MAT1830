# Lecture 8: Predicate Logic

"She is the most famous actor in the world." is different from "She is the most
famous mathematician in the world."

## 8.1 Valid sentences

A sentence is valid in predicate logic is _valid_ if it has value T under all
interpretations.

## 8.2 Interpretations

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/17f64a139e50b1b08ba835c5ec43a907.svg?invert_in_darkmode" align=middle width=58.44762pt height=24.65759999999998pt/>

Two of the possible interpretations of this are:

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/200dba14407b3b760eaadaad8ae9bc2d.svg?invert_in_darkmode" align=middle width=39.920265pt height=24.65759999999998pt/> is "she is at least as famous as <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/>" and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/> ranges over all actors.

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/200dba14407b3b760eaadaad8ae9bc2d.svg?invert_in_darkmode" align=middle width=39.920265pt height=24.65759999999998pt/> is "she is at least as famous as <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/>" and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/> ranges over all
mathematicians.

### Question 8.1

Give interpretations which make the following false.

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6b729e736533801f0d91dbec08039870.svg?invert_in_darkmode" align=middle width=134.54743499999998pt height=16.438356pt/></p>

n ranges over the positive integers and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode" align=middle width=35.48919pt height=24.65759999999998pt/> is "n is prime"

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f6acacd1fd4e8fa8f07b420a8222576b.svg?invert_in_darkmode" align=middle width=176.15234999999998pt height=16.438356pt/></p>

x and y range over the real numbers and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/73919a441dd89d8138f79ea73c6a0d2f.svg?invert_in_darkmode" align=middle width=50.7441pt height=24.65759999999998pt/> is "<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/aa99d366a0125c60e3800f3bed358ad4.svg?invert_in_darkmode" align=middle width=39.961845000000004pt height=17.723969999999973pt/>".

### Question

Which of the following interpretations makes <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d706176a1a887dd5fedcc5687ae9067e.svg?invert_in_darkmode" align=middle width=97.98360000000001pt height=24.65759999999998pt/> false?

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/0e51a2dede42189d77627c4d742822c3.svg?invert_in_darkmode" align=middle width=14.433210000000003pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> range over the integers and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/dfd553bebb4c370f93bd39d020d83992.svg?invert_in_darkmode" align=middle width=55.418715pt height=24.65759999999998pt/> is "<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4085aa2f6047be42715b0d21cc1cdb2b.svg?invert_in_darkmode" align=middle width=54.436800000000005pt height=21.18732pt/>".

## 8.3 Recognising valid sentences

**Example**: <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/bafaccca156cfe0da6cb0152cf1c00db.svg?invert_in_darkmode" align=middle width=132.66pt height=24.65759999999998pt/> is true for all properties P, and
hence is valid.

## 8.4 Consequence and equivalence

### Question 8.2

Give an interpretation to show that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/faaf171caa9fc28ba3701d54bdbc5646.svg?invert_in_darkmode" align=middle width=117.96246pt height=24.65759999999998pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/79c7e94fe87a9d97cb0c1f44a4ad8564.svg?invert_in_darkmode" align=middle width=128.92143pt height=24.65759999999998pt/> are not equivalent.

Let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/> range over the integers, and let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/52be0087c9da1f0683ccc50761e8bcab.svg?invert_in_darkmode" align=middle width=35.01729pt height=24.65759999999998pt/> be "10 divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/>" and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/bc8afb5802dbe3a960f6436ffa035ed4.svg?invert_in_darkmode" align=middle width=33.367785000000005pt height=24.65759999999998pt/>
be "<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/> is even".

Then <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/faaf171caa9fc28ba3701d54bdbc5646.svg?invert_in_darkmode" align=middle width=117.96246pt height=24.65759999999998pt/> is true because there is an integer that is
divisible by 10 and is even (20 for example).

But <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/26ece453f5353462ff94ed2460ddc16f.svg?invert_in_darkmode" align=middle width=128.92143pt height=24.65759999999998pt/> is false because there is no integer that
is divisible by 10 and is odd.

So there is an interpretation in which one of these formulas is true and the
other is false. This means they're not logically equivalent.

### Question 8.3

Does <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/820067aa974b181de3f4f2726bde1924.svg?invert_in_darkmode" align=middle width=199.677555pt height=24.65759999999998pt/>?

No. Let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode" align=middle width=8.649300000000004pt height=14.155350000000013pt/> range over the real numbers and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/73919a441dd89d8138f79ea73c6a0d2f.svg?invert_in_darkmode" align=middle width=50.7441pt height=24.65759999999998pt/> be <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/aa99d366a0125c60e3800f3bed358ad4.svg?invert_in_darkmode" align=middle width=39.961845000000004pt height=17.723969999999973pt/>. Then
<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8a90d486d5bcd783a38aabbaf009c768.svg?invert_in_darkmode" align=middle width=87.053175pt height=24.65759999999998pt/> is true but <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e0e6c3457129622b4e7c6d81ffebea8e.svg?invert_in_darkmode" align=middle width=87.053175pt height=24.65759999999998pt/> is false.

## Question 8.4

Does <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/3d5c031e54db377f3a955f4159d26c51.svg?invert_in_darkmode" align=middle width=199.677555pt height=24.65759999999998pt/>?

Yes. If <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e0e6c3457129622b4e7c6d81ffebea8e.svg?invert_in_darkmode" align=middle width=87.053175pt height=24.65759999999998pt/> is true then there is one specific <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode" align=middle width=8.649300000000004pt height=14.155350000000013pt/>, say
<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7988ace88d5befc4da7b1849751ce84d.svg?invert_in_darkmode" align=middle width=13.169805000000002pt height=18.265169999999976pt/>, such that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/fdc63d70df5836450a94a3e1d823850f.svg?invert_in_darkmode" align=middle width=89.071455pt height=24.65759999999998pt/> for all <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/>. So then for any <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/332cc365a4987aacce0ead01b8bdcc0b.svg?invert_in_darkmode" align=middle width=9.395100000000005pt height=14.155350000000013pt/>
there is a value of <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/deceeaf6940a8c7a5a02373728002b0f.svg?invert_in_darkmode" align=middle width=8.649300000000004pt height=14.155350000000013pt/>, namely <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7988ace88d5befc4da7b1849751ce84d.svg?invert_in_darkmode" align=middle width=13.169805000000002pt height=18.265169999999976pt/>, such that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/1bf46c3434f57df254f8ffa991086cdf.svg?invert_in_darkmode" align=middle width=89.071455pt height=24.65759999999998pt/>.
So <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8a90d486d5bcd783a38aabbaf009c768.svg?invert_in_darkmode" align=middle width=87.053175pt height=24.65759999999998pt/> is true.

