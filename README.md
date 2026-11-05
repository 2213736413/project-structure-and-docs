# Project Structure and Docs

从项目上下文设计或优化目录，按统一规则起草、编辑和迁移文档。仓库也提供面向报表、物料、财务和研发的独立技能。

| 类别 | Skill | 典型交付 |
| --- | --- | --- |
| 跨部门通用 | [workspace-docs](workspace-docs/SKILL.md) | 项目目录设计、文档规范化、知识归档和迁移 |
| 报表与指标 | [business-reporting](skills/reporting/business-reporting/SKILL.md) | KPI 报表、指标口径、来源核对与刷新说明 |
| 物料与供应链 | [material-analysis](skills/operations/material-analysis/SKILL.md) | 库存供需、缺料与异常清单 |
| 财务 | [finance-reconciliation](skills/finance/finance-reconciliation/SKILL.md) | 单据匹配、对账底稿和差异清单 |
| 研发交付 | [engineering-issues](skills/engineering/engineering-issues/SKILL.md) | 缺陷复现、需求拆解、验收与项目交接 |

## 选择与使用

- `$workspace-docs 根据本次对话里的项目背景，结合现有仓库，给我一份目录优化方案和迁移清单。`
- `$workspace-docs 按项目约定修改部署文档，核对目录入口、命令参数和回滚条件。`
- 以交付物为准。库存月报如果主要是统计指标，选 `business-reporting`。如果要算缺料，先选 `material-analysis` 计算供需，再按需汇总成报表。
- 用 Codex 内置的 `$skill-installer` 安装所需技能。可直接发送下方示例。试用版来自 `dev` 分支。
- 手动安装时，复制所需的完整技能目录，保留 `SKILL.md`、模板和参考资料。
- 文件归放遵循目标工作区规则。涉及指标口径、库存策略、财务容差或审批时，以公司确认的规则为准，缺失项标注待核实。

> `$skill-installer` 请从 GitHub 仓库 `2213736413/project-structure-and-docs` 的 `dev` 分支安装 `workspace-docs` 和 `skills/operations/material-analysis`，并报告安装结果。

## 扩展类别

专业技能放入 `skills/<领域>/<技能名>/`。跨部门的文档管理沿用已有的 `workspace-docs/` 入口。新增技能时同步更新上表，为技能写清触发条件、输入、交付物、关键核对和模板。评审时用一个典型场景和一个边界场景核对工作流，例如一对多订单明细、缺交期物料、拆分付款或未复现缺陷。

公开仓库只收录通用流程、空白模板及合成示例。公司业务数据、内部路径、账号凭据和审批细则留在获授权的内部工作区。
