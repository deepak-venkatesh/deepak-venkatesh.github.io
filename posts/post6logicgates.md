---
title: Combinational Logic Gates
description: Building a Computer from the ground up
keywords: [Logic Gates, AND, OR, NAND, XOR, NOT, Transistors, PNP transistor, BJT, Solid State Physics, Silicon, N-Type, P-Type, Doping, Band Structure, PN Junction, Computer Architecture, First Principles, Logic Gates, Transistors, ALU, RAM, CPU, Memory, Machine Language, Assembly, Virtual Machine, High Level Language, Compiler, Interpreter, Nand to Tetris]
header-includes:
  - <link rel="icon" type="image/x-icon" href="../favicon.ico">
---

<header class="header">
  <a href="./post3.html" class="home-link">← back</a>
</header>

> _The invention of the transistor may be the most important invention of the 20th century._ - Gordon Moore

Starting from this section of my notepad on building a computer I can align each section with the Nand to Tetris Course. Actually I am using the book _The Elements of Computing Systems_ by the same professors. 

**Progress:** Completed Project 1 from the book. All material updated on my github [here](https://github.com/deepak-venkatesh/nand-to-tetris)

Some of the combinational logic gates I have built are documented below. 

## NOT Logic Gate
Also called the inverter simply converts a 0 to 1 and a 1 to 0. 

| IN | NOT |
|----|-----|
| 0  | 1   |
| 1  | 0   |

![](../assets/not_gate.jpeg){.responsive-img}
<center> <small>1 Bit Not Logic Gate Circuit</small> </center>

<div class="video-container video-landscape">
  <iframe
    src="https://www.youtube.com/embed/HKwXmZ-kiXQ"
    title="NOT Gate"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>

## AND Logic Gate
The truth table is below.

| A | B | AND |
|---|---|-----|
| 0 | 0 | 0   |
| 0 | 1 | 0   |
| 1 | 0 | 0   |
| 1 | 1 | 1   |

## OR Logic Gate
The truth table is below.

| A | B | OR |
|---|---|----|
| 0 | 0 | 0  |
| 0 | 1 | 1  |
| 1 | 0 | 1  |
| 1 | 1 | 1  |

## NOR Logic Gate
The truth table is below.

| A | B | NOR |
|---|---|-----|
| 0 | 0 | 1   |
| 0 | 1 | 0   |
| 1 | 0 | 0   |
| 1 | 1 | 0   |

## NAND Logic Gate
The truth table is below.

| A | B | NAND |
|---|---|------|
| 0 | 0 | 1    |
| 0 | 1 | 1    |
| 1 | 0 | 1    |
| 1 | 1 | 0    |

## XOR Logic Gate
The truth table is below. I used NAND gates to build the XOR gate.

| A | B | XOR |
|---|---|-----|
| 0 | 0 | 0   |
| 0 | 1 | 1   |
| 1 | 0 | 1   |
| 1 | 1 | 0   |


_Last Updated: 4 Oct 2026_

<footer class="footer">
  <a href="./post3.html" class="home-link">← back</a>
</footer>
