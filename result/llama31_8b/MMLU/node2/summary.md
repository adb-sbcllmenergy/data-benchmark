# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/llama31_8b/idle_config2.csv` — 5.71939 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1109.3 | 1173.7 | 1173.5 | 1152.2 | 37.1 |
| Total tokens | 13128 | 13423 | 13418 | 13323 | 169 |
| Cluster energy (J) | 18524.02 | 19512.89 | 19510.79 | 19182.57 | 570.32 |
| Idle energy (J) | 6344.72 | 6712.98 | 6711.43 | 6589.71 | 212.16 |
| Net (idle-subtracted) energy (J) | 12179.29 | 12799.92 | 12799.36 | 12592.86 | 358.16 |
| Overall J/token (cluster) | 1.41103 | 1.45369 | 1.45408 | 1.43960 | 0.02474 |
| Overall net J/token | 0.92773 | 0.95358 | 0.95389 | 0.94507 | 0.01501 |
| Eval J/token (cluster) | 1.36360 | 1.36170 | 1.36317 | 1.36282 | 0.00100 |
| Prediction J/token (cluster) | 3.41201 | 3.42315 | 3.41655 | 3.41723 | 0.00560 |
| Avg eval tokens/sec | 12.27 | 12.26 | 12.25 | 12.26 | 0.01 |
| Avg prediction tokens/sec | 4.54 | 4.53 | 4.53 | 4.54 | 0.01 |
| Total tokens/sec (wall-clock) | 11.83 | 11.44 | 11.43 | 11.57 | 0.23 |
