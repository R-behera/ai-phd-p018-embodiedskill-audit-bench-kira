# EmbodiedSkill Audit Bench: robot perception for Kira-Aligned Research

A research-grade AI/ML PhD preparation project aligned with **Zsolt Kira** at **Georgia Institute of Technology**.

## Research Question

Can explicit progress-state modeling improve language-conditioned robot policy generalization and recovery?

## Advisor Fit

- **Professor:** Zsolt Kira
- **University:** Georgia Institute of Technology
- **Program:** ML PhD / College of Computing
- **CSV research area:** ML, robot perception, continual & self-supervised learning
- **Representative paper:** Learning to Cluster in Order to Transfer Across Domains and Tasks; 2018; ICLR
- **Scholar link:** https://scholar.google.com/scholar?q=Learning+to+Cluster+in+Order+to+Transfer+Across+Domains+and+Tasks

## Research-Grade Deliverable

This repo is scaffolded to become a serious research artifact, not a demo-only project. The finished version should include:

- Reproducible dataset pipeline with raw-data provenance.
- Strong baselines and locked experiment configs.
- Original method or evaluation contribution.
- Ablation studies that isolate what changed.
- Failure analysis with concrete examples.
- Paper-style report, limitations, and reproducibility notes.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m pytest
```

## Repository Map

- `docs/research_brief.md` - project hypothesis, novelty, methods, and evaluation plan.
- `docs/experiment_plan.md` - concrete baseline, ablation, and reporting protocol.
- `configs/baseline.yaml` - first experiment configuration placeholder.
- `src/` - implementation package placeholder.
- `tests/` - smoke and metric tests placeholder.
- `reports/` - figures, tables, and final writeup.
- `reproducibility/commands.md` - exact commands and environment notes.
- `data/source_programs.csv` - original CSV for traceability.

## Status

Scaffolded from the Fall 2027 AI PhD programs CSV. Before external use, re-verify professor interests, application dates, and paper/citation metadata.
