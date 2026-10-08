# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_8b/idle_config4.csv` — 11.64519 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 2765.3 | 2705.0 | 2584.4 | 2684.9 | 92.1 |
| Total tokens | 18462 | 18459 | 18758 | 18560 | 172 |
| Cluster energy (J) | 73787.35 | 72699.75 | 71111.22 | 72532.77 | 1345.85 |
| Idle energy (J) | 32202.70 | 31499.94 | 30096.21 | 31266.28 | 1072.51 |
| Net (idle-subtracted) energy (J) | 41584.65 | 41199.81 | 41015.01 | 41266.49 | 290.61 |
| Overall J/token (cluster) | 3.99671 | 3.93844 | 3.79098 | 3.90871 | 0.10604 |
| Overall net J/token | 2.25245 | 2.23196 | 2.18653 | 2.22365 | 0.03373 |
| Eval J/token (cluster) | 1.66259 | 1.64864 | 1.66063 | 1.65729 | 0.00755 |
| Prediction J/token (cluster) | 4.42600 | 4.35966 | 4.17549 | 4.32038 | 0.12979 |
| Avg eval tokens/sec | 17.68 | 17.81 | 17.92 | 17.80 | 0.12 |
| Avg prediction tokens/sec | 5.98 | 6.11 | 6.54 | 6.21 | 0.29 |
| Total tokens/sec (wall-clock) | 6.68 | 6.82 | 7.26 | 6.92 | 0.30 |
