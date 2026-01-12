# Teacher Skills for Grade 9-10 Math & Physics

A collection of 6 AI-powered Agent Skills that automate repetitive teaching tasks for 9th/10th grade Mathematics and Physics teachers.

**Built using the official [Anthropic Agent Skills](https://github.com/anthropics/skills) specification.**

---

## Demo Video

[![Watch Demo](https://cdn.loom.com/sessions/thumbnails/4fda039948234062bc22898b5fb458b7-00001.jpg)](https://www.loom.com/share/4fda039948234062bc22898b5fb458b7)

▶️ **[Click to watch 60-90 second demo](https://www.loom.com/share/4fda039948234062bc22898b5fb458b7)**

---

## Skills Overview

| # | Skill                         | Skill Name              | What It Replaces           | Time Saved          |
| - | ----------------------------- | ----------------------- | -------------------------- | ------------------- |
| 1 | Math Lesson Plan Generator    | `math-lesson-plan`    | Manual lesson planning     | 30-45 min/lesson    |
| 2 | Physics Lesson Plan Generator | `physics-lesson-plan` | Manual lesson planning     | 30-45 min/lesson    |
| 3 | Math Worksheet Generator      | `math-worksheet`      | Creating practice problems | 20-30 min/worksheet |
| 4 | Physics Worksheet Generator   | `physics-worksheet`   | Creating practice problems | 20-30 min/worksheet |
| 5 | Math Rubric Creator           | `math-rubric`         | Writing grading criteria   | 15-20 min/rubric    |
| 6 | Physics Rubric Creator        | `physics-rubric`      | Writing grading criteria   | 15-20 min/rubric    |

---

## Project Structure (Official Anthropic Format)

```
Project-1/
├── .claude/
│   └── skills/
│       ├── math-lesson-plan/
│       │   └── SKILL.md
│       ├── physics-lesson-plan/
│       │   └── SKILL.md
│       ├── math-worksheet/
│       │   └── SKILL.md
│       ├── physics-worksheet/
│       │   └── SKILL.md
│       ├── math-rubric/
│       │   └── SKILL.md
│       └── physics-rubric/
│           └── SKILL.md
├── outputs/                        # Auto-saved generated materials
│   ├── lesson-plans/
│   │   ├── math/                   # e.g., quadratic-equations-2026-01-12.md
│   │   └── physics/                # e.g., newtons-laws-2026-01-12.md
│   ├── worksheets/
│   │   ├── math/                   # e.g., linear-equations-worksheet-2026-01-12.md
│   │   └── physics/                # e.g., ohms-law-quiz-2026-01-12.md
│   └── rubrics/
│       ├── math/                   # e.g., algebra-test-rubric-2026-01-12.md
│       └── physics/                # e.g., mechanics-lab-rubric-2026-01-12.md
├── README.md
└── CLAUDE.md
```

Each `SKILL.md` follows the official format with:

- YAML frontmatter (`name`, `description`)
- Markdown instructions
- Examples and guidelines
- **Auto-save location** for generated outputs

---

## Auto-Save Feature

All skills automatically save generated materials to organized folders:

| Skill Type   | Output Location                     | File Naming                             |
| ------------ | ----------------------------------- | --------------------------------------- |
| Lesson Plans | `outputs/lesson-plans/[subject]/` | `[topic]-[YYYY-MM-DD].md`             |
| Worksheets   | `outputs/worksheets/[subject]/`   | `[topic]-[type]-[YYYY-MM-DD].md`      |
| Rubrics      | `outputs/rubrics/[subject]/`      | `[assignment]-rubric-[YYYY-MM-DD].md` |

**Examples:**

- `outputs/lesson-plans/math/quadratic-equations-2026-01-12.md`
- `outputs/worksheets/physics/newtons-laws-quiz-2026-01-12.md`
- `outputs/rubrics/math/algebra-test-rubric-2026-01-12.md`

---

## Detailed Skill Descriptions

### 1. Math Lesson Plan Generator

**Skill name:** `math-lesson-plan`

**What it replaces:** The cognitive task of structuring a 45-minute math lesson from scratch, including warm-up problems, examples, practice problems, and differentiation strategies.

**Input required:**

- Topic (e.g., "Quadratic Equations")
- Duration (default: 45 minutes)
- Learning objective

**Output:**

- Complete lesson plan with timed sections
- Bell ringer warm-up problem
- Step-by-step worked examples
- Progressive practice problems (basic → challenge)
- Differentiation for struggling/advanced students
- Exit ticket

**Quality improvement:** Consistent lesson structure, no forgetting sections, built-in differentiation.

---

### 2. Physics Lesson Plan Generator

**Skill name:** `physics-lesson-plan`

**What it replaces:** Planning physics lessons that balance theory, demonstrations, and calculations.

**Input required:**

- Topic (e.g., "Newton's Second Law")
- Duration (default: 45 minutes)
- Learning objective
- Lab available? (Yes/No)

**Output:**

- Engaging real-world hook
- Concept explanation with formulas
- Demonstration or mini-lab activity
- Practice problems with units
- Common misconceptions addressed

**Quality improvement:** Every lesson includes hands-on elements and real-world connections.

---

### 3. Math Worksheet Generator

**Skill name:** `math-worksheet`

**What it replaces:** Creating practice worksheets and quizzes with proper difficulty progression.

**Input required:**

- Topic
- Type (Worksheet or Quiz)
- Number of problems (default: 10)
- Difficulty mix

**Output:**

- Formatted worksheet ready to print
- Progressive difficulty (basic → medium → challenge)
- Word problems included
- Complete answer key with solutions

**Quality improvement:** Professional formatting, guaranteed answer key accuracy.

---

### 4. Physics Worksheet Generator

**Skill name:** `physics-worksheet`

**What it replaces:** Creating physics practice materials with proper units and conceptual questions.

**Input required:**

- Topic
- Type (Worksheet or Quiz)
- Number of problems (default: 10)

**Output:**

- Formula reference box
- Conceptual questions section
- Calculation problems with realistic values
- Answer key with full solutions and units

**Quality improvement:** Consistent unit emphasis, balanced conceptual/calculation mix.

---

### 5. Math Rubric Creator

**Skill name:** `math-rubric`

**What it replaces:** Writing grading criteria for math assignments and projects.

**Input required:**

- Assignment type (Test, Quiz, Project, etc.)
- Topic/skills assessed
- Total points

**Output:**

- Point-by-point scoring guide
- Partial credit guidelines
- Common deduction scenarios
- Grade scale

**Quality improvement:** Consistent, fair grading; clear expectations for students.

---

### 6. Physics Rubric Creator

**Skill name:** `physics-rubric`

**What it replaces:** Creating rubrics for physics tests, labs, and projects.

**Input required:**

- Assignment type
- Topic/skills assessed
- Total points

**Output:**

- Calculation scoring guide (with unit requirements)
- Conceptual question rubric
- Lab report rubric template
- Error analysis criteria

**Quality improvement:** Emphasizes units throughout, includes lab-specific criteria.

---

## Weekly Time Savings Estimate

| Task            | Without Skill        | With Skill       | Weekly Savings            |
| --------------- | -------------------- | ---------------- | ------------------------- |
| 5 lesson plans  | 2.5 hours            | 25 min           | ~2 hours                  |
| 3 worksheets    | 1.5 hours            | 15 min           | ~1.25 hours               |
| 2 rubrics       | 40 min               | 10 min           | ~30 min                   |
| **TOTAL** | **4.5+ hours** | **50 min** | **~3.5 hours/week** |

---

## Measurable Outcomes

Each skill has clear, measurable success criteria:

| Skill        | Measurable Outcome                                                                       |
| ------------ | ---------------------------------------------------------------------------------------- |
| Lesson Plans | Complete 5-section structure, timed to specified duration, includes 3+ practice problems |
| Worksheets   | Specified number of problems, progressive difficulty, 100% accurate answer key           |
| Rubrics      | Clear point breakdowns, partial credit guidelines, student-friendly language             |

---

## How to Use

### With Claude Code CLI:

1. Clone this repository
2. Open Claude Code in the project directory
3. Skills are automatically available

### With Claude.ai:

1. Upload the skill folder to Claude.ai (paid plans)
2. Reference the skill in your conversation

---

## Installation

```bash
# Clone the repository
git clone https://github.com/MohammadNoman/High-School-Teacher-Skills.git

# Navigate to project
cd High-School-Teacher-Skills

# Open with Claude Code
claude
```

---

## References

- [Anthropic Agent Skills Specification](https://github.com/anthropics/skills)
- [Claude Code Skills Documentation](https://docs.anthropic.com/en/docs/claude-code/skills)

---

## Author

Created for **AI-300 Checkpoint A1: Extract Your Human Job Into Skills**

**Target Role:** High School Math & Physics Teacher (Grade 9-10)

**Checkpoint Requirements Met:**

- [X] 3-5 focused, reusable skills (6 created)
- [X] Each skill has one clear outcome
- [X] Each skill is measurable
- [X] Skills are small (100-200 lines each)
- [X] README describes what each replaces and time saved
