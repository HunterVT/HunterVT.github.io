---
layout: project
type: project
image: img/reu-protein.png
title: "AI-Driven Discovery of Novel Molecular Tools for Intraoperative Nerve Visualization"
date: 2025-7-31
published: true
labels:
  - Bash
  - Machine Learning
  - High-Performance Computing
  - Cluster Computing
summary: "Generating and testing protein binder designs using machine learning and molecular dynamics simulations"
---

Our poster for this project can be found <a href="../pdf/reuposter.pdf">here</a>.

## The Project
The project I was assigned during my REU at Temple University dealt with protein binders and machine learning. The goal of the project was to develop and test a machine learning based pipeline for generating protein binders that would eventually be used in surgery and theraputics drugs. A total of three different machine learning models were used, with a molecular dynamics simulation done with the generated designes at the end. The first model, RFdiffusion, is a diffusion based model, that, when given a protein, can generate a backbone of a potential binder. The next model, ProteinMPNN, takes the backbone, and outputs a plausible amino acid sequence that the backbone could have. The third and final model, AlphaFold, takes the amino acid sequence, and predicts the structure of the binder, which we could then compare to the generated backbone from RFdiffusion. Molecular dynamics simulations would then be run with the generated binder being "fixed" next to the original protein, to assess how well the binder interacts with the initial structure. 

## My Contribution
I mainly ran the machine learning models on Temple's HPC cluster and recorded the data provided from each run. I reported the successful runs, and organized the data into the 10 "best" potential binders for use in molecular dynamics simulations. I also ran some of the molecular dynamics simulations.

## Takeaways
This project taught me a lot about different concepts in biology, improved my skill with Python and Bash, and exposed me to a different side of machine learning in the context of biology. The project also exposed me to use of an HPC cluster, which I gained more proficiency with using throughout my time as an REU student. 