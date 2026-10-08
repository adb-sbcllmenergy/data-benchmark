# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/llama32_1b/idle_config2.csv` — 5.93077 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 708.4 | 694.6 | 707.4 | 703.5 | 7.7 |
| Total tokens | 18774 | 18556 | 18734 | 18688 | 116 |
| Cluster energy (J) | 10620.13 | 10483.26 | 10631.38 | 10578.26 | 82.46 |
| Idle energy (J) | 4201.43 | 4119.79 | 4195.27 | 4172.16 | 45.46 |
| Net (idle-subtracted) energy (J) | 6418.70 | 6363.47 | 6436.11 | 6406.09 | 37.92 |
| Overall J/token (cluster) | 0.56568 | 0.56495 | 0.56749 | 0.56604 | 0.00131 |
| Overall net J/token | 0.34189 | 0.34293 | 0.34355 | 0.34279 | 0.00084 |
| Eval J/token (cluster) | 0.27508 | 0.27368 | 0.27878 | 0.27585 | 0.00264 |
| Prediction J/token (cluster) | 0.61138 | 0.61138 | 0.61300 | 0.61192 | 0.00094 |
| Avg eval tokens/sec | 55.00 | 55.53 | 55.04 | 55.19 | 0.29 |
| Avg prediction tokens/sec | 24.19 | 24.36 | 24.18 | 24.24 | 0.10 |
| Total tokens/sec (wall-clock) | 26.50 | 26.71 | 26.48 | 26.57 | 0.13 |
