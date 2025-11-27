---
title: Building a Computer
description: Building a Computer from the ground up
keywords: [Computer Architecture, First Principles, Logic Gates, Transistors, ALU, RAM, CPU, Memory, Machine Language, Assembly, Virtual Machine, High Level Language, Compiler, Interpreter, Nand to Tetris]
header-includes:
  - <link rel="icon" type="image/x-icon" href="../favicon.ico">
---

<header class="header">
  <a href="../index.html" class="home-link">← home</a>
</header>

> _What I hear, I forget; What I see, I remember; What I do, I Understand._ - Confucius


One of the most famous programming books 'The C Programming Language' by Kernighan and Ritchie starts with the following few lines.

'The only way to learn a new programming language is by writing programs in it. The first program to write is the same for all languages: Print the words'

```
hello, world
```

'This is the big hurdle, to leap over it you have to be able to create the program text somewhere, compile it successfully, load it, and find out where your output went. With these _mechanical details_ mastered, everything else is comparatively easy.'

'In C, the program to print "hello, world" is'

```
#include <stdio.h>

main ()
{
    printf("hello, world\n");
}
```

## Mechanical Details
What do Kernighan and Ritchie mean by _mechanical_ details? What does a compiler do? How does it read the text in the C code above? Then how does it tell the CPU in the computer to print 'hello, world'. How does the CPU execute these instructions? Where are the 0s and 1s? How are these binary states held? What science allows these binary states? ..... It is a rabbit hole. The only way to learn what a computer is by building one.

I am inspired by a few projects online where an 8 bit computer is constructed on breadboards but what really motivated me is the book 'The Elements of Computing Systems' (2nd ed.) by Noam Nisan and Shimon Schocken. They have wonderful content on their website called [Nand to Tetris](https://www.nand2tetris.org/). 

In this project, which I expect to last many months perhaps years I intend to build a computer in real hardware just like the Nand to Tetris book does but in a simulated environment. I honestly do not have the specifics as I type this at the start here but have two approaches in mind. First, use Integrated Circuits (ICs) such as SN7400 chips or the other being use NPN transistors such as 2N3904. With the ICs I can aim for an 8 bit computer maybe even a 16 bit computer that would be a real challenge but with the transistors a 4 bit computer is more realistic. Currently I am undecided. Second, I will build the computer exactly as mentioned in the Nand to Tetris book in software so my learning is complete.

In Summary:\
1. Hardware:\
    - Option 1: Use Transistors NPN 2N3904 to build a 4 bit computer (realistic goal)\
    - Option 2: Use IC SN7400 to build an 8 bit computer (realistic goal)\

2. A 16 bit computer in a simulated software environment

## Abstraction
The key principle with which I will be working with is that when I have built a certain piece of hardware and move on to the next step I will not focus on how the layer beneath works. I would have extracted away that underlying layer. It is valid even for theoretical physics concepts where we hold some axioms as true and work with that. 

## Progress
This will be the list of posts of every step in building this computer. I will be updating this as and when I complete a section.

1. [Particle Physics](./post3particle.html)

2. Solid State Physics

3. Transistors

4. Logic Gates



<footer class="footer">
  <a href="../index.html" class="home-link">← home</a>
</footer>
