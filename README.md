# dsa-scaler

A structured walkthrough of Scaler's DSA curriculum — organized by module and
lecture in the order I'm working through it. Each lecture is documented with
notes and the problems solved in that session.

## Structure

```
dsa-scaler/
├── 01-intro-to-problem-solving-1/
│   ├── L1-time-complexity/
│   │   ├── lecture-notes.md
│   │   └── problems/
│   │       ├── count_factors.py
│   │       └── sum_of_n_natural.py
│   ├── L2-intro-to-arrays/
│   │   ├── lecture-notes.md
│   │   └── problems/
│   └── ...
├── 02-intro-to-problem-solving-2/
│   └── ...
└── 03-advanced-dsa-1/
    └── ...
```

Modules are numbered in the order I'm working through them (not Scaler's own
module numbering, which is only used as a content reference). Each module
folder contains lecture folders (`L1`, `L2`, ...), and each lecture folder
has:

- `lecture-notes.md` — concepts, formulas, and key points from that session
- `problems/` — one Python file per problem solved in that lecture

## Problem file format

Each problem is a standalone `.py` file. The problem statement (paraphrased,
not copied verbatim), hints, and approach live in a docstring at the top of
the file, followed by the solution.

_(Exact docstring format still being finalized — will document here once
locked in.)_

## Why this repo exists

Built as part of a structured DSA practice routine while working through
Scaler's curriculum — a record of problems solved and concepts learned,
module by module, lecture by lecture.