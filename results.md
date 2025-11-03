======================================================================
COMPARISON MATRIX 1: Best Objective Values (lower is better)
======================================================================
optimizer          Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves      Momentum   Nelder-Mead       RMSProp
function
Function1  5.787528e-13       3.858465e-14      1.430522e-09        0.000000  4.207479e-12  7.019806e-15  9.350284e-13
Function2  9.457132e-01       8.959654e-01      3.130075e+00        0.796470  9.457132e-01  9.457132e-01  1.043369e+00
Function3  3.276422e-01       3.507459e-01      3.263923e+78        0.243356  8.111856e+94  1.000000e-01  4.419818e-01
Function4  1.000000e-01       1.000000e-01      3.910443e+99        0.100000  1.000000e-01  1.000000e-01  1.742561e-01
Function5  7.970061e-01       7.953970e-01      7.970024e-01        0.637836  7.954508e-01  8.496547e-01  8.097152e-01

======================================================================
COMPARISON MATRIX 2: Average Iterations
======================================================================
optimizer    Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves  Momentum  Nelder-Mead  RMSProp
function
Function1  164.50              125.0            375.25           20.50    375.25        90.75    38.75
Function2  293.75              125.0            500.00           33.25    272.00        99.00   500.00
Function3  500.00              125.0             12.75          500.00    253.75       189.25   500.00
Function4  323.25              125.0              6.00           26.00    312.00       130.25   276.50
Function5  305.00              125.0            148.25           28.25    331.00        96.75   500.00

======================================================================
COMPARISON MATRIX 3: Total API Calls
======================================================================
optimizer    Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves  Momentum  Nelder-Mead  RMSProp
function
Function1   330.0             564.00             751.5          128.50     751.5        90.75     78.5
Function2   588.5             544.25            1001.0          251.75     545.0        99.00   1001.0
Function3  1001.0             514.00              26.5         4851.00     508.5       189.25   1001.0
Function4   647.5             587.25              13.0          180.25     625.0       130.25    554.0
Function5   611.0             570.75             297.5          204.00     663.0        96.75   1001.0

======================================================================
BEST OPTIMIZER PER FUNCTION
======================================================================
Function1: Hooke & Jeeves       (f = 0.000000)
Function2: Hooke & Jeeves       (f = 0.796470)
Function3: Nelder-Mead          (f = 0.100000)
Function4: Momentum             (f = 0.100000)
Function5: Hooke & Jeeves       (f = 0.637836)

---

{'objective_values': optimizer          Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves  \
 function
 Function1  5.787528e-13       3.858465e-14      1.430522e-09        0.000000
 Function2  9.457132e-01       8.959654e-01      3.130075e+00        0.796470
 Function3  3.276422e-01       3.507459e-01      3.263923e+78        0.243356
 Function4  1.000000e-01       1.000000e-01      3.910443e+99        0.100000
 Function5  7.970061e-01       7.953970e-01      7.970024e-01        0.637836

 optimizer      Momentum   Nelder-Mead       RMSProp
 function
 Function1  4.207479e-12  7.019806e-15  9.350284e-13
 Function2  9.457132e-01  9.457132e-01  1.043369e+00
 Function3  8.111856e+94  1.000000e-01  4.419818e-01
 Function4  1.000000e-01  1.000000e-01  1.742561e-01
 Function5  7.954508e-01  8.496547e-01  8.097152e-01  ,
 'iterations': optimizer    Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves  \
 function
 Function1  164.50              125.0            375.25           20.50
 Function2  293.75              125.0            500.00           33.25
 Function3  500.00              125.0             12.75          500.00
 Function4  323.25              125.0              6.00           26.00
 Function5  305.00              125.0            148.25           28.25

 optimizer  Momentum  Nelder-Mead  RMSProp
 function
 Function1    375.25        90.75    38.75
 Function2    272.00        99.00   500.00
 Function3    253.75       189.25   500.00
 Function4    312.00       130.25   276.50
 Function5    331.00        96.75   500.00  ,
 'api_calls': optimizer    Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves  \
 function
 Function1   330.0             564.00             751.5          128.50
 Function2   588.5             544.25            1001.0          251.75
 Function3  1001.0             514.00              26.5         4851.00
 Function4   647.5             587.25              13.0          180.25
 Function5   611.0             570.75             297.5          204.00

 optimizer  Momentum  Nelder-Mead  RMSProp
 function
 Function1     751.5        90.75     78.5
 Function2     545.0        99.00   1001.0
 Function3     508.5       189.25   1001.0
 Function4     625.0       130.25    554.0
 Function5     663.0        96.75   1001.0  ,
 'dataframe':              optimizer   function  start_point  \
 0     Gradient Descent  Function1   [0.0, 0.0]
 1             Momentum  Function1   [0.0, 0.0]
 2              RMSProp  Function1   [0.0, 0.0]
 3                 Adam  Function1   [0.0, 0.0]
 4    Coordinate Search  Function1   [0.0, 0.0]
 ..                 ...        ...          ...
 134            RMSProp  Function5  [3.0, -3.0]
 135               Adam  Function5  [3.0, -3.0]
 136  Coordinate Search  Function5  [3.0, -3.0]
 137     Hooke & Jeeves  Function5  [3.0, -3.0]
 138        Nelder-Mead  Function5  [3.0, -3.0]

                                        final_x   final_f  iterations  n_evals  \
 0                                   [0.0, 0.0]  0.000000           1        2
 1                                   [0.0, 0.0]  0.000000           1        2
 2                                   [0.0, 0.0]  0.000000           1        2
 3                                   [0.0, 0.0]  0.000000           1        2
 4                                   [0.0, 0.0]  0.000000         125      625
 ..                                         ...       ...         ...      ...
 134   [3.0456201587062233, -2.420513964977554]  1.139359         500      501
 135  [2.9949203266304645, -2.4744976435925143]  1.125797         242      243
 136  [2.9949198964260697, -2.4744971906204842]  1.125797         125      563
 137   [2.992767333984375, -1.4709186553955078]  0.981315          30      223
 138  [2.9963030972709017, -3.4777484203837736]  1.252529          94       94

      n_grad_evals  total_api_calls  \
 0               1                3
 1               1                3
 2               1                3
 3               1                3
 4               0              625
 ..            ...              ...
 134           500             1001
 135           242              485
 136             0              563
 137             0              223
 138             0               94

                                                history  success
 0                                  [([0.0, 0.0], 0.0)]     True
 1                                  [([0.0, 0.0], 0.0)]     True
 2                                  [([0.0, 0.0], 0.0)]     True
 3                                  [([0.0, 0.0], 0.0)]     True
 4    [([0.0, 0.0], 0.0), ([0.0, 0.0], 0.0), ([0.0, ...     True
 ..                                                 ...      ...
 134  [([3.0, -3.0], 1.3646552972638575), ([2.683772...     True
 135  [([3.0, -3.0], 1.3646552972638575), ([2.900000...     True
 136  [([3.0, -3.0], 1.3646552972638575), ([3.0, -2....     True
 137  [([3.0, -3.0], 1.3646552972638575), ([3.0, -1....     True
 138  [([3.0, -3.0], 1.3646552972638575), ([3.150000...     True

 [139 rows x 11 columns]}

---
---


======================================================================
RUNNING FULL EXPERIMENT
======================================================================
Starting 140 experiments...
======================================================================

======================================================================
Testing on Function1
======================================================================

  Starting point 1/4: [0.0, 0.0]
Converged after 1 iterations (gradient norm < 1e-06)
    [  1/140] Gradient Descent     → f=0.000000 (iters=  1, calls=   3)
Converged after 1 iterations (gradient norm < 1e-06)
    [  2/140] Momentum             → f=0.000000 (iters=  1, calls=   3)
Converged after 1 iterations (gradient norm < 1e-06)
    [  3/140] RMSProp              → f=0.000000 (iters=  1, calls=   3)
Converged after 1 iterations (gradient norm < 1e-06)
    [  4/140] Adam                 → f=0.000000 (iters=  1, calls=   3)
Converged after 76 epochs (step size < 1e-06)
    [  5/140] Coordinate Search    → f=0.000000 (iters= 76, calls= 380)
Converged after 25 iterations (step size < 1e-06)
    [  6/140] Hooke & Jeeves       → f=0.000000 (iters= 25, calls= 151)
    [  7/140] Nelder-Mead          → f=0.000000 (iters= 37, calls=  37)

  Starting point 2/4: [2.0, 2.0]
    [  8/140] Gradient Descent     → f=0.108052 (iters=500, calls=1001)
    [  9/140] Momentum             → f=0.000002 (iters=500, calls=1001)
Converged after 92 iterations (gradient norm < 1e-06)
    [ 10/140] RMSProp              → f=0.000000 (iters= 92, calls= 185)
Converged after 350 iterations (gradient norm < 1e-06)
    [ 11/140] Adam                 → f=0.000000 (iters=350, calls= 701)
Converged after 76 epochs (step size < 1e-06)
    [ 12/140] Coordinate Search    → f=0.088890 (iters= 76, calls= 380)
Converged after 44 iterations (step size < 1e-06)
    [ 13/140] Hooke & Jeeves       → f=0.000000 (iters= 44, calls= 326)
    [ 14/140] Nelder-Mead          → f=0.000000 (iters=107, calls= 107)

  Starting point 3/4: [-2.0, -2.0]
    [ 15/140] Gradient Descent     → f=0.108052 (iters=500, calls=1001)
    [ 16/140] Momentum             → f=0.000002 (iters=500, calls=1001)
Converged after 92 iterations (gradient norm < 1e-06)
    [ 17/140] RMSProp              → f=0.000000 (iters= 92, calls= 185)
Converged after 350 iterations (gradient norm < 1e-06)
    [ 18/140] Adam                 → f=0.000000 (iters=350, calls= 701)
Converged after 76 epochs (step size < 1e-06)
    [ 19/140] Coordinate Search    → f=0.088890 (iters= 76, calls= 228)
Converged after 44 iterations (step size < 1e-06)
    [ 20/140] Hooke & Jeeves       → f=0.000000 (iters= 44, calls= 318)
    [ 21/140] Nelder-Mead          → f=0.000000 (iters=107, calls= 107)

  Starting point 4/4: [3.0, -3.0]
    [ 22/140] Gradient Descent     → f=0.243116 (iters=500, calls=1001)
    [ 23/140] Momentum             → f=0.000005 (iters=500, calls=1001)
Converged after 126 iterations (gradient norm < 1e-06)
    [ 24/140] RMSProp              → f=0.000000 (iters=126, calls= 253)
    [ 25/140] Adam                 → f=0.000000 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [ 26/140] Coordinate Search    → f=0.555559 (iters= 76, calls= 304)
Converged after 29 iterations (step size < 1e-06)
    [ 27/140] Hooke & Jeeves       → f=0.000000 (iters= 29, calls= 187)
    [ 28/140] Nelder-Mead          → f=0.000000 (iters=112, calls= 112)

======================================================================
Testing on Function2
======================================================================

  Starting point 1/4: [0.0, 0.0]
Converged after 39 iterations (gradient norm < 1e-06)
    [ 29/140] Gradient Descent     → f=0.100000 (iters= 39, calls=  79)
Converged after 496 iterations (gradient norm < 1e-06)
    [ 30/140] Momentum             → f=0.100000 (iters=496, calls= 993)
    [ 31/140] RMSProp              → f=0.124748 (iters=500, calls=1001)
Converged after 288 iterations (gradient norm < 1e-06)
    [ 32/140] Adam                 → f=0.100000 (iters=288, calls= 577)
Converged after 76 epochs (step size < 1e-06)
    [ 33/140] Coordinate Search    → f=0.199496 (iters= 76, calls= 329)
Converged after 48 iterations (step size < 1e-06)
    [ 34/140] Hooke & Jeeves       → f=0.199496 (iters= 48, calls= 368)
    [ 35/140] Nelder-Mead          → f=0.100000 (iters=123, calls= 123)

  Starting point 2/4: [2.0, 2.0]
Converged after 39 iterations (gradient norm < 1e-06)
    [ 36/140] Gradient Descent     → f=0.895966 (iters= 39, calls=  79)
    [ 37/140] Momentum             → f=0.895966 (iters=500, calls=1001)
    [ 38/140] RMSProp              → f=0.920499 (iters=500, calls=1001)
Converged after 319 iterations (gradient norm < 1e-06)
    [ 39/140] Adam                 → f=0.895966 (iters=319, calls= 639)
Converged after 76 epochs (step size < 1e-06)
    [ 40/140] Coordinate Search    → f=1.393443 (iters= 76, calls= 331)
Converged after 50 iterations (step size < 1e-06)
    [ 41/140] Hooke & Jeeves       → f=1.393443 (iters= 50, calls= 387)
    [ 42/140] Nelder-Mead          → f=0.895966 (iters= 94, calls=  94)

  Starting point 3/4: [-2.0, -2.0]
Converged after 39 iterations (gradient norm < 1e-06)
    [ 43/140] Gradient Descent     → f=0.895966 (iters= 39, calls=  79)
    [ 44/140] Momentum             → f=0.895966 (iters=500, calls=1001)
    [ 45/140] RMSProp              → f=0.920499 (iters=500, calls=1001)
Converged after 319 iterations (gradient norm < 1e-06)
    [ 46/140] Adam                 → f=0.895966 (iters=319, calls= 639)
Converged after 76 epochs (step size < 1e-06)
    [ 47/140] Coordinate Search    → f=0.597479 (iters= 76, calls= 329)
Converged after 45 iterations (step size < 1e-06)
    [ 48/140] Hooke & Jeeves       → f=0.597479 (iters= 45, calls= 338)
    [ 49/140] Nelder-Mead          → f=0.895966 (iters= 94, calls=  94)

  Starting point 4/4: [3.0, -3.0]
Converged after 39 iterations (gradient norm < 1e-06)
    [ 50/140] Gradient Descent     → f=1.890920 (iters= 39, calls=  79)
Converged after 487 iterations (gradient norm < 1e-06)
    [ 51/140] Momentum             → f=1.890920 (iters=487, calls= 975)
    [ 52/140] RMSProp              → f=1.915308 (iters=500, calls=1001)
Converged after 239 iterations (gradient norm < 1e-06)
    [ 53/140] Adam                 → f=1.890920 (iters=239, calls= 479)
Converged after 76 epochs (step size < 1e-06)
    [ 54/140] Coordinate Search    → f=1.393443 (iters= 76, calls= 326)
Converged after 47 iterations (step size < 1e-06)
    [ 55/140] Hooke & Jeeves       → f=1.393443 (iters= 47, calls= 363)
    [ 56/140] Nelder-Mead          → f=1.890920 (iters= 85, calls=  85)

======================================================================
Testing on Function3
======================================================================

  Starting point 1/4: [0.0, 0.0]
    [ 57/140] Gradient Descent     → f=0.124205 (iters=500, calls=1001)
    [ 58/140] Momentum             → f=0.101552 (iters=500, calls=1001)
    [ 59/140] RMSProp              → f=0.147103 (iters=500, calls=1001)
    [ 60/140] Adam                 → f=0.100003 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [ 61/140] Coordinate Search    → f=0.132909 (iters= 76, calls= 258)
    [ 62/140] Hooke & Jeeves       → f=0.100132 (iters=500, calls=4233)
    [ 63/140] Nelder-Mead          → f=0.100000 (iters=175, calls= 175)

  Starting point 2/4: [2.0, 2.0]
    [ 64/140] Gradient Descent     → f=0.105831 (iters=500, calls=1001)
    [ 65/140] Momentum             → f=0.103629 (iters=500, calls=1001)
    [ 66/140] RMSProp              → f=0.199875 (iters=500, calls=1001)
    [ 67/140] Adam                 → f=0.130192 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [ 68/140] Coordinate Search    → f=0.139348 (iters= 76, calls= 369)
    [ 69/140] Hooke & Jeeves       → f=0.102522 (iters=500, calls=5397)
    [ 70/140] Nelder-Mead          → f=0.100000 (iters=147, calls= 147)

  Starting point 3/4: [-2.0, -2.0]
Converged after 6 iterations (gradient norm < 1e-06)
    [ 71/140] Gradient Descent     → f=9213371873856172389733769322978136879763760766261258050034763051302912.000000 (iters=  6, calls=  13)
    [ 72/140] Momentum             → f=0.171460 (iters=500, calls=1001)
    [ 73/140] RMSProp              → f=0.148322 (iters=500, calls=1001)
    [ 74/140] Adam                 → f=0.314544 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [ 75/140] Coordinate Search    → f=12.723758 (iters= 76, calls= 228)
    [ 76/140] Hooke & Jeeves       → f=0.100121 (iters=500, calls=4218)
    [ 77/140] Nelder-Mead          → f=0.100000 (iters=178, calls= 178)

  Starting point 4/4: [3.0, -3.0]
Converged after 6 iterations (gradient norm < 1e-06)
    [ 78/140] Gradient Descent     → f=512850487324610440791021518594927882796038088053948638762862901455316990535272390942017222693442354447578335262277632.000000 (iters=  6, calls=  13)
    [ 79/140] Momentum             → f=0.102421 (iters=500, calls=1001)
    [ 80/140] RMSProp              → f=0.927498 (iters=500, calls=1001)
    [ 81/140] Adam                 → f=1.004789 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [ 82/140] Coordinate Search    → f=1.014394 (iters= 76, calls= 344)
    [ 83/140] Hooke & Jeeves       → f=0.641452 (iters=500, calls=5023)
    [ 84/140] Nelder-Mead          → f=0.100000 (iters=257, calls= 257)

======================================================================
Testing on Function4
======================================================================

  Starting point 1/4: [0.0, 0.0]
    [ 85/140] Gradient Descent     → f=0.100000 (iters=500, calls=1001)
    [ 86/140] Momentum             → f=0.100000 (iters=500, calls=1001)
Converged after 154 iterations (gradient norm < 1e-06)
    [ 87/140] RMSProp              → f=0.100000 (iters=154, calls= 309)
    [ 88/140] Adam                 → f=0.100001 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [ 89/140] Coordinate Search    → f=63.847264 (iters= 76, calls= 228)
Converged after 45 iterations (step size < 1e-06)
    [ 90/140] Hooke & Jeeves       → f=0.100000 (iters= 45, calls= 342)
    [ 91/140] Nelder-Mead          → f=0.100000 (iters=193, calls= 193)

  Starting point 2/4: [2.0, 2.0]
Converged after 462 iterations (gradient norm < 1e-06)
    [ 92/140] Gradient Descent     → f=0.100000 (iters=462, calls= 925)
    [ 93/140] Momentum             → f=0.100000 (iters=500, calls=1001)
Converged after 95 iterations (gradient norm < 1e-06)
    [ 94/140] RMSProp              → f=0.100000 (iters= 95, calls= 191)
Converged after 487 iterations (gradient norm < 1e-06)
    [ 95/140] Adam                 → f=0.100000 (iters=487, calls= 975)
Converged after 76 epochs (step size < 1e-06)
    [ 96/140] Coordinate Search    → f=0.100000 (iters= 76, calls= 349)
Converged after 31 iterations (step size < 1e-06)
    [ 97/140] Hooke & Jeeves       → f=0.100000 (iters= 31, calls= 206)
    [ 98/140] Nelder-Mead          → f=0.100000 (iters=108, calls= 108)

  Starting point 3/4: [-2.0, -2.0]
Converged after 210 iterations (gradient norm < 1e-06)
    [ 99/140] Gradient Descent     → f=0.100000 (iters=210, calls= 421)
    [100/140] Momentum             → f=0.100000 (iters=500, calls=1001)
Converged after 114 iterations (gradient norm < 1e-06)
    [101/140] RMSProp              → f=0.100000 (iters=114, calls= 229)
    [102/140] Adam                 → f=0.100000 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [103/140] Coordinate Search    → f=9.715503 (iters= 76, calls= 366)
Converged after 48 iterations (step size < 1e-06)
    [104/140] Hooke & Jeeves       → f=0.100000 (iters= 48, calls= 374)
    [105/140] Nelder-Mead          → f=0.100000 (iters=126, calls= 126)

  Starting point 4/4: [3.0, -3.0]
Converged after 489 iterations (gradient norm < 1e-06)
    [106/140] Gradient Descent     → f=0.100000 (iters=489, calls= 979)
    [107/140] Momentum             → f=0.100000 (iters=500, calls=1001)
    [108/140] RMSProp              → f=0.141671 (iters=500, calls=1001)
    [109/140] Adam                 → f=0.100000 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [110/140] Coordinate Search    → f=0.100000 (iters= 76, calls= 337)
Converged after 49 iterations (step size < 1e-06)
    [111/140] Hooke & Jeeves       → f=0.100000 (iters= 49, calls= 385)
    [112/140] Nelder-Mead          → f=0.100000 (iters= 94, calls=  94)

======================================================================
Testing on Function5
======================================================================

  Starting point 1/4: [0.0, 0.0]
Converged after 351 iterations (gradient norm < 1e-06)
    [113/140] Gradient Descent     → f=0.755965 (iters=351, calls= 703)
    [114/140] Momentum             → f=0.755965 (iters=500, calls=1001)
    [115/140] RMSProp              → f=0.759247 (iters=500, calls=1001)
Converged after 240 iterations (gradient norm < 1e-06)
    [116/140] Adam                 → f=0.755965 (iters=240, calls= 481)
Converged after 76 epochs (step size < 1e-06)
    [117/140] Coordinate Search    → f=0.755965 (iters= 76, calls= 327)
Converged after 47 iterations (step size < 1e-06)
    [118/140] Hooke & Jeeves       → f=0.755965 (iters= 47, calls= 363)
    [119/140] Nelder-Mead          → f=0.755965 (iters=121, calls= 121)

  Starting point 2/4: [2.0, 2.0]
    [120/140] Gradient Descent     → f=0.100417 (iters=500, calls=1001)
    [121/140] Momentum             → f=0.100183 (iters=500, calls=1001)
    [122/140] RMSProp              → f=0.108727 (iters=500, calls=1001)
    [123/140] Adam                 → f=0.100469 (iters=500, calls=1001)
Converged after 76 epochs (step size < 1e-06)
    [124/140] Coordinate Search    → f=0.100000 (iters= 76, calls= 356)
Converged after 42 iterations (step size < 1e-06)
    [125/140] Hooke & Jeeves       → f=0.100000 (iters= 42, calls= 321)
    [126/140] Nelder-Mead          → f=0.100000 (iters= 84, calls=  84)

  Starting point 3/4: [-2.0, -2.0]
Converged after 365 iterations (gradient norm < 1e-06)
    [127/140] Gradient Descent     → f=1.199826 (iters=365, calls= 731)
    [128/140] Momentum             → f=1.199826 (iters=500, calls=1001)
    [129/140] RMSProp              → f=1.202911 (iters=500, calls=1001)
Converged after 220 iterations (gradient norm < 1e-06)
    [130/140] Adam                 → f=1.199826 (iters=220, calls= 441)
Converged after 76 epochs (step size < 1e-06)
    [131/140] Coordinate Search    → f=1.199826 (iters= 76, calls= 339)
Converged after 48 iterations (step size < 1e-06)
    [132/140] Hooke & Jeeves       → f=1.199826 (iters= 48, calls= 371)
    [133/140] Nelder-Mead          → f=1.290126 (iters= 88, calls=  88)

  Starting point 4/4: [3.0, -3.0]
Converged after 355 iterations (gradient norm < 1e-06)
    [134/140] Gradient Descent     → f=1.125797 (iters=355, calls= 711)
    [135/140] Momentum             → f=1.125797 (iters=500, calls=1001)
    [136/140] RMSProp              → f=1.128907 (iters=500, calls=1001)
Converged after 240 iterations (gradient norm < 1e-06)
    [137/140] Adam                 → f=1.125797 (iters=240, calls= 481)
Converged after 76 epochs (step size < 1e-06)
    [138/140] Coordinate Search    → f=1.125797 (iters= 76, calls= 336)
Converged after 48 iterations (step size < 1e-06)
    [139/140] Hooke & Jeeves       → f=1.125797 (iters= 48, calls= 374)
    [140/140] Nelder-Mead          → f=1.252529 (iters= 94, calls=  94)

======================================================================
✅ Completed 140 / 140 experiments successfully!
======================================================================
✅ Results saved to full_results.pkl

---


======================================================================
COMPARISON MATRIX 1: Best Objective Values (lower is better)
======================================================================
optimizer          Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves  Momentum   Nelder-Mead       RMSProp
function
Function1  1.323446e-08           0.183335      1.148048e-01    2.170483e-14  0.000003  7.019806e-15  8.912979e-13
Function2  9.457132e-01           0.895965      9.457132e-01    8.959654e-01  0.945713  9.457132e-01  9.702637e-01
Function3  3.873819e-01           3.502602     1.282126e+116    2.360567e-01  0.119765  1.000000e-01  3.556992e-01
Function4  1.000003e-01          18.440692      1.000000e-01    1.000000e-01  0.100000  1.000000e-01  1.104178e-01
Function5  7.955144e-01           0.795397      7.955012e-01    7.953971e-01  0.795443  8.496547e-01  7.999478e-01

======================================================================
COMPARISON MATRIX 2: Average Iterations
======================================================================
optimizer    Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves  Momentum  Nelder-Mead  RMSProp
function
Function1  300.25               76.0            375.25           35.50    375.25        90.75    77.75
Function2  291.25               76.0             39.00           47.50    495.75        99.00   500.00
Function3  500.00               76.0            253.00          500.00    500.00       189.25   500.00
Function4  496.75               76.0            415.25           43.25    500.00       130.25   215.75
Function5  300.00               76.0            392.75           46.25    500.00        96.75   500.00

======================================================================
COMPARISON MATRIX 3: Total API Calls
======================================================================
optimizer    Adam  Coordinate Search  Gradient Descent  Hooke & Jeeves  Momentum  Nelder-Mead  RMSProp
function
Function1   601.5             323.00             751.5          245.50     751.5        90.75    156.5
Function2   583.5             328.75              79.0          364.00     992.5        99.00   1001.0
Function3  1001.0             299.75             507.0         4717.75    1001.0       189.25   1001.0
Function4   994.5             320.00             831.5          326.75    1001.0       130.25    432.5
Function5   601.0             339.50             786.5          357.25    1001.0        96.75   1001.0

======================================================================
BEST OPTIMIZER PER FUNCTION
======================================================================
Function1: Nelder-Mead          (f = 0.000000)
Function2: Coordinate Search    (f = 0.895965)
Function3: Nelder-Mead          (f = 0.100000)
Function4: Gradient Descent     (f = 0.100000)
Function5: Coordinate Search    (f = 0.795397)
