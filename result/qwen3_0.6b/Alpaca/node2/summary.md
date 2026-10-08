# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_0.6b/idle_config2.csv` — 5.95216 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 392.8 | 384.1 | 401.6 | 392.8 | 8.7 |
| Total tokens | 17250 | 16985 | 17437 | 17224 | 227 |
| Cluster energy (J) | 5610.41 | 5545.47 | 5760.76 | 5638.88 | 110.43 |
| Idle energy (J) | 2338.01 | 2286.33 | 2390.44 | 2338.26 | 52.06 |
| Net (idle-subtracted) energy (J) | 3272.40 | 3259.14 | 3370.33 | 3300.62 | 60.73 |
| Overall J/token (cluster) | 0.32524 | 0.32649 | 0.33038 | 0.32737 | 0.00268 |
| Overall net J/token | 0.18970 | 0.19188 | 0.19329 | 0.19162 | 0.00180 |
| Eval J/token (cluster) | 0.16310 | 0.16287 | 0.18029 | 0.16875 | 0.00999 |
| Prediction J/token (cluster) | 0.35757 | 0.35973 | 0.35992 | 0.35908 | 0.00130 |
| Avg eval tokens/sec | 85.51 | 85.97 | 76.03 | 82.51 | 5.61 |
| Avg prediction tokens/sec | 39.63 | 39.87 | 39.74 | 39.75 | 0.12 |
| Total tokens/sec (wall-clock) | 43.92 | 44.22 | 43.42 | 43.85 | 0.40 |
