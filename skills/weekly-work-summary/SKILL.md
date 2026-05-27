---
name: weekly-work-summary
description: Create concise Chinese weekly work summaries from rough work notes, especially project delivery, system integration, acceptance, deployment, testing, and vendor coordination updates. Use when the user asks to polish a weekly report, make a complete compact version for a work summary, apply SCQA or START to weekly work, rewrite "本周完成/遇到的问题/下周计划/剩余待办", or turn scattered project notes into a report that can be pasted directly into a weekly update.
---

# Weekly Work Summary

Use this skill to turn raw weekly work notes into a concise, ready-to-paste Chinese weekly report.

## Workflow

1. Preserve facts.
   - Keep system names, owners, statuses, deadlines, blockers, and explicit decisions from the source.
   - Do not invent completion status, dates, or responsible people.
   - If a point is unclear, keep it as "待确认" or phrase it as a risk.

2. Lead with SCQA.
   - Situation: what this week focused on.
   - Complication: what changed, what was found, or what blocks progress.
   - Question: what risk or decision matters now.
   - Answer: what will be done next week.
   - Do not label every paragraph with SCQA unless the user asks; write it as natural weekly-report prose.

3. Use START for individual items when needed.
   - Situation/Task: context or target.
   - Action: work completed or coordination performed.
   - Result: current state.
   - Takeaway: next step, risk, or dependency.
   - Compress these into one bullet rather than exposing the framework labels.

4. Output the report directly.
   - If the user asks for a "可直接放进周报" version, provide the polished report first.
   - Avoid long explanation before the report.
   - Put suggestions after the report only when the user asks for optimization advice.

## Recommended Structure

Use this structure by default:

1. `整体情况`
2. `本周完成事项`
3. `主要问题与风险`
4. `下周计划`
5. `后续待办事项`
6. `系统对接情况汇总` when system integration status exists
7. `总结`

For very short notes, collapse sections 5-7.

## Writing Rules

- Write in concise Chinese business style.
- Put conclusions before details.
- Merge repeated points instead of listing the same fact in multiple sections.
- Convert vague wording into "问题 + 影响 + 下一步".
- Keep bullets parallel and action-oriented.
- Prefer "已完成/进行中/待确认/需持续跟进/存在延期风险" over loose descriptions.
- For acceptance or audit work, emphasize delivery-basis compliance, demonstration readiness, and verification risk.
- For integration work, emphasize external dependency, current status, owner, and next coordination action.
- For deployment work, separate environment, domain, hardware, network access, and operations handover.

## Project Delivery Emphasis

When notes include project-specific names, abstract them into reusable categories before writing the summary:

- delivery basis: contract requirements, acceptance criteria, scope documents, interface documents, or agreed feature lists;
- milestone events: internal validation, external review, leadership demo, acceptance inspection, go-live, production verification, or handover;
- key stakeholders: owner, client, prime contractor, supervisor, vendor, platform team, operations team, or other decision makers;
- key modules: cockpit, dashboard, report, workflow, integration, mobile, deployment, monitoring, or other high-risk feature areas;
- integration dependencies: upstream systems, downstream systems, integration channels, API documents, data sources, test devices, or environment readiness.

After abstraction, highlight:

- whether the feature exists according to the delivery basis;
- whether the implementation is correct enough for the current milestone;
- whether the demo path and data are ready;
- which external dependencies still block progress;
- which items need stakeholder confirmation, decision, or coordination.

## Reference

For a reusable weekly-report template and phrasing examples, read `references/weekly-summary-template.md`.
