# dx's Probability Theory

## Preface

Probability theory is easy to misunderstand. At first glance it looks like a course about distributions, formulas, expectation, variance, and integrals. But the part that matters most is often not calculation itself. It is the judgment that comes before calculation: what is the sample space, what is the event, what is the condition, which quantity should be fixed first, and which object should be handled later.

This book is therefore not only a rearranged list of definitions and theorems. It keeps the path by which probability gradually became understandable to me. Many notes pause before applying a formula and ask a more basic question: what is this probability actually talking about?

## Why This Book Is Written This Way

The real difficulty in probability is often not that a computation is impossible, but that the problem has been read in the wrong space. Once the sample space, condition, and random object are identified correctly, many frightening formulas become natural.

The notes preserve many short practical tips because they train that habit: do not rush into computation, first identify the structure. Conditional probability, Bayes' rule, total probability, conditional distributions, and independence all become much clearer once this viewpoint is stable.

## What This Book Keeps

The main line starts from random events, probability axioms, conditional probability, and independence. It then moves to random variables, distribution functions, common discrete and continuous distributions, joint distributions, numerical characteristics, characteristic functions, the law of large numbers, and the central limit theorem.

The exercise and review files are not just appendices. They form a second route through the book: using concrete problems to make the most fragile probability judgments firm.

## Intended Readers

This book is for readers who understand lectures but feel lost when solving problems, and also for readers returning to probability while preparing for exams or rebuilding the subject. Its goal is to replace formula hunting with a clearer habit of asking what random structure the problem is describing.

## Overall Roadmap

Following the structure of MIT probability courses, the main line runs through sample spaces, probability axioms, conditional probability, Bayes' rule, random variables, common distributions, joint distributions, expectation and variance, the law of large numbers, and the central limit theorem. This tree matches the repository's notes on events and probability, random variables and distributions, numerical characteristics, characteristic functions, and limit theorems.

```

## Repository Notes

- The main entry is `main.tex`.
- The body is split into chapter files covering events and probability, random variables and distributions, numerical characteristics, characteristic functions, and limit theorems.
- Exercises and review materials are kept as separate TeX files.
- For local compilation, running `xelatex main.tex` twice is usually enough.
