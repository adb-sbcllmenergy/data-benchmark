# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_0.6b/idle_config1.csv` — 2.91817 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 673.0 | 798.4 | 681.6 | 717.7 | 70.0 |
| Total tokens | 22329 | 23967 | 22990 | 23095 | 824 |
| Cluster energy (J) | 5515.69 | 6487.67 | 5614.65 | 5872.67 | 534.90 |
| Idle energy (J) | 1963.89 | 2329.85 | 1989.17 | 2094.30 | 204.38 |
| Net (idle-subtracted) energy (J) | 3551.80 | 4157.82 | 3625.48 | 3778.37 | 330.67 |
| Overall J/token (cluster) | 0.24702 | 0.27069 | 0.24422 | 0.25398 | 0.01454 |
| Overall net J/token | 0.15907 | 0.17348 | 0.15770 | 0.16342 | 0.00874 |
| Eval J/token (cluster) | 0.13055 | 0.13021 | 0.13100 | 0.13059 | 0.00040 |
| Prediction J/token (cluster) | 0.41964 | 0.44683 | 0.40054 | 0.42234 | 0.02327 |
| Avg eval tokens/sec | 77.71 | 77.89 | 77.76 | 77.78 | 0.09 |
| Avg prediction tokens/sec | 24.30 | 24.19 | 24.30 | 24.26 | 0.06 |
| Total tokens/sec (wall-clock) | 33.18 | 30.02 | 33.73 | 32.31 | 2.00 |
