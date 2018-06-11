# Lecture 15: Composition and Inversion

Complicated functions are often built from single parts. For example, the
function <img src="/lectures/tex/b279a1f7296f643186b7be3760225978.svg?invert_in_darkmode&sanitize=true" align=middle width=72.83079209999998pt height=22.831056599999986pt/> defined by <img src="/lectures/tex/bcbc92d29ff44c848a040b4a1d96c493.svg?invert_in_darkmode&sanitize=true" align=middle width=118.33329419999998pt height=26.76175259999998pt/>
is computed by doing the following steps in succession:

* square
* add 1,
* cube.

We say that function <img src="/lectures/tex/bcbc92d29ff44c848a040b4a1d96c493.svg?invert_in_darkmode&sanitize=true" align=middle width=118.33329419999998pt height=26.76175259999998pt/> is the composite of the functions
(from <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/> to <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>)

- square <img src="/lectures/tex/560e6a06958749f60c6766986c0d9557.svg?invert_in_darkmode&sanitize=true" align=middle width=60.04558724999999pt height=26.76175259999998pt/>,
- successor <img src="/lectures/tex/cea59b1eb51c98df4ab701840adb719e.svg?invert_in_darkmode&sanitize=true" align=middle width=81.80344094999998pt height=24.65753399999998pt/>,
- cube <img src="/lectures/tex/8acb1ceffc413f625fcb8f21a19cf8fe.svg?invert_in_darkmode&sanitize=true" align=middle width=60.04558724999999pt height=26.76175259999998pt/>.

## 15.1 Notation for composite functions

In the present example we write <img src="/lectures/tex/ec520f3422fe97913095c6e91e51827b.svg?invert_in_darkmode&sanitize=true" align=middle width=49.349366549999985pt height=24.65753399999998pt/> cube(successor(square(x))), of <img src="/lectures/tex/bd6abd2cafcc81b21a2b8fca891cc5a8.svg?invert_in_darkmode&sanitize=true" align=middle width=27.16894454999999pt height=22.831056599999986pt/>
cube <img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/> successor <img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/> square.

In general, if <img src="/lectures/tex/62e2aa271191da72c6047c5230ecb438.svg?invert_in_darkmode&sanitize=true" align=middle width=97.38780479999998pt height=24.65753399999998pt/> we write <img src="/lectures/tex/d6832c688c63ed32bfd83fbd5a295c83.svg?invert_in_darkmode&sanitize=true" align=middle width=65.16148319999998pt height=22.831056599999986pt/> and say <img src="/lectures/tex/190083ef7a1625fbc75f243cffb9c96d.svg?invert_in_darkmode&sanitize=true" align=middle width=9.81741584999999pt height=22.831056599999986pt/> is the
_composite_ of <img src="/lectures/tex/3cf4fbd05970446973fc3d9fa3fe3c41.svg?invert_in_darkmode&sanitize=true" align=middle width=8.430376349999989pt height=14.15524440000002pt/> and <img src="/lectures/tex/2ad9d098b937e46f9f58968551adac57.svg?invert_in_darkmode&sanitize=true" align=middle width=9.47111549999999pt height=22.831056599999986pt/>.

**Warning:** Remember that <img src="/lectures/tex/06ec5e32a8124273ebcfa396bf45f006.svg?invert_in_darkmode&sanitize=true" align=middle width=33.42643919999999pt height=22.831056599999986pt/> means "do <img src="/lectures/tex/2ad9d098b937e46f9f58968551adac57.svg?invert_in_darkmode&sanitize=true" align=middle width=9.47111549999999pt height=22.831056599999986pt/> first, then <img src="/lectures/tex/3cf4fbd05970446973fc3d9fa3fe3c41.svg?invert_in_darkmode&sanitize=true" align=middle width=8.430376349999989pt height=14.15524440000002pt/>." <img src="/lectures/tex/41774ef1644cee87886dcbbd15c317a9.svg?invert_in_darkmode&sanitize=true" align=middle width=33.42643919999999pt height=22.831056599999986pt/> is usually different from <img src="/lectures/tex/d9ad90108b7758ac55eaeee2a1657616.svg?invert_in_darkmode&sanitize=true" align=middle width=33.426458999999994pt height=22.831056599999986pt/>.

**Example.**

square(successor(x)) = <img src="/lectures/tex/c62d45be56957d6a7af0888ee993f2ad.svg?invert_in_darkmode&sanitize=true" align=middle width=162.56814914999998pt height=26.76175259999998pt/>

successor(square(x)) = <img src="/lectures/tex/a5a30da7dbf3b5aa59781cf342da1718.svg?invert_in_darkmode&sanitize=true" align=middle width=45.079847999999984pt height=26.76175259999998pt/>
