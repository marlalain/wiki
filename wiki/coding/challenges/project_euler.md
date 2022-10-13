---
title: Project Euler
description: Website dedicated to a series of computational problems intended to be solved with computer programs.
date: 2022-10-13
toc: true
---

Some explanations about the first hundred project euler's problems.

## [001](https://projecteuler.net/problem=1)

This is a simple one. It asks for the sum of all multiples of 3 or 5 below 1000. <br />
The number it asks is small enough that bruteforce will be quick enough to solve the problem on the website's time constraints.

##### Pseudocode Solution to Project Euler's 001 Problem
```text
sum = 0
for x in 0 to 1000:
  if x is divisible by 3 or 5:
    sum += x

print sum
```