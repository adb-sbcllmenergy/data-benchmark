# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_1.7b/idle_config4.csv` — 11.69365 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 783.1 | 770.6 | 777.5 | 777.1 | 6.3 |
| Total tokens | 19250 | 19080 | 19241 | 19190 | 96 |
| Cluster energy (J) | 20376.25 | 20063.45 | 20235.51 | 20225.07 | 156.66 |
| Idle energy (J) | 9157.79 | 9011.08 | 9091.37 | 9086.75 | 73.46 |
| Net (idle-subtracted) energy (J) | 11218.46 | 11052.37 | 11144.14 | 11138.32 | 83.20 |
| Overall J/token (cluster) | 1.05851 | 1.05154 | 1.05169 | 1.05391 | 0.00398 |
| Overall net J/token | 0.58278 | 0.57926 | 0.57919 | 0.58041 | 0.00205 |
| Eval J/token (cluster) | 0.51305 | 0.51866 | 0.51799 | 0.51657 | 0.00306 |
| Prediction J/token (cluster) | 1.15400 | 1.14581 | 1.14517 | 1.14833 | 0.00492 |
| Avg eval tokens/sec | 52.21 | 51.50 | 51.43 | 51.71 | 0.43 |
| Avg prediction tokens/sec | 22.39 | 22.47 | 22.44 | 22.43 | 0.04 |
| Total tokens/sec (wall-clock) | 24.58 | 24.76 | 24.75 | 24.70 | 0.10 |
