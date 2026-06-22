---
name: submission-helper
slug: submission-helper
version: 1.0.0
displayName: 投稿辅助工具
summary: 学术投稿全环节实战工具箱——Cover Letter撰写、Rebuttal回复框架、投稿前检查清单、审稿意见分类应对。
description: |
  ## 中文描述
  
  投稿辅助工具（Submission Helper）是一个学术论文投稿全环节实战工具箱。本技能聚焦投稿流程中期刊推荐工具无法覆盖的核心环节：Cover Letter撰写、Rebuttal（审稿意见回复）框架、投稿前材料检查清单、审稿意见分类应对策略、投稿周期管理与催稿/撤稿邮件模板。
  
  ### 与已有技能的关系
  
  本技能与 SkillHub 上的 `journal-submission`、`journal-matchmaker`、`journal-selector`、`journal-recommender` 等期刊查找/推荐类技能形成**互补**关系：
  - **它们帮您选刊**（哪个期刊适合您的论文）
  - **本技能帮您投刊**（怎么把选好的论文投出去并应对审稿流程）
  
  建议组合使用：先用期刊推荐工具定位目标期刊，再用本技能完成投稿全流程。
  
  ### 触发词
  
  投稿、Cover Letter、submission、审稿回复、rebuttal、投稿检查清单、reviewer response、催稿、投稿材料、审稿意见回复、cover letter template、rebuttal letter、appeal letter、撤稿、投稿状态、manuscript submission、response to reviewers、投稿前检查
  
  ### 核心能力
  
  1. **Cover Letter 模板** — 4类学科（工程/技术、管理/社科、医学/生科、计算机科学）的完整 Cover Letter 模板，含中英双语版本和占位符系统
  2. **Rebuttal 框架** — 6大审稿意见类型的逐点回复框架，含实际话术模板和回复语气指南
  3. **投稿检查清单** — 7大类45项投稿前自检清单，含中文学报特有要求
  4. **审稿意见解析** — 审稿信阅读方法、意见分类优先级、分歧意见处理、申诉信模板
  5. **投稿周期管理** — 状态解读、等待时间预期、催稿邮件、撤稿邮件模板

  ## English Description

  Submission Helper is a comprehensive academic manuscript submission toolkit. It covers the critical parts of the submission process that journal-finding tools don't address: Cover Letter writing, Rebuttal/Response to Reviewers frameworks, pre-submission checklists, reviewer comment classification strategies, and timeline management with inquiry/withdrawal email templates.

  ### Relationship with Existing Skills

  This skill complements journal-finding tools (journal-submission, journal-matchmaker, journal-selector, journal-recommender, etc.):
  - **They help you find** the right journal
  - **This skill helps you submit** to the journal and navigate peer review

  ### Triggers

  submission, Cover Letter, rebuttal, reviewer response, submission checklist, appeal letter, manuscript submission, response to reviewers, pre-submission check, inquiry email, withdrawal email, submission status

  ### Core Capabilities

  1. **Cover Letter Templates** — 4 discipline-specific templates (Engineering/Tech, Management/Social Sciences, Medicine/Life Sciences, Computer Science) with bilingual versions
  2. **Rebuttal Framework** — Point-by-point response frameworks for 6 reviewer comment types with actual phrasing templates
  3. **Submission Checklist** — 45-item pre-submission checklist across 7 categories
  4. **Reviewer Response Analysis** — Comment classification, priority sorting, conflicting opinions handling, appeal letters
  5. **Timeline Management** — Status interpretation, expected wait times, inquiry and withdrawal templates
---

# 投稿辅助工具 (Submission Helper)

## 概述

本技能为学术论文投稿提供全环节实战支持。当您完成论文并选定目标期刊后，本技能指导您完成从投稿准备到审稿回复的每一步。

## 与已有技能的协作

| 阶段 | 使用技能 | 做什么 |
|------|---------|--------|
| 选刊 | journal-recommender / journal-matchmaker | 根据论文主题和摘要推荐合适期刊 |
| 期刊调研 | journal-submission | 调查目标期刊的审稿周期和投稿要求 |
| **投稿准备** | **submission-helper（本技能）** | Cover Letter撰写、材料检查清单 |
| **审稿应对** | **submission-helper（本技能）** | 审稿意见分类、Rebuttal回复、申诉 |
| 截止日跟踪 | resubmission-deadline-tracker | 跟踪修改稿提交截止日期 |

## 文件索引

| 文件 | 内容 | 何时使用 |
|------|------|---------|
| [references/cover-letter-templates.md](references/cover-letter-templates.md) | 4类学科 Cover Letter 模板（中英双语） | 准备投稿时 |
| [references/rebuttal-framework.md](references/rebuttal-framework.md) | 6大审稿意见类型回复框架 | 收到审稿意见后 |
| [references/submission-checklist.md](references/submission-checklist.md) | 7大类45项投稿前检查清单 | 最终投稿前逐条核对 |
| [references/reviewer-response.md](references/reviewer-response.md) | 审稿意见分类解析与应对策略 | 深入理解审稿意见时 |
| [references/timeline-management.md](references/timeline-management.md) | 投稿周期管理与催稿/撤稿模板 | 等待审稿结果或超时跟进时 |

## 使用流程

```
选定期刊 → [cover-letter-templates.md] 写Cover Letter
         → [submission-checklist.md] 逐条核对投稿材料
         → 提交投稿
         → [timeline-management.md] 跟踪投稿状态
         → 收到审稿意见
         → [reviewer-response.md] 解析审稿意见
         → [rebuttal-framework.md] 撰写逐点回复
         → 提交修改稿
```

## 快速入口

- **我要投稿，需要写Cover Letter** → 打开 `references/cover-letter-templates.md`，选择对应学科模板
- **收到审稿意见，不知道怎么回复** → 打开 `references/rebuttal-framework.md`，按审稿意见类型找到对应框架
- **准备提交，怕遗漏材料** → 打开 `references/submission-checklist.md`，逐条核对
- **投稿3个月没消息，想催稿** → 打开 `references/timeline-management.md`，使用催稿邮件模板
- **被拒稿了，想申诉** → 打开 `references/reviewer-response.md`，查看申诉信模板

## 重要提示

- 所有模板和示例中的期刊名、论文标题、作者名、审稿意见均为**虚构**，请替换为您的实际信息
- 各学科的投稿规范可能不同，模板提供了基础框架，建议根据目标期刊的具体要求调整
- 如遇到模板未覆盖的特殊情况（如特刊投稿、邀请投稿等），请告知具体需求
