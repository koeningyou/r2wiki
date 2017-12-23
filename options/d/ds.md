<!-- TITLE: ds -->

#  **`ds[?]`** Step, over, source line


```text
Usage: ds Step commands
```


- **`ds`** Step one instruction
- **`ds <num>`** Step <num> instructions
- **`dsb`** Step back one instruction
  > _When you run dsb, reverse debugger restore previous recorded state and execute program from it until desired point_
- **`dsf`** Step until end of frame
- **`dsi <cond>`** Continue/Step until condition matches
  - _Example: _ _`dsi eax==3,ecx>0`_ _ _
- **`dsl`** Step one source line
- **`dsl <num>`** Step <num> source lines
- **`dso <num>`** Step over <num> instructions
- **`dsp`** Step into program (skip libs)
- **`dss <num>`** Skip <num> step instructions

- [ **`dsu[?]<address>`** Step until address](/options/d/ds/dsu)

- **`dsui[r] <instr>`** Step until an instruction that matches `instr` , use dsuir for regex match
- **`dsue <esil>`** Step until esil expression matches
- **`dsuf <flag>`** Step until pc == flag matching name