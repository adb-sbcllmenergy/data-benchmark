# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_4b/idle_config4.csv` — 11.54410 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 686.4 | 661.8 | 660.9 | 669.7 | 14.5 |
| Total tokens | 16090 | 16070 | 15735 | 15965 | 199 |
| Cluster energy (J) | 19134.86 | 18931.69 | 18566.77 | 18877.77 | 287.85 |
| Idle energy (J) | 7924.17 | 7639.71 | 7629.29 | 7731.06 | 167.32 |
| Net (idle-subtracted) energy (J) | 11210.69 | 11291.98 | 10937.48 | 11146.71 | 185.71 |
| Overall J/token (cluster) | 1.18924 | 1.17808 | 1.17997 | 1.18243 | 0.00597 |
| Overall net J/token | 0.69675 | 0.70267 | 0.69511 | 0.69818 | 0.00398 |
| Eval J/token (cluster) | 0.92807 | 0.93534 | 0.94222 | 0.93521 | 0.00707 |
| Prediction J/token (cluster) | 2.45224 | 2.36053 | 2.49967 | 2.43748 | 0.07073 |
| Avg eval tokens/sec | 30.97 | 31.12 | 30.61 | 30.90 | 0.26 |
| Avg prediction tokens/sec | 10.89 | 11.39 | 10.36 | 10.88 | 0.52 |
| Total tokens/sec (wall-clock) | 23.44 | 24.28 | 23.81 | 23.84 | 0.42 |
