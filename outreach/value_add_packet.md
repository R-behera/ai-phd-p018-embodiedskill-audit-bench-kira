# Professor Outreach Value-Add Packet

## Bottom Line

This repository is currently a **research proposal and execution scaffold**, not a completed result. Use it to show Professor Kira that you understand the research area and can contribute a concrete, reproducible artifact.

## Target Professor

- **Professor:** Zsolt Kira
- **University:** Georgia Institute of Technology
- **Program:** ML PhD / College of Computing
- **Research area from CSV:** ML, robot perception, continual & self-supervised learning
- **Representative paper from CSV:** Learning to Cluster in Order to Transfer Across Domains and Tasks; 2018; ICLR
- **Scholar link:** https://scholar.google.com/scholar?q=Learning+to+Cluster+in+Order+to+Transfer+Across+Domains+and+Tasks

## Proposed Value Add

Build **a robustness and failure-analysis benchmark for vision or vision-language models** focused on **robot perception**.

### What You Can Contribute

- Create a targeted shift dataset from existing benchmarks and lab-relevant failure modes.
- Run strong pretrained baselines and measure calibration, robustness, and explanation quality.
- Convert qualitative model failures into a labeled taxonomy that can guide new research.

## Concrete Starter Project

Build a small curated evaluation suite over 3-5 distribution shifts and compare CLIP/ViT-style baselines against adaptation or calibration variants.

## 30/60/90-Day Plan

### First 30 Days

- Re-read 3-5 recent lab papers and write a one-page problem framing memo.
- Build the first dataset or evaluation slice with documented source provenance.
- Reproduce one credible baseline and record exact commands.
- Create a failure bank with at least 20 concrete examples.

### Days 31-60

- Add the proposed method or evaluation contribution.
- Run ablations that isolate the contribution from data scale and model-size effects.
- Add robustness, temporal, domain-shift, or subgroup tests where relevant.
- Write interim results as a short lab-note style report.

### Days 61-90

- Expand the benchmark to 50-100 examples or the equivalent for the domain.
- Run statistical checks, seed variance checks, and cost/runtime analysis.
- Convert results into a paper-style technical report.
- Package the repo so another student can reproduce the main table.

## Deliverables To Offer The Professor

- A documented evaluation split with examples and source provenance.
- Baseline results for zero-shot, fine-tuned, and adapted models.
- Failure gallery with tags for viewpoint, object, context, annotation, and shortcut failures.
- A concise report identifying the highest-value next method to try.

## Skills This Demonstrates

computer vision evaluation, dataset curation, robustness testing, visualization, reproducible experiments.

## Honest Outreach Framing

Do **not** claim this is finished. The honest claim is:

> I prepared a concrete research scaffold aligned with your work and would like to turn it into a reproducible contribution if it matches your lab's current priorities.

## Sharing Note

This GitHub repository is public. Before emailing, verify the professor's current work, personalize the email, and be ready to explain exactly what is implemented versus planned.
