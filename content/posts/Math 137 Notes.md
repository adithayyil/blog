---
title: Math 137 Notes
fileName: Math 137 Notes
tags:
  - math
categories:
  - notes
date: 2024-01-8
lastMod: 2024-01-10
math: true
ShowToc: true
Params:
  ShowReadingTime: true
---

# Lecture 1

- What is Mathematics?

  - A Language that describe the world around us

- Notional shorthand

  - $\forall$ -> for all

  - $\exists$ -> there exists

  - $\ni$ -> such that

  - $\therefore$ -> therefore

  - wlog -> without loss of generality

  - $\in$ -> is an element of

  - WSIC -> why should I care?

- ### Absolute Values

  - Here is the mathematical definition of absolute values:

    $$
    \lvert x \rvert =
    \begin{cases}
      x & \text{if } x \geq 0,\\
      -x & \text{if } x < 0
    \end{cases}
    $$

  - In words, $\lvert x \rvert$ is the distance of $x$ from 0, also known as its _magnitude/size_.

  - $\forall a,b \in \mathbb{R}$, the distance between $a$ and $b$ is given by $\lvert a - b \rvert = \lvert b - a \rvert$.

- ### Triangle Inequality

  - The sum of the lengths of any two sides of a triangle exceeds the length of the third.

  - **Theorem 1: The Triangle Inequality**

    - For $a, b, c \in \mathbb{R}$, we have:

    $$ \lvert a - b \rvert \leq \lvert a - c \rvert + \lvert c - b \rvert $$

  - Proof for 1D Case:

    - Since $\lvert a - b \rvert = \lvert b - a \rvert$, assume without loss of generality that $a < b$. Then, there are three possible cases for the value of $c$.

    - **Case 1: $c < a$**

      - $\lvert a - b \rvert < \lvert c - b \rvert$. Since $c \neq a$, we have $\lvert a - c \rvert > 0$.

      - Thus, $\lvert a - b \rvert < \lvert c - b \rvert + \lvert a - c \rvert$.

      - $\therefore \lvert a - b \rvert \leq \lvert c - b \rvert + \lvert a - c \rvert$.

    - **Case 2: $a \leq c \leq b$**

      - To be continued...
