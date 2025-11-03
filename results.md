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
