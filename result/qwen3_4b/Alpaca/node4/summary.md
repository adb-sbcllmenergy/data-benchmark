# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_4b/idle_config4.csv` — 11.54410 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1706.5 | 1756.2 | 1763.6 | 1742.1 | 31.1 |
| Total tokens | 19696 | 19696 | 19844 | 19745 | 85 |
| Cluster energy (J) | 44373.47 | 45187.48 | 45297.41 | 44952.79 | 504.70 |
| Idle energy (J) | 19699.47 | 20274.16 | 20358.67 | 20110.77 | 358.69 |
| Net (idle-subtracted) energy (J) | 24674.01 | 24913.33 | 24938.73 | 24842.02 | 146.06 |
| Overall J/token (cluster) | 2.25292 | 2.29425 | 2.28268 | 2.27661 | 0.02132 |
| Overall net J/token | 1.25274 | 1.26489 | 1.25674 | 1.25812 | 0.00619 |
| Eval J/token (cluster) | 0.97787 | 0.96126 | 0.98703 | 0.97538 | 0.01306 |
| Prediction J/token (cluster) | 2.47022 | 2.52143 | 2.50157 | 2.49774 | 0.02582 |
| Avg eval tokens/sec | 28.49 | 29.05 | 28.09 | 28.54 | 0.48 |
| Avg prediction tokens/sec | 10.56 | 10.16 | 10.26 | 10.33 | 0.21 |
| Total tokens/sec (wall-clock) | 11.54 | 11.21 | 11.25 | 11.34 | 0.18 |
