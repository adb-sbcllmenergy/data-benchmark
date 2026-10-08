# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_0.6b/idle_config2.csv` — 5.95216 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 440.0 | 466.1 | 417.9 | 441.3 | 24.1 |
| Total tokens | 22584 | 22904 | 22052 | 22513 | 430 |
| Cluster energy (J) | 6183.26 | 6551.69 | 5837.62 | 6190.86 | 357.10 |
| Idle energy (J) | 2618.79 | 2774.40 | 2487.27 | 2626.82 | 143.73 |
| Net (idle-subtracted) energy (J) | 3564.47 | 3777.29 | 3350.35 | 3564.04 | 213.47 |
| Overall J/token (cluster) | 0.27379 | 0.28605 | 0.26472 | 0.27485 | 0.01070 |
| Overall net J/token | 0.15783 | 0.16492 | 0.15193 | 0.15823 | 0.00650 |
| Eval J/token (cluster) | 0.18060 | 0.17901 | 0.17895 | 0.17952 | 0.00094 |
| Prediction J/token (cluster) | 0.40810 | 0.43516 | 0.39588 | 0.41305 | 0.02010 |
| Avg eval tokens/sec | 76.82 | 76.59 | 76.76 | 76.72 | 0.12 |
| Avg prediction tokens/sec | 37.98 | 38.02 | 38.00 | 38.00 | 0.02 |
| Total tokens/sec (wall-clock) | 51.33 | 49.14 | 52.77 | 51.08 | 1.83 |
