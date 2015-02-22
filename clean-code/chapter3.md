# Chapter 3: Functions

## Observations

- Functions are your first line of organization.
- Three minute time limit given to understand a 64-line function. (Spoiler: I failed.)
- "How can we make a function communicate its intent?"
- We're no longer constrained by technology (screen resolution) but that doesn't give us free reign to write lengthy functions. Functions should hardly ever be longer than 20 lines.
- "Each [function] told a story." Strive for this. See Ward Cunningham's definition of clean code doing exactly what you expect it to.
- Blocks and indenting of `if` statements. If statements should effectively just call a function. Ruby encourages this with its `do_something if this` syntax.
- Functions should follow the Single Reponsibility Principle.
    - "Functions should do one thing. They should do it well. They should do it only.""
- Once details are mixed in with essential concepts, more and more details will find their way into the function.
    - See Broken Windows in The Pragmatic Programmer.
- Learn how to write functions that stay at a single level of abstraction. This trick is difficult for programmers to pick up.
- Don't be afraid to make a name long. Long and descriptive is better than short and enigmatic.
- Be consistent in naming.
- Function argument continuum: niladic, monadic, dyadict. Triadic and polyadic should raise eyebrows.
- Output arguments are hard to understand. We don't expect information flowing out of functions through arguments.
- **Flag arguments are ugly.** They are a clear indication a function does more than one thing. Avoid flag arguments. Refactor.

## What I'm going to do

- Unknown.
