# Lecture 4 - Logic

## Question 4.1

Which of the following are propositions?

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/fe38cd50ce053e4d42c61e3274903966.svg?invert_in_darkmode" align=middle width=152.237415pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6b5b444e8c773bb701dfcc280d02839f.svg?invert_in_darkmode" align=middle width=62.55711pt height=12.602732999999999pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e547b88bb92debf1a2f66447e5b41395.svg?invert_in_darkmode" align=middle width=160.50259499999999pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/deb28fedbdb5470d49cb87f7e79a1b6d.svg?invert_in_darkmode" align=middle width=62.55711pt height=12.602732999999999pt/></p>

## 4.1 Connectives ∧, ∨ and ¬

Define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/0b6832fb78c570edf56af766820951ee.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=18.265169999999976pt/> by the following _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/cb78b0cacb6c794f10bfd9e6761398ac.svg?invert_in_darkmode" align=middle width=34.463385pt height=18.265169999999976pt/> |
|-----|-----|-------------|
|  T  |  T  |     T       |
|  T  |  F  |     F       |
|  F  |  T  |     F       |
|  F  |  F  |     F       |

Define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/6007a29527e0ec27309d7829f5754d08.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=18.265169999999976pt/> by the _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/82385103bdbbacdc2e6ac03827c9e3e1.svg?invert_in_darkmode" align=middle width=34.463385pt height=18.265169999999976pt/> |
|-----|-----|------------|
|  T  |  T  |     T      |
|  T  |  F  |     T      |
|  F  |  T  |     T      |
|  F  |  F  |     F      |

Define <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/23bf728170c10d0449b90561f827623a.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=14.155350000000013pt/> by the _truth table_:

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/eea93f3519d9141e9e02f11439b4588d.svg?invert_in_darkmode" align=middle width=19.229595000000003pt height=14.155350000000013pt/> |
|-----|----------|
|  T  |  F       |
|  F  |  T       |

### Notation

<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/47b61b8ae5cc2531c99faa80efb9d429.svg?invert_in_darkmode" align=middle width=59.360895pt height=11.415524999999999pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/4f65d921512dd7f5ca052dd36d71b665.svg?invert_in_darkmode" align=middle width=127.07804999999999pt height=16.438356pt/></p>
<p align="center"><img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/057ed779a82f90fbcefdc229d6a994b4.svg?invert_in_darkmode" align=middle width=56.621235pt height=11.415524999999999pt/></p>

### Order of precedence

<img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/23bf728170c10d0449b90561f827623a.svg?invert_in_darkmode" align=middle width=10.958970000000004pt height=14.155350000000013pt/> has precedence over the other connectives.

For example, <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/8aedfee9c431ef7507b4706570dfad7f.svg?invert_in_darkmode" align=middle width=45.422354999999996pt height=18.265169999999976pt/> means <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/51e44209e800e5c2fe7deec52d7ee52f.svg?invert_in_darkmode" align=middle width=58.207875pt height=24.65759999999998pt/>.

### Example

Find the truth tables for <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e0f736f33ed56c4985d37ee5f4270bb9.svg?invert_in_darkmode" align=middle width=73.386555pt height=24.65759999999998pt/> and <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/9c613ce6e53ed8a3e3fef0fee2f7a473.svg?invert_in_darkmode" align=middle width=112.70720999999999pt height=24.65759999999998pt/>

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/2ec6e630f199f589a2402fdf3e0289d5.svg?invert_in_darkmode" align=middle width=8.270625000000004pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/d5c18a8ca1894fd3a7d25f242cbe8890.svg?invert_in_darkmode" align=middle width=7.928167500000005pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode" align=middle width=7.873024500000003pt height=14.155350000000013pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/81c2563ebeefaddb896d1a3bb032ed9c.svg?invert_in_darkmode" align=middle width=34.065735pt height=18.265169999999976pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/e0f736f33ed56c4985d37ee5f4270bb9.svg?invert_in_darkmode" align=middle width=73.386555pt height=24.65759999999998pt/> |
|-----|-----|-----|------------|----------------------|
|  T  |  T  |  T  |     T      |     T                |
|  T  |  T  |  F  |     T      |     T                |
|  T  |  F  |  T  |     T      |     T                |
|  T  |  F  |  F  |     F      |     F                |
|  F  |  T  |  T  |     T      |     F                |
|  F  |  T  |  F  |     T      |     F                |
|  F  |  F  |  T  |     T      |     F                |
|  F  |  F  |  F  |     F      |     F                |

| <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/cb78b0cacb6c794f10bfd9e6761398ac.svg?invert_in_darkmode" align=middle width=34.463385pt height=18.265169999999976pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/fe2c89613a52d32d41c1e538565c74d6.svg?invert_in_darkmode" align=middle width=34.408275pt height=18.265169999999976pt/> | <img src="https://rawgit.com/dylanpinn/MAT1830/master//lectures/tex/3598d0808113f23ad5732168d6f9d2c7.svg?invert_in_darkmode" align=middle width=112.36467000000002pt height=24.65759999999998pt/> |
|-------------|-------------|---------------------------------|
|     T       |     T       |     T                           |
|     T       |     F       |     T                           |
|     F       |     T       |     T                           |
|     F       |     F       |     F                           |
|     F       |     F       |     F                           |
|     F       |     F       |     F                           |
|     F       |     F       |     F                           |
|     F       |     F       |     F                           |
