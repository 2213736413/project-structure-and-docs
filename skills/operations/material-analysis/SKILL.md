---
name: material-analysis
description: Analyze inventory, material master, consumption and open supply to identify shortages and material exceptions.
---

# 物料分析

先读取工作区规则及业务口径。输出与配套材料按项目或话题归组。

执行分析或整理时读 [工作流与合成案例](references/workflow.md)，按其中的规则记录证据、异常和交付校验。

- 确定库存快照、仓库或工厂和计划窗口，核对物料编码、版本、计量单位与换算依据。
- 分别保留账面库存、可用库存、冻结、预留和在途。核对预留或需求是否已扣除，避免重复扣减。按交期与状态判断在途是否可纳入窗口。
- 按物料、地点和时间桶对齐供需，展示净量各分项。只有汇总数据时标注时间粒度限制。缺交期、无法换算和重复编码单独列出。
- 缺料、呆滞、临期等标签使用已确认的判定条件，结果回链到原始行或单据。

交付时沿用团队现有模板，或使用[交付模板](templates/deliverable.md)。
