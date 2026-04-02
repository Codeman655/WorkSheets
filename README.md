# Worksheet Generator

A lightweight, single-page web application designed for parents and teachers to quickly generate randomly populated educational worksheets for Kindergarten through 2nd Grade.

## Features

- **Math Practice**: Generates addition and subtraction problems.
  - *Kindergarten*: Numbers 1-10.
  - *1st Grade*: Numbers 1-20.
  - *2nd Grade*: Numbers 1-100.
- **Counting Assignments**: Visual counting exercises using various symbols (stars, hearts, etc.) to help children develop one-to-one correspondence.
- **Bipartite Matching**: A logic and literacy exercise where students match words to their character lengths.
- **Reading Assignments**: Short, grade-appropriate passages followed by comprehension questions and writing lines.
- **Print-Ready Design**: The application uses custom CSS to ensure that when printing (Ctrl+P / Cmd+P), only the worksheet content is visible. All UI buttons and background styling are automatically hidden.

## How to Use

1. **Configure**: Select the assignment type, grade level, and (where applicable) the number of questions.
2. **Generate**: Click the "Generate Worksheet" button to create a unique version of the assignment.
3. **Print**: Use your browser's print function. The layout is optimized for standard A4 or Letter paper.
4. **Navigate**: Use the floating "Back" button in the bottom-right corner to return to the generator and create a new set.

## Technical Details

- **Framework**: Built with React 18 (via CDN for zero-setup portability).
- **Styling**: Vanilla CSS with a focus on print-media optimization.
- **Portability**: The entire application is contained within a single `index.html` file, making it easy to share or run offline.

---
*Created for quick, on-the-fly educational resource generation.*
