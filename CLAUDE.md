# Python Course — AE 444 Computer Programming

## Project Overview
This is a university-level Python course (AE 444) delivered as Jupyter notebooks (.ipynb).
The course targets engineering students who are newcomers to programming.
Notebooks are numbered 1–28+ and each covers a specific topic.

## Course Topic Order
1. Variables, Types
2. Math Operators
3. Printing & Inputting
4. Lists
5. Tuples
6. Booleans
7. Dictionaries
8. Indexing
9. Slicing
10. Functions Input/Output
11. NumPy
12. Pandas
13. Functions Help
14. Creating Functions
15. Global/Local Variable Scopes
16. Classes & OOP
17. If/Else
18. For Loops
19. Continue/Break
20. While Loops
21. Initializing Variables
22. Function Error Checking
23. Multiple Inputs with Zip
24. Single-line Loops (Comprehensions)
25. Broadcasting in NumPy
26. fprintf / f-strings
27. Plotting (dots & lines)
28. Subplots
Extras: For Loops, Lambda Functions, Variables (Clean English)

## Notebook Style Guide
Every notebook MUST follow this structure:

1. **Header** — course title (`# AE 444 - Computer Programming`) and topic subtitle
2. **Learning Goals** — bullet list of what students will be able to do
3. **Numbered Sections** — each concept gets its own `## N. Title` section with:
   - A short markdown explanation (2–5 sentences, beginner-friendly)
   - One or more code cells with commented examples
4. **Common Pitfalls** section (where applicable) — numbered list of mistakes and fixes
5. **Practice Tasks** — 2–5 hands-on exercises, increasing in difficulty
6. **Task Solutions** — in separate code cells below the tasks
7. **Mini-Quiz** (optional) — 3–5 quick-check questions with answers
8. **Wrap-Up** — 2–3 sentence summary of what was learned

## Writing Style Rules
- Use simple, clear English appropriate for non-native speakers
- Every code cell should have inline comments explaining what each line does
- Use `print()` to show results (don't rely on notebook auto-display)
- Use engineering/science-themed examples when possible (experiments, measurements, data)
- Refer back to earlier notebooks when using concepts from them (e.g., "We learned about lists in Notebook 4")
- Use emojis only in the top-level header (the rocket emoji)
- Variable names should use snake_case
- Keep code cells short (under 15 lines each)

## Enhancement Guidelines
When enhancing a notebook, add:
- **More detailed explanations** for each concept (analogies, visual descriptions)
- **Additional examples** showing edge cases and real-world usage
- **Comparison tables** (e.g., list vs tuple, `//` vs `/`)
- **More practice tasks** (aim for 3–5 tasks per notebook, easy to hard)
- **Common mistakes** section if missing
- **Cross-references** to related notebooks
- Do NOT remove existing content — only add to it
- Do NOT change the numbering of existing sections — add new sections after existing ones
- Keep solutions in separate cells from task descriptions

## Resources
- `Resources/` folder contains reference PDFs (NumPy exercises, Python built-in methods)

## Technical Notes
- Notebooks are Jupyter .ipynb format — use NotebookEdit tool to modify them
- Avoid `input()` in solution cells unless commented out (can hang in non-interactive environments)
- All notebooks should be runnable top-to-bottom without errors
