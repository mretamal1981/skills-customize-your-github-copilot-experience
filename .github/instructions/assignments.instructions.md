---
description: "Rules for creating and updating assignment markdown files so they match the project template and learning standards."
applyTo: "assignments/**/*.md"
---

# Assignment writing guidelines

Use this instruction set for any markdown file inside the assignments folder.

## Required structure

- Each assignment must live in a folder under `assignments/`
- The main file should be `README.md`
- Keep the heading structure aligned with the project template
- Include the following sections in order:
  - `# 📘 Assignment: [Title]`
  - `## 🎯 Objective
  - `## 📝 Tasks`
  - `### 🛠️ [Task Name]`
  - `#### Description`
  - `#### Requirements`

## Examples

```md
# 📘 Assignment: Python Basics

## 🎯 Objective

Practice basic Python concepts such as variables, input, and conditionals.

## 📝 Tasks

### 🛠️ User Input and String Formatting

#### Description
Write a program that asks for a name and prints a personalized greeting.

#### Requirements
- Use `input()` to collect user data
- Store the value in a variable
- Print a greeting message with the collected name
```

## Quality checks

- Do not use ad hoc sections that are not part of the template
- Keep wording student-friendly and task-focused
- Use measurable requirements and clear examples when needed
