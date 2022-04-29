# convention 
- [(0x-y:z)](https://www.iqihang.com/ark/record/7191/8673/1507816/161543942/3/72/2/4555)
  - 0x 视频集数
  - y:z time
- P... means from ZhangYu book
  - p means others
# book 
## recommended reading part
### ^^^@The Cauchy-Schwarz Master Class An Introduction to the Art of Mathematical Inequalities (J. Michael Steele) (z-lib.org).pdf
- Landau’s notation p133, not confused with little-o notation 
  - o is O, but O is not necessaryly o.
  - `GM is PM limit derivation ` on this page is highly recommended 
    - use `log`, then `O` twice
- this book derivation of general AM-GM Inequality(p37) is really simple but also very heuristic.  
- PM-GM inequality p132 notice theorem 8.2 & 8.8
  - also see [this](#PM)
## less recommended 
- %Inequalities-Korovkin.pdf may be too redundant 
# ZhangYu book supplement
- P20 see `^^^@The Cauchy-Schwarz Master Class An Introduction to the Art of Mathematical Inequalities (J. Michael Steele) (z-lib.org).pdf` p133 
# topic classification 

## derivative  
- [derivation](https://www.wyzant.com/resources/lessons/math/calculus/derivative_proofs/a_to_the_x)
- [much derivation of basis theorems](https://tutorial.math.lamar.edu/classes/calci/DerivativeProofs.aspx#mjx-eqn-eqeq1) including Quotient Rule,chain rule, etc.
- [common derivative derivation](https://www.wyzant.com/resources/lessons/math/calculus/derivative_proofs/)

## integral 
- [ trigonometry ](https://tutorial.math.lamar.edu/classes/calcii/integralswithtrig.aspx)
# notice 
- p9 elementary function
- 14 Cartesian coordinate system <-> polar coordinate system
- 19 [polynomial factorization](https://tutorial.math.lamar.edu/classes/alg/factoring.aspx)
> inequality: **ALWAYS** remember that sum can be generalized as integral .
# notes
> also see matepad [stylus](#stylus) notes
- p7 
  - [Trigonometry](https://en.wikipedia.org/wiki/Trigonometry) note SOH-CAH-TOA
  - [naming ](https://www.quora.com/Why-is-sin-the-opposite-of-CSC-and-cos-the-opposite-of-sec)convention<a id="naming_convention"></a>
- p8 
  - $f(x)=C$ can be proved by just calculating the indefinite integral or Lagrange median value theorem (05-6:45)
# miscellaneous 
- [What-is-the-relationship-between-a-tangent-line-and-the-tangent-function](https://www.quora.com/What-is-the-relationship-between-a-tangent-line-and-the-tangent-function)
## interesting 
- [hyperbola area relation with hyperbolic sine&cosine](https://brilliant.org/wiki/hyperbolic-trigonometric-functions/)<a id="hyperbola"></a> same with https://en.wikipedia.org/wiki/Hyperbola#Rectangular_hyperbola
  - **Prerequisite** 
    - [Hyperbolic angle](https://en.wikipedia.org/wiki/Hyperbolic_angle) 
      - po not confused with circular angle , especially magnitude is just area , not related with angle
  - questions 
    - https://en.wikipedia.org/wiki/Hyperbolic_functions see hyhypothesis note
  - also see https://en.wikipedia.org/wiki/Hyperbolic_sector
  - others
    - https://www.whitman.edu/mathematics/calculus_online/section04.11.html
    - https://betterexplained.com/articles/hyperbolic-functions/#Part_4_Geometric_Viewpoint
  - [derivation](http://tediousderivations.blogspot.com/2013/08/hyperbolic-functions.html) by ode mentioned in [brilliant page](#hyperbola)
  - proof 
    - see stylus `proofs.pdf` p12-
    - 13  squeeze mapping proof
    - also https://math.stackexchange.com/questions/3504662/circular-angles-vs-hyperbolic-angles
## frequently used inequality 
- [Jensen's inequality ](https://artofproblemsolving.com/wiki/index.php/Jensen's_Inequality)
- [Cauchy(–Schwarz) inequality](https://en.wikipedia.org/wiki/Cauchy%E2%80%93Schwarz_inequality#real_number_proof)
- [most of derivation _1](https://www.cut-the-knot.org/proofs/ExponentialInequalityForMeans.shtml) / [most of derivation _2](https://en.wikipedia.org/wiki/List_of_inequalities#Geometry)
## basis proof
- $\frac{d\frac{f(x)}{g(x)}}{dx}$ 
  - Thomas calculus P120
  - stylus `proofs.pdf` P3  

## alternative proof
- [Cycloid function ](https://en.wikipedia.org/wiki/Cycloid) by calculating center point coordinate 

## supplementary proof
- trigonometry sum and difference formulas<a id="trigonometry1"></a>  
  - geometry
    - https://www.themathpage.com/aTrig/sum-proof.htm
    - [more concise](https://math.stackexchange.com/questions/1382661/looking-for-an-alternative-proof-of-the-angle-difference-expansion/1382809#1382809)
  - algebra
    - https://mymission.lamission.edu/userdata/sargsye2/docs/Math%20240/Proof%20of%20the%20difference%20formula%20for%20cosine.pdf
  - rotation matrix & complex number , etc
    - https://math.stackexchange.com/questions/1292/how-can-i-understand-and-prove-the-sum-and-difference-formulas-in-trigonometry
### stylus proofs.pdf<a id="stylus"></a>
#### stylus writing convention 
- circle means from ebook 
#### list 
- P4 [ derivative of high order of cycloid  equals zero $C^\infty$](https://en.wikipedia.org/wiki/Cycloid) 
- P5 [Astroid](https://proofwiki.org/wiki/Equation_of_Astroid/Parametric_Form)
  - according to the symmetry , OC OB must be collinear
- P6
  - p16 visualization proof : sum of squares & cubes [1](https://www.geogebra.org/m/Ka5xBBkH) or [2](https://math.stackexchange.com/questions/3081649/understanding-some-proofs-without-words-for-sums-of-consecutive-numbers-consecu)
- P7
  - sec definition with [this](#naming_convention) 
- P9 
  - `cot` half angle formula  supplement the `half_tan.png`
- P10
  - [trigonometry sum and difference formulas](#trigonometry1)
- P11<a id="PM"></a>
  - power mean and Geometric Mean inequality derivation based on `^^[[analytic_inequality_kazarinoff.pdf` p76 by searching `power mean`, also see [AoPS_1](https://artofproblemsolving.com/wiki/index.php/Root-Mean_Square-Arithmetic_Mean-Geometric_Mean-Harmonic_mean_Inequality) & [AoPS_2 more concise](https://artofproblemsolving.com/wiki/index.php/Power_Mean_Inequality)
# TODO
- [Multiple-Angle Formulas](https://mathworld.wolfram.com/Multiple-AngleFormulas.html) proof P8 
- check [trigonometry sum and difference formulas](#trigonometry1) in the high school math book
- general polynomial factorization
  - check primary school Olympiad Math textbook 