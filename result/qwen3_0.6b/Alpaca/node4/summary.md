# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_0.6b/idle_config4.csv` — 11.79037 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 364.5 | 337.1 | 351.9 | 351.2 | 13.7 |
| Total tokens | 16744 | 17349 | 17990 | 17361 | 623 |
| Cluster energy (J) | 8656.90 | 8483.92 | 8862.49 | 8667.77 | 189.52 |
| Idle energy (J) | 4297.95 | 3974.40 | 4148.47 | 4140.27 | 161.93 |
| Net (idle-subtracted) energy (J) | 4358.96 | 4509.53 | 4714.02 | 4527.50 | 178.21 |
| Overall J/token (cluster) | 0.51702 | 0.48902 | 0.49263 | 0.49955 | 0.01523 |
| Overall net J/token | 0.26033 | 0.25993 | 0.26204 | 0.26077 | 0.00112 |
| Eval J/token (cluster) | 0.49231 | 0.29774 | 0.30746 | 0.36583 | 0.10964 |
| Prediction J/token (cluster) | 0.52212 | 0.52690 | 0.52775 | 0.52559 | 0.00304 |
| Avg eval tokens/sec | 81.96 | 83.75 | 83.67 | 83.13 | 1.01 |
| Avg prediction tokens/sec | 47.16 | 47.20 | 46.76 | 47.04 | 0.24 |
| Total tokens/sec (wall-clock) | 45.93 | 51.47 | 51.13 | 49.51 | 3.10 |
