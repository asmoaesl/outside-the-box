6/25/19 @ 20:31, last updated: @ 20:40

# The Multi-Lang Compiler
We see compilers and programming languages all the time trying to remain a single syntax and a single specification throughout all source code. With exceptions like most preprocessors, including the C preprocessor, which are different languages by themselves.

If the languages are both minimal, or lightly developed, then they could combine to form more compounded ideas and structures, tethering through all of the paradigms.

Imagine if you had a divided language between pragmatic, C-like programming, but also a pure-functional programming language as part of it. They may not even communicate within the same source files. But the simple fact they can, and are able to, robustly and losslessly, communicate the raw data amongst each-other like siblings, means a world of possibilities.

## The "True" Multi-Paradigm
As mentioned previously, imagine a language divided between two syntaxes, one pragmatic, the other purely functional. But why? Why should someone have both, when usually you only chose one?

I have no idea, but let me give it a shot.

 - It may be easier to write some parts of your software in a functional language, while the others in a pragmatic one.
 - You could be writing a compiler and have the parsing be done using the functional language, while retaining your comfort zone with the security of "you always have a fallback."
 - Maybe this applies to game development: writing the more high-performance code with the lower-level syntax, but these rendering algorithms could be much improved using a functional approach!

 ## Summary

In practice, this is just admitting that we as programmers may be more comfortable sticking to a single tool that can successfully "do it all."

Who said programming languages had to be so specific? Why can't we, instead of having the advantages of one and cons of another, not just have two languages whose pros and cons have been exaggerated for the better? Where one lacks, the other makes up for, and vice versa.

### More
 - Secondary language could be a DSL in a way, in such that you could have a high-level language, and then a "swap" whose principle is parsing. But again, these tools are tightly intertwined and are only in difference by the way they like to work.
 - 