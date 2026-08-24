# Learn Python for Data Work

This repository is a guided Python learning path. Start with the main lesson, then complete the weekly practice notebooks in order.

## Prerequisite

You need:

- A Databricks Free Edition account.
- GitHub enabled and connected in Databricks.
- A GitHub account.
- Basic familiarity with opening notebooks and running cells.

## Getting Started

### 1. Fork this repository

Open this repository on GitHub and select **Fork**. Create the fork under your own GitHub account. You should do your work in your fork so that you can save your progress without changing the original repository.

### 2. Clone your fork into Databricks

1. Sign in to Databricks Free Edition.
2. Open the workspace and choose **Workspace**.
3. Select **Git folders** or the option to add a Git folder.
4. Choose GitHub as the Git provider.
5. Paste the URL of your fork, not the URL of the original repository.
6. Sign in or authorize GitHub if Databricks asks you to do so.
7. Choose a workspace location and clone the repository.

After cloning, you should see `intro2python.ipynb`, `week1.ipynb`, `week2.ipynb`, `week3.ipynb`, `week4.ipynb`, and `week5.ipynb` in Databricks.

## Recommended Learning Order

### First: Complete `intro2python.ipynb`

Read every Markdown cell and run the code cells from top to bottom. Do not only copy the code and move on. Pause after each example and make sure you understand:

- Basic data types such as integers, floats, strings, and booleans.
- Lists, tuples, sets, and dictionaries.
- How a `for` loop visits each item in a list.
- How an `if` statement makes a decision.
- What `assert` checks and why it is useful for testing an expected result.
- How a simple function can be reused.

Change small values in the examples, predict the output, and run the cell again. This is one of the best ways to connect the code with its result.

### Then: Complete the weekly notebooks

Work through the notebooks in this order:

1. `week1.ipynb`: Super-easy practice with individual values, collections, conditions, loops, and functions.
2. `week2.ipynb`: Easy exercises with small calculations and simple transformations.
3. `week3.ipynb`: Intermediate exercises with multiple records and reusable functions.
4. `week4.ipynb`: More challenging validation and data-processing tasks.
5. `week5.ipynb`: Advanced, production-style practice using complete pipeline ideas.

Read each question carefully and write your solution in the answer cell. Try the problem yourself before looking back at the lesson or searching for help. Run your answer, inspect the output, and correct any errors.

## Commit Your Progress Every Week

When you finish and review a weekly notebook:

1. Save the notebook in Databricks.
2. Open the Git changes or Git folder controls.
3. Review the changed files and confirm that your work is included.
4. Write a useful commit message, such as `Complete Week 1 Python basics`.
5. Commit and push the changes to your fork on GitHub.

Commit after each week rather than waiting until the end. This gives you a clear learning history, protects your work, and lets you return to an earlier version when you want to compare solutions.

## How to Get the Most From This Repository

- Study regularly in short sessions instead of completing everything in one sitting.
- Before running a cell, predict what it will print.
- After running it, explain why the output appeared.
- Change one value or one line at a time and observe what changes.
- Use `print()` to inspect variables while learning.
- Use `assert` to check simple expectations, for example `assert total == 10`.
- Keep your own notes in Markdown cells or in a separate study document.
- When an error appears, read the last line first, then find the line number Python reports.
- Re-solve exercises without looking at your first answer after a few days.
- Use the weekly commit history as a record of what you have learned.

The goal is not just to make a notebook run. The goal is to understand each step well enough to explain it and use the same idea with new data.