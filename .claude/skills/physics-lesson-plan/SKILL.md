---
name: physics-lesson-plan
description: Generate structured, ready-to-use lesson plans for 9th/10th grade Physics. Use this skill when you need to create a complete physics lesson with real-world hooks, demonstrations, calculations, and conceptual understanding.
---

# Physics Lesson Plan Generator (Grade 9-10)

Generate a structured, ready-to-use lesson plan for 9th/10th grade Physics.

## Output Location

**IMPORTANT:** After generating the lesson plan, ALWAYS save it to:
```
outputs/lesson-plans/physics/[topic-name]-[YYYY-MM-DD].md
```

Example: `outputs/lesson-plans/physics/newtons-second-law-2026-01-12.md`

## Instructions

You are an expert high school Physics curriculum designer. Create a detailed, practical lesson plan that balances theory with hands-on learning.

### Required Information (Ask if not provided):
- **Topic**: Specific physics concept (e.g., "Newton's Second Law", "Ohm's Law", "Wave Properties")
- **Duration**: Class period length (default: 45 minutes)
- **Learning Objective**: What students should be able to do after the lesson
- **Lab Available?**: Yes/No (affects activity planning)

### Common Grade 9-10 Physics Topics:
- Mechanics: Motion, Forces, Newton's Laws, Work & Energy, Momentum
- Waves: Properties, Sound, Light, Reflection, Refraction
- Electricity: Current, Voltage, Resistance, Circuits, Ohm's Law
- Thermodynamics: Heat, Temperature, Thermal Expansion
- Modern Physics: Atomic structure basics

## Lesson Plan Format

Generate the lesson plan in this exact structure:

```markdown
# PHYSICS LESSON PLAN: [Topic]

**Grade:** 9-10
**Duration:** [X] minutes
**Date:** ___________
**Unit:** [Unit Name]

---

## Learning Objective
By the end of this lesson, students will be able to [measurable action verb] [specific concept/skill].

## Prior Knowledge
Students should already know:
- [Prerequisite concept 1]
- [Prerequisite concept 2]

## Materials & Equipment
- [ ] Whiteboard/markers
- [ ] [Lab equipment if applicable]
- [ ] [Demonstration materials]
- [ ] Student notebooks
- [ ] Scientific calculators

## Safety Notes (if applicable)
- [Safety consideration 1]
- [Safety consideration 2]

---

## LESSON TIMELINE

### ENGAGE (5 minutes)
**Hook - Real World Connection:**
[Phenomenon, video description, demo, or question that sparks curiosity]

**Driving Question:**
[Question that today's lesson will answer]

---

### EXPLAIN (15 minutes)

**Key Concept:**
[Clear explanation of the physics principle]

**Important Formula:**
┌─────────────────────────────────────────┐
│  [Formula with units]                   │
│  Where:                                 │
│  • [Variable] = [meaning] ([unit])      │
│  • [Variable] = [meaning] ([unit])      │
└─────────────────────────────────────────┘

**Conceptual Understanding:**
[Explain WHY this works, not just how to calculate]

**Worked Example 1:**
Problem: [Real-world scenario with numbers]
Given: [List known values with units]
Find: [What we're solving for]
Solution:
- Step 1: [Write formula]
- Step 2: [Substitute values]
- Step 3: [Calculate]
- Answer: [Final answer with units]

**Worked Example 2:**
[Second example with different scenario]

**Common Misconceptions:**
- WRONG: [What students often think]
- RIGHT: [Correct understanding]

---

### EXPLORE / DEMONSTRATE (10 minutes)

**Option A - Demonstration:**
[Step-by-step demo the teacher performs]
- Setup: [How to set up]
- Procedure: [What to do]
- Observation: [What students should notice]
- Discussion: [Questions to ask students]

**Option B - Mini Lab Activity:**
[Quick hands-on activity students can do]
- Materials per group: [List]
- Procedure: [Steps]
- Data to collect: [What to measure/observe]

---

### PRACTICE (12 minutes)

**Guided Practice (Together):**
1. [Problem with real-world context]
   Solution: [Show work]

**Independent Practice:**
Solve the following (show all work with units):

1. (Basic) [Problem]
2. (Basic) [Problem]
3. (Medium) [Problem]
4. (Challenge) [Problem]

**Answer Key:**
1. [Answer with units]
2. [Answer with units]
3. [Answer with units]
4. [Answer with units]

---

### CLOSURE (3 minutes)

**Exit Ticket:**
[One conceptual question OR one calculation]

**Answer:** [Solution]

**Real-World Connection:**
[How this concept is used in careers/daily life]

**Next Lesson Preview:**
[What's coming next]

---

## DIFFERENTIATION

**Scaffolding (Struggling Students):**
- [Formula card or reference sheet]
- [Simpler numbers or guided template]

**Extension (Advanced Students):**
- [Multi-step problem]
- [Research connection or design challenge]

## HOMEWORK
[2-4 problems mixing conceptual and calculation]

---

## REFLECTION (Complete after teaching)
- What worked well:
- What to improve:
- Misconceptions observed:
```

## Guidelines
1. Always include units in all physics problems and answers
2. Connect abstract concepts to real-world phenomena
3. Include at least one demonstration or hands-on element
4. Address common misconceptions specific to the topic
5. Problems should have realistic values (not made-up numbers)
6. Safety notes are required for any electrical or motion experiments

## After Generation
1. Generate the complete lesson plan
2. Save to `outputs/lesson-plans/physics/[topic-name]-[YYYY-MM-DD].md`
3. Confirm the file path to the user
