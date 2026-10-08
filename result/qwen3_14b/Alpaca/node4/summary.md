# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_14b/idle_config4.csv` — 11.80973 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 5289.7 | 5297.9 | 5423.0 | 5336.9 | 74.7 |
| Total tokens | 19168 | 19344 | 19521 | 19344 | 177 |
| Cluster energy (J) | 139391.02 | 140219.79 | 143410.65 | 141007.15 | 2122.33 |
| Idle energy (J) | 62470.22 | 62566.61 | 64043.65 | 63026.82 | 881.92 |
| Net (idle-subtracted) energy (J) | 76920.80 | 77653.19 | 79367.00 | 77980.33 | 1255.48 |
| Overall J/token (cluster) | 7.27207 | 7.24875 | 7.34648 | 7.28910 | 0.05104 |
| Overall net J/token | 4.01298 | 4.01433 | 4.06572 | 4.03101 | 0.03007 |
| Eval J/token (cluster) | 2.85690 | 2.85320 | 2.86531 | 2.85847 | 0.00621 |
| Prediction J/token (cluster) | 8.04892 | 8.01389 | 8.11823 | 8.06035 | 0.05310 |
| Avg eval tokens/sec | 10.40 | 10.47 | 10.46 | 10.44 | 0.04 |
| Avg prediction tokens/sec | 3.25 | 3.29 | 3.23 | 3.26 | 0.03 |
| Total tokens/sec (wall-clock) | 3.62 | 3.65 | 3.60 | 3.62 | 0.03 |
