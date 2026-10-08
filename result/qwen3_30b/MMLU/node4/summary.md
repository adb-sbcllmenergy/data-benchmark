# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_30b/idle_config4.csv` — 11.57850 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 635.6 | 634.7 | 615.0 | 628.4 | 11.6 |
| Total tokens | 13638 | 13558 | 13558 | 13585 | 46 |
| Cluster energy (J) | 19415.08 | 19308.06 | 18864.54 | 19195.90 | 291.91 |
| Idle energy (J) | 7359.05 | 7349.15 | 7121.06 | 7276.42 | 134.64 |
| Net (idle-subtracted) energy (J) | 12056.03 | 11958.91 | 11743.48 | 11919.47 | 159.96 |
| Overall J/token (cluster) | 1.42360 | 1.42411 | 1.39140 | 1.41304 | 0.01874 |
| Overall net J/token | 0.88400 | 0.88206 | 0.86617 | 0.87741 | 0.00978 |
| Eval J/token (cluster) | 1.40682 | 1.41154 | 1.37862 | 1.39900 | 0.01780 |
| Prediction J/token (cluster) | 2.15702 | 2.16872 | 2.14830 | 2.15801 | 0.01025 |
| Avg eval tokens/sec | 21.42 | 21.31 | 21.96 | 21.56 | 0.35 |
| Avg prediction tokens/sec | 12.46 | 12.43 | 12.51 | 12.46 | 0.04 |
| Total tokens/sec (wall-clock) | 21.46 | 21.36 | 22.04 | 21.62 | 0.37 |
