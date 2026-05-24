# sunruofei-skill

Personal Codex skills for focused learning and exam preparation.

This repository currently contains `exam-cram-coach`, a bilingual Chinese/English skill for helping learners prepare during the final month, final week, or final day before an exam. It turns study materials, weak-point records, practice answers, and time constraints into an active-recall cram plan.

## Skills

### exam-cram-coach

`exam-cram-coach` is designed for learners who need a compact, high-pressure review workflow rather than a broad textbook-style explanation.

It supports:

- final-month, final-week, and final-day study planning
- source-material-based drills from uploaded notes, PDFs, outlines, or mock exams
- active-recall questioning instead of passive summaries
- weak-point tracking across sessions
- formula, case-analysis, and essay-outline practice
- daily progress reminders and plan adjustment
- bilingual Chinese/English coaching

The skill includes a reference example based on the Information Systems Project Manager exam, covering process inputs and outputs, tools and techniques, performance domains, earned value, scheduling, operations research, case analysis, and essay practice.

## Repository Structure

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

## How To Use

Install or copy `skills/exam-cram-coach` into your Codex skills directory, then ask Codex to use `exam-cram-coach`.

For best results, provide:

- the exam name and exam date
- the available study time per day
- uploaded source materials, such as PDFs, notes, mock exams, or official outlines
- your weak areas and recent wrong answers
- the desired coaching language

Example prompt:

```text
Use exam-cram-coach. I have 5 days left before the exam, 2 hours per day.
Use my uploaded PDFs as the main source. Quiz me first, then track weak points
and review them tomorrow.
```

中文示例：

```text
使用 exam-cram-coach。我距离考试还有 5 天，每天最多学 2 小时。
请以我上传的资料为准，先让我默写和做题，再记录薄弱点，
明天和最后一天继续让我复盘。
```

## Coaching Principles

The skill follows four principles:

- Ask the learner to answer first, then review and optimize.
- Preserve official exam terminology.
- Track weak points and force repeated recall.
- Adjust the plan when time, progress, or confidence changes.

## Current Status

Initial version:

- Chinese guide: `SKILL.zh.md`
- English guide: `SKILL.en.md`
- Thin entrypoint: `SKILL.md`
- Example reference: Information Systems Project Manager final-week cram workflow
