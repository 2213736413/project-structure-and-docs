---
name: workspace-docs
description: Design or optimize project directory structures from conversation context and repository evidence. Create, edit, audit, or migrate project documentation with consistent conventions and working references. Use for project layout proposals, workspace filing, reference standards, and deployment runbooks.
---

# 项目目录与文档管理

## 选择工作流程

- **设计或优化项目目录**：用当前对话和仓库建立项目简报，按 [项目目录设计](references/project-structure.md) 生成目录树和变更方案。需要交付方案文件时用 [目录方案模板](templates/project-structure-plan.md)。
- **生成或编辑文档**：先读 [文档规范](references/document-conventions.md)，检查同类文档和主入口，按读者和用途选模板。编辑范围以用户要求为准。
- **保存或更新文件**：先读目标目录适用的规则，例如 `AGENTS.md`，再查同主题的主文档与附件。根据下表选位置和动作。
- **移动、合并或审计已有文档**：读 [归档与迁移](references/filing-and-migration.md)。涉及多文件迁移时使用 [迁移清单](templates/migration-plan.md) 追踪文件与引用。审计任务只报告发现，整理任务按授权范围处理。
- **写参考规范、运维手册或 AI 实验记录**：选用 [参考规范](templates/reference-standard.md)、[发布与回滚手册](templates/deployment-runbook.md) 或 [AI 实验记录](templates/ai-experiment.md)。需要判断字段如何填写时，读 [写作指南](references/document-patterns.md) 的对应小节。普通问答按对话回复，用户要求保存时再落盘。

模板作为起稿材料。已有仓库模板时沿用其结构。将方括号中的说明替换为已知事实或待确认项，删除确实不适用的小节。运维手册缺少回滚或验证信息时，标出缺口及确认方法。

## 选位置与动作

以用户指定位置和适用的仓库规则为准。独立项目的正式文档由该项目维护时，工作区笔记链接到它。

| 情况 | 处理 |
| --- | --- |
| 内容依赖特定服务、环境、模型版本或团队决策 | 放进对应项目目录。正文、脚本、附件、样例和导出件在同一项目或主题下归组。 |
| 内容可跨项目复用 | 放在通用话题下。项目文档链接通用规则，并记录项目自己的参数、例外和验证结果。 |
| 已有面向同一读者、解决同一问题的主文档 | 更新主文档。来源或结论冲突时先记录差异和证据。 |
| 已有同主题文件，但用途或有效范围不同 | 按用途保留并互链。例如，参考规范和采用它的项目决策各有自己的文件。 |
| 没有合理位置 | 优先在相近分类下建立子目录。只有独立且会持续产生内容时才按工作区授权新增一级分类，同步更新现有规则及索引。归属未定的材料放入已有收集区，并记录待确认项。 |

初始化空白工作区时，可从收集箱、日常、开发、知识与参考、归档开始。项目和话题目录随产物建立。

## 交付检查

检查产物能否从已有入口找到、关联文件是否可打开，以及新增分类是否写进规则。交付时报告主文件路径、新增分类、未确认的文档结论和实际做过的验证。
