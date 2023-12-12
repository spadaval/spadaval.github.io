---
title: Compiler
publishDate: 2019-10-02 00:00:00
img: /assets/smplc.png
img_alt: The control-flow graph generated for a simple bubble-sort algorithm. 
description: |
    I wrote a compiler that can translate a simplified language to a LLVM-like IR and generate control-flow graphs.
tags:
    - Compiler
    - Systems
    - Rust
badge: /assets/badge/uci.png
---
https://github.com/spadaval/smplc

This compiler takes in programs in SMPL (a made-up language) and produces control-flow graphs.

The whole compiler is written in Rust. The output is in graphviz (dot) format.