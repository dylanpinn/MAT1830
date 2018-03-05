# Lecture 3: Congruences

Even integers are those that can be written as <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/f1738bbe3646e5962be59daa0aa34d56.svg?invert_in_darkmode" align=middle width=17.29464pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>. The
odd integers are those that can be written as <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6b00e9fecad2c902c76321d82303b8ce.svg?invert_in_darkmode" align=middle width=45.60501pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>.

We can split the integers into three classes; those that are <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/bcb0fe7fc0db81671c2169cae7d31ceb.svg?invert_in_darkmode" align=middle width=17.29464pt height=22.831379999999992pt/> for some
integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>, those that are <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/263b06bca66c6813dfa9f6a44b37410c.svg?invert_in_darkmode" align=middle width=45.60501pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>, and those that are
<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/734b57c261dea2f08d2d8716eae9801c.svg?invert_in_darkmode" align=middle width=45.60501pt height=22.831379999999992pt/> for some integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>.

These classes also have particular properties. For example, the some of an
integer in the second class and an integer in the third class will always be in
the first class.

We don't have to stop with 3. We could divide integers into 4 different classes
according to their remainders when divided by 4, and so on.

## 3.1 Congruences

Let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> be a positive integer and let <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode" align=middle width=8.689230000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/> be integers.

Basically <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode" align=middle width=37.66158pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) means that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/44bc9d542a92714cac84e01cbbb7fd61.svg?invert_in_darkmode" align=middle width=8.689230000000004pt height=14.155350000000013pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode" align=middle width=7.054855500000005pt height=22.831379999999992pt/> have the same remainder
when you divide them by <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>.

**Definition** We say <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode" align=middle width=37.66158pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) if <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/> divides <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/60ea14f79e208ac729da92907e80ab04.svg?invert_in_darkmode" align=middle width=35.835195000000006pt height=22.831379999999992pt/>.

**Equivalent definition** We say <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/221a6eec2aff3385193ce94d706a1b7c.svg?invert_in_darkmode" align=middle width=37.66158pt height=22.831379999999992pt/> (mod <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>) if <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/7e1cb77fdc8d07448d4c6e039adff15d.svg?invert_in_darkmode" align=middle width=76.69513500000001pt height=22.831379999999992pt/> for some
integer <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>.

Note we are talking about "congruence modulo _n_" as a relation here, which is
not quite the same as using a mod operation.

