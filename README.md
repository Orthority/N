# NMCN cbt format

This repository contains a JavaScript object that provides a framework for NMCN exams. The quiz is designed to test knowledge on various aspects related of nursing practice.

## Quiz Structure

The quiz is structured as a JavaScript object with questions. Each question includes:

- **ID**: Unique identifier for the question.
- **Question**: The text of the question.
- **Options**: Array of options presented as objects with keys like `a`, `b`, `c`, etc.
- **Answer**: Correct answer to the question.
- **Score**: Initial score set to 0 for tracking purposes.
- **Status**: Initially empty, can be used to mark if the question has been answered or reviewed.

