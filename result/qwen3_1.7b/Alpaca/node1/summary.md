# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_1.7b/idle_config1.csv` — 2.91050 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1687.9 | 1678.8 | 1671.5 | 1679.4 | 8.2 |
| Total tokens | 19088 | 19035 | 18909 | 19011 | 92 |
| Cluster energy (J) | 13953.39 | 13904.07 | 13835.81 | 13897.76 | 59.04 |
| Idle energy (J) | 4912.58 | 4886.27 | 4864.76 | 4887.87 | 23.95 |
| Net (idle-subtracted) energy (J) | 9040.82 | 9017.80 | 8971.05 | 9009.89 | 35.55 |
| Overall J/token (cluster) | 0.73100 | 0.73045 | 0.73171 | 0.73105 | 0.00063 |
| Overall net J/token | 0.47364 | 0.47375 | 0.47443 | 0.47394 | 0.00043 |
| Eval J/token (cluster) | 0.30296 | 0.30627 | 0.30452 | 0.30459 | 0.00165 |
| Prediction J/token (cluster) | 0.80669 | 0.80570 | 0.80808 | 0.80682 | 0.00120 |
| Avg eval tokens/sec | 28.31 | 28.36 | 28.32 | 28.33 | 0.03 |
| Avg prediction tokens/sec | 10.27 | 10.30 | 10.27 | 10.28 | 0.02 |
| Total tokens/sec (wall-clock) | 11.31 | 11.34 | 11.31 | 11.32 | 0.02 |
