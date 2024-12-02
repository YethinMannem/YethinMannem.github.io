---
name: Mips Assembly Instructions Simulator
tools: [C++, QTspim, MIPS, Tkinter, Multi-threading]
image: https://figures.semanticscholar.org/0b27b9683f9208b4c451c75b923c0b36a8b27b15/2-Figure1-1.png
description: Simulating the assembly instructions compiled and generating output - also involved optimising via instruction pipelining in MIPS architecture.
---

# Mips Assembly Instructions Simulator

This project was a part of course Computer Organisation, it was done in three phases:

Parsing assembly code, executing instructions one by one to generate correct ouput.
Optimising this simulator to distribute instructions in 5 phases as per MIPS arch. and execute in pipelined fashion while using latches to transfer data between pipeline.
Implementing a two level cache with configurable cache size, associativity and block size.
To generate how the pipeline looked like and where did the stalls occur we generate excel file with visualisation something like this.



We(me and my team mate) also implemented an interface which is similar to QtSpim(simulator in market to run MIPS code). This was done with the help of Tkinter in python. This is how our cache finally looks like in GUI once the programs finishes execution.


As an optional adventure we went out to write multi-threaded program for simulating the pipeline model to execute instructions parallelly.

This was interesting as it produced correct output less frequently or sometimes halting with error. After studying about threads in Operating Systems course the folowing year it finally became clear as to why our program wasn’t thread safe as we hadn’t used mutex to protect data and also didn’t sync the instructions well. I believe it’s an art to write concurrent multi-threaded programs with validity and determinism.

<p class="text-center">
{% include elements/button.html link="https://github.com/YethinMannem/mips-yethin-pavan" text="Github Repo" %}
</p>