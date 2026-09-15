# 04 — Linear Algebra & ODEs (Fortran)

Revisiting: eigenvalues/eigenvectors, matrix decomposition, systems of ODEs.

**Tools:** `gfortran` (part of GCC — `sudo apt install gfortran` on Ubuntu/Debian)

## Setup

```bash
gfortran src/gauss_elim.f90 -o gauss_elim
./gauss_elim
```

## Projects

- [ ] `src/gauss_elim.f90` — Gaussian elimination / LU decomposition from scratch, solve Ax = b
- [ ] `src/power_iteration.f90` — dominant eigenvalue/eigenvector via power iteration
- [ ] `src/rk4_ode.f90` — RK4 solver for a system of ODEs (e.g. predator-prey or spring-mass-damper), write output to CSV and plot separately (e.g. with Python or gnuplot)

## Log

_What clicked seeing this in code vs. on paper — fill in as you go._
