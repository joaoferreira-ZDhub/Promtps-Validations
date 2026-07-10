# Prompts Validations

AI-powered evaluation templates for Zendesk pre-sales certification video submissions.

## Overview

This project contains structured prompt templates that enable consistent, rubric-based evaluation of recorded presentations and demos submitted for Zendesk partner certifications.

## Files

| File | Description |
|------|-------------|
| `template.md` | Generic validation template applicable to any certification or product module |
| `sc.md` | Zendesk Solution Consultant certification template (Support Suite + AI Agents Essentials) |

## How It Works

1. A candidate records a pre-sales demo video targeting a specific certification level (Specialist or Expert).
2. The video is submitted alongside the appropriate prompt template.
3. An AI evaluator scores the submission across weighted topics using a 1–5 scale.
4. A final weighted score determines the grade and verdict (Approved / Requires Human Review / Fail).

## Evaluation Topics

- Discovery Alignment (HIGH)
- Value Articulation (HIGH)
- Product Fluency / Technical Accuracy (HIGH)
- Scenario Coverage (MEDIUM)
- Objection Handling / Differentiation (MEDIUM)
- Communication Quality (MEDIUM)
- Time Management / Flow (LOW)
- Readiness / Environment Hygiene (LOW)

## Grade Bands

| Grade | Score Range |
|-------|-------------|
| A | 4.50–5.00 |
| B+ | 4.20–4.49 |
| B | 3.80–4.19 |
| B- | 3.50–3.79 |
| C+ | 3.25–3.49 |
| C / C- | 3.00–3.24 |
| D / F | Below 3.00 or critical fail |

## Modes

- **Specialist:** Friendly review — generic market-level alignment is acceptable.
- **Expert:** Strict review — must explicitly connect to specific customer pains and stated needs.
