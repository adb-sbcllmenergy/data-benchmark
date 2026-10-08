# Run summary — 3 repeats

_Idle baseline: `/home/orangepi/benchmark/result-cluster-run/qwen3_4b/idle_config1.csv` — 2.93065 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 4116.4 | 4140.3 | 3974.8 | 4077.2 | 89.4 |
| Total tokens | 19992 | 20118 | 19667 | 19926 | 233 |
| Cluster energy (J) | 34210.69 | 34416.28 | 33126.60 | 33917.86 | 692.92 |
| Idle energy (J) | 12063.75 | 12133.67 | 11648.74 | 11948.72 | 262.13 |
| Net (idle-subtracted) energy (J) | 22146.94 | 22282.62 | 21477.86 | 21969.14 | 430.83 |
| Overall J/token (cluster) | 1.71122 | 1.71072 | 1.68437 | 1.70210 | 0.01536 |
| Overall net J/token | 1.10779 | 1.10760 | 1.09208 | 1.10249 | 0.00902 |
| Eval J/token (cluster) | 0.72151 | 0.72331 | 0.72068 | 0.72183 | 0.00135 |
| Prediction J/token (cluster) | 1.87698 | 1.87489 | 1.84890 | 1.86692 | 0.01564 |
| Avg eval tokens/sec | 12.16 | 12.14 | 12.17 | 12.16 | 0.02 |
| Avg prediction tokens/sec | 4.44 | 4.45 | 4.53 | 4.47 | 0.05 |
| Total tokens/sec (wall-clock) | 4.86 | 4.86 | 4.95 | 4.89 | 0.05 |
