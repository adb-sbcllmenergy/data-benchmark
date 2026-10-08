# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/llama32_1b/idle_config1.csv` — 2.92675 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 581.4 | 563.6 | 589.3 | 578.1 | 13.2 |
| Total tokens | 16524 | 16272 | 16617 | 16471 | 179 |
| Cluster energy (J) | 4959.85 | 4816.25 | 5021.63 | 4932.58 | 105.37 |
| Idle energy (J) | 1701.73 | 1649.48 | 1724.82 | 1692.01 | 38.60 |
| Net (idle-subtracted) energy (J) | 3258.12 | 3166.77 | 3296.81 | 3240.57 | 66.77 |
| Overall J/token (cluster) | 0.30016 | 0.29598 | 0.30220 | 0.29945 | 0.00317 |
| Overall net J/token | 0.19718 | 0.19461 | 0.19840 | 0.19673 | 0.00193 |
| Eval J/token (cluster) | 0.21732 | 0.21682 | 0.21739 | 0.21718 | 0.00032 |
| Prediction J/token (cluster) | 0.58726 | 0.59043 | 0.58892 | 0.58887 | 0.00158 |
| Avg eval tokens/sec | 40.70 | 40.71 | 40.71 | 40.71 | 0.00 |
| Avg prediction tokens/sec | 13.82 | 13.82 | 13.81 | 13.82 | 0.01 |
| Total tokens/sec (wall-clock) | 28.42 | 28.87 | 28.20 | 28.50 | 0.34 |
