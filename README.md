# Conservation Spectral Analysis — Publication-Ready Papers

Three research papers on conservation spectral analysis, prepared for peer review.

## Papers

### Paper 1: Theory
**"Spectral Conservation: A Universal Measure of Structural Coherence in Complex Systems"**

- Target: *Journal of Mathematical Physics* / *Physical Review E*
- Directory: `paper1-theory/`
- Five foundational theorems (T1–T5), the Conservation Universal Theorem, Domain Transfer Theorem, and Grand Unified Theorem (V3 with corrected Ramanujan bounds)
- 12 experimental domains with honest negative results

### Paper 2: Applications
**"Conservation Spectral Analysis for Cross-Domain Anomaly Detection"**

- Target: *Nature Computational Science* / *PNAS*
- Directory: `paper2-applications/`
- ConservationRegimeDetector algorithm
- 7-domain experimental campaign, mean AUC 0.92
- +0.22 over strongest baseline

### Paper 3: Agents
**"The Laplacian as Compatibility Operator: Agent-Native Communication via Spectral Alignment"**

- Target: *AAMAS* / *JAIR*
- Directory: `paper3-agents/`
- A2A Spectral Protocol
- Fiedler routing, PLATO rooms, conservation-based trust
- Multi-agent fleet simulation with adversarial injection

## Building

Each paper directory contains a `Makefile`:

```bash
cd paper1-theory && make
cd paper2-applications && make
cd paper3-agents && make
```

Requires a LaTeX distribution with `pdflatex`.

## Reproducibility

All experiments are reproducible via the open-source Conservation Spectral SDK (9 languages, 204 cross-verified tests).

## License

MIT

Part of the [SuperInstance OpenConstruct](https://github.com/SuperInstance/OpenConstruct) ecosystem.
