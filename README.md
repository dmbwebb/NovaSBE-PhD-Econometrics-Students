# NovaSBE PhD Econometrics

Course materials for PhD Econometrics at Nova School of Business and Economics.

## Contents

- **lectures/** - Lecture slides (PDF)
- **readings/** - Required and recommended readings organized by lecture
- **syllabus/** - Course syllabus (Markdown and PDF)
- **assignments/** - Problem sets and data files

---

# Instructor

Duncan Webb is a development economist who uses tools and insights from behavioural economics. His current research focuses on discrimination, social change, and human capital. He has worked extensively on field randomized controlled trials in India, Madagascar, and Colombia.

Duncan is an Assistant Professor of Economics at [Nova School of Business and Economics](https://www.novasbe.unl.pt/en/). He recently spent a year as a postdoctoral researcher at Princeton University, completed his PhD at the Paris School of Economics in 2024, and spent 2022–23 as a visiting scholar at MIT. He is a [J-PAL](https://www.povertyactionlab.org/) Invited Researcher and a member of the [NOVAFRICA](https://novafrica.org/) group.

**Contact:** [dmbwebb@gmail.com](mailto:dmbwebb@gmail.com) | Office B115B | [www.duncan-webb.com](https://www.duncan-webb.com)

# Synopsis

This course provides a rigorous introduction to modern causal inference methods using the potential outcomes framework. Students will learn the theoretical foundations and practical implementation of the core identification strategies used in applied microeconomics: randomized experiments, instrumental variables, difference-in-differences, and regression discontinuity designs. The course emphasizes both formal derivations and hands-on empirical analysis.

# Course Overview

Credible causal inference is at the heart of modern empirical economics. Over the past three decades, the "credibility revolution" has transformed how economists approach empirical questions—moving from regression-based correlations to research designs that isolate causal effects under explicit and testable assumptions.

This course covers the essential toolkit for applied microeconomic research. We begin with the potential outcomes framework, which provides a unified language for thinking about causality. We then systematically work through the major identification strategies: randomized experiments, instrumental variables, difference-in-differences, and regression discontinuity designs.

For each method, we will:

- Develop the formal theory and derive key identification results
- Examine the assumptions required and when they might fail
- Study practical implementation and modern refinements
- Analyze published applications to see how the methods work in practice

## Topics

**Potential Outcomes and Randomization.** We introduce the Rubin causal model and the fundamental problem of causal inference. Randomized experiments provide the benchmark for causal identification. We cover design considerations including stratification, balance testing, clustered randomization, and power analysis. We also examine what happens when compliance is imperfect, introducing instrumental variables reasoning.

**Instrumental Variables.** IV methods identify causal effects when treatment is endogenous by exploiting exogenous variation in an instrument. We develop the theory rigorously, examining the exclusion restriction, relevance condition, and monotonicity. We focus on heterogeneous treatment effects and the Local Average Treatment Effect (LATE), and address practical concerns including weak instruments and finite-sample bias.

**Difference-in-Differences.** DiD exploits variation in treatment timing across groups to identify causal effects under a parallel trends assumption. We cover the canonical 2×2 case, two-way fixed effects regressions, and event study specifications. We examine recent developments in the literature on staggered adoption and heterogeneous treatment effects.

**Regression Discontinuity Design.** RDD identifies causal effects at a threshold where treatment assignment changes discontinuously. We cover both sharp and fuzzy designs, local polynomial estimation, bandwidth selection, and graphical presentation. We examine threats to validity including manipulation and covariate discontinuities.

**Empirical Tools.** We cover practical implementation issues across all methods, including standard error computation, multiple hypothesis testing, pre-analysis plans, and replication.

# Learning Objectives

Upon completion of this course, students should be able to:

**A. Knowledge and Understanding**

- Formally derive identification results under the potential outcomes framework
- Understand the assumptions underlying each identification strategy
- Recognize when methods are appropriate and when they may fail
- Interpret treatment effect parameters (ATE, ATT, LATE) correctly

**B. Subject-Specific Skills**

- Implement causal inference methods in statistical software (Stata/R/Python)
- Conduct specification tests and robustness checks
- Critically evaluate the identification strategy in published research

**C. General Skills**

- Communicate empirical findings clearly and precisely
- Write replicable code for empirical analysis

# Class Expectations

You are expected to prepare for class, attend, and participate actively.

## Preparation

The readings listed below are references for those who want to explore topics in more depth. The lectures are designed to be self-contained, so you do not need to complete readings before class. That said, if a particular topic interests you or you want additional perspective, the readings can be helpful.

## Attendance and Participation

Active participation is strongly encouraged and may affect your grade. I will ask questions during lectures and expect students to engage with the material. A key rule: laptops, iPads, and phones are not permitted in class except when explicitly needed for coding demonstrations. All slides will be posted after each lecture.

# Assessment

## Grading

| Component    | Weight |
| ------------ | ------ |
| Final exam   | 80%    |
| Problem sets | 20%    |

## Problem Sets

There will be 4 problem sets throughout the course, distributed during weeks 2–6. Problem sets must be completed individually.

**Deadline:** Tuesdays at 12:00 (noon)

**Submission instructions:**
- Submit to **dmbwebb@gmail.com**
- Include your name in the output
- Submit **.tex files**, **.pdf files**, AND **code files** (Stata .do, R .R, or Python .py)

Each problem set will contain two types of questions:

- **Applied/empirical**: These require you to analyze data, implement estimators, and interpret results using statistical software (Stata, R, or Python)
- **Mathematical/theoretical**: These require formal derivations, proofs, and analytical work

Both components are essential preparation for the exam and for applied research.

## Exam

One 1.5-hour closed-book exam covering all material from lectures. The exam will test both theoretical understanding (derivations, proofs) and applied reasoning (interpreting results, evaluating identification strategies).

## Late Policy

Late submissions will receive a grade of 0, except in cases of force majeure.

## AI Policy

Large language models like ChatGPT, Claude, and Gemini are now remarkably powerful tools. They are the best tools we have ever had for learning. But they are also the best tools we have ever had for avoiding learning.

Which you do is up to you. You may use AI assistants to help with problem sets, particularly for debugging code and understanding implementation. However, since 80% of your grade comes from a closed-book exam, AI will only help you if you use it in a way that deepens your understanding rather than substitutes for doing the work yourself.

Using AI to write your code without understanding what it does would be unwise. You will not get a good grade in this course if you do.

# Schedule

| Week | Topic                                | Problem Set |
| ---- | ------------------------------------ | ----------- |
| 1    | Potential Outcomes and Randomization |             |
| 2    | Instrumental Variables               | PS1 out     |
| 3    | Difference-in-Differences            | PS2 out     |
| 4    | Regression Discontinuity Design      | PS3 out     |
| 5–6  | Empirical Tools                      | PS4 out     |

# Software

Problem sets can be completed using Stata, R, or Python. Recommended packages:

- **Stata**: `rdrobust`, `did`, `eventstudyinteract`
- **R**: `rdrobust`, `did`, `fixest`, `HonestDiD`
- **Python**: `rdrobust`, `linearmodels`
