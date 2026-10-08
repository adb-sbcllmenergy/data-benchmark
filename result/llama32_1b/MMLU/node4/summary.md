# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/llama32_1b/idle_config4.csv` — 11.75375 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 253.0 | 261.0 | 265.6 | 259.9 | 6.4 |
| Total tokens | 15622 | 15887 | 16023 | 15844 | 204 |
| Cluster energy (J) | 6769.15 | 6993.59 | 7073.31 | 6945.35 | 157.71 |
| Idle energy (J) | 2974.07 | 3067.78 | 3121.67 | 3054.50 | 74.69 |
| Net (idle-subtracted) energy (J) | 3795.09 | 3925.82 | 3951.64 | 3890.85 | 83.93 |
| Overall J/token (cluster) | 0.43331 | 0.44021 | 0.44145 | 0.43832 | 0.00438 |
| Overall net J/token | 0.24293 | 0.24711 | 0.24662 | 0.24555 | 0.00228 |
| Eval J/token (cluster) | 0.35415 | 0.35395 | 0.34985 | 0.35265 | 0.00243 |
| Prediction J/token (cluster) | 0.79612 | 0.80134 | 0.80863 | 0.80203 | 0.00629 |
| Avg eval tokens/sec | 74.66 | 74.68 | 73.95 | 74.43 | 0.42 |
| Avg prediction tokens/sec | 31.53 | 31.47 | 31.44 | 31.48 | 0.05 |
| Total tokens/sec (wall-clock) | 61.74 | 60.87 | 60.33 | 60.98 | 0.71 |
