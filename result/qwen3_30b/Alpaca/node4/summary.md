# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_30b/idle_config4.csv` — 11.57850 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 1208.1 | 1248.8 | 1207.6 | 1221.5 | 23.7 |
| Total tokens | 16196 | 16648 | 16311 | 16385 | 235 |
| Cluster energy (J) | 33951.94 | 35129.99 | 34138.77 | 34406.90 | 633.14 |
| Idle energy (J) | 13987.72 | 14459.19 | 13981.88 | 14142.93 | 273.90 |
| Net (idle-subtracted) energy (J) | 19964.22 | 20670.80 | 20156.89 | 20263.97 | 365.25 |
| Overall J/token (cluster) | 2.09632 | 2.11016 | 2.09299 | 2.09982 | 0.00911 |
| Overall net J/token | 1.23266 | 1.24164 | 1.23578 | 1.23670 | 0.00456 |
| Eval J/token (cluster) | 1.47346 | 1.48017 | 1.45205 | 1.46856 | 0.01469 |
| Prediction J/token (cluster) | 2.23035 | 2.24128 | 2.22973 | 2.23379 | 0.00650 |
| Avg eval tokens/sec | 19.85 | 19.81 | 20.43 | 20.03 | 0.34 |
| Avg prediction tokens/sec | 12.44 | 12.40 | 12.51 | 12.45 | 0.06 |
| Total tokens/sec (wall-clock) | 13.41 | 13.33 | 13.51 | 13.41 | 0.09 |
