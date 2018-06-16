# Lecture 23: Random variables

In a game, three standard dice will be rolled and the number of sixes will be
recorded. We could let _X_ stand for the number of sixes rolled. Then _X_ is a
special kind of variable whose value is based on a random process. These are
called _random variables_.

Because the value of _X_ is random, it doesn't make sense to ask whether <img src="/lectures/tex/5a8dcb8ad1298f287084a6a4446167f3.svg?invert_in_darkmode&sanitize=true" align=middle width=45.04550654999999pt height=22.465723500000017pt/>, for example. But we can ask what the _probability is_ that <img src="/lectures/tex/bca0701b83e430a17ccc917b8bc3da06.svg?invert_in_darkmode&sanitize=true" align=middle width=45.04550654999999pt height=22.465723500000017pt/> or that <img src="/lectures/tex/353cd32c9d5684716f79173e2cbdff35.svg?invert_in_darkmode&sanitize=true" align=middle width=45.04550654999999pt height=22.465723500000017pt/>. This is because "<img src="/lectures/tex/bca0701b83e430a17ccc917b8bc3da06.svg?invert_in_darkmode&sanitize=true" align=middle width=45.04550654999999pt height=22.465723500000017pt/>" and "<img src="/lectures/tex/7062decdde4d09083037326793f150fb.svg?invert_in_darkmode&sanitize=true" align=middle width=45.04550654999999pt height=22.465723500000017pt/>" correspond to events from our
sample space.

## Formal definition

Formally, a random variable is defined as a function from the sample space to
<img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>.

**Example.** Let <img src="/lectures/tex/cbfb1b2a33b28eab8a3e59464768e810.svg?invert_in_darkmode&sanitize=true" align=middle width=14.908688849999992pt height=22.465723500000017pt/> be the number of 1s in a binary string of length 2 chosen
uniformly at random. Formally, _X_ is the function from <img src="/lectures/tex/31251fcd9c044bab453a064c7e4c71dd.svg?invert_in_darkmode&sanitize=true" align=middle width=104.10974309999999pt height=24.65753399999998pt/> to
<img src="/lectures/tex/3f4efc607a90eb7ad1e9c1db443d0a13.svg?invert_in_darkmode&sanitize=true" align=middle width=55.70781314999999pt height=24.65753399999998pt/> such that

<p align="center"><img src="/lectures/tex/775d57ae4f5aa64ff28a8c54364404ee.svg?invert_in_darkmode&sanitize=true" align=middle width=318.99508575pt height=16.438356pt/></p>

## Probability distribution

![](images/L23-P4.png)
