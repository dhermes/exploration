# `exploration`

This is a collection of "exploratory" math, science and / or programming
forays I've undertaken (typically in GitHub gists).

I am making this repository because I just have a hard time searching
through my gists (302 in total as of August 8, 2017).

Occasionally, a gist will get "filed" as a potential blog
post ([e.g.][2]).

Sometimes, these gists get "promoted" to full repositories ([e.g.][1]).

## Explorations

- Finding roots (`sympy`) of polynomials in Bernstein basis ([gist][3])
- Using `ctypes` and `cffi` to call `sprintf` / `printf` from
  `libc` ([gist][4])
- Playing around with "user defined types" in Fortran; acts as a sort
  of Rosetta stone, calling Fortran from C / Fortran / `f2py` / Cython /
  `ctypes` / `cffi` ([gist][5], [promoted repository][53])
- Vetting literals in Python source code ([gist][6])
- Profiling core usage of Python with `multiprocessing` / `threading`
  ([gist][7], [promoted repository][1])
- Custom `float` subclass (in Python) that counts every single FLOP ([gist][8])
- Simulate a rubber band: discretize and treat each segment as a damped spring
  ([gist][9])
- Project Laplacian onto span of linear shape functions ([gist][10])
- Show that contour plots with a small number of levels give strange
  artifacts ([gist][11])
- Computing Pi (for Pi day) via quadrature ([gist][12])
- Fully algebraic intersection of B&#xe9;zier curves; as a very well-posed
  eigenvalue problem ([gist][13], [blog post TODO][2])
- Examples showing conditioning of polynomial roots ([gist][14],
  [blog post TODO][14-blog])
- HOWTO: Raising Python errors from Fortran code in `f2py` ([gist][15])
- Showing how `matmul` (matrix multiplication) can be platform
  dependent even in simple cases ([gist][16])
- (Poor) conditioning of B&#xe9;zier curve and surface subdivision
  ([gist][17])
- (Poor) conditioning of basis conversion for B&#xe9;zier curves and
  surfaces into: power/monomial basis, Chebyshev basis, Legendre
  basis, "nodal" basis of shape functions ([gist][18])
- Differences between exponentiation in Python/C vs. in Fortran
  ([gist][19], [another gist][19-also], [blog post TODO][19-blog])
- Numerical loss of precision for polynomials with repeated roots
  ([gist][20])
  - Using a "compensated" version of floating point addition and multiplication to implement compensated Horner's algorithm ([gist][55])
- Playing around with Newton's method on non-simple roots of 2D systems ([gist][54])
- `+=` vs. `.join` for Python strings: combatting a true-ism ([gist][21])
- Massive research project with curved supermeshes ([gist][22])
- Compute spectra for Kronecker product involving Radau RK scheme
  ([gist][23])
- Show level curves resulting from mapping from unit triangle onto
  a quadratric surface patch ([gist][24], [nbviewer][24-nbviewer])
- Transfinite interpolation on a triangle ([gist][25])
- Animate the transformation from one triangle to another: does so
  by doing this in projective space and taking fractional powers
  of the map via the SVD ([gist][26], [nbviewer][26-nbviewer])
- Remez algorithms, particularly for `log(x)` ([gist][27],
  [blog post TODO][27-blog], [existing post][27-post])
- Plot that refers to itself ([gist][28])
- Issues parametrizing a quadratic: just use a B&#xe9;zier curve,
  duh ([gist][29])
- Performing `max` in `C` without branching ([gist][30],
  [another gist][30-also], [blog post TODO][30-blog])
- iTunes AppleScript Power Hour Hack ([gist][31])
- Python class for `Q[sqrt(3)]` ([gist][32])
- Convert a file to `hex` and binary; to show a person to
  get a little better understanding of computers ([gist][33])
- Compare how often fighters fight across eras ([gist][34],
  [blog post TODO][34-blog])
- Visualize applying a matrix by using the SVD ([gist][35],
  [blog post TODO][35-blog])
- Solving the "sum-product" [riddle][36-riddle] ([gist][36], [HTML][36-page])
- UNFINISHED: Extract Matrix From Image and Connectivity Graph
  ([gist][37])
- Tic-Tac-Toe simulation ([gist][38])
- All monic irreducible degree 6 polynomials over `F3` ([gist][39])
- Create Delaunay mesh for polygon ([gist][40])
- Find initial condition that makes a PDE's solution periodic, does so
  via variational / functional magic ([gist][41], [another gist][41-also])
- UNFINISHED: Animate the process of a Butterfly algorithm ([gist][42], [nbviewer][42-nbviewer], [blog post TODO][42-blog])
- Advection demo ([gist][43], [nbviewer][43-nbviewer])
- Heat equation demo ([gist][44], [nbviewer][44-nbviewer])
- Profitability of NCAA Athletic Departments in 2011-2012 ([gist][45])
- Compute eigenvalues with `liblapack` via `ctypes` ([gist][46])
- Examine how to check "is eigenvalue?" via row reduction ([gist][47])
- Playing around with precision in Fortran ([gist][48])
- How to build a "dylib" on OS X? ([gist][49], [more complex gist][49-also])
- Fortran `allocatable` fields in user-defined types ([gist][50])
- Hack for a "packed" version of a C struct that contains a pointer ([gist][51])
- `valgrind` "failure" on OS X ([gist][52])
- "Stencil" project to find optimal finite difference stencils using a fixed
  number of points to approximate a fixed derivative (e.g. `u''(c)`)
  ([gist][56])
- Discussion of parametric curves; particularly classification and implicitization ([gist][57])
- Some notes on GMRES ([gist][58])

[1]: https://github.com/dhermes/profiling-multicore-python
[2]: https://github.com/dhermes/bossylobster-blog/issues/63
[3]: https://gist.github.com/dhermes/8c177036e426ed6fb936943ebb01b5fb
[4]: https://gist.github.com/dhermes/27cf3cacbf7ad457cbea571bd302865d
[5]: https://gist.github.com/dhermes/8c402e560f4222d04f4215722501e696
[6]: https://gist.github.com/dhermes/d819139f50dcc0b38fd0bbc2ce153f33
[7]: https://gist.github.com/dhermes/9c92cb6468ed39c51213b5e0a6176fb4
[8]: https://gist.github.com/dhermes/04fb1a416df8b01e41225a84afcf2f05
[9]: https://gist.github.com/dhermes/b9f132f48321e2827d9d79b8748c9353
[10]: https://gist.github.com/dhermes/a94dd99ccea4c62775cb0a86512697df
[11]: https://gist.github.com/dhermes/e0b4028630c8134557d1adb4ccdb30dc
[12]: https://gist.github.com/dhermes/c1231a9cdc62ea56516f8d9d8b8a4e57
[13]: https://gist.github.com/dhermes/4933f881b57ca57bf512e1e530389350
[14]: https://gist.github.com/dhermes/a0593b8a922eb25a180b42c093c7b06e
[14-blog]: https://github.com/dhermes/bossylobster-blog/issues/62
[15]: https://gist.github.com/dhermes/81486f13dc30a48c5622981d3b87a093
[16]: https://gist.github.com/dhermes/012e3512ea503e98997da4c9ac05a4dd
[17]: https://gist.github.com/dhermes/66a30cb66725d4b7e30f285d3e929128
[18]: https://gist.github.com/dhermes/6c512ba04637cd2ac94b8234d60bb9be
[19]: https://gist.github.com/dhermes/872a13a2a20a86f3c46e
[19-blog]: https://github.com/dhermes/bossylobster-blog/issues/59
[19-also]: https://gist.github.com/dhermes/e6f7c81449cbbbcf26ed2355f35c749c
[20]: https://gist.github.com/dhermes/44e7c8762902f88e197f4f10ceaf26c7
[21]: https://gist.github.com/dhermes/306a390aa688f8322504819afaefb7a1
[22]: https://gist.github.com/dhermes/def6276026333018c07acab24866e2bd
[23]: https://gist.github.com/dhermes/1e035b14515c9de9e7786b224550c676
[24]: https://gist.github.com/dhermes/cf282db3d0e69c9310d61cbbb5db2dc0
[24-nbviewer]: https://nbviewer.jupyter.org/gist/dhermes/cf282db3d0e69c9310d61cbbb5db2dc0
[25]: https://gist.github.com/dhermes/259bf162a608c4ceb126a1f7e5e1952b
[26]: https://gist.github.com/dhermes/b44f5c5bb7cabd4d607f
[26-nbviewer]: https://nbviewer.jupyter.org/gist/dhermes/b44f5c5bb7cabd4d607f
[27]: https://gist.github.com/dhermes/105da2a3c9861c90ea39
[27-blog]: https://github.com/dhermes/bossylobster-blog/issues/58
[27-post]: https://blog.bossylobster.com/2017/02/golang-and-log-x.html
[28]: https://gist.github.com/dhermes/f6e3730059ddb23f09f1
[29]: https://gist.github.com/dhermes/5979bb857eaa0ab5c43a
[30]: https://gist.github.com/dhermes/c79846c6074b938b2e10
[30-also]: https://gist.github.com/dhermes/f17fc85999f79ae2f304
[30-blog]: https://github.com/dhermes/bossylobster-blog/issues/56
[31]: https://gist.github.com/dhermes/6a26c0daab5b81c5880f
[32]: https://gist.github.com/dhermes/e5918dab1ea936b41475
[33]: https://gist.github.com/dhermes/2bfe5e2531dfe048ba41
[34]: https://gist.github.com/dhermes/f0e3587f7061bc96b835
[34-blog]: https://github.com/dhermes/bossylobster-blog/issues/60
[35]: https://gist.github.com/dhermes/d83fe28c1262e084356d
[35-blog]: https://github.com/dhermes/bossylobster-blog/issues/57
[36]: https://gist.github.com/dhermes/d2c99ca6bde1d91a627c
[36-riddle]: https://en.wikipedia.org/wiki/Sum_and_Product_Puzzle
[36-page]: https://www.bossylobster.com/sum-product-problem
[37]: https://gist.github.com/dhermes/ba978feb8c0ea945e233
[38]: https://gist.github.com/dhermes/93a3d9cd7bbb465db168
[39]: https://gist.github.com/dhermes/16ae520d532d056b2640
[40]: https://gist.github.com/dhermes/cc241c819b221f0ee89d
[41]: https://gist.github.com/dhermes/aabaa58119c018a3e3a6
[41-also]: https://gist.github.com/dhermes/1059fb8405a77a341e6c
[42]: https://gist.github.com/dhermes/c82a2f7d9233eb0fd6aa
[42-nbviewer]: https://nbviewer.jupyter.org/gist/dhermes/c82a2f7d9233eb0fd6aa/butterfly_animation.ipynb
[42-blog]: https://github.com/dhermes/bossylobster-blog/issues/55
[43]: https://gist.github.com/dhermes/65814d2445b7a26ab842
[43-nbviewer]: https://nbviewer.jupyter.org/gist/dhermes/65814d2445b7a26ab842
[44]: https://gist.github.com/dhermes/608abdf5ddf26ce39b76
[44-nbviewer]: https://nbviewer.jupyter.org/gist/dhermes/608abdf5ddf26ce39b76
[45]: https://gist.github.com/dhermes/e31b85238a0ecc43ae8a
[46]: https://gist.github.com/dhermes/8bd7f39e1c2b216b5d61571188dd5d0a
[47]: https://gist.github.com/dhermes/98836e156d1320cec1d3052a2813ec06
[48]: https://gist.github.com/dhermes/585ec0f80a431f3412d36a18661baa62
[49]: https://gist.github.com/dhermes/91078c56dde1f46445cb703267c67e00
[49-also]: https://gist.github.com/dhermes/d26a12648f8c7da06d12f88cd8e1d289
[50]: https://gist.github.com/dhermes/3672116037190217ade1a061a59a2f23
[51]: https://gist.github.com/dhermes/8bc282d0cfc14307aee9893b8487f33f
[52]: https://gist.github.com/dhermes/ff87149740cee06b7f495dcec6d63ff0
[53]: https://github.com/dhermes/foreign-fortran
[54]: https://gist.github.com/dhermes/0518d1c6ac111ca9c835709aaf861aad
[55]: https://gist.github.com/dhermes/8999485869531dad1345eacf8acc8c91
[56]: https://gist.github.com/dhermes/ba7276f20d5a4947cafbb911671ab8f1
[57]: https://gist.github.com/dhermes/3551f053e3f81a85d488c7cdb22a18c8
[58]: https://gist.github.com/dhermes/d72e36c40626bd93a4a02704ee79c7d1
