---
name: finance-reconciliation
description: Match supplied ledger entries to invoices or statements and prepare reconciliation schedules for internal review.
---

# 财务资料整理与对账

先读取工作区规则及业务口径。输出与配套材料按项目或话题归组。

执行分析或整理时读 [工作流与合成案例](references/workflow.md)，按其中的规则记录证据、异常和交付校验。

- 确认主体、期间、币种、正负号、含税口径和容差来源。保留原始账务文件和可追溯的行标识。
- 优先使用双方共有的唯一标识，再核对金额、币种和日期。重复标识保留候选，拆分或合并入账按可验证的分组匹配。
- 分列已匹配、待确认、仅一侧出现和重复记录。按币种核对来源总额、匹配金额和未匹配余额。缺少汇率、容差或差异依据时标记待确认。
- 交付供内部复核的底稿。账务调整与入账交由有权限的人员按公司流程审批。共享版本按权限保留必要字段。

交付时沿用团队现有模板，或使用[交付模板](templates/deliverable.md)。
