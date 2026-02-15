## Regular Expressions & Formal Languages

The detection engine is based on regular expressions, which define
regular languages recognized by finite automata.

### Limitations
- Regex cannot handle nested structures
- Susceptible to obfuscation
- High false positives

### Why not CFG?
Certain attack patterns require context-free grammars
to be fully recognized (e.g. nested encodings).

### Future Work
- Automaton-based matching
- Hybrid regex + ML detection