# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_4b/idle_config1.csv` — 2.93065 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1776.8 | 1794.9 | 1825.6 | 1799.1 | 24.6 |
| Total tokens | 16110 | 16189 | 16324 | 16208 | 108 |
| Cluster energy (J) | 15379.33 | 15512.45 | 15768.68 | 15553.49 | 197.89 |
| Idle energy (J) | 5207.22 | 5260.17 | 5350.07 | 5272.48 | 72.21 |
| Net (idle-subtracted) energy (J) | 10172.11 | 10252.28 | 10418.62 | 10281.00 | 125.74 |
| Overall J/token (cluster) | 0.95464 | 0.95821 | 0.96598 | 0.95961 | 0.00580 |
| Overall net J/token | 0.63142 | 0.63329 | 0.63824 | 0.63431 | 0.00353 |
| Eval J/token (cluster) | 0.75481 | 0.75380 | 0.75386 | 0.75416 | 0.00057 |
| Prediction J/token (cluster) | 1.91407 | 1.91246 | 1.91154 | 1.91269 | 0.00128 |
| Avg eval tokens/sec | 12.53 | 12.52 | 12.54 | 12.53 | 0.01 |
| Avg prediction tokens/sec | 4.46 | 4.45 | 4.45 | 4.45 | 0.00 |
| Total tokens/sec (wall-clock) | 9.07 | 9.02 | 8.94 | 9.01 | 0.06 |
