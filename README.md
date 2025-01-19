# Hive Helsinki - My Overview

A summary of my programming experience as part of the studies at 42-network's Hive Helsinki

---

## Table of Contents

- [General Guidelines](#general-guidelines)
- [Projects](#projects)

---

## General Guidelines

- To finish a project, a student needs to pass multiple successful code reviews by peers. The evaluatee needs to be able to explain their code and "defend" why it's valid (if it is) - since students have varying levels of perfectionism and there's _some_ subjectivity to software engineering, we often defer to (and discuss) the wording of the assignment in evaluations.
- For all projecting using the C programming language, we were required to follow the "Norm": A set of code style rules (e.g. no for loops or switch or ternary statements, maximum of 25 lines per function, maximum of 80 characters per line), linting rules (e.g. no unused library inclusions), and other guidelines (e.g. maximum of 5 variable declarations per function and 4 function parameters, no assignment in the same line as declaration except consts or statics)

---

## Projects

| Name            | Topic                                                                  | Score |
| --------------- | ---------------------------------------------------------------------- | ----- |
| `libft`         | Utility functions library                                              | 125   |
| `ft_printf`     | Variadic function for printing string templates with value conversions | 100   |
| `get_next_line` | Buffer-based file reading - single line per function call              | 125   |
| `born2beroot`   | VM (virtual machine) security & monitoring configuration               | 100   |
| `push_swap`     | Sorting lists with a specific and limited set of operations            | 88    |
| `so_long`       | Simple 2D game using minimal windowing/graphics library (MLX42)        |       |

#### Extras

| Name         | Topic                                                     |
| ------------ | --------------------------------------------------------- |
| `libft_full` | Combination of `libft`, `ft_printf`, and `get_next_line`. |
