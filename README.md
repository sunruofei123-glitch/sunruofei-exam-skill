# sunruofei-skill

这是一个个人 Codex skills 仓库，用于沉淀可复用的学习、工作总结和项目交付类工作流。

仓库中的每个子目录都是一个独立 skill，可以复制到 Codex 的 skills 目录中使用，也可以作为个人技能库持续维护。

## 技能列表

### `exam-cram-coach`

考前冲刺教练，支持中文和英文场景。

适用于考试前最后一个月、最后一周或最后一天的复习规划、主动回忆训练、错点追踪、资料出题、公式复盘、案例分析和论文提纲练习。

位置：`skills/exam-cram-coach`

### `weekly-work-summary`

周报精简助手，用于把原始工作记录整理成可直接放进周报的精简版本。

适用于项目交付、系统对接、生产环境测试、验收准备、交付依据核对、关键干系人协调、问题风险梳理和下周计划整理。默认采用 SCQA 或 START 思路组织内容，输出包含整体情况、本周完成、主要问题、下周计划、后续待办和系统对接状态等部分。

位置：`skills/weekly-work-summary`

## 仓库结构

```text
skills/
  exam-cram-coach/
    SKILL.md
    SKILL.zh.md
    SKILL.en.md
    README.md
    agents/
    references/
  weekly-work-summary/
    SKILL.md
    agents/
    references/
      weekly-summary-template.md
```

## 使用方式

将需要的 skill 目录复制到 Codex 的 skills 目录，或在支持技能仓库的环境中直接引用本仓库。

示例：

```text
使用 exam-cram-coach。我距离考试还有 5 天，希望先做主动回忆训练。
```

```text
使用 weekly-work-summary，把这些原始周报内容整理成可直接放进周报的完整精简版。
```

## 维护说明

- 每个 skill 的核心说明放在 `SKILL.md`。
- `agents/openai.yaml` 用于展示名称、简短说明和默认提示词。
- 较长的模板、示例或参考资料放在 `references/` 中。
- 仓库根目录 README 只说明整体用途；单个 skill 的详细说明放在对应目录内。
