---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multivariable Calculus Cheatsheet"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-09-03T21:00:39-04:00
lastmod: 2020-09-03T21:00:39-04:00
featured: false
draft: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
This multivariable calculus cheathsheet was used for elective math class at Marianopolis College. PDF version is also available.

Sequences:
- a sequence $$a_{1}, a_{2}, a_{3}, a_{4}, a_{5}, ... \\{a_{n}\\}_{n=1}^{\infty},$$ 
has a limit if $\lim _{n \rightarrow \infty} a_{n}=L$ exists and is a finite calculation of the limit of a sequence, upper and lower bounds and whether or not increasing or decreasing.
- an increasing (decreasing) sequence which is bounded abouve (below) has a limit
- **A bounded monotone sequence is convergent**

Series:
- infinite series: $$
\sum_{n=1}^{\infty} a_{n}=a_{1}+a_{2}+a_{3}+a_{4}+a_{5}+\ldots
$$
where the **sequence of partial sums** $ s_1, s_2, s_3, s_4, s_5, ...$ is $s_n = \sum_{k=1}^n a_k$.
The series $\sum_{n=1}^{\infty} a_{n}$ converges to a sum $s$ if the limit of the partial sums $\lim _{n \rightarrow \infty} s_{n}=s$ exists and is finite.

- geometric series: $$\sum_{n=0}^{\infty} a r^{n}= a + ar + ar^2 + ar^3 + ..$$ partial sum formula: $s_n = \frac{a(1-r^n)}{1-r}$, infinite sum formula $s=\frac{a}{1-r}$ if $|r|<1$

- The following tests can be used for determining convergence or divergence of a series $\sum_{n=1}^{\infty} a_{n}$:
    1. $n^{th}$ Term test
    2. Integral test
    3. Root test
    4. Comparison test
    5. p-Test
    6. Alternating Series test
    7. Limit Comparison test
    8. Ratio test

- absolute convergence implies convergence of a series

Power Series:
 - **interval of covergence** of a power series including end points
 - **power series** of basic functions $e$
