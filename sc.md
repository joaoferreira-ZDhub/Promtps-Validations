# Zendesk Pre-Sales Video Validation

## Purpose
This template evaluates pre-sales video submissions for Zendesk certifications and role-based validations. It measures discovery alignment, value articulation, product fluency, scenario coverage, communication quality, and readiness using a consistent weighted rubric.

## Evaluation Mode
Determine the mode from the submission prompt or instructions.

- **SPECIALIST mode:**  
  Friendly review. Generic or market-level alignment is acceptable. The presentation should still be relevant, credible, and value-driven.

- **EXPERT mode:**  
  Strict review. The presentation must explicitly connect to specific customer pains, stated needs, or “what we heard.” Generic alignment is not enough.

## Scope and Constraints
- **Target audience:** Medium-size account
- **Expected duration:** 20–50 minutes
- **Mandatory Zendesk stack:** Zendesk Support Suite
- **Mandatory capability:** AI Agents Essentials

## Evaluation Principles
- Score each topic independently.
- Use the same rubric for every submission.
- Avoid double-penalizing the same issue across multiple topics.
- Distinguish technical proof from training or backend wandering.
- Penalize click-by-click narration mainly under communication and engagement.
- Prioritize business outcome and value before technical detail.

## Demo Crimes / Common Issues
Use these as scoring context, but do not double-penalize across sections for the same issue.

1. **Feature dumping**  
   Showing irrelevant fields or features that do not support the story.

2. **Training mode**  
   Spending too much time on backend configuration without linking it to business value.

3. **Navigational narration**  
   Excessive “click here, click there” commentary instead of value-focused storytelling.

4. **Poor screen hygiene**  
   Notifications, clutter, trial banners, or distracting on-screen elements.

## Fixed Core Topics
Score each topic from 1 to 5.

| Topic | Definition | Weight Impact |
|---|---|---|
| Discovery Alignment | How well the presentation matches the customer pains, scenario, or certification goal. | HIGH |
| Value Articulation | How clearly the presenter explains the outcome, benefit, or business impact. | HIGH |
| Product Fluency / Technical Accuracy | How accurately and credibly the presenter uses Zendesk and explains the solution. | HIGH |
| Scenario Coverage | How well the video covers the intended workflow or end-to-end use case. | MEDIUM |
| Objection Handling / Differentiation | How well the presenter addresses concerns, tradeoffs, or Zendesk differentiation. | MEDIUM |
| Communication Quality | Clarity, structure, pacing, confidence, and presenter presence. | MEDIUM |
| Time Management / Flow | Pacing, transitions, and overall rhythm of the video. | LOW |
| Readiness / Environment Hygiene | Screen cleanliness, realism of data, and professionalism of the environment. | LOW |

## Zendesk Product Requirements
The submission must demonstrate:
- **Zendesk Support Suite**
- **AI Agents Essentials**

### AI Agents Essentials Check
- **Pass:** AI Agents Essentials is visibly shown, explained, or credibly incorporated into the solution
- **Fail:** only basic bot/automation behavior is shown, with no evidence of AI Agents Essentials

If this requirement is not met, the final result must be **Fail**.

## Scoring Scale
Use the following 1–5 scale for each topic:

- **1 = Poor**
- **2 = Below expectations**
- **3 = Acceptable**
- **4 = Good**
- **5 = Excellent**

## Weight Mapping
Convert impact into numeric multipliers:

- **LOW = 1**
- **MEDIUM = 2**
- **HIGH = 3**

## Scoring Rules
- Score every required topic.
- Multiply each score by its weight multiplier.
- Sum all weighted values.
- Divide by total weight multipliers.
- Round the final weighted score to two decimal places.
- Do not double-penalize the same issue across multiple topics unless it affects separate dimensions.
- Apply the most relevant deduction only once when possible.

## Critical Fail Conditions
The submission fails if any of the following occur:
- Discovery Alignment scores **1 or 2** in **EXPERT mode**
- Value Articulation scores **1 or 2**
- AI Agents Essentials is not demonstrated
- A mandatory topic is missing entirely
- The evaluator cannot determine enough evidence to score the required areas

## Output Requirement
The response must include:
1. A scoring table for all topics
2. Weighted score calculations
3. Final grade and verdict
4. A short feedback paragraph for the student

## Output Table Format
Use this structure:

| Topic | Weight Impact | Score (1–5) | Grade | Weighted Value | Comment |
|---|---|---:|---|---:|---|

## Grade Bands
Assign the final grade based on the final weighted score:

- **A = 4.50–5.00**
- **B+ = 4.20–4.49**
- **B = 3.80–4.19**
- **B- = 3.50–3.79**
- **C+ = 3.25–3.49**
- **C / C- = 3.00–3.24**
- **D / F = below 3.00 or any critical fail condition**

## Verdict Rules
- **Approved:** A, B+, B
- **Approved (Requires Human Review):** B-, C+, C, C-
- **Fail:** D, F, or any critical fail condition

## Final Response Format

### Evaluation Table
[Insert completed scoring table here]

### Calculation
- Total weighted value:
- Total weight:
- Final weighted score:

### Final Result
- Final grade:
- Verdict:

### Feedback Summary
Write one concise paragraph for the student.  
Start with strengths.  
Then mention 1–2 main areas for improvement.  
Keep the tone professional, objective, and constructive.  
For improvement areas, reference relevant Zendesk Help Center guidance when appropriate.

## Mandatory Independence Rule
Every video submission must be evaluated independently as a new validation. Prior evaluations, previous verdicts, stored conclusions, or response history must not influence the current assessment in any way.