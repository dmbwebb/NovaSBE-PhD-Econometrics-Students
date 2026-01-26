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

# NOVA Course Details

## Course Unit Aims

The primary objective is to train students to be critical consumers and producers of empirical research in economics. Students will develop both the theoretical understanding to evaluate identification strategies and the practical skills to implement them. The course prepares students for applied research in any field of economics.

## Course Unit Content

The course covers the core identification strategies in applied microeconometrics. We begin with the potential outcomes framework and randomized experiments as the benchmark for causal inference. We then study instrumental variables, focusing on heterogeneous effects and the LATE interpretation. Difference-in-differences methods are covered including recent advances for staggered designs. Finally, regression discontinuity designs are examined with emphasis on estimation, inference, and validity tests.

## Learning Objectives

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

## Demonstration of Coherence: Syllabus with Course Unit Aims

The syllabus systematically covers the identification strategies most commonly used in applied economics research. The combination of theoretical derivations and empirical implementation prepares students for both academic research and policy analysis.

## Teaching and Learning Methods

There will be one 3-hour class per week. Classes combine lectures on theory with interactive discussion of applications and implementation. Student participation is strongly encouraged throughout.

## Demonstration of Coherence: Teaching Methods with Learning Objectives

The weekly classes develop theoretical foundations through formal derivations while reinforcing understanding through discussion of applications. Problem sets provide hands-on experience with both mathematical derivations and empirical implementation.

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
| 5–6 | Empirical Tools                      | PS4 out     |

---

# Readings

## Lecture 1: Potential Outcomes and Randomization

#### Required

- **Holland (1986)** "Statistics and Causal Inference." *JASA* 81(396), 945-960.
- **Angrist & Pischke (2010)** "The Credibility Revolution in Empirical Economics." *JEP* 24(2), 3-30.
- **Imbens & Rubin (2015)** *Causal Inference for Statistics, Social, and Biomedical Sciences*, Chapters 1, 3-4.

#### Recommended

- **Imbens (2020)** "Potential Outcome and Directed Acyclic Graph Approaches to Causality." *JEL* 58(4), 1129-1179.
- **Deaton (2010)** "Instruments, Randomization, and Learning about Development." *JEL* 48(2), 424-455.
- **Imbens (2010)** "Better LATE Than Nothing: Some Comments on Deaton (2009) and Heckman and Urzua (2009)." *JEL* 48(2), 399-423.
- **Leamer (1983)** "Let's Take the Con out of Econometrics." *AER* 73(1), 31-43.

#### Applications

- **Krueger (1999)** "Experimental Estimates of Education Production Functions." *QJE* 114(2), 497-532.
- **Miguel & Kremer (2004)** "Worms: Identifying Impacts on Education and Health in the Presence of Treatment Externalities." *Econometrica* 72(1), 159-217.
- **Egger et al. (2022)** "General Equilibrium Effects of Cash Transfers." *Econometrica* 90(6), 2603-2643.

## Lecture 2: Instrumental Variables

#### Core

- **Imbens & Angrist (1994)** "Identification and Estimation of Local Average Treatment Effects." *Econometrica* 62(2), 467-475.
- **Angrist, Imbens & Rubin (1996)** "Identification of Causal Effects Using Instrumental Variables." *JASA* 91(434), 444-455.
- **Andrews, Stock & Sun (2019)** "Weak Instruments in Instrumental Variables Regression: Theory and Practice." *Annual Review of Economics* 11, 727-753.

#### Recommended

- **Angrist & Krueger (1991)** "Does Compulsory School Attendance Affect Schooling and Earnings?" *QJE* 106(4), 979-1014.
- **Bound, Jaeger & Baker (1995)** "Problems with Instrumental Variables Estimation When the Correlation Between the Instruments and the Endogenous Explanatory Variable is Weak." *JASA* 90(430), 443-450.
- **Stock & Yogo (2005)** "Testing for Weak Instruments in Linear IV Regression." In *Identification and Inference for Econometric Models*, Cambridge University Press.
- **Heckman (1997)** "Instrumental Variables: A Study of Implicit Behavioral Assumptions Used in Making Program Evaluations." *Journal of Human Resources* 32(3), 441-462.

#### Applications

- **Angrist (1990)** "Lifetime Earnings and the Vietnam Era Draft Lottery: Evidence from Social Security Administrative Records." *AER* 80(3), 313-336.
- **Angrist & Evans (1998)** "Children and Their Parents' Labor Supply: Evidence from Exogenous Variation in Family Size." *AER* 88(3), 450-477.
- **Sarsons (2015)** "Rainfall and Conflict: A Cautionary Tale." *Journal of Development Economics* 115, 62-72.
- **Acemoglu, Johnson & Robinson (2001)** "The Colonial Origins of Comparative Development: An Empirical Investigation." *AER* 91(5), 1369-1401.

## Lecture 3: Difference-in-Differences

#### Core

- **Roth, Sant'Anna, Bilinski & Poe (2023)** "What's Trending in Difference-in-Differences? A Synthesis of the Recent Econometrics Literature." *Journal of Econometrics* 235(2), 2218-2244.
- **Goodman-Bacon (2021)** "Difference-in-Differences with Variation in Treatment Timing." *Journal of Econometrics* 225(2), 254-277.
- **Callaway & Sant'Anna (2021)** "Difference-in-Differences with Multiple Time Periods." *Journal of Econometrics* 225(2), 200-230.

#### Recommended

- **de Chaisemartin & D'Haultfoeuille (2020)** "Two-Way Fixed Effects Estimators with Heterogeneous Treatment Effects." *AER* 110(9), 2964-2996.
- **Sun & Abraham (2021)** "Estimating Dynamic Treatment Effects in Event Studies with Heterogeneous Treatment Effects." *Journal of Econometrics* 225(2), 175-199.
- **Rambachan & Roth (2023)** "A More Credible Approach to Parallel Trends." *Review of Economic Studies* 90(5), 2555-2591.
- **Bertrand, Duflo & Mullainathan (2004)** "How Much Should We Trust Differences-in-Differences Estimates?" *QJE* 119(1), 249-275.

#### Synthetic Control

- **Abadie, Diamond & Hainmueller (2010)** "Synthetic Control Methods for Comparative Case Studies." *JASA* 105(490), 493-505.
- **Arkhangelsky, Athey, Hirshberg, Imbens & Wager (2021)** "Synthetic Difference-in-Differences." *AER* 111(12), 4088-4118.

#### Applications

- **Card & Krueger (1994)** "Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania." *AER* 84(4), 772-793.

## Lecture 4: Regression Discontinuity Design

#### Core

- **Cattaneo, Idrobo & Titiunik (2020)** *A Practical Introduction to Regression Discontinuity Designs: Foundations*. Cambridge Elements.
- **Calonico, Cattaneo & Titiunik (2014)** "Robust Nonparametric Confidence Intervals for Regression-Discontinuity Designs." *Econometrica* 82(6), 2295-2326.
- **Hahn, Todd & Van der Klaauw (2001)** "Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design." *Econometrica* 69(1), 201-209.

#### Recommended

- **McCrary (2008)** "Manipulation of the Running Variable in the Regression Discontinuity Design: A Density Test." *Journal of Econometrics* 142(2), 698-714.
- **Gelman & Imbens (2019)** "Why High-Order Polynomials Should Not Be Used in Regression Discontinuity Designs." *Journal of Business & Economic Statistics* 37(3), 447-456.
- **Kolesar & Rothe (2018)** "Inference in Regression Discontinuity Designs with a Discrete Running Variable." *AER* 108(8), 2277-2304.
- **Gerard, Rokkanen & Rothe (2020)** "Bounds on Treatment Effects in Regression Discontinuity Designs with a Manipulated Running Variable." *Quantitative Economics* 11(3), 839-870.

#### Applications

- **Lee (2008)** "Randomized Experiments from Non-random Selection in U.S. House Elections." *Journal of Econometrics* 142(2), 675-697.
- **Card, Lee, Pei & Weber (2015)** "Inference on Causal Effects in a Generalized Regression Kink Design." *Econometrica* 83(6), 2453-2483.

## Lecture 5: Challenges and Tools in Empirical Work

#### Core

- **Athey & Imbens (2017)** "The State of Applied Econometrics: Causality and Policy Evaluation." *JEP* 31(2), 3-32.
- **Lee (2009)** "Training, Wages, and Sample Selection: Estimating Sharp Bounds on Treatment Effects." *Review of Economic Studies* 76(3), 1071-1102.
- **Benjamini & Hochberg (1995)** "Controlling the False Discovery Rate: A Practical and Powerful Approach to Multiple Testing." *JRSS Series B* 57(1), 289-300.

#### Heterogeneous Treatment Effects

- **Athey & Imbens (2016)** "Recursive Partitioning for Heterogeneous Causal Effects." *PNAS* 113(27), 7353-7360.
- **Chernozhukov, Demirer, Duflo & Fernández-Val (2020)** "Generic Machine Learning Inference on Heterogeneous Treatment Effects in Randomized Experiments." *NBER Working Paper* 24678.

#### Inference and Standard Errors

- **Abadie, Athey, Imbens & Wooldridge (2023)** "When Should You Adjust Standard Errors for Clustering?" *QJE* 138(1), 1-35.
- **Belloni, Chernozhukov & Hansen (2014)** "Inference on Treatment Effects after Selection among High-Dimensional Controls." *Review of Economic Studies* 81(2), 608-650.

#### Bounds and Partial Identification

- **Manski (1990)** "Nonparametric Bounds on Treatment Effects." *AER P&P* 80(2), 319-323.

#### Spillovers

- **Borusyak & Hull (2023)** "Non-Random Exposure to Exogenous Shocks." *Econometrica* 91(6), 2155-2185.
- **Miguel & Kremer (2004)** "Worms: Identifying Impacts on Education and Health in the Presence of Treatment Externalities." *Econometrica* 72(1), 159-217.
