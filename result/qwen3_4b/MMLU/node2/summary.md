# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_4b/idle_config2.csv` — 5.73955 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1045.7 | 994.2 | 961.1 | 1000.3 | 42.7 |
| Total tokens | 16540 | 16108 | 15856 | 16168 | 346 |
| Cluster energy (J) | 16579.95 | 15764.52 | 15274.52 | 15873.00 | 659.44 |
| Idle energy (J) | 6002.02 | 5706.54 | 5516.12 | 5741.56 | 244.84 |
| Net (idle-subtracted) energy (J) | 10577.92 | 10057.99 | 9758.40 | 10131.44 | 414.67 |
| Overall J/token (cluster) | 1.00242 | 0.97868 | 0.96333 | 0.98147 | 0.01969 |
| Overall net J/token | 0.63954 | 0.62441 | 0.61544 | 0.62646 | 0.01218 |
| Eval J/token (cluster) | 0.77927 | 0.78037 | 0.78042 | 0.78002 | 0.00065 |
| Prediction J/token (cluster) | 1.93015 | 1.93148 | 1.92994 | 1.93052 | 0.00083 |
| Avg eval tokens/sec | 20.99 | 20.94 | 20.98 | 20.97 | 0.02 |
| Avg prediction tokens/sec | 8.13 | 8.11 | 8.13 | 8.12 | 0.01 |
| Total tokens/sec (wall-clock) | 15.82 | 16.20 | 16.50 | 16.17 | 0.34 |
