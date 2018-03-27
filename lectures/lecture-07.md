# Lecture 7: Predicates and quantifiers

"Every real number is positive or negative."

False! But we want to be able to write it in logic and do things with it.

For example, we'd like to be able to say that its negation is "There is a real
number which is neither positive or negative."

## 7.1 Predicates

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode" align=middle width=35.48919pt height=24.65759999999998pt/>: "n is prime."

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/76aacde399706233c450f7a48e28adb4.svg?invert_in_darkmode" align=middle width=19.178115000000002pt height=14.155350000000013pt/> |
|-----|---|---|---|---|---|---|---|---|---|----|----|---------|
| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode" align=middle width=35.48919pt height=24.65759999999998pt/> |F|T | T | F | T | F | T | F | F | F  |  T | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/76aacde399706233c450f7a48e28adb4.svg?invert_in_darkmode" align=middle width=19.178115000000002pt height=14.155350000000013pt/> |

## 7.2 Building sentences from predicates

_Quantifiers_:

- <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ecea226b5977d1a327732124dccb8969.svg?invert_in_darkmode" align=middle width=9.132585000000002pt height=22.831379999999992pt/> (meaning "for all")
- <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/42353da95c0a3784bd8339b6e4fb1260.svg?invert_in_darkmode" align=middle width=9.132585000000002pt height=22.831379999999992pt/> (meaning "there exists" or "there is").

## 7.3 Quantifiers and connectives

### Question 7.1

Write down "roses are red" in predicate logic using:

rose(x): "x is a rose"

red(x): "x is red"

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8e5d5cee4ce9b587f97783a949902271.svg?invert_in_darkmode" align=middle width=152.56857pt height=24.65759999999998pt/>

### Question 7.2

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/df97415f8172a229024f8fdd42b8180b.svg?invert_in_darkmode" align=middle width=142.47535499999998pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/636115037645d5b7fae29df0bbef5ab0.svg?invert_in_darkmode" align=middle width=133.54274999999998pt height=16.438356pt/></p>

What does <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/bc8603105f0cd774b753dd97dabc42ca.svg?invert_in_darkmode" align=middle width=100.447215pt height=24.65759999999998pt/> mean?

"n is prime and n is not even." OR "n is an odd prime."

### Question 7.3

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/df8bbdcd15bd129bf9384026dbff6821.svg?invert_in_darkmode" align=middle width=190.76475pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f21ef815b40acdd01084ee3cd3356046.svg?invert_in_darkmode" align=middle width=148.84716pt height=16.438356pt/></p>

"All politicians are liars."

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7d8af122d1d9cd2a6aa985cf1c261583.svg?invert_in_darkmode" align=middle width=147.40885499999996pt height=24.65759999999998pt/>

"Some politicians are liars."

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/84e4a36e0edfbb12f5286a443f86d2a0.svg?invert_in_darkmode" align=middle width=140.102985pt height=24.65759999999998pt/>

"No politicians are liars."

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8a4670f0458facc0e31de16ec71d6b7b.svg?invert_in_darkmode" align=middle width=158.368155pt height=24.65759999999998pt/>

"Some politicians are not liars."

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/77edd86bd9299e652d197b58f13560bd.svg?invert_in_darkmode" align=middle width=151.061955pt height=24.65759999999998pt/>

### Question

Let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> range over the integers.

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/c8c02a6fffa7cbdf49bc81021a13e318.svg?invert_in_darkmode" align=middle width=44.621445pt height=24.65759999999998pt/> "n is prime."

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/da1213b6cdc8fd55abf73929a239e5cd.svg?invert_in_darkmode" align=middle width=44.8668pt height=24.65759999999998pt/> "n is even."

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7cef5b7dc8769438eb9d946c46331097.svg?invert_in_darkmode" align=middle width=44.70939pt height=24.65759999999998pt/> "<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/84872ff6fed071721ce0bdbc5e6a80be.svg?invert_in_darkmode" align=middle width=40.003755pt height=21.18732pt/>."

What does <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ac9fc2ab8274b08d26551ee5ccdc5691.svg?invert_in_darkmode" align=middle width=216.43165499999995pt height=24.65759999999998pt/> mean?

"All primes are greater than or equal to 3 are odd."

## 7.4 Alternating quantifiers

### Order of quantifiers

Let x and y range over all people.

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d6c5bc14f61bdf78d9bbbf1e94c7cd75.svg?invert_in_darkmode" align=middle width=180.153105pt height=24.65759999999998pt/> Think: ∀x(∃y(x is friends
with y)).

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/ff909371fdb83cca6f2cd3e326554342.svg?invert_in_darkmode" align=middle width=161.62525499999998pt height=24.65759999999998pt/> is saying “x has a friend.”

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d6c5bc14f61bdf78d9bbbf1e94c7cd75.svg?invert_in_darkmode" align=middle width=180.153105pt height=24.65759999999998pt/> is saying “Everybody has a
friend.”

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e93cf46348ef04504ee20a11551c387f.svg?invert_in_darkmode" align=middle width=180.153105pt height=24.65759999999998pt/> Think: ∃x(∀y(x is friends
with y))

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d7c12f651998dcea8f65a7566d15d9bb.svg?invert_in_darkmode" align=middle width=161.62525499999998pt height=24.65759999999998pt/> is saying “x is friends with
everybody.”

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e93cf46348ef04504ee20a11551c387f.svg?invert_in_darkmode" align=middle width=180.153105pt height=24.65759999999998pt/> is saying “There is
somebody that is friends with everybody."

### Question

Let c range over all countries and p range over all people <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/927b3e2edc178c188f19b22d8da7eeee.svg?invert_in_darkmode" align=middle width=57.444915pt height=24.65759999999998pt/> "p lives in
c."

What does <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4b403aead4b08b3e3e030794f0e8c83d.svg?invert_in_darkmode" align=middle width=72.82935pt height=24.65759999999998pt/> mean? Is it true?

"Every country has somebody living in it." TRUE

What does <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7e8596744510fcd44f0f6cfc8ae7940b.svg?invert_in_darkmode" align=middle width=81.96177pt height=24.65759999999998pt/> mean? Is it true?

"There is one country that everybody lives in." FALSE

### Question

Let x and y range over the integers. <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e404f236a293ec4a37cd7acfd97265c6.svg?invert_in_darkmode" align=middle width=151.54458pt height=24.65759999999998pt/>

Is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/cfa171e8bed4b838833ea24074dcda3b.svg?invert_in_darkmode" align=middle width=89.44468499999999pt height=24.65759999999998pt/> true or false? Is <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/424daa8813a9045c186f40079863f661.svg?invert_in_darkmode" align=middle width=89.44468499999999pt height=24.65759999999998pt/>
true or false?

The first statement says there is a single integer so that when any other
integer is added to it the result is 0. This is false.

The second statement says that for every integer there is another integer so
that when the two are added the result is 0. This is true.
