---
permalink: /projects/
title: "Projects"
author_profile: true
---

Selected unpublished projects and systems I have built.

## ProgCheck: Neuro-Symbolic Prolog Lab Assistant
[[Code](https://github.com/thuraaungjune/ProgCheck)]

A Prolog assignment checker with interactive visual debugging. ProgCheck combines a grammar-based syntax checker, a SWI-Prolog meta-interpreter that produces proof trees and execution traces, and a Shapiro-style algorithmic debugger that uses an LLM as the oracle. It then explains students' errors in natural language. A React web UI shows programs as a drag-and-drop knowledge graph and as a step-through backtracking tree, including paths pruned by cuts.

## Adaptive Traffic Signal Control with Prolog-based Multi-Agent Reasoning
[[Code](https://github.com/thuraaungjune/traffic-light-control-agent)] [[Demo](https://youtu.be/ondSEdPLgzc)]

A microscopic traffic simulation of a 4-way intersection using the Intelligent-Driver Model (IDM), controlled by a Prolog-based multi-agent decision system. The agents pick among 12 signal patterns based on queue lengths, turn-demand ratios, and flow rates from simulated inductive loop detectors. Simulation data is logged to ZODB and turned into HTML reports for analysis afterwards. Course project for Artificial Intelligence at KMITL, with Ei Myat Nwe and Nay Chi Shunn Lei.
