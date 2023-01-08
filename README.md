# Numerical methods of data processing.

Problem 1(03)

Set of files containing 1D set of data (XY) is given. Assuming dependency Y(x) = k * X + b + noise, define noise type (white noise, gaussian noise, random telegraph process), 
noise intensity, confidence intervals and expected valeus of k and b. Repeat calculations for each implemetation and implementation ensemble.

Problem 2(13)

Set of files containing 1D set of data (XY) is given. Assuming dependency Y(x) = a_{n} * X^n + a_{n-1} * X^{n-1} + … + a_{1} * X + a_{0} + noise, 
where polynomial degree n is unknown, define noise type (white noise, gaussian noise, random telegraph process), noise intensity, confidence intervals and 
expected valeus of a_{i}. Repeat calculations for each implemetation and implementation ensemble.

For each implementation and implementation ensemble eliminate high frequency noise and calculate derivative dY/dX. 
For mean parameters find extremes of deterministic signal component.

Problem 3(23)

Set of files containing 1D set of data (XY) is given.  Assuming dependency Y(X) as combination of localized peaks and additive noise, estimate peaks parameters 
(mean values and confidence intervals of amlitude, location and width). Define type of peaks (lorentz of gaussian).

Problem 4(33)

Set of files containing 1D set of data (X: time, s; Y: signal, units) is given.  Assuming dependency Y(X) as combination of periodical signal and additive noise, 
define signal parameters (frequency, amplitude and relative phase) for each implementation and ensamble.

Results are presented in NumMeth.pdf, calculation details in Jupyter notebooks.

