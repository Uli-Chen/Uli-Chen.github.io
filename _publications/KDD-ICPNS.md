---
title: "Towards Reliable Negative Sampling for Recommendation with Implicit Feedback via In-Community Popularity"
collection: publications
category: manuscripts
permalink: /publication/ICPNS
excerpt: "Submitted to KDD'26."
date: 2026-02-09
# venue: "KDD"
slidesurl: "http://academicpages.github.io/files/slides1.pdf"
paperurl: "http://academicpages.github.io/files/paper1.pdf"
bibtexurl: "http://academicpages.github.io/files/bibtex1.bib"
citation: ""
---

Learning from implicit feedback is a fundamental problem in modern recommender systems, where only positive interactions are observed and explicit negative signals are unavailable. In such settings, negative sampling plays a critical role in model training by constructing negative items that enable effective preference learning and ranking optimization. However, designing reliable negative sampling strategies remains challenging, as they must simultaneously ensure realness, hardness, and interpretability. To this end, we propose **ICPNS (In-Community Popularity Negative Sampling)**, a novel framework that leverages user community structure to identify reliable and informative negative samples. Our approach is grounded in the insight that item exposure is driven by latent user communities. By identifying these communities and utilizing in-community popularity, ICPNS effectively approximates the probability of item exposure. Consequently, items that are popular within a user's community but remain unclicked are identified as more reliable true negatives. Extensive experiments on four benchmark datasets demonstrate that ICPNS yields consistent improvements on graph-based recommenders and competitive performance on MF-based models, outperforming representative negative sampling strategies under a unified evaluation protocol.
