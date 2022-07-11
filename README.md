# Seminar in Economics of Information and Privacy
## Getting started
Start by cloning the Git repsitory: 
```sh
git clone https://github.com/lena-will/differential-privacy-seminar.git
```
## Differential Privacy in Economics
This repository holds the code to my seminar project on differential privacy in economics.
The file `info-utility.ipynb` has the code to the bisection method (via `scipy`) that numerically finds the root of a function. It's used to find the optimal $\epsilon^*$ for differential private algorithms when equating the MRT and the MRS as described by Abowd and Schmute (2019), but applied to my model extension.
The file `info-utility-quadratic.ipynb` has the code to find the optimal epsilon in the case of a quadratic infomration utility function. 
## Graphical solution 
`info-utility.ipynb` and `info-utility.ipynb` also have the code to my plots showing the optimal epsilon graphically for an exponential and quadratic information utility respectively.
## References
(1) Abowd, John M. and Ian M. Schmutte (2019). “An Economic Analysis of Privacy Protection and
Statistical Accuracy as Social Choices”. In: American Economic Review 109.1, pp. 171–202.

(2) Official Scipy Documentation: https://docs.scipy.org/doc/scipy/
