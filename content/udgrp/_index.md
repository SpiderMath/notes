---
title: "Automata Theory"
toc: true
---

Welcome! You've found the home for our **Introduction to Automata Theory** materials. 

This undergraduate directed group reading project is part of the [UDGRP Summer 2026](https://mathclubisib.github.io) program.

## Project Details
*   **Host:** [Math Club, ISI Bengaluru Centre](#)
*   **Co-Leads:** [Daibik Barik](https://theikosb.github.io/) (BMath '26) & [Shankha Suvra Dam](https://spidermath.github.io/) (BMath '26)

## Prerequisites

No formal prerequisites. A basic understanding of graph theory, and mathematical logic may be helpful.

## Abstract

__I'll put this in later__

## References

- *Introduction to the Theory of Computation* by Michael Sipser
- *Introduction to Automata Theory, Languages, and Computation* by Hopcroft, Motwani and Ullman
- *Theory of Computation* by Michael Sipser, MIT OpenCourseWare
- *200 Problems on Languages, Automata and Computation* by Murlak, Niwinski, and Rytter

## Schedule

Meetings are held every _Tuesday_ 6 PM - 8 PM, and _(Friday/Saturday)_ 6 PM - 8 PM

## The Jewel Puzzle

Before diving into the formal theory, we like to start with nice motivating question. It does not require any formal background, and we'd highly recommend just playing around with it! 😁

> Imagine a strange lock with only two buttons: *A* and *B*.
> 
> The lock has a jewel that can glow in different colors. Initially, it glows *Red*. Every time you press a button, the color changes according to some fixed rules. For example, a rule could be:
> 
> > “If the jewel is Red and you press B, it turns Blue.”
> 
> The important part is that the lock has no memory other than its current color. It does not remember the whole sequence you typed, only the current state it is in.
> 
> Now suppose the jewel can glow in only *3 colors*.
> 
> 1. Can you design rules so that the jewel glows Green exactly when the number of A’s pressed is a multiple of 3?
> 2. Can you design rules so that the jewel glows Green exactly when the sequence never contains two consecutive A’s?
> 3. Now for the harder question: can you design such a system so that the jewel glows Green exactly when the number of A’s pressed is equal to the number of B’s pressed?
> 
> And if 3 colors are not enough, what if the jewel could glow in *1000 different colors*? Would that help?
> 
> If yes, explain how. If not, try to explain what feels fundamentally different about this condition.

## Materials

| Date | Led By | Topics Covered | Notes | Problem Set |
| :-: | :- | :--- | :--- | :---: |
| Friday, 22<sup>nd</sup> May 2026 | • Daibik Barik<br>• Shankha Suvra Dam | • Introduction<br>• Solution to the Jewel Puzzle<br>• What is a finite automaton?<br>• Definition of Regular Languages, DFA and Regular Operations<br>• Closure of Regular Operations | • [Daibik's Notes](/notes/pdf/udgrp/automata_theory/Daibik_lecture1.pdf)<br>• [Shankha's Notes](/notes/pdf/udgrp/automata_theory/Shankha_lecture1.pdf) | [Problem Set 1](/notes/pdf/udgrp/automata_theory/Problem_Set_1.pdf) |
| Tuesday, 26<sup>th</sup> May 2026 | Daibik Barik |  | [Notes](/notes/pdf/udgrp/automata_theory/lecture2.pdf) | __ |
| Saturday, 30<sup>th</sup> May 2026 | Shankha Suvra Dam | • Rigorously defining NFA<br>• Every DFA has an equivalent NFA and vice-versa <br>• Pumping Lemma for Regular Languages | To Be Uploaded | To be Uploaded |
