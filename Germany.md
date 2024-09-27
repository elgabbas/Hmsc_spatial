# Convergence of Germany models

- Study area: Germany (3,350 grid cells)
- 102 species
- grid size: 10x10 km
- thinning = 30 / transient = 30\*500 / samples: 1000
- 4 Chains

---

## 493 knots spaced by 30 km

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

---

## 1,033 knots spaced by 20 km

![image](https://github.com/user-attachments/assets/b0ff6b7a-746b-4483-96bb-8f912ceee59c)

```r
Iterations = 15030:45000
Thinning interval = 30
Number of chains = 4
Sample size per chain = 1000

1. Empirical mean and standard deviation for each variable,
   plus standard error of the mean:

                  Mean    SD Naive SE Time-series SE
Alpha1[factor1] 169955 45342    716.9         7180.5
Alpha1[factor2]  10661     0      0.0            0.0
Alpha1[factor3] 101961 14300    226.1          557.3

2. Quantiles for each variable:

                 2.5%    25%    50%    75%  97.5%
Alpha1[factor1] 95946 138589 159910 202553 266517
Alpha1[factor2] 10661  10661  10661  10661  10661
Alpha1[factor3] 74625  95946  95946 106607 128195

```

---

## 1,757 knots spaced by 15 km

thinning = 30

![image](https://github.com/user-attachments/assets/26c826b2-f9fa-4110-8431-a16ef305e614)

```r
Iterations = 15030:45000
Thinning interval = 30
Number of chains = 4
Sample size per chain = 1000

1. Empirical mean and standard deviation for each variable,
   plus standard error of the mean:

                  Mean    SD Naive SE Time-series SE
Alpha1[factor1] 157994 78175     1236          17992
Alpha1[factor2]  10661     0        0              0
Alpha1[factor3]  99048 14106      223            592

2. Quantiles for each variable:

                 2.5%    25%    50%    75%  97.5%
Alpha1[factor1] 31982 117267 159910 191892 330481
Alpha1[factor2] 10661  10661  10661  10661  10661
Alpha1[factor3] 74625  85285  95946 106607 127928
```

---

## 3,350 knots spaced by 10 km

### thinning = 30

![image](https://github.com/user-attachments/assets/e0abb19c-f27d-4099-8ffe-01c38f515f79)

```r
Iterations = 15030:45000
Thinning interval = 30
Number of chains = 4
Sample size per chain = 1000

1. Empirical mean and standard deviation for each variable,
   plus standard error of the mean:

                  Mean    SD Naive SE Time-series SE
Alpha1[factor1] 191828 93254   1474.5          40342
Alpha1[factor2]  10661     0      0.0              0
Alpha1[factor3]  93222 24452    386.6           5570

2. Quantiles for each variable:

                 2.5%    25%    50%    75%  97.5%
Alpha1[factor1] 31982 149249 181231 223874 437088
Alpha1[factor2] 10661  10661  10661  10661  10661
Alpha1[factor3] 21321  85285  95946 106607 127928
```

---

### thinning = 50

![image](https://github.com/user-attachments/assets/10fcb445-bdfd-49b1-853f-9eb959afe1f8)

```r

Iterations = 15030:45000
Thinning interval = 30
Number of chains = 4
Sample size per chain = 1000

1. Empirical mean and standard deviation for each variable,
   plus standard error of the mean:

                  Mean    SD Naive SE Time-series SE
Alpha1[factor1] 144772 88216   1394.8         4207.5
Alpha1[factor2]  31803 37482    592.6          624.3
Alpha1[factor3] 100943 14259    225.5          499.5

2. Quantiles for each variable:

                 2.5%   25%    50%    75%  97.5%
Alpha1[factor1] 10661 66629 159910 202553 298499
Alpha1[factor2] 10661 10661  10661  23987 117267
Alpha1[factor3] 74625 95946  95946 106607 127928
```
