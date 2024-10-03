# Germany models

- knot distance: 30 km (493 knots)
- 4 chains (HPC) / 6 chains (R)
- thinning: 30 (HPC) / 10 (R)

<img src="https://github.com/user-attachments/assets/3790c3dc-2094-4a85-9b35-d4bfbc0e0686" width="390"/> <img src="https://github.com/user-attachments/assets/6c522184-8e4c-4faf-91a3-fbc56c1a64e2" width="425"/>

---

## R

- 6 chains

![image](https://github.com/user-attachments/assets/3790c3dc-2094-4a85-9b35-d4bfbc0e0686)

```r
Iterations = 2010:12000
Thinning interval = 10
Number of chains = 6
Sample size per chain = 1000

1. Empirical mean and standard deviation for each variable,
   plus standard error of the mean:

                  Mean      SD Naive SE Time-series SE
Alpha1[factor1] 144118 76317.7  985.258       11923.08
Alpha1[factor2]  10629   583.1    7.528          38.82
Alpha1[factor3]  89887 42478.0  548.389         695.67

2. Quantiles for each variable:

                 2.5%   25%    50%    75%  97.5%
Alpha1[factor1] 31982 95946 127928 202553 309160
Alpha1[factor2] 10661 10661  10661  10661  10661
Alpha1[factor3]     0 85285 106607 117267 138589
```

## Hmsc-HPC

![image](https://github.com/user-attachments/assets/6c522184-8e4c-4faf-91a3-fbc56c1a64e2)

```r
Iterations = 15030:45000
Thinning interval = 30
Number of chains = 4
Sample size per chain = 1000

1. Empirical mean and standard deviation for each variable,
   plus standard error of the mean:

                  Mean     SD Naive SE Time-series SE
Alpha1[factor1] 212648  42870    677.8         5315.6
Alpha1[factor2] 194253 330640   5227.9         8091.4
Alpha1[factor3]  84902  44928    710.4          524.2

2. Quantiles for each variable:

                  2.5%    25%    50%    75%  97.5%
Alpha1[factor1] 138589 181231 213214 234535 309160
Alpha1[factor2]  10661  10661  10661  85285 991443
Alpha1[factor3]  10661  58634 106607 117267 138589
```
