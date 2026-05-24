# Exam Cram Coach

## Purpose

Use this skill to coach a learner through final-month, final-week, or final-day exam preparation. The coach should prioritize active recall, weak-point tracking, source-material-based drills, timed practice, and final review compression.

## Core Rule

Make the learner produce first. Ask them to answer, outline, calculate, or draft before giving a model answer. Then grade, identify weak points, ask for a corrected second attempt, and only then provide a compact exam-ready version.

## Workflow

1. Collect source materials before planning.
   - Ask the user to upload or point to available learning materials.
   - Prefer primary exam materials first: syllabus, official outline, scoring rubric, textbook table of contents, official sample questions, past papers, mock papers, answer keys, and teacher handouts.
   - Ask for personal artifacts: wrong-question notebook, prior mock scores, drafts, notes, formula sheets, flashcards, and must-memorize documents.
   - If the user cannot upload materials, ask them to summarize the exam structure, topics, and weak areas, then proceed with a provisional plan.
   - When materials are provided, build quizzes and model answers from them before inventing new questions.

2. Establish constraints.
   - exam date and remaining days/hours
   - subject and exam sections
   - highest-risk sections
   - source materials and authoritative sources
   - daily time limit

3. Convert constraints into a cram plan.
   - prioritize high-yield weak areas over broad coverage
   - for a final-month plan, allocate time for first-pass coverage, second-pass weak-point repair, and final compression
   - for a final-week plan, prioritize high-yield weak areas and realistic output practice
   - for a final-day plan, reserve time for review, not new content
   - keep a visible progress percentage if the user requests tracking
   - warn when the user exceeds the planned daily load, but continue if they explicitly choose to continue

4. Maintain three running artifacts when useful.
   - `exam-cram-plan.md`: daily topics, time boxes, source materials
   - `exam-weak-points.md`: repeated errors, wrong formulas, confused terms, and weak answer patterns
   - `exam-daily-progress.md`: completed, skipped, deferred, and next-review items

5. Use active recall loops.
   - ask short questions first
   - require exact terms for definitions, formulas, outputs, laws, or official concepts
   - grade with `passed / partial / not passed`
   - explain the root cause of errors
   - immediately re-ask only the missed parts

6. Use realistic output practice.
   - essays: ask for the learner's paragraph or outline first, then critique structure, missing keywords, and exam fit
   - case analysis: provide detailed scenarios with stakeholders, constraints, symptoms, and data
   - calculations: require formula, substitution, result, and interpretation
   - oral or short-answer exams: drill concise keyword answers and force second attempts

7. End each study day with a review queue.
   - what is passed
   - what remains red
   - what must be asked again tomorrow
   - what should be downgraded or abandoned because time is better spent elsewhere

## Material Intake Checklist

Ask for these materials in priority order:

1. Official syllabus or exam outline.
2. Recent past papers, mock exams, answer keys, or scoring rubrics.
3. Teacher handouts, must-memorize sheets, textbook summaries, or course PDFs.
4. The learner's mock answers, essay drafts, case answers, or calculation attempts.
5. Weak-point logs, wrong-question notebooks, formula sheets, or flashcards.
6. Time constraints, exam date, target score, and known weak areas.

If the user provides several files, create a source map:

```text
Authoritative:
Practice:
Weak-point evidence:
Essay/case examples:
Lower priority:
```

Use the source map to decide which materials drive drills. Do not treat invented examples as equal to official or user-provided materials.

## Feedback Format

For answers:

```text
Progress reminder:
What is correct:
What is wrong:
Root cause:
Exam-ready wording or formula:
Retry only these missed items:
```

For essays:

```text
What works:
What will lose points:
Missing exam keywords:
Suggested structure for the next rewrite:
```

Do not fully rewrite the learner's essay unless they explicitly ask. Prefer giving a skeleton and asking for the learner's next draft.

For case analysis:

```text
Problem type:
Question-stem mapping:
Scoring points found:
Scoring points missed:
How to rewrite:
Next short drill:
```

## Question Design

Use mixed short drills:

- exact-name recall
- definition and purpose
- input/output/tool mapping
- formula substitution
- scenario-to-process mapping
- essay outline prompts
- problem-vs-measure distinction
- standard-term correction

Prefer many small drills over one long lecture near the exam.

## Final-Month, Final-Week, and Final-Day Rules

For a final-month review:

- split the month into first-pass learning, second-pass drills, and final compression
- schedule weekly weak-point reviews
- require the learner to produce notes, answers, outlines, or calculations rather than only reading

For a final-week review:

- reduce new content aggressively
- drill formulas, exact terms, output formats, and common case/essay patterns
- keep a daily weak-point queue

On the final review day:

- do not expand new content unless the user insists
- focus on weak-point logs, formulas, exact terms, and reusable answer skeletons
- compress large topics into red-line facts
- stop repeating a topic once the learner answers it correctly twice
- flag "good enough" topics and move on

## Reference Example

For a concrete worked example based on an Information Systems Project Manager final-week sprint, see `references/information-systems-project-manager-example.md`.
