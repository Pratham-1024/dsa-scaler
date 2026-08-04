# L1: Time Complexity

## Introduction

This class session primarily focuses on understanding Big O complexity and
exploring introductory problems in algorithm analysis. It's crucial to grasp
these foundational concepts to effectively tackle more complex
algorithm-related problems in the future.

## Agenda for Today

- **Power of Observation** — understanding the significance of observing
  patterns and structures within problems
- **Count of Factors** — a problem-focused exercise to understand factors
- **Sum of N Natural Numbers** — exploring the formulaic and observational
  approach
- **Geometric Progression (GP) and Sum of GP** — basic mathematical concepts
  relevant to algorithm efficiency
- **Iterations and Example Problems** — practical applications to
  demonstrate theoretical concepts
- **Comparing Two Algorithms** — understanding how to evaluate different
  algorithms
- **Introduction to Big O - Time Complexity** — key for evaluating
  algorithmic efficiency

## Concepts Covered

### 1. Power of Observation

The session started with emphasizing the ability to observe and recognize
patterns. This skill is instrumental in problem-solving and is not merely
limited to algorithm classes but is essential across disciplines.

### 2. Count of Factors

**Definition:** A factor of a number `N` is any integer `i` such that
`N % i == 0`. In this context, we explored programmatically determining if
`i` is a factor of `N` using the modulus operator.

**Example**

- **Problem Statement:** Given a number `N`, count the total number of
  factors.
- **Example Exercise:** Find all factors of 24 → `1, 2, 3, 4, 6, 8, 12, 24`

### 3. Sum of N Natural Numbers

The class discussed an efficient way to compute the sum of natural numbers
up to `N` using the formula:

$$S = \frac{N \times (N + 1)}{2}$$

**Historical Context:** The story of Gauss solving this problem by arranging
numbers in pairs to simplify the addition was shared, demonstrating a
systematic approach to problem-solving.

### 4. Geometric Progression and Sum of GP

**Formulas**

- **nth Term:** $A_n = A \times R^{\,n-1}$
- **Sum of GP:** $S_n = A \dfrac{R^n - 1}{R - 1}$ (provided $R \neq 1$)

### 5. Iterations and Examples

Introduced to basic loop constructs and their complexity analysis:

- **Iterations and Contributions** — understanding how each component of an
  algorithm contributes to overall complexity through examples

### 6. Comparing Two Algorithms

**Exercise**

A scenario was presented where algorithm efficiency is compared using
iterations.

- **Thought Exercise:** Given the same problem, determine which algorithm
  performs better in terms of efficiency and why.

### 7. Introduction to Big O - Time Complexity

Introduced Big O notation, a mathematical representation used to
qualitatively describe the complexity of an algorithm.

- **Example Discussion:** how to calculate complexity for different types
  of functions, e.g. constant, logarithmic, linear
- **Simplifying Assumptions:** ignore lower-order terms and constant
  coefficients in complexity expressions to emphasize scalability

## Conclusion and Next Steps

This session's foundational elements lay the groundwork for more advanced
concepts in future classes, such as bit manipulation and memory management
techniques. The emphasis on Big O notation prepares for in-depth algorithm
analysis and better performance evaluation in subsequent lessons.