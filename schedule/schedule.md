---
layout: course
title: Biostat 257
---

## Course Schedule

BIOSTAT 257 tentative schedule and handouts (expect frequent updates)

Location and time: CHS 41-268A, Tuesday and Thursday @ 1pm-2:50pm.

BruinLearn: <https://bruinlearn.ucla.edu/courses/160238>

Slack channel: <https://uclabiostat25-0hr8566.slack.com>   
Invitation link: <https://join.slack.com/t/uclabiostat25-0hr8566/shared_invite/zt-1rcvhwe0m-3IYNRDkMMDO8s78FHRhNvQ>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master)

Readings:  

* [_50 years of data sicence_](../readings/Donoho15FiftyYearsDataScience.pdf) by David Donoho (2015)  
* [_Julia: a fresh approach to numerical computing_](../readings/BezansonEdelmanKarpinskiShah17Julia.pdf) by Bezanson, Edelman, Karpinski, and Shah (2017)  
* [_Julia for biologists_](https://www.nature.com/articles/s41592-023-01832-z), published in Nature Methods (2023).  
* [_What every computer scientist should know about floating-point arithmetic_](../readings/Goldberg91FloatingPoint.pdf) by David Goldberg  
* Top 10 algorithms in the 20th century  
[Metropolis](../readings/metropolis.pdf), [Simplex](../readings/simplex.pdf), [Krylov](../readings/krylov.pdf), [Matrix decomposition](../readings/decomp.pdf), [Fortran](../readings/fortran.pdf), [QR algorithm](../readings/qr.pdf), [Quicksort](../readings/qsort.pdf), [FFT](../readings/fft.pdf), [Integer relation](../readings/integer.pdf), [FMM](../readings/fmm.pdf)  

| Week | Tuesday | Thursday | Homework |
|:-----------|:-----------|:------------|:------------|
| 1 | [4/4](https://ucla-biostat-257.github.io/2023spring/biostat257spring2023/2023/04/04/week1-day1.html) course introduction and logistics \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F01-intro%2Fintro.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/01-intro/intro.qmd), [html](../slides/01-intro/intro.html)\] | [4/6](https://ucla-biostat-257.github.io/2023spring/biostat257spring2023/2023/04/06/week1-day2.html) computer languages \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F02-langs%2Flangs.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/02-langs/langs.qmd), [html](../slides/02-langs/langs.html)\], Julia intro. \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F03-juliaintro%2Fjuliaintro.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/03-juliaintro/juliaintro.qmd), [html](../slides/03-juliaintro/juliaintro.html)\] | HW1 \[[ipynb](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/hw/hw1/hw01.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/hw/hw1/hw01.qmd), [html](../hw/hw1/hw01.html)\] |
| 2 | [4/11](https://ucla-biostat-257.github.io/2023spring/biostat257spring2023/2023/04/11/week2-day1.html) plotting in Julia \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F04-juliaplot%2Fjuliaplots.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/04-juliaplot/juliaplots.qmd), [html](../slides/04-juliaplot/juliaplots.html)\], Jupyter Notebook \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F05-jupyter%2Fjupyter.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/05-jupyter/jupyter.qmd), [html](../slides/05-jupyter/jupyter.html)\] | [4/13](https://ucla-biostat-257.github.io/2023spring/biostat257spring2023/2023/04/13/week2-day2.html) computer arithmetic \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F06-arith%2Farith.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/06-arith/arith.qmd), [html](../slides/06-arith/arith.html)\], algo. intro. \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F07-algo%2Falgo.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/07-algo/algo.qmd), [html](../slides/07-algo/algo.html)\] | |
| 3 | [4/18](https://ucla-biostat-257.github.io/2023spring/biostat257spring2023/2023/04/18/week3-day1.html) BLAS \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F08-numalgintro%2Fnumalgintro.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/08-numalgintro/numalgintro.qmd), [html](../slides/08-numalgintro/numalgintro.html)\], NLA on GPU \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257/2023spring/master?filepath=slides%2F09-juliagpu%2Fjuliagpu.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/slides/09-juliagpu/juliagpu.qmd), [html](../slides/09-juliagpu/juliagpu.html)\] | 4/20 triangular systems, GE/LU | HW2 \[[ipynb](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/hw/hw2/hw02.ipynb), [qmd](https://raw.githubusercontent.com/ucla-biostat-257/2023spring/master/hw/hw2/hw02.qmd), [html](../hw/hw2/hw02.html)\] |
| 4 | 4/25 Cholesky, QR (GS, Householder, Givens) | 4/27 Sweep operator, summary of linear regression | |
| 5 | 5/2 condition number, iterative methods intro | 5/4 conjugate gradient | HW3 |
| 6 | 5/9 easy linear system, eigen-decomposition and SVD | 5/11 optimization intro. | HW4 | 
| 7 | 5/16 optimization in Julia | 5/18 Newton-Raphson, Fisher scoring, GLM, nonlinear regression (Gauss-Newton), quasi-Newton | |  
| 8 | 5/23 KKT, constrained optimization | 5/25 EM algorithm | HW5 |  
| 9 | 5/30 MM algorithm | 6/2 LP, QP | HW6 |  
| 10 | 6/6 SOCP, SDP, GP | 6/8 concluding remarks | |  
