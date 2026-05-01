# Code Structure

One script per analysis module, numbered for order.

```
04_code/
├── 01_sample_construction.*
├── 02_descriptives.*
├── 03_baseline_regressions.*
├── 04_event_study.*
├── 05_robustness.*
├── 06_heterogeneity.*
└── 07_tables_and_figures.*
```

**Naming convention:** `module_number_description_vN`, e.g. `03_baseline_v2.do`

**Versioning rule:** Save a new version before making changes; never delete old versions. Log the script version for every key result in [[result_log]].
