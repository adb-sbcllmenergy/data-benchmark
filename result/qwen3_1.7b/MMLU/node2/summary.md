# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_1.7b/idle_config2.csv` — 5.91215 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 969.8 | 1091.8 | 1158.6 | 1073.4 | 95.7 |
| Total tokens | 24035 | 25921 | 26978 | 25645 | 1491 |
| Cluster energy (J) | 14446.72 | 16051.67 | 17291.28 | 15929.89 | 1426.18 |
| Idle energy (J) | 5733.85 | 6454.99 | 6850.00 | 6346.28 | 565.96 |
| Net (idle-subtracted) energy (J) | 8712.88 | 9596.67 | 10441.28 | 9583.61 | 864.28 |
| Overall J/token (cluster) | 0.60107 | 0.61925 | 0.64094 | 0.62042 | 0.01996 |
| Overall net J/token | 0.36251 | 0.37023 | 0.38703 | 0.37326 | 0.01254 |
| Eval J/token (cluster) | 0.35762 | 0.35231 | 0.35702 | 0.35565 | 0.00291 |
| Prediction J/token (cluster) | 0.90437 | 0.90200 | 0.91837 | 0.90824 | 0.00885 |
| Avg eval tokens/sec | 42.40 | 42.51 | 42.71 | 42.54 | 0.16 |
| Avg prediction tokens/sec | 16.65 | 16.54 | 16.66 | 16.62 | 0.07 |
| Total tokens/sec (wall-clock) | 24.78 | 23.74 | 23.28 | 23.94 | 0.77 |
