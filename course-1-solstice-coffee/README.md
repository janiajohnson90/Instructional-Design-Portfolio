# Welcome to Solstice Coffee Co. — New Hire Onboarding

**Tool:** Articulate Rise 360
**Format:** Microlearning, 5 lessons, ~20–25 minutes
**Status:** ✅ Complete

**[▶ Launch the live course](https://janiajohnson90.github.io/Instructional-Design-Portfolio/course-1-solstice-coffee/build/)**

---

## The Scenario

Solstice Coffee Co. is a fictitious 40-location specialty coffee chain. New retail hires (baristas and trainees) need to be brought up to speed on company culture, their team and role, food safety basics, and the point-of-sale system before their first shift. This course was designed to be their day-one onboarding.

*Solstice Coffee Co. is a fictitious company created for portfolio purposes.*

---

## Learning Objectives

By the end of this course, learners are able to:
- Explain Solstice's core values and how they show up in daily work
- Identify their role and how it fits into the team
- Follow key food safety and handling procedures
- Use the point-of-sale system to ring up common orders
- Know who to go to with questions in their first week

---

## Course Structure

| Lesson | Focus | Key Interactions |
|---|---|---|
| 1. Welcome & Culture | Company story and values | Statement block, tabs (4 values), timeline (a day in the life), 2-question knowledge check |
| 2. Meet the Team & Org Structure | Roles and physical layout | Labeled graphic with hotspots (café floor plan), process block (role progression), flashcards |
| 3. Health, Safety & Handling | Food safety and emergency prep | Accordion (food safety basics), statement block (zero-tolerance allergy policy), labeled graphic (safety map), scenario-based multiple choice |
| 4. Systems & Tools | POS basics | Labeled graphic (POS screen tour), process block (mobile order workflow), matching activity (drink abbreviations) |
| 5. Wrap-Up & Certification | Recap and assessment | Statement block, 7-question graded final quiz, completion screen |

---

## Design Rationale

**Why Rise, and why this format.** Rise 360 is built for exactly this kind of content: short, self-paced, mobile-friendly onboarding that a new hire can complete on their own before day one. Rather than one long scrolling lesson, the course is split into five short lessons so a manager can assign it in digestible chunks, and so a learner returning after a pause always has a clear "where was I."

**Why five distinct interaction types, not five variations of the same one.** A common failure mode in Rise courses is that every screen ends up being a slightly different flavor of "text block + image." This course deliberately rotates through Rise's interactive block library — tabs, a timeline, a labeled graphic with hotspots, flashcards, an accordion, a process block, and a matching activity — so that each topic gets the interaction that fits it best, and so the course reads as intentionally designed rather than templated:
- **Tabs** for the four company values, since they're parallel, comparable items a learner would want to browse rather than read straight through.
- **A timeline** for "a day in the life," because the content is inherently sequential and time-based.
- **A labeled graphic with hotspots** for both the café floor plan and the safety map, since spatial content (where things physically are) is best learned spatially, not as a bulleted list.
- **Flashcards** for team roles, giving the content a low-stakes, self-check quality appropriate for something a new hire will reference casually rather than be tested hard on.
- **An accordion** for food safety basics, letting a learner scan four topics without a wall of text competing for attention at once.
- **A process block** for the mobile-order workflow, because it's a literal step-by-step procedure.
- **A matching activity** for drink abbreviations, turning otherwise dry memorization (SB, DD, WL...) into a low-stakes interactive check.

**Why the scenario-based question in Lesson 3, not just a recall question.** Most of the knowledge checks in this course are straightforward recall (matching a value to its definition, etc.), but the food-allergy question in Lesson 3 is written as a realistic workplace scenario with plausible, non-obvious distractors ("tell them to order something else," "ask a manager and do nothing yourself") rather than one obviously-correct and three throwaway options. Food safety is the one topic in this course with real consequences if misunderstood, so it's the one place a simple definition check wasn't enough — the learner needs to demonstrate they'd act correctly in the moment, not just recognize the policy.

**Why gating and a graded final quiz.** Lessons are locked sequentially so a learner can't skip straight to the final quiz without engaging with the content, and the final quiz (80% pass threshold) pulls questions from all five lessons rather than being weighted toward the end of the course, so it functions as a genuine check of retention rather than a formality.

---


## Files in This Folder

```
course-1-solstice-coffee/
├── README.md                                       ← this file
├── build/                                           ← live HTML5 export (what's running at the link above)
├── solstice-coffee-co-new-hire-onboarding.zip       ← SCORM package (for LMS import)
└── solstice-coffee-co-new-hire-on...zip             ← xAPI package (for LRS-compatible LMS import)
```

The SCORM and xAPI packages are provided as downloadable zip files rather than run directly from this repo, since they're built to be imported into a learning management system (or a tool like SCORM Cloud) rather than opened as a standalone webpage.
