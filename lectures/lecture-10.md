# Lecture 10: Induction and well-ordering

In the previous lecture we were able to prove a property _P_ holds for 0,1,2,...
as follows:

**Base step.** Prove <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/c94461c42a545e128f875c4c5b07f994.svg?invert_in_darkmode" align=middle width=33.8415pt height=24.65759999999998pt/>

**Induction step.** Prove <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8d964ff95bb74502bce8da917cfee26f.svg?invert_in_darkmode" align=middle width=123.27612000000002pt height=24.65759999999998pt/> for each natural number <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/63bb9849783d01d91403bc9a5fea12a2.svg?invert_in_darkmode" align=middle width=9.075495000000004pt height=22.831379999999992pt/>.

This is sufficient to prove that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e720ef2e3dc10278f2cc0341a8635074.svg?invert_in_darkmode" align=middle width=35.48919pt height=24.65759999999998pt/> holds for all natural numbers <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/55a049b8f161ae7cfeb0197d75aff967.svg?invert_in_darkmode" align=middle width=9.867000000000003pt height=14.155350000000013pt/>, but
it may be difficult to prove that <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/11ef9f3112a5610ca9d47a508db9dc2d.svg?invert_in_darkmode" align=middle width=63.008055pt height=24.65759999999998pt/> follows from <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4aea7d03cb3afc4a3d2c5963d5d5d280.svg?invert_in_darkmode" align=middle width=34.69768500000001pt height=24.65759999999998pt/>. It may in fact
be easier to prove the induction step

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/05a45a135d2511e0c2696d52d0124eb8.svg?invert_in_darkmode" align=middle width=264.93059999999997pt height=16.438356pt/></p>

That is, it may help to assume _P_ holds for _all_ numbers before <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/33359de825e43daa97171e27f6558ae9.svg?invert_in_darkmode" align=middle width=37.385865pt height=22.831379999999992pt/>.
Induction with this style of induction step is sometimes called the _strong
form_ of mathematical induction.
