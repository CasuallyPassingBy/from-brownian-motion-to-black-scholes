# Mathematical Foundations of the Black–Scholes Equation  
*A personal exploration of stochastic calculus and option pricing*

This project is the result of something I’ve wanted to understand for a long time:  
**how mathematics, probability, and finance come together to produce the Black–Scholes equation.**

Instead of memorizing the formula or following a standard derivation, I decided to rebuild the result myself, step by step, from the core ideas of stochastic calculus.  
The goal was to create something that felt rigorous, intuitive, and accessible.

---

## Why I made this

I wanted to understand *why* the Black–Scholes formula works, not just *what* it is.

As a mathematician, I’m fascinated by the way:
- randomness becomes structure,
- noise becomes equations,
- and simple assumptions lead to elegant PDEs.
  
It is not meant to be comprehensive or overly formal, but a first step into mathematical finances

---

## Mathematical Highlights

- Uses **geometric Brownian motion** as the model for asset prices.  
- Applies **Itô’s lemma** to derive dynamics of option prices.  
- Constructs a **delta-hedged, self-financing portfolio** to eliminate randomness.  
- Obtains the **Black–Scholes PDE** via no-arbitrage principles.  
- Solves the PDE by turning it into a **heat equation** and applying Fourier methods.  

## Repository Structure

```css
black-scholes-derivation/
├── paper/
│   ├── main.pdf
│   ├── main.tex
│   ├── references.bib
├── notes/
│   └── derivation-outline.md
├── README.md
├── LICENSE
```

I’d love to eventually add:
- simple Monte Carlo simulations,
- plots of GBM sample paths,
- or small numerical experiments comparing theory and simulation.

---

## 🖋️ Compilation

To compile the document:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## References
- Shreve, *Stochastic Calculus for Finance*
- Øksendal, *Stochastic Differential Equations*


