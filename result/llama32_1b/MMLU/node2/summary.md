# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/llama32_1b/idle_config2.csv` — 5.93077 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 352.6 | 339.8 | 350.6 | 347.7 | 6.9 |
| Total tokens | 16334 | 15969 | 16213 | 16172 | 186 |
| Cluster energy (J) | 5410.64 | 5193.92 | 5335.44 | 5313.33 | 110.04 |
| Idle energy (J) | 2091.47 | 2015.30 | 2079.25 | 2062.01 | 40.91 |
| Net (idle-subtracted) energy (J) | 3319.17 | 3178.62 | 3256.19 | 3251.33 | 70.40 |
| Overall J/token (cluster) | 0.33125 | 0.32525 | 0.32908 | 0.32853 | 0.00304 |
| Overall net J/token | 0.20321 | 0.19905 | 0.20084 | 0.20103 | 0.00209 |
| Eval J/token (cluster) | 0.25393 | 0.25342 | 0.25265 | 0.25333 | 0.00064 |
| Prediction J/token (cluster) | 0.61376 | 0.61814 | 0.61832 | 0.61674 | 0.00258 |
| Avg eval tokens/sec | 59.81 | 59.29 | 59.25 | 59.45 | 0.31 |
| Avg prediction tokens/sec | 24.11 | 24.09 | 23.96 | 24.05 | 0.08 |
| Total tokens/sec (wall-clock) | 46.32 | 46.99 | 46.25 | 46.52 | 0.41 |
