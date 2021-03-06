# Evolutionary Keygenning
A toy example for smart input generation (in this case keygenning) using genetic algorithm and control flow graph information.

# Main idea
This software is based on [1,2] and BlackHat presentations, which proposes a model for evolutionary fuzzing. 

# Usage

It would be best if you had clang++ for control-flow graph extraction but, you can compile the main `cr4ckm3` executable with g++ or most of the other compilers. 

```
make 
make cfg
make clean
```

## Rewriting context-free grammar

gramEvol class offers a basic framework for generating input string using context-free grammars. 

# References

[1] "Sidewinder": An Evolutionary Guidance System for Malicious Input Crafting, Embleton, S., Sparks, S., Cunningham, R.     
[2] Automated Vulnerability Analysis: Leveraging Control Flow for Evolutionary Input Crafting, Sparks, S., Embleton, S., Cunningham, R., Zou, C.
