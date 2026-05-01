# 项目文件夹结构说明

> 复制整个文件夹作为新项目的起点。将所有 `YYYY-MM-DD` 替换为实际日期，填写 `project_overview.md` 中的基本信息。

---

## 文件夹

| 文件夹                  | 用途                      |
| -------------------- | ----------------------- |
| `00_admin/`          | 合同、伦理申请、基金材料            |
| `01_literature/`     | 文献 PDF 和阅读笔记            |
| `02_design/`         | 研究设计文档、pre-registration |
| `03_data/raw/`       | 原始数据，**只读，永远不手改**       |
| `03_data/processed/` | 中间数据，全部由代码生成            |
| `04_code/`           | 分析脚本，按模块编号命名            |
| `05_results/`        | 输出的表格和图                 |
| `06_writing/`        | 论文草稿                    |
| `07_presentations/`  | Slides                  |

## 核心文件

| 文件                         | 用途        | 更新时机            |
| -------------------------- | --------- | --------------- |
| `project_overview.md`      | 项目控制面板    | 每周维护            |
| `decision_log.md`          | 关键决策记录    | 每次做重要决定时        |
| `task_list.md`             | 任务三栏看板    | 每天/每次 meeting 后 |
| `meeting_notes.md`         | 会议纪要      | meeting 结束15分钟内 |
| `source_log.md`            | 数据来源与变量字典 | 数据有变动时          |
| `result_log.md`            | 结果与代码版本绑定 | 每次跑出新关键结果       |
| `presentation_feedback.md` | 汇报反馈      | 每次对外汇报后         |

## 每周维护（30分钟）

- [ ] 更新 `project_overview.md` 的「本周下一步」
- [ ] 把 meeting notes 里的 action items 转入 `task_list.md`
- [ ] 把本周关键决定写进 `decision_log.md`
- [ ] 把新结果登记进 `result_log.md`
- [ ] 清理桌面和下载文件夹的临时文件
- [ ] 归档废弃文件

## 核心规则

1. `raw data` 只读，永远不手改
2. 所有中间数据由代码生成
3. 任何人工修改都要在 `source_log.md` 中记录
4. 所有关键结果写进 `result_log.md`
5. 所有关键决定写进 `decision_log.md`
6. meeting 结束后15分钟内整理纪要
