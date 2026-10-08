# Finite-time breakdown of Euler flows from smooth, compactly supported initial data

**Author:** Tseng  
**Manuscript version:** 8 October 2026

This research manuscript studies finite-time breakdown of the incompressible Euler equation on $\mathbb{R}^d$ for each fixed integer $d \geq 3$, with smooth, compactly supported, divergence-free initial data. It presents a dimension-dependent extension of a localized oscillatory construction, together with transverse evolution, pressure estimates, and summability of the initial increments in every Sobolev space.

## Files

- [main.pdf](main.pdf): typeset manuscript.
- [main.tex](main.tex): complete, self-contained LaTeX source, including the bibliography.

## Compilation

Use a current TeX distribution with `latexmk`, or Tectonic. No additional source files, figures, or bibliography database are required.

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

Alternatively:

```sh
tectonic main.tex
```

## Reference and authorship

The principal reference is OpenAI, *Finite time blowup for the Euler equation*, [manuscript](https://cdn.openai.com/pdf/315b36cd-ec98-4023-8342-93345194ece1/euler.pdf).

## Use of artificial intelligence

All mathematical derivations in this manuscript were produced using
artificial intelligence.
