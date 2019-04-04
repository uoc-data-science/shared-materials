![uzk_logo](../uzk.png)

# Programming Data Science

Presentation used by the instructor in week 1

Topic of the presentation: _Organization of the course, basic project management._

Learning objectives:

```text
> Students will learn,
- how the course is set up,
- how they are expected to work together,
- how they are expected to code.
```

## Organization

- Dates
  - See toc at bottom of the document
  - There is no formal "exam", hence no day for that
- Exam
  - You will submit a report that analyse a dataset. The reports will be written in RMarkdown and Jupyter.
  - Everything has to be finished and submitted at the end of the semester, usually last day of last week.
- Logistics of the course
  - Please leave your _ego at the door_. Knowing should always lead to teaching. Support your group, help others. Contribute.
  - The lecture consists of two sets of activities
  - (1) you will _learn_ to program for data science projects. This happens weekly, and according to a fixed schedule. Most of this is problem-based. 
  - (2) you will _apply_ your skills to a real dataset. We simulate project work in a data science firm. The instructor is the boss (sorry), working with several project leaders who are in turn leading their teams.
  - There is an artificial customer who is asking questions about the data. The customer is "scripted" and will do things.
  - The golden rule: `All programming is done in R and Python`
- Groups and project leaders
  - Please form groups of three
  - In each week, each group has a project leader
  - Project leader is responsible for finishing his/her part(s) of the report. Cannot do the work alone, team has to support.
  - You take turns: everybody will lead the group once or multiple times
- Tools and accounts
  - VScode is prefered for Python, but good alternatives available; VScode can partly produce Jupyter semi-automatically, which is good and speeds up the process of writing your report
  - Python >= 3.5 is required for grammar of graphics in Python
  - Rstudio is prefered for R, best for RMarkdown
  - Please register at GitHub
  - Learn basics of using Git and Github

- All materials will be distributed over GitHub; two repositories (as of now), one for teaching materials (read-only, fetch updates regularly), one for the project work (contains data, clone, then work on topic branches, raise pull request as submission)
- Groups work together on GitHub

## Programming-related basics

- Reproducibility
  - source control everything (exception: raw data, see below)
  - commenting and clean code
  - there are always two readers of your code: the current you, the future you
  - in Python: Pep8, in R similar
  - modes in R and Python (interactive, rMarkdown, source, Jupyter)
  - two modes used in this class: coding and reporting,
  - only your code is real, not the current environment
  - create environment through a pipeline
- good folder structure (example)
- use relative paths

## Data-related

- do not change the raw data, raw data is immutable
- raw data not under source control (exception)
- why? it does not change. it is too large
- tidy data: every row is an observation, every column a variable, each cell a value
- deliverable defines structure of tidy data, ie. observations, features and possible values
- define milestones such as tidy data to shorten time required for long workflows
- csv as universal format
- example: a single pipe from raw data to tidy, another one from tidy to report
- milestones define the structure of the pipe
- method chaining with milestone or end in mind

## Table of contents

| #   | Date  | Topic  |
| :---------: | :---- | :----- |
| 1  | 04.04.2019 | **Fundamentals** Organization, dates, groups, project leaders. Tools and accounts (VScode, GitHub, Git, Rstudio, ILIAS, Klips2).  Reproducibility: source control, commenting, modes (interactive, rMarkdown, source), two modes: coding and reporting, a pipe from raw data to report, good folder structure, use relative paths, only code is real - not environment, create env through a pipeline, .csv is universal format, tidy data, think with end in mind, result defines observations, features, values, method chaining, reports (Markdown, rMarkdown, Jupyter, Python) |
| 2  | 11.04.2019 | **What can computers learn from data?** Mapping questions to model classes, statements, and tests. The ladder of causality. |
| 3 | 25.04.2019 | **Visualizations (plots)**  Grammar of graphics |
| 4 | 02.05.2019 | **Coding 1** Data wrangling 1/2  + pipes|
| 5  | 09.05.2019 | **Coding 2** Data wrangline 2/2|  
| 6  | 16.05.2019 | **Tables** for descriptive statistics, regression results  |
| 7  | 23.05.2019 | **Comparisons** basic inference, tests, p-values, multiple comparisons  |
| 8  | 06.06.2019 | **Choosing the best model** Overfitting, bias-variance tradeoff, resampling schemes, choosing the best ML model, cross-validation, paired T-tests, training and evaluation errors |
| 9  | 27.06.2019 | **In-depth** linear regression  |
| 10 | 04.07.2019 | **In-depth** decision trees |
| 11 | 11.07.2019 | _Buffer_ |