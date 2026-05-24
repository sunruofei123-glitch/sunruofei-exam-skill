# sunruofei-skill

Personal Codex skills for focused learning, exam preparation, and reusable study workflows.

个人 Codex 技能仓库，用于沉淀高强度学习、考试冲刺和可复用的复习工作流。

## Overview / 项目简介

This repository currently contains `exam-cram-coach`, a bilingual Chinese/English Codex skill for learners preparing during the final month, final week, or final day before an exam.

本仓库当前包含 `exam-cram-coach` 技能。这是一个中英双语的 Codex 学习教练技能，适合考试前最后一个月、最后一周或最后一天进行高强度冲刺复习。

Instead of only summarizing materials, the skill focuses on active recall: it asks the learner to answer first, reviews the answer, records weak points, and brings those weak points back in later review sessions.

它不是简单总结资料，而是强调主动回忆：先让学习者作答，再进行点评、记录薄弱点，并在后续复习中反复拉回这些薄弱点。

## Skills / 技能列表

### `exam-cram-coach`

`exam-cram-coach` is designed for learners who need a compact, pressure-aware review process rather than broad textbook-style explanation.

`exam-cram-coach` 面向时间紧、任务重的学习者，重点不是展开式讲教材，而是帮助学习者在有限时间内完成计划、默写、做题、纠错和复盘。

It supports:

- final-month, final-week, and final-day study planning
- source-material-based drills from uploaded PDFs, notes, outlines, or mock exams
- active-recall questioning instead of passive summaries
- weak-point tracking across sessions
- formula, case-analysis, and essay-outline practice
- daily progress reminders and plan adjustment
- bilingual Chinese/English coaching

它支持：

- 最后一个月、最后一周、最后一天冲刺规划
- 基于上传 PDF、笔记、考试大纲、模拟题等资料出题
- 以主动回忆为核心，而不是只给总结
- 跨会话记录和复盘薄弱点
- 公式、案例分析、论文大纲等专项练习
- 每日学习进度提醒和计划动态调整
- 中文和英文双语辅导

## Example Use Case / 示例场景

The included reference example is based on the Information Systems Project Manager exam. It covers process inputs and outputs, tools and techniques, performance domains, earned value, scheduling, operations research, case analysis, and essay practice.

仓库中的参考示例基于“信息系统项目管理师”考前冲刺场景，覆盖十大管理过程输入输出、工具技术、八大绩效域、挣值管理、进度计算、运筹学、案例分析和论文练习。

## Repository Structure / 仓库结构

```text
skills/
  exam-cram-coach/
    SKILL.md
    SKILL.zh.md
    SKILL.en.md
    agents/
      openai.yaml
    references/
      information-systems-project-manager-example.md
```

File descriptions:

- `SKILL.md`: thin entrypoint that routes to the Chinese or English guide
- `SKILL.zh.md`: Chinese skill instructions
- `SKILL.en.md`: English skill instructions
- `agents/openai.yaml`: skill metadata
- `references/information-systems-project-manager-example.md`: exam-cram reference example

文件说明：

- `SKILL.md`：技能入口文件，根据语言引导读取中文或英文说明
- `SKILL.zh.md`：中文技能说明
- `SKILL.en.md`：英文技能说明
- `agents/openai.yaml`：技能元数据
- `references/information-systems-project-manager-example.md`：考试冲刺参考示例

## How To Use / 使用方式

Install or copy `skills/exam-cram-coach` into your Codex skills directory, then ask Codex to use `exam-cram-coach`.

将 `skills/exam-cram-coach` 安装或复制到你的 Codex skills 目录后，在对话中要求 Codex 使用 `exam-cram-coach` 即可。

For best results, provide:

- exam name and exam date
- available study time per day
- uploaded source materials, such as PDFs, notes, mock exams, or official outlines
- weak areas and recent wrong answers
- preferred coaching language

为了获得更好的效果，建议提供：

- 考试名称和考试日期
- 每天可用学习时间
- 上传的资料，例如 PDF、笔记、模拟题、官方大纲
- 当前薄弱点和最近错题
- 希望使用的辅导语言

English prompt example:

```text
Use exam-cram-coach. I have 5 days left before the exam, 2 hours per day.
Use my uploaded PDFs as the main source. Quiz me first, then track weak points
and review them tomorrow.
```

中文提示词示例：

```text
使用 exam-cram-coach。我距离考试还有 5 天，每天最多学 2 小时。
请以我上传的资料为准，先让我默写和做题，再记录薄弱点，
明天和最后一天继续让我复盘。
```

## Coaching Principles / 辅导原则

The skill follows four principles:

- Ask the learner to answer first, then review and optimize.
- Preserve official exam terminology.
- Track weak points and force repeated recall.
- Adjust the plan when time, progress, or confidence changes.

该技能遵循四个原则：

- 先让学习者作答，再点评和优化
- 保留考试官方术语，不随意改写概念
- 记录薄弱点，并通过重复回忆强化掌握
- 根据时间、进度和信心变化动态调整计划

## Current Status / 当前状态

Initial version is available with:

- Chinese guide: `SKILL.zh.md`
- English guide: `SKILL.en.md`
- thin entrypoint: `SKILL.md`
- reference example: Information Systems Project Manager final-week cram workflow

当前已包含：

- 中文说明：`SKILL.zh.md`
- 英文说明：`SKILL.en.md`
- 技能入口：`SKILL.md`
- 参考示例：信息系统项目管理师最后一周冲刺工作流
