# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/llama32_1b/idle_config1.csv` — 2.92675 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1134.3 | 1144.9 | 1127.8 | 1135.7 | 8.6 |
| Total tokens | 17415 | 17484 | 17388 | 17429 | 50 |
| Cluster energy (J) | 9259.60 | 9342.31 | 9226.38 | 9276.10 | 59.70 |
| Idle energy (J) | 3319.88 | 3350.86 | 3300.70 | 3323.81 | 25.31 |
| Net (idle-subtracted) energy (J) | 5939.72 | 5991.45 | 5925.68 | 5952.28 | 34.64 |
| Overall J/token (cluster) | 0.53170 | 0.53434 | 0.53062 | 0.53222 | 0.00191 |
| Overall net J/token | 0.34107 | 0.34268 | 0.34079 | 0.34151 | 0.00102 |
| Eval J/token (cluster) | 0.22472 | 0.22333 | 0.22346 | 0.22383 | 0.00077 |
| Prediction J/token (cluster) | 0.58439 | 0.58746 | 0.58343 | 0.58509 | 0.00211 |
| Avg eval tokens/sec | 38.27 | 38.14 | 38.24 | 38.21 | 0.07 |
| Avg prediction tokens/sec | 13.89 | 13.84 | 13.94 | 13.89 | 0.05 |
| Total tokens/sec (wall-clock) | 15.35 | 15.27 | 15.42 | 15.35 | 0.07 |
