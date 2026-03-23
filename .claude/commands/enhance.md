---
description: Enhance a Python course notebook with more details, examples, and tasks
allowed-tools: Read, NotebookEdit, Glob, Grep, Agent, AskUserQuestion
---

# Enhance Notebook: $ARGUMENTS

You are enhancing a Jupyter notebook from the AE 444 Python course. The goal is to make it more comprehensive for engineering students learning Python.

## Instructions

1. **Read the notebook** specified by the user argument (match by number or topic name from the .ipynb files in the project root).

2. **Analyze gaps** — compare the current content against what a thorough lesson should cover:
   - Are there enough examples for each concept? (aim for 2–3 per section)
   - Are edge cases and common mistakes covered?
   - Are there enough practice tasks? (aim for 3–5, easy → hard)
   - Are explanations beginner-friendly with analogies or visual descriptions?
   - Are there cross-references to related notebooks?

3. **Present a detailed enhancement plan to the user** listing exactly what you propose to add, section by section. For example:
   - Section 2: Add an analogy comparing lists to...
   - New Section 6: Common Pitfalls — cover X, Y, Z
   - New Task 3: Exercise about...
   - Add Mini-Quiz with 4 questions

   **WAIT for user approval before making any changes.** The user may accept the full plan, ask for modifications, or reject parts of it. Only proceed with the changes the user approves.

4. **Enhance the notebook** by adding (never removing existing content):
   - **Richer explanations**: Add analogies, "think of it like..." descriptions, or comparison tables
   - **More code examples**: Show edge cases, alternative approaches, what happens when things go wrong
   - **Common Pitfalls section**: If missing, add one with numbered mistakes and fixes
   - **Additional Practice Tasks**: Add tasks that build in difficulty; use engineering/science themes
   - **Task Solutions**: In separate cells below tasks
   - **Mini-Quiz**: If missing, add 3–5 quick-check questions with answers
   - **Cross-references**: Link to earlier/later notebooks where relevant

4. **Follow the style guide** from CLAUDE.md:
   - Simple English for non-native speakers
   - Inline comments in all code cells
   - `print()` for all outputs
   - snake_case variable names
   - Engineering/science-themed examples where possible
   - Keep code cells under 15 lines

6. **Present a summary** of what was added when done.

## Important
- Do NOT delete or reorder existing cells
- Add new cells AFTER relevant existing sections
- Keep `input()` calls commented out in solution cells
- Ensure the notebook runs top-to-bottom without errors
