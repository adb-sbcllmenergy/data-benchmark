# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/llama32_1b/idle_config4.csv` — 11.75375 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 557.3 | 582.2 | 541.6 | 560.4 | 20.5 |
| Total tokens | 19311 | 20017 | 18774 | 19367 | 623 |
| Cluster energy (J) | 14503.73 | 15090.18 | 14093.97 | 14562.63 | 500.71 |
| Idle energy (J) | 6550.48 | 6843.40 | 6366.09 | 6586.66 | 240.71 |
| Net (idle-subtracted) energy (J) | 7953.26 | 8246.77 | 7727.88 | 7975.97 | 260.19 |
| Overall J/token (cluster) | 0.75106 | 0.75387 | 0.75072 | 0.75188 | 0.00173 |
| Overall net J/token | 0.41185 | 0.41199 | 0.41163 | 0.41182 | 0.00018 |
| Eval J/token (cluster) | 0.37876 | 0.39653 | 0.39848 | 0.39126 | 0.01086 |
| Prediction J/token (cluster) | 0.80773 | 0.80606 | 0.80611 | 0.80663 | 0.00095 |
| Avg eval tokens/sec | 70.10 | 67.29 | 68.74 | 68.71 | 1.41 |
| Avg prediction tokens/sec | 31.61 | 31.58 | 31.60 | 31.59 | 0.02 |
| Total tokens/sec (wall-clock) | 34.65 | 34.38 | 34.66 | 34.56 | 0.16 |
