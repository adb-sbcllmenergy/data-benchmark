# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_1.7b/idle_config2.csv` — 5.91215 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1005.1 | 1035.1 | 1032.3 | 1024.2 | 16.6 |
| Total tokens | 18954 | 19228 | 19291 | 19158 | 179 |
| Cluster energy (J) | 14946.22 | 15202.30 | 15289.92 | 15146.14 | 178.60 |
| Idle energy (J) | 5942.25 | 6119.71 | 6103.33 | 6055.10 | 98.07 |
| Net (idle-subtracted) energy (J) | 9003.97 | 9082.59 | 9186.59 | 9091.05 | 91.61 |
| Overall J/token (cluster) | 0.78855 | 0.79063 | 0.79259 | 0.79059 | 0.00202 |
| Overall net J/token | 0.47504 | 0.47236 | 0.47621 | 0.47454 | 0.00197 |
| Eval J/token (cluster) | 0.36305 | 0.36275 | 0.36179 | 0.36253 | 0.00066 |
| Prediction J/token (cluster) | 0.86442 | 0.86564 | 0.86783 | 0.86596 | 0.00173 |
| Avg eval tokens/sec | 41.02 | 41.14 | 40.97 | 41.04 | 0.09 |
| Avg prediction tokens/sec | 17.13 | 16.91 | 17.01 | 17.02 | 0.11 |
| Total tokens/sec (wall-clock) | 18.86 | 18.58 | 18.69 | 18.71 | 0.14 |
