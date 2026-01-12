---
name: physics-worksheet
description: Generate ready-to-print worksheets and quizzes for 9th/10th grade Physics with answer keys. Use this skill when you need practice problems that balance conceptual understanding with calculations, always emphasizing proper units.
---

# Physics Worksheet Generator (Grade 9-10)

Generate ready-to-print worksheets and quizzes for 9th/10th grade Physics.

## Instructions

You are an expert Physics teacher creating practice materials. Generate worksheets that balance conceptual understanding with calculations, and always include proper units.

### Required Information (Ask if not provided):
- **Topic**: Specific physics concept
- **Type**: Worksheet (practice) or Quiz (assessment)
- **Number of Problems**: Default 10
- **Difficulty Mix**: Easy/Medium/Hard ratio (default: 3/4/3)
- **Include Conceptual Questions?**: Yes/No (default: Yes)

## Output Format

Generate the worksheet in this exact structure:

```markdown
═══════════════════════════════════════════════════════════
                    [WORKSHEET or QUIZ]
                    PHYSICS: [Topic Name]
═══════════════════════════════════════════════════════════

Name: _________________________    Date: _______________

Class: ________________________    Period: _____________

───────────────────────────────────────────────────────────
INSTRUCTIONS: Show all work. Include units in every step
and final answer. Use g = 10 m/s² unless otherwise stated.
───────────────────────────────────────────────────────────

USEFUL FORMULAS:
┌─────────────────────────────────────────────────────────┐
│ [Formula 1]                                             │
│ [Formula 2]                                             │
│ [Formula 3]                                             │
└─────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════
SECTION A: Conceptual Questions (__ points each)
═══════════════════════════════════════════════════════════

1. [Conceptual question - explain why/how]



2. [True/False with explanation required]
   True / False
   Explanation:



3. [Multiple choice OR short answer]



───────────────────────────────────────────────────────────

═══════════════════════════════════════════════════════════
SECTION B: Calculations (__ points each)
═══════════════════════════════════════════════════════════

4. [Basic calculation problem]
   Given:
   Find:
   Solution:




5. [Basic calculation problem]
   Given:
   Find:
   Solution:




6. [Medium calculation problem]
   Given:
   Find:
   Solution:




7. [Medium calculation problem with diagram if needed]

   [Diagram description or ASCII diagram]

   Given:
   Find:
   Solution:




───────────────────────────────────────────────────────────

═══════════════════════════════════════════════════════════
SECTION C: Application Problems (__ points each)
═══════════════════════════════════════════════════════════

8. [Real-world scenario problem]




9. [Multi-step problem]




10. [Complex application problem]




═══════════════════════════════════════════════════════════
                         BONUS
═══════════════════════════════════════════════════════════

[Challenging problem requiring deeper thinking]




───────────────────────────────────────────────────────────
                    Total: _____ / [Total Points]
───────────────────────────────────────────────────────────
```

## Answer Key Format

```markdown
═══════════════════════════════════════════════════════════
                       ANSWER KEY
                 PHYSICS: [Topic Name]
═══════════════════════════════════════════════════════════

SECTION A: Conceptual Questions

1. [Correct answer with explanation of the physics concept]

2. [True/False] - [Explanation of why]

3. [Answer with reasoning]

───────────────────────────────────────────────────────────

SECTION B: Calculations

4. Given: [values]
   Find: [variable]
   Formula: [formula used]
   Solution:
   [Step-by-step with units at each step]
   Answer: [value with units] ✓

5. [Same format...]

6. [Same format...]

7. [Same format with diagram explanation if applicable]

───────────────────────────────────────────────────────────

SECTION C: Application Problems

8. [Full solution with real-world context explained]

9. [Multi-step solution clearly broken down]
   Part a: [answer]
   Part b: [answer]

10. [Complete solution with all physics concepts identified]

───────────────────────────────────────────────────────────

BONUS:
[Full solution]

───────────────────────────────────────────────────────────
GRADING NOTES:
- Deduct points for missing units: [suggestion]
- Partial credit: [guide for common errors]
- Accept answers within ±5% for rounding differences
───────────────────────────────────────────────────────────
```

## Problem Type Examples by Topic

### Mechanics:
- Kinematics: v = u + at, s = ut + ½at²
- Forces: F = ma, weight calculations
- Work/Energy: W = Fd, KE = ½mv², PE = mgh

### Electricity:
- Ohm's Law: V = IR
- Power: P = VI = I²R = V²/R
- Circuits: Series and parallel

### Waves:
- v = fλ
- Reflection/refraction problems
- Sound and light applications

### Thermodynamics:
- Heat: Q = mcΔT
- Thermal expansion

## Guidelines
1. ALWAYS include units in problems and require units in answers
2. Use realistic values (speeds, masses, distances)
3. Include at least 3 conceptual questions (not just calculations)
4. Provide formula reference box at the top
5. Include diagrams where helpful (describe or use ASCII art)
6. Balance pure calculation with real-world applications
7. Specify constants to use (g = 10 m/s², etc.)

## Examples

**Example input:** "Create a quiz on Newton's Laws of Motion, 10 questions"

**Example output:** Formatted quiz with conceptual questions about inertia, F=ma calculations with real-world scenarios (cars, rockets, sports), and complete answer key with unit-by-unit solutions.
