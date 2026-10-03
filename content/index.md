---
title: Home
cssclasses: [landing-page]
---

## Hello World!!

<p>Welcome to my digital space.</p>

<p>I'm Vismay Raj, currently working as a Senior Compiler Engineer at Imagination Technologies.
    I completed my Undergraduate studies at Indian Institute of Technology Palakkad.</p>
<p>My interests span Compilers, Codegen, Functional programming, Formal verification, Databases,
    and Low-Level programming. I'm familiar with languages such as Rust, Haskell, C++/C, Python, Zig, and Scala. </p>
<p>In my free time, I like to tinker with projects that involve parsing, codegen, and compiler optimizations. </p>

<div class="portfolio-tabs">
<input type="radio" name="section-tabs" id="tab-projects" class="tab-input" checked>
<label for="tab-projects" class="tab-btn"> Projects</label>
<input type="radio" name="section-tabs" id="tab-blogs" class="tab-input">
<label for="tab-blogs" class="tab-btn"> Writing & Blogs</label>

<div class="tab-panels">

<div class="tab-panel" id="panel-projects" onclick="const t = event.target.closest('.callout-title'); if (t) { const c = t.parentElement; if (!c.classList.contains('is-collapsed')) { this.querySelectorAll('.callout').forEach(el => { if (el !== c) el.classList.add('is-collapsed'); }); } }">

> [!note]- Typed Actor System
> A typed Actor system written in Rust, any type that derives the trait within the library enables us to create an actor with the following functions messages can be sent to the actor which the actor can process. queries can be asked to the actor and responses will be sent back from the actor to the place from which the queries are asked, this can be awaited with a timeout as well. The framework also provides with a termination switch that terminates the actor after performing the cleanup tasks specified in the trait \
**[View on GitHub ↗](https://github.com/vismeoww/typed_actor)**

> [!note]- Probabilistic Finite Automaton Simulator
> Specify the states and transition probabilities of a probabilistic
finite automaton in Lua language and this engine can simulate the
movement of the system through states, starting from the start
state and until the system reaches the state marked as end.
It also provides global variables that evolve over time through
which we can affect the behavior of multiple PFAs as the system
allows us to run multiple PFAs at the same time\
**[View on GitHub ↗](https://github.com/vismeoww/dfa-simulation-engine)**

> [!note]- Compiler
> A simple compiler for a language similiar to c type infered and strictly
  typed old implementation in standard ML currently being exported to Haskell\
> **[View on GitHub - Standard ML ↗](https://github.com/JarYamsiv/compiler-lab-sem6/tree/master/project)**\
> **[View on GitHub - Haskell ↗](https://github.com/JarYamsiv/Haskell/tree/master/parsec/pretty-printer)**

> [!note]- Voxel Engine
> A simple voxel engine to render 3d objects
    Voexel is the short for volumetric pixel
    Any shape can be divided into a set of voxels
    This project is to create such an engine in C++ \
**[View on GitHub ↗](https://github.com/vismeoww/voxelEngine)**

> [!note]- Cellular Automaton
> A cellular automaton to simulate John Conwoy's Game of life
    Cellular automatons are cells interacting with nearby cells with some given rules
    to perform behaviors that are similiar to real life systems\
**[View on GitHub ↗](https://github.com/vismeoww/GameOfLife_CellularAutomaton)**
 
</div> <!-- End Projects Panel -->

<div class="tab-panel" id="panel-blogs">

Head over to the [blogs](https://vismeoww.github.io/notes/) to read my latest notes, deep dives, and technical write-ups.

</div> <!-- End Blogs Panel -->

</div> <!-- End Tab Panels -->

</div> <!-- End Tabs -->
