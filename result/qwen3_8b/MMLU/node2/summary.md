# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_8b/idle_config2.csv` — 5.72718 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 2275.3 | 2086.0 | 2269.1 | 2210.1 | 107.5 |
| Total tokens | 18341 | 17562 | 18281 | 18061 | 433 |
| Cluster energy (J) | 36390.64 | 33504.83 | 36349.44 | 35414.97 | 1654.36 |
| Idle energy (J) | 13030.85 | 11946.97 | 12995.70 | 12657.84 | 615.88 |
| Net (idle-subtracted) energy (J) | 23359.79 | 21557.86 | 23353.74 | 22757.13 | 1038.60 |
| Overall J/token (cluster) | 1.98411 | 1.90780 | 1.98837 | 1.96010 | 0.04534 |
| Overall net J/token | 1.27364 | 1.22753 | 1.27749 | 1.25955 | 0.02780 |
| Eval J/token (cluster) | 1.37120 | 1.37300 | 1.37152 | 1.37191 | 0.00096 |
| Prediction J/token (cluster) | 3.61591 | 3.59390 | 3.65055 | 3.62012 | 0.02855 |
| Avg eval tokens/sec | 12.13 | 12.11 | 12.12 | 12.12 | 0.01 |
| Avg prediction tokens/sec | 4.42 | 4.42 | 4.42 | 4.42 | 0.00 |
| Total tokens/sec (wall-clock) | 8.06 | 8.42 | 8.06 | 8.18 | 0.21 |
