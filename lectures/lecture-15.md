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

**Question 15.1** Let _f_, _m_ and _s_ be the functions on the set of people
defined by

- _m(x)_ = mother of _x_
- _f(x)_ = father of _x_
- _s(x)_ = spouse of _x_

What are the following?

- <img src="/lectures/tex/e7d04a8dee8c260fd6bdb73938f43d39.svg?invert_in_darkmode&sanitize=true" align=middle width=59.843968799999985pt height=24.65753399999998pt/> mother in law of _x_
- <img src="/lectures/tex/d99182446bec9a2f0d60d93175b73319.svg?invert_in_darkmode&sanitize=true" align=middle width=55.22828024999998pt height=24.65753399999998pt/> father in law of _x_
- <img src="/lectures/tex/9ee5b5559182d2f2c6aa1b564075b416.svg?invert_in_darkmode&sanitize=true" align=middle width=66.57158969999999pt height=24.65753399999998pt/> grandmother (maternal) of _x_
- <img src="/lectures/tex/47ea9dfef214ebba3e9562938061ae4c.svg?invert_in_darkmode&sanitize=true" align=middle width=61.95590279999999pt height=24.65753399999998pt/> grandfather (maternal) of _x_
- <img src="/lectures/tex/618e460ba8a5ba64a259ae6dd9c50e4b.svg?invert_in_darkmode&sanitize=true" align=middle width=53.11634789999999pt height=24.65753399999998pt/> _x_

**Question 15.2** Write the following as composites of square(x), sqrt(x),
successor(x) and cube(x).

(Assume that all of these have domain and codomain <img src="/lectures/tex/78dc6a7b0fbd5bdfaa3cc0ce1768db2b.svg?invert_in_darkmode&sanitize=true" align=middle width=72.6709236pt height=24.65753399999998pt/> and
<img src="/lectures/tex/265856b9ffc446a5010f60defa9f882f.svg?invert_in_darkmode&sanitize=true" align=middle width=47.75103794999999pt height=24.65753399999998pt/>.)

- <img src="/lectures/tex/2837c63b51a68029b6e3d5f888e25c5e.svg?invert_in_darkmode&sanitize=true" align=middle width=58.778486249999986pt height=28.712280299999996pt/> = sqrt(successor(cube(x))) = sqrt <img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/> successor <img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/>
  cube(x)
- <img src="/lectures/tex/47a1fa65c17c613491a26d816b8bdb4d.svg?invert_in_darkmode&sanitize=true" align=middle width=16.96128554999999pt height=31.359338999999984pt/> = sqrt((cube(x)) = sqrt <img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/> cube(x)
- <img src="/lectures/tex/11bb4af6c32bb5990133b96b4e39eb0a.svg?invert_in_darkmode&sanitize=true" align=middle width=57.043369349999985pt height=26.76175259999998pt/> = cube(successor(x)) = cube <img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/> successor(x)
- <img src="/lectures/tex/ecfdc04fded1f35eb049b1525e278a79.svg?invert_in_darkmode&sanitize=true" align=middle width=64.41782819999999pt height=26.76175259999998pt/> = square(successor(cube(x))) = square <img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/> successor <img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/>
  cube(x)

**Note** Composition of functions is associative: <img src="/lectures/tex/6c2422e33699d023a0dbdc54e020eaa5.svg?invert_in_darkmode&sanitize=true" align=middle width=165.02613599999998pt height=24.65753399999998pt/>. So we don't bother with the brackets.

## 15.2 Conditions for composition

Composite functions do not always exist.

**Example.** If reciprocal <img src="/lectures/tex/de118071b67a1778651e8d1e68b3a55f.svg?invert_in_darkmode&sanitize=true" align=middle width=94.06377749999999pt height=24.65753399999998pt/> is
defined by reciprocal(x) = <img src="/lectures/tex/f6de2147c9c203a34732c0a74515a98c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.454371649999997pt height=27.77565449999998pt/> and predecessor <img src="/lectures/tex/588990cbb4a95d7ec97b62a82197866e.svg?invert_in_darkmode&sanitize=true" align=middle width=58.44728174999999pt height=22.648391699999998pt/> is defined by predecessor(x) = <img src="/lectures/tex/6e2a027fd5d65c9f49f111b1fa539e7a.svg?invert_in_darkmode&sanitize=true" align=middle width=37.70538914999999pt height=21.18721440000001pt/>, then reciprocal
<img src="/lectures/tex/c0463eeb4772bfde779c20d52901d01b.svg?invert_in_darkmode&sanitize=true" align=middle width=8.219209349999991pt height=14.611911599999981pt/> predecessor does not exists, because predecessor(1) = 0 is not a legal
input for reciprocal.

To avoid this problem, we demand that the codomain of <img src="/lectures/tex/2ad9d098b937e46f9f58968551adac57.svg?invert_in_darkmode&sanitize=true" align=middle width=9.47111549999999pt height=22.831056599999986pt/> be equal to the domain
of <img src="/lectures/tex/3cf4fbd05970446973fc3d9fa3fe3c41.svg?invert_in_darkmode&sanitize=true" align=middle width=8.430376349999989pt height=14.15524440000002pt/> for <img src="/lectures/tex/06ec5e32a8124273ebcfa396bf45f006.svg?invert_in_darkmode&sanitize=true" align=middle width=33.42643919999999pt height=22.831056599999986pt/> to exist. This ensures that each output of <img src="/lectures/tex/2ad9d098b937e46f9f58968551adac57.svg?invert_in_darkmode&sanitize=true" align=middle width=9.47111549999999pt height=22.831056599999986pt/> will be a
legal input of <img src="/lectures/tex/3cf4fbd05970446973fc3d9fa3fe3c41.svg?invert_in_darkmode&sanitize=true" align=middle width=8.430376349999989pt height=14.15524440000002pt/>.

Let <img src="/lectures/tex/29df52baee1e9208464f4b7dbd026928.svg?invert_in_darkmode&sanitize=true" align=middle width=74.69024805pt height=22.465723500000017pt/> and <img src="/lectures/tex/fbd9ac9a3e7482dd734f2acae08d89f6.svg?invert_in_darkmode&sanitize=true" align=middle width=74.3623452pt height=22.831056599999986pt/> be functions. The function <img src="/lectures/tex/2ce6f98628fccadf9124efcc316d969d.svg?invert_in_darkmode&sanitize=true" align=middle width=33.42643919999999pt height=22.831056599999986pt/> exists if and only if <img src="/lectures/tex/8950f69cac2093283b054723028106e7.svg?invert_in_darkmode&sanitize=true" align=middle width=48.13567769999999pt height=22.465723500000017pt/>. If it exists, <img src="/lectures/tex/dca03096ba2f48381170da396d1e5771.svg?invert_in_darkmode&sanitize=true" align=middle width=99.09049094999997pt height=22.831056599999986pt/> and is defined by <img src="/lectures/tex/c27d74b79890e98d1f82f77d8bdc7772.svg?invert_in_darkmode&sanitize=true" align=middle width=130.39181925pt height=24.65753399999998pt/>.

**Question** Let <img src="/lectures/tex/c2308dccf241052557114444f47dcd72.svg?invert_in_darkmode&sanitize=true" align=middle width=74.70864224999998pt height=22.831056599999986pt/> and <img src="/lectures/tex/1c24f11be166117cd68eee560cbe2757.svg?invert_in_darkmode&sanitize=true" align=middle width=74.69024805pt height=22.465723500000017pt/> be the functions
pictured below.

![](images/L15-P10.png)

Does <img src="/lectures/tex/95d22f4ccb6c0263a2496cf871cd7777.svg?invert_in_darkmode&sanitize=true" align=middle width=33.77274119999999pt height=22.831056599999986pt/> exist?

codomain<img src="/lectures/tex/f262a67483bfe4bbd13bc0385a744ae4.svg?invert_in_darkmode&sanitize=true" align=middle width=144.61210994999996pt height=24.65753399999998pt/> and domain<img src="/lectures/tex/71831453e26c833a2866df610e2f6b64.svg?invert_in_darkmode&sanitize=true" align=middle width=143.22505395pt height=24.65753399999998pt/>.
So <img src="/lectures/tex/95d22f4ccb6c0263a2496cf871cd7777.svg?invert_in_darkmode&sanitize=true" align=middle width=33.77274119999999pt height=22.831056599999986pt/> does exist because codomain(f) = domain(g). <img src="/lectures/tex/fbe2fde076b85c9c0441450ec61e512c.svg?invert_in_darkmode&sanitize=true" align=middle width=99.43678799999999pt height=22.831056599999986pt/>.

**Question** Let <img src="/lectures/tex/c2308dccf241052557114444f47dcd72.svg?invert_in_darkmode&sanitize=true" align=middle width=74.70864224999998pt height=22.831056599999986pt/> and <img src="/lectures/tex/1c24f11be166117cd68eee560cbe2757.svg?invert_in_darkmode&sanitize=true" align=middle width=74.69024805pt height=22.465723500000017pt/> be the functions
pictured below.

![](images/L15-P11.png)

Does <img src="/lectures/tex/95d22f4ccb6c0263a2496cf871cd7777.svg?invert_in_darkmode&sanitize=true" align=middle width=33.77274119999999pt height=22.831056599999986pt/> exist?

codomain<img src="/lectures/tex/88ef50850587fa26b19ae505a22967ee.svg?invert_in_darkmode&sanitize=true" align=middle width=167.35188359999998pt height=24.65753399999998pt/> and domain<img src="/lectures/tex/88564320dc02c450507d3f0da2b4ede6.svg?invert_in_darkmode&sanitize=true" align=middle width=143.22505395pt height=24.65753399999998pt/>. So <img src="/lectures/tex/95d22f4ccb6c0263a2496cf871cd7777.svg?invert_in_darkmode&sanitize=true" align=middle width=33.77274119999999pt height=22.831056599999986pt/> does not exist because codomain(f) <img src="/lectures/tex/34da809cf641dbc24baded3b37e17d7b.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=22.831056599999986pt/> domain(g).

**Question** Let _f_, _g_ and _h_ be the functions

- <img src="/lectures/tex/7bd639ba04bf15eaa24c843bda137990.svg?invert_in_darkmode&sanitize=true" align=middle width=71.91755504999998pt height=22.831056599999986pt/> defined by <img src="/lectures/tex/85fe9a4186a6843308dedc77e9ed97f7.svg?invert_in_darkmode&sanitize=true" align=middle width=77.92236374999999pt height=24.65753399999998pt/>.
- <img src="/lectures/tex/e153ede977e29e2e868d3d87455bbff3.svg?invert_in_darkmode&sanitize=true" align=middle width=70.53049904999999pt height=22.648391699999998pt/> defined by <img src="/lectures/tex/c6a98072302d35d5e3004aa0fc1db034.svg?invert_in_darkmode&sanitize=true" align=middle width=61.955379749999985pt height=24.65753399999998pt/>
- <img src="/lectures/tex/d3a052edf31d96bacddbc8ce4f32d89d.svg?invert_in_darkmode&sanitize=true" align=middle width=72.48449504999998pt height=22.831056599999986pt/> defined by <img src="/lectures/tex/0a9e1ffa2e7a09e029fd997c25949a0a.svg?invert_in_darkmode&sanitize=true" align=middle width=98.64901529999997pt height=26.76175259999998pt/>

Which of the following statements if **false**?

- **A.** <img src="/lectures/tex/95d22f4ccb6c0263a2496cf871cd7777.svg?invert_in_darkmode&sanitize=true" align=middle width=33.77274119999999pt height=22.831056599999986pt/> exists, <img src="/lectures/tex/ac4119ed1edd1f99ffa75faa6e721f4e.svg?invert_in_darkmode&sanitize=true" align=middle width=96.78611744999999pt height=22.831056599999986pt/>
- **B.** <img src="/lectures/tex/29f8035de6d3defd73810dc62e37f6b1.svg?invert_in_darkmode&sanitize=true" align=middle width=33.77275604999999pt height=22.831056599999986pt/> exists, <img src="/lectures/tex/77e404f315270ad762aed5278a4ee229.svg?invert_in_darkmode&sanitize=true" align=middle width=94.95964004999998pt height=22.831056599999986pt/>
- **C.** <img src="/lectures/tex/06ec5e32a8124273ebcfa396bf45f006.svg?invert_in_darkmode&sanitize=true" align=middle width=33.42643919999999pt height=22.831056599999986pt/> does not exist
- **D.** <img src="/lectures/tex/8ff25f8f4fbe5ff2898b6a2e562bc59e.svg?invert_in_darkmode&sanitize=true" align=middle width=57.728081399999986pt height=22.831056599999986pt/> does not exist.

**Answer**

- **A** is true because codomain(f) = domain(g), domain(f) = <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>,
  codomain(g) = <img src="/lectures/tex/f3e711926cecfed3003f9ae341f3d92b.svg?invert_in_darkmode&sanitize=true" align=middle width=11.87217899999999pt height=22.648391699999998pt/>
- **B** is true because codomain(g) = domain(f), domain(g) = <img src="/lectures/tex/b9477ea14234215f4d516bad55d011b8.svg?invert_in_darkmode&sanitize=true" align=middle width=10.95894029999999pt height=22.648391699999998pt/>,
  codomain(f) = <img src="/lectures/tex/b9477ea14234215f4d516bad55d011b8.svg?invert_in_darkmode&sanitize=true" align=middle width=10.95894029999999pt height=22.648391699999998pt/>
- **C** is true because codomain(h) <img src="/lectures/tex/c7d8187b40e520f7a72551434f713727.svg?invert_in_darkmode&sanitize=true" align=middle width=12.785434199999989pt height=22.831056599999986pt/> domain(g)
- **D** is false because codomain(g) = domain<img src="/lectures/tex/94f52e74478dd00a8459324f73777bfc.svg?invert_in_darkmode&sanitize=true" align=middle width=46.558170449999984pt height=24.65753399999998pt/>.
