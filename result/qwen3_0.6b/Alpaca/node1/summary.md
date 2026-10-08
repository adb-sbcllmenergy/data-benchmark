# Run summary — 3 repeats

_Idle baseline: `result-cluster-run/qwen3_0.6b/idle_config1.csv` — 2.91817 W cluster-wide._

| Metric | run1 | run2 | run3 | Mean | Stdev |
|---|---:|---:|---:|---:|---:|
| Items OK | 100 | 100 | 100 | 100 | 0 |
| Items total | 100 | 100 | 100 | 100 | 0 |
| Wall time (s) | 828.0 | 597.4 | 562.2 | 662.5 | 144.4 |
| Total tokens | 17681 | 17262 | 16630 | 17191 | 529 |
| Cluster energy (J) | 5021.00 | 4909.98 | 4652.75 | 4861.24 | 188.90 |
| Idle energy (J) | 2416.12 | 1743.24 | 1640.61 | 1933.32 | 421.25 |
| Net (idle-subtracted) energy (J) | 2604.88 | 3166.75 | 3012.15 | 2927.92 | 290.25 |
| Overall J/token (cluster) | 0.28398 | 0.28444 | 0.27978 | 0.28273 | 0.00257 |
| Overall net J/token | 0.14733 | 0.18345 | 0.18113 | 0.17064 | 0.02022 |
| Eval J/token (cluster) | 0.11088 | 0.11084 | 0.11238 | 0.11137 | 0.00088 |
| Prediction J/token (cluster) | 0.31749 | 0.31903 | 0.31467 | 0.31706 | 0.00221 |
| Avg eval tokens/sec | 77.89 | 77.37 | 77.75 | 77.67 | 0.27 |
| Avg prediction tokens/sec | 26.18 | 26.14 | 26.67 | 26.33 | 0.29 |
| Total tokens/sec (wall-clock) | 21.36 | 28.90 | 29.58 | 26.61 | 4.56 |
