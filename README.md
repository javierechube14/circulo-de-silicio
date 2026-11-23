# El Círculo de Silicio (The Silicon Circle)

**From Life as Code to Quantum Computing: A Journey Through What We Take for Immaterial**

[![Read Online (Quarto Book)](https://img.shields.io/badge/Read_Online-Quarto_Book-blue?style=for-the-badge)](https://javierechube14.github.io/circulo-de-silicio/)
[![Download Full PDF](https://img.shields.io/badge/Download-Full_PDF_(102_pp.)-red?style=for-the-badge)](https://javierechube14.github.io/circulo-de-silicio/El_C%C3%ADrculo_de_Silicio.pdf)

---

## Overview & Portfolio Context

Unlike previous quantitative projects in this portfolio—which rely on statistical modeling and survey microdata (such as Spanish Labor Force Survey [EPA], INE TIC-H, or CIS barometers)—this work represents my **first qualitative, theoretical, and Science and Technology Studies (STS) research essay**.

Written in Spanish as a six-chapter monograph, *El Círculo de Silicio* examines the hidden materiality of digital technologies. It challenges the pervasive rhetoric of "the cloud," "virtuality," and "immateriality" by tracing the physical, energetic, linguistic, and social infrastructures that sustain modern computing, artificial intelligence, and quantum hardware.

---

## Core Analytical Threads

The essay connects five seemingly distant domains—molecular biology, classical computing, artificial intelligence, quantum physics, and sociology—through three recurring analytical lenses:

1. **The Body of Information (*El cuerpo*):** Following Rolf Landauer's principle that *information is physical*, every bit, DNA base pair, neural network weight, and qubit requires a material substrate, energy, water, and mineral extraction.
2. **Scale (*La escala*):** How controlling matter at progressively smaller dimensions (from cells and genes to nanometers and individual atoms) reshapes technological capabilities and concentrates industrial and geopolitical power.
3. **Error (*El error*):** How different informational systems handle noise and failure—biology exploits mutation to evolve, classical computing suppresses error through redundancy, quantum computing fights decoherence without cloning, and society decides *who* bears the cost when automated systems fail.

---

## Book Structure

* **Introduction:** *La información necesita un cuerpo* (Information needs a body)
* **Chapter 1:** *La vida como información* — Evolutionary trial and error, DNA replication fidelity, directed evolution, and synthetic biology (xenobots, CRISPR).
* **Chapter 2:** *La ilusión de la inmaterialidad* — Data centers, submarine cables, hardware vs. software layers, EUV lithography (ASML/TSMC), and resource footprints.
* **Chapter 3:** *La inteligencia artificial y quién puede permitírsela* — From Dartmouth to Transformers, NVIDIA/CUDA lock-in, compute divides, and specialist vs. generalist AI (AlphaFold vs. LLMs).
* **Chapter 4:** *Las palabras que ocultan* — Critical discourse and metaphor analysis ("cloud," "memory," "hallucination," "algorithm," and "ghost work").
* **Chapter 5:** *La revolución cuántica* — Qubits, dilution refrigerators, quantum error correction (NISQ era), post-quantum cryptography, and molecular simulation.
* **Chapter 6:** *Quién sostiene lo invisible* — A sociological toolkit (Marx, Star, Latour, Winner, Perrow, Zuboff, Fourcade) addressing black boxes, algorithmic bias, supply chain chokepoints, and data colonialism.
* **Conclusion & Glossary:** *El círculo como metáfora, el cuerpo como hecho*

---

## Methodological Note on AI-Assisted Writing

In line with the book's central argument—that technologies should not hide the mechanisms that make them possible—this project includes an explicit methodological disclosure. Concept design, thematic selection, structural architecture, sociological framing, and source verification (updated to late 2026) were directed by the author, while text drafting and synthesis were executed iteratively using Anthropic's Claude under close human editorial supervision.

---

## Repository Structure

```text
circulo-de-silicio/
├── _quarto.yml                  # Quarto Book configuration
├── index.qmd                    # Cover, methodological note, and introduction
├── cap1-vida.qmd                # Chapter 1 source
├── cap2-inmaterialidad.qmd      # Chapter 2 source
├── cap3-ia.qmd                  # Chapter 3 source
├── cap4-palabras.qmd            # Chapter 4 source
├── cap5-cuantica.qmd            # Chapter 5 source
├── cap6-sociedad.qmd            # Chapter 6 source
├── conclusion.qmd               # Conclusion and glossary source
├── images/                      # Conceptual diagrams and figures
├── El_Círculo_de_Silicio.pdf    # Full typeset PDF edition
└── docs/                        # Rendered HTML book deployed via GitHub Pages
