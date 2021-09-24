# Lark

Lark [^1] is a parsing toolkit for Python, built with a focus on ergonomics, performance and modularity.

Lark can parse all context-free languages. To put it simply, it means that it is capable of parsing almost any programming language out there, and to some degree most natural languages too.

Lark provides:

- Advanced grammar language, based on EBNF
- Three parsing algorithms to choose from: Earley, LALR(1) and CYK
- Automatic tree construction, inferred from your grammar
- Fast unicode lexer with regexp support, and automatic line-counting

## Installation

It can be installed using `pip`:

```bash
$ pip install lark --upgrade
```

# References

[^1]: [Lark homepage](https://lark-parser.readthedocs.io)