---
title: "Automata Theory"
toc: true
math: true
---

Welcome! You've found the home for our **Introduction to Automata Theory** materials. 

This undergraduate directed group reading project is part of the [UDGRP Summer 2026](https://mathclubisib.github.io) program.

## Project Details
*   **Host:** [Math Club, ISI Bengaluru Centre](#)
*   **Co-Leads:** [Daibik Barik](https://theikosb.github.io/) (BMath '26) & [Shankha Suvra Dam](https://spidermath.github.io/) (BMath '26)

## Prerequisites

No formal prerequisites. A basic understanding of graph theory, and mathematical logic may be helpful.

## Abstract

Automata theory is, at its heart, about understanding how simple machines can process information. It starts with a natural question: if we give a machine a fixed set of rules and only limited memory, what kinds of patterns can it recognize, and what is beyond its reach?

These machines can be viewed as state-based systems, almost like directed graphs, that read strings and decide whether they satisfy certain properties. Even very simple ones can detect patterns such as whether a binary string contains “11” or has an even number of zeroes. More generally, many problems can be reframed as membership questions: for example, checking whether a number is prime can be seen as asking whether its binary representation belongs to the set of all primes, such as \(\{10, 11, 101, \dots \}\). 

In this project, we will build this idea gradually, moving from simple models to more expressive ones while understanding both what they can do and where they fail. Along the way, we will meet finite automata, regular languages, context-free grammars, pushdown automata, and
Turing machines.

## References

- *Introduction to the Theory of Computation* by Michael Sipser
- *Introduction to Automata Theory, Languages, and Computation* by Hopcroft, Motwani and Ullman
- *Theory of Computation* by Michael Sipser, MIT OpenCourseWare
- *200 Problems on Languages, Automata and Computation* by Murlak, Niwinski, and Rytter

## Schedule

Meetings are held every _Tuesday_ 6 PM - 8 PM, and _(Friday/Saturday)_ 6 PM - 8 PM, as discussed in the WhatsApp group.

## The Jewel Puzzle

Before diving into the formal theory, we like to start with nice motivating question. It does not require any formal background, and we'd highly recommend just playing around with it! 😁

--- 

Imagine a strange lock with only two buttons: *A* and *B*.

The lock has a jewel that can glow in different colors. Initially, it glows *Red*. Every time you press a button, the color changes according to some fixed rules. For example, a rule could be:

“If the jewel is Red and you press B, it turns Green.”

The important part is that the lock has no memory other than its current color. It does not remember the whole sequence you typed, only the current state it is in.

Now suppose the jewel can glow in only *3 colors*.

1. Can you design rules so that the jewel glows Green exactly when the number of A’s pressed is a multiple of 3?
2. Can you design rules so that the jewel glows Green exactly when the sequence never contains two consecutive A’s?
3. Now for the harder question: can you design such a system so that the jewel glows Green exactly when the number of A’s pressed is equal to the number of B’s pressed? And if 3 colors are not enough, what if the jewel could glow in *1000 different colors*? Would that help?

If yes, explain how. If not, try to explain what feels fundamentally different about this condition.

## Materials

| Date | Led By | Topics Covered | Notes | Problem Set |
| :-: | :- | :--- | :--- | :---: |
| Friday, 22<sup>nd</sup> May 2026 | • Daibik Barik<br>• Shankha Suvra Dam | • Introduction<br>• Solution to the Jewel Puzzle<br>• What is a finite automaton?<br>• Definition of Regular Languages, DFA and Regular Operations<br>• Closure of Regular Operations | • [Daibik's Notes](/notes/pdf/udgrp/automata_theory/Daibik_lecture1.pdf)<br>• [Shankha's Notes](/notes/pdf/udgrp/automata_theory/Shankha_lecture1.pdf) | [Problem Set 1](/notes/pdf/udgrp/automata_theory/Problem_Set_1.pdf) |
| Tuesday, 26<sup>th</sup> May 2026 | Daibik Barik |  | [Notes](/notes/pdf/udgrp/automata_theory/lecture2.pdf) | __ |
| Saturday, 30<sup>th</sup> May 2026 | Shankha Suvra Dam | • Rigorously defining NFA<br>• Every DFA has an equivalent NFA and vice-versa <br>• Pumping Lemma for Regular Languages | To Be Uploaded | To be Uploaded |
| Tuesday, 2<sup>nd</sup> June 2026 | __ | Problem Set 2, combining questions on topics from both lectures | __ | [Problem Set 2](/notes/pdf/udgrp/automata_theory/Problem_Set_2.pdf) |
| Thursday, 4<sup>th</sup> June 2026 | Daibik Barik | I'm too lazy mannnn | [Notes](/notes/pdf/udgrp/automata_theory/lecture4.pdf) | __ |
| Monday or Tuesday, 8 or 9 June 2026 | Shankha Suvra Dam | __ | __ | __ |
| Tuesday, 9 June 2026 | __ | Problem Set 3, combining questions on topics from both lectures | __ | [*wait for it*] |
