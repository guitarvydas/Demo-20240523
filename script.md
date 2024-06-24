# slide 1 Title
- Exploring techniques and notations for augmenting developer experience
- this demo needs explanation, so I will present a few slides first
- this is about HOW to create new notations instead of championing a single notation
# slide 2 Manifesto
1. we must stop believing that old-fashioned notations meant for printing presses are suitable for programming and reprogramming this new medium
2. we must use many programming languages and join them together into a workflow for program development
3. documentation doesn't work - must generate code
# slide 3 Function-Based Notation
- function-based notation is useful for programming calculators and compute-ers
- function-based notation is stressed beyond its sweet spot for programming other kinds of things, like truly asynchronous actions
- function-based notation is based on mathematics notation instead of hardware CPUs
  - Alan Kay, even, said that "a computer is more than functions and sets"
# slide 4 Hardware Centric Perspective
- we have become accustomed to a 1950s biased, mathematical, cost-cutting view of reprogrammable electronic machines
- using old-fashioned ideas from the 1950s, we are biased towards sharing memory and time-sharing CPUs - this causes accidental complexities and creates the need for workarounds
- originally, CPU ICs were designed to be non-reentrant and not to be thread-safe
  - the idea was to have networks of many hardware actors 
  - but, cost-cutting caused us to move away from those ideas
  - cost-cutting forced us to use shared memory and to create development systems that needed extra software to fake out the function-based paradigm
  - in 2024, we can cease to cut these kinds of costs - we can waste machine power to create development workflows that are more like the model of hardware actors
# slide 5 Goal & Definition of Success of this work
- the goal is to simplify DX - Developer Experience
- I strongly believe that a simpler DX will lead to invention of simpler UXs for non-programmers
- to work towards this goal, we need to explore many avenues of simplification
  - DaS - Diagrams as Syntax
  - 0D - extreme decoupling, zero dependencies
  - t2t - text-to-text transpilation
  - detangling Design Intent from Implementation
  - studying smallness vs. bloatware
  - creating separate notations for Software Architecture, Software Engineering and Software Production Engineering
  - identifying and replacing baggage due to old-fashioned ideas from the 1950s
  - Failure Driven Development - coping with program development where programs have bugs and fail
	  - we need to make it easy to wipe everything out and to start afresh as we learn about the problems we are trying to solve
	  - we need to prevent calcification of design ideas that need to be revised, caused by the feeling of investment in partial solutions caused by the notation we use
# slide 6 This Demo
- This demo will concentrate on only *one* kind of simplification
  - the idea of using different syntaxes for programming
  - how to create different syntaxes using current technologies
- 0D is a necessary aspect of this simplification, 0D is incorporated into this demo, but, will not be detailed due to time limitations, ask me or pm me for more detail
- this demo implements a node-and-arrow Diagrammatic Programming Language, why?
  - node-and-arrow is simple
	- is node-and-arrow the next "spreadsheet"? 
	- is node-and-arrow intuitively obvious to non-programmers and developers?
  - expresses sequential control flow simply, and, expresses true asynchronous control flow simply
  - node-and-arrow is especially easy with 0D, yet, appears to be complicated when expressed in a function-based notation
	- this shows that switching notations can lead to more expressitivity
  - it is easy to build node-and-arrow DPLs using existing tech, e.g. closures, queue objects - supported by all modern programming languages
  - existing programming languages are but "assembler" for higher level programming notations
  - advances in technology make it easy to invent and implement new notations, unlike in the 1950s
  - not shown: multiple inputs and outputs, feedback, connection directions (down/up/across/through)
  - this is an implementation technique rather than advocacy for node-and-arrow
  - no prior art - to my knowledge, all existing DPLs are based on synchronous implementations, this technique is fundamentally different
  
  
