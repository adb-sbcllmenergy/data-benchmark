# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_1.7b/idle_config1.csv` — 2.91050 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1648.8 | 1875.1 | 1806.3 | 1776.7 | 116.0 |
| Total tokens | 24429 | 26121 | 25688 | 25413 | 879 |
| Cluster energy (J) | 13757.49 | 15560.05 | 15017.59 | 14778.38 | 924.78 |
| Idle energy (J) | 4798.89 | 5457.37 | 5257.11 | 5171.12 | 337.56 |
| Net (idle-subtracted) energy (J) | 8958.61 | 10102.68 | 9760.49 | 9607.26 | 587.23 |
| Overall J/token (cluster) | 0.56316 | 0.59569 | 0.58462 | 0.58116 | 0.01654 |
| Overall net J/token | 0.36672 | 0.38676 | 0.37996 | 0.37782 | 0.01019 |
| Eval J/token (cluster) | 0.31350 | 0.31413 | 0.31383 | 0.31382 | 0.00031 |
| Prediction J/token (cluster) | 0.86315 | 0.88925 | 0.87684 | 0.87641 | 0.01305 |
| Avg eval tokens/sec | 29.32 | 29.30 | 29.32 | 29.31 | 0.01 |
| Avg prediction tokens/sec | 9.91 | 9.84 | 9.87 | 9.87 | 0.04 |
| Total tokens/sec (wall-clock) | 14.82 | 13.93 | 14.22 | 14.32 | 0.45 |
