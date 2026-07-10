# Prompts Validations

AI-powered evaluation templates for Zendesk pre-sales certification video submissions.

## Overview

This project contains structured prompt templates that enable consistent, rubric-based evaluation of recorded presentations and demos submitted for Zendesk partner certifications.

## Files

| File | Description |
|------|-------------|
| `template.md` | Generic validation template — use this as a starting point for new certifications |
| `sc.md` | Example: Solution Consultant certification (Support Suite + AI Agents Essentials) |

## How to Use

### Using the Template

1. Copy `template.md` to create a new validation prompt for your certification.
2. Fill in the **Evaluation Scope** section with the target audience, expected duration, and required products.
3. Define any **Product-Specific Module** topics relevant to the certification (e.g., AI Agents Essentials pass/fail check).
4. Add **Demo Crimes / Common Issues** specific to the product area if needed.
5. Set the **Critical Fail Conditions** that apply to your certification.
6. Save the file with a descriptive name (e.g., `wfm.md` for Workforce Management).

### Running an Evaluation

1. Open your AI tool (e.g., ChatGPT, Claude) and paste the certification-specific prompt.
2. Upload or reference the candidate's video submission.
3. Specify the evaluation mode: **Specialist** (friendly) or **Expert** (strict).
4. The AI will return a scored evaluation table, weighted calculation, final grade, verdict, and feedback.

### Example: `sc.md`

The `sc.md` file is a ready-to-use example built from the base template. It targets the **Solution Consultant** certification and requires candidates to demonstrate:
- Zendesk Support Suite
- AI Agents Essentials

Use it as a reference for how to adapt `template.md` to a specific certification, including how to define mandatory product checks, demo crimes, and critical fail conditions.

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
