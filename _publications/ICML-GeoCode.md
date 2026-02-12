---
title: "Synthesizing Multimodal Geometry Datasets from Scratch and Enabling Visual Alignment via Plotting Code"
collection: publications
category: manuscripts
permalink: /publication/GeoCode
excerpt: "Submitted to ICML'26."
date: 2026-01-21
# venue: "KDD"
slidesurl: "http://academicpages.github.io/files/slides1.pdf"
paperurl: "http://academicpages.github.io/files/paper1.pdf"
bibtexurl: "http://academicpages.github.io/files/bibtex1.bib"
# citation: ""
---

Multimodal geometry reasoning requires models to jointly understand visual diagrams and perform structured symbolic inference, yet current vision--language models struggle with complex geometric constructions due to limited training data and weak visual--symbolic alignment. We propose a pipeline for synthesizing complex multimodal geometry problems from scratch and construct a dataset named **GeoCode**, which decouples problem generation into symbolic seed construction, grounded instantiation with verification, and code-based diagram rendering, ensuring consistency across structure, text, reasoning, and images. Leveraging the plotting code provided in GeoCode, we further introduce code prediction as an explicit alignment objective, transforming visual understanding into a supervised structured prediction task. GeoCode exhibits substantially higher structural complexity and reasoning difficulty than existing benchmarks, while maintaining mathematical correctness through multi-stage validation. Extensive experiments show that models trained on GeoCode achieve consistent improvements on multiple geometry benchmarks, demonstrating both the effectiveness of the dataset and the proposed alignment strategy.
