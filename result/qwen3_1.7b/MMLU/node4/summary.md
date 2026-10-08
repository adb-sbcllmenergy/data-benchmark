# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_1.7b/idle_config4.csv` — 11.69365 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 984.0 | 768.9 | 725.8 | 826.3 | 138.3 |
| Total tokens | 28376 | 24949 | 24088 | 25804 | 2268 |
| Cluster energy (J) | 26053.04 | 20281.83 | 19167.87 | 21834.24 | 3695.79 |
| Idle energy (J) | 11506.80 | 8991.66 | 8487.42 | 9661.96 | 1617.45 |
| Net (idle-subtracted) energy (J) | 14546.24 | 11290.17 | 10680.45 | 12172.29 | 2078.38 |
| Overall J/token (cluster) | 0.91814 | 0.81293 | 0.79574 | 0.84227 | 0.06626 |
| Overall net J/token | 0.51262 | 0.45253 | 0.44339 | 0.46952 | 0.03761 |
| Eval J/token (cluster) | 0.48931 | 0.49279 | 0.49092 | 0.49101 | 0.00174 |
| Prediction J/token (cluster) | 1.29821 | 1.18039 | 1.17363 | 1.21741 | 0.07006 |
| Avg eval tokens/sec | 54.37 | 53.92 | 54.40 | 54.23 | 0.27 |
| Avg prediction tokens/sec | 22.18 | 22.21 | 22.28 | 22.22 | 0.05 |
| Total tokens/sec (wall-clock) | 28.84 | 32.45 | 33.19 | 31.49 | 2.33 |
