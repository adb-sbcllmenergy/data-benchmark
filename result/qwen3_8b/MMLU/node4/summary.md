# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_8b/idle_config4.csv` — 11.64519 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1437.7 | 1569.2 | 1387.6 | 1464.8 | 93.8 |
| Total tokens | 18128 | 18999 | 17790 | 18306 | 624 |
| Cluster energy (J) | 41819.12 | 45634.70 | 40340.27 | 42598.03 | 2731.81 |
| Idle energy (J) | 16742.06 | 18273.65 | 16159.24 | 17058.32 | 1092.11 |
| Net (idle-subtracted) energy (J) | 25077.06 | 27361.05 | 24181.03 | 25539.71 | 1639.72 |
| Overall J/token (cluster) | 2.30688 | 2.40195 | 2.26758 | 2.32547 | 0.06909 |
| Overall net J/token | 1.38333 | 1.44013 | 1.35925 | 1.39424 | 0.04153 |
| Eval J/token (cluster) | 1.59090 | 1.58492 | 1.59033 | 1.58872 | 0.00330 |
| Prediction J/token (cluster) | 4.29773 | 4.32457 | 4.29355 | 4.30528 | 0.01683 |
| Avg eval tokens/sec | 19.03 | 19.19 | 19.04 | 19.09 | 0.09 |
| Avg prediction tokens/sec | 6.54 | 6.61 | 6.49 | 6.55 | 0.06 |
| Total tokens/sec (wall-clock) | 12.61 | 12.11 | 12.82 | 12.51 | 0.37 |
