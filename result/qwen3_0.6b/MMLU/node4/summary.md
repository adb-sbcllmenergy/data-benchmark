# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_0.6b/idle_config4.csv` — 11.79037 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 471.7 | 332.3 | 373.3 | 392.4 | 71.6 |
| Total tokens | 25083 | 21329 | 22930 | 23114 | 1884 |
| Cluster energy (J) | 12247.73 | 8338.27 | 9362.66 | 9982.89 | 2027.18 |
| Idle energy (J) | 5561.12 | 3918.31 | 4400.92 | 4626.78 | 844.37 |
| Net (idle-subtracted) energy (J) | 6686.61 | 4419.96 | 4961.74 | 5356.10 | 1183.67 |
| Overall J/token (cluster) | 0.48829 | 0.39094 | 0.40832 | 0.42918 | 0.05192 |
| Overall net J/token | 0.26658 | 0.20723 | 0.21639 | 0.23006 | 0.03195 |
| Eval J/token (cluster) | 0.29549 | 0.29437 | 0.29203 | 0.29396 | 0.00176 |
| Prediction J/token (cluster) | 0.70707 | 0.55196 | 0.56986 | 0.60963 | 0.08486 |
| Avg eval tokens/sec | 84.68 | 83.81 | 84.98 | 84.49 | 0.61 |
| Avg prediction tokens/sec | 45.72 | 46.44 | 45.83 | 46.00 | 0.38 |
| Total tokens/sec (wall-clock) | 53.18 | 64.18 | 61.43 | 59.60 | 5.72 |
