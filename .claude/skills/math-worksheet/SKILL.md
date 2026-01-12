---
name: math-worksheet
description: Generate ready-to-print worksheets and quizzes for 9th/10th grade Mathematics with answer keys. Use this skill when you need practice problems, homework sheets, or quiz assessments with progressive difficulty.
---

# Mathematics Worksheet Generator (Grade 9-10)

Generate ready-to-print worksheets and quizzes for 9th/10th grade Mathematics.

## Instructions

You are an expert Math teacher creating practice materials. Generate worksheets that are properly formatted and include answer keys.

### Required Information (Ask if not provided):
- **Topic**: Specific math concept
- **Type**: Worksheet (practice) or Quiz (assessment)
- **Number of Problems**: Default 10
- **Difficulty Mix**: Easy/Medium/Hard ratio (default: 3/4/3)
- **Include Word Problems?**: Yes/No (default: Yes)

## Output Format

Generate the worksheet in this exact structure:

```markdown
═══════════════════════════════════════════════════════════
                    [WORKSHEET or QUIZ]
                    [Topic Name]
═══════════════════════════════════════════════════════════

Name: _________________________    Date: _______________

Class: ________________________    Period: _____________

───────────────────────────────────────────────────────────
INSTRUCTIONS: [Specific instructions for this worksheet]
Show all your work. Circle or box your final answers.
───────────────────────────────────────────────────────────

SECTION A: Basic Problems (__ points each)

1. [Problem]




2. [Problem]




3. [Problem]




───────────────────────────────────────────────────────────

SECTION B: Application Problems (__ points each)

4. [Problem]




5. [Problem]




6. [Problem]




7. [Problem]




───────────────────────────────────────────────────────────

SECTION C: Challenge Problems (__ points each)

8. [Problem]




9. [Problem]




10. [Word Problem with real-world context]





═══════════════════════════════════════════════════════════
                         BONUS (Optional)
═══════════════════════════════════════════════════════════

[Challenging bonus problem]




───────────────────────────────────────────────────────────
                    Total: _____ / [Total Points]
───────────────────────────────────────────────────────────
```

## Answer Key Format

```markdown
═══════════════════════════════════════════════════════════
                       ANSWER KEY
                    [Topic Name]
═══════════════════════════════════════════════════════════

SECTION A:
1. [Answer]
   Solution: [Brief work shown]

2. [Answer]
   Solution: [Brief work shown]

3. [Answer]
   Solution: [Brief work shown]

SECTION B:
4. [Answer]
   Solution: [Work shown]

5. [Answer]
   Solution: [Work shown]

6. [Answer]
   Solution: [Work shown]

7. [Answer]
   Solution: [Work shown]

SECTION C:
8. [Answer]
   Solution: [Detailed work]

9. [Answer]
   Solution: [Detailed work]

10. [Answer]
    Solution: [Detailed work with explanation]

BONUS:
[Answer with full solution]

───────────────────────────────────────────────────────────
GRADING NOTES:
- Accept equivalent forms (e.g., 0.5 = 1/2)
- Partial credit guide: [Suggestions for partial credit]
───────────────────────────────────────────────────────────
```

## Problem Type Examples by Topic

### Algebra:
- Solve equations: 3x + 7 = 22
- Factor expressions: x² + 5x + 6
- Word problems: Age problems, mixture problems

### Geometry:
- Find missing angles
- Calculate area/perimeter
- Coordinate geometry problems

### Trigonometry:
- Find sin/cos/tan values
- Solve right triangles
- Application problems (height/distance)

### Functions:
- Evaluate f(x) for given values
- Find domain/range
- Graph interpretation

## Guidelines
1. Problems must have numerical answers (no variables in final answers unless specified)
2. Increase difficulty progressively within each section
3. Include at least 2 word problems with real-world context
4. Leave adequate space between problems for student work
5. Point values should be clearly marked
6. Answer key must show work, not just final answers
7. Use clear, unambiguous problem statements

## Examples

**Example input:** "Create a 10-question worksheet on Solving Quadratic Equations by Factoring"

**Example output:** Formatted worksheet with 3 basic factoring problems, 4 medium difficulty, 3 challenging including word problems, plus complete answer key with solutions.
