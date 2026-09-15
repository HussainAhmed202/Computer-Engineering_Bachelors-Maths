# Maths courses taught in my Bachelor's in Computer Engineering

Revisiting six semesters of university math courses — but on computers this time.
Each subject gets the language most idiomatic to it, rather than forcing everything into one toolchain.

| # | Course (original) | Language | Why this language |
|---|---|---|---|
| 01 | Calculus | Python | SymPy for symbolic work, NumPy/Matplotlib for numeric + visual |
| 02 | Discrete Math | Haskell | Recursion, induction, and logic map directly onto Haskell's style |
| 03 | Complex Variables & Fourier Analysis | MATLAB | Native complex numbers, built for signal processing / FFT |
| 04 | Linear Algebra & ODE | Fortran | The actual language LAPACK/BLAS are written in — the root of numerical linear algebra |
| 05 | Probability & Stats | R | Built by statisticians, for statisticians |
| 06 | Numerical Methods | C | Forces you to see floating-point precision and iteration, not just call a solver |

## Structure

Each folder is self-contained: its own README (what concept it revisits, what clicked),
its own build/run instructions, and starter code to build on.

```
math-revisited/
├── 01-calculus-python/
├── 02-discrete-math-haskell/
├── 03-complex-fourier-matlab/
├── 04-linalg-ode-fortran/
├── 05-prob-stats-r/
└── 06-numerical-methods-c/
```
## Log

Each subfolder README doubles as a running log — the original course topic, what was built,
and what looked different in code vs. on paper.
