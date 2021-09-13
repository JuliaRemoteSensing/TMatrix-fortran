# Fortran codes for T-Matrix calculation

This repo contains LAPACK-based T-Matrix codes originally written by [M. Mishchenko](https://www.giss.nasa.gov/staff/mmishchenko/t_matrix.html).

`ampld.lp.f`, `ampld.par.f` and `lpd.f` are used for nonspherical particles in a fixed orientation. Here, `ampld.lp.f` is modified by Jussi Leinonen (jsleinonen@gmail.com) for his Python package [pytmatrix](https://github.com/jleinonen/pytmatrix).

`tmd.lp.f`, `tmd.par.f` and `lpd.f` are used for randomly oriented nonspherical particles.

Note that both are double-precision versions. The extended-precision versions are not included.
