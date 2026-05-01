# 代码结构

按分析模块命名，每个模块独立脚本。

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

**命名规则：** `模块编号_描述_v版本号`，例如 `03_baseline_v2.do`

**版本原则：** 修改前另存新版本，旧版本不删。关键结果对应的代码版本记录在 [[result_log]]。
