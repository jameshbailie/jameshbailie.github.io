---
title: "A refreshment stirred, not shaken: Invariant-preserving deployments of differential privacy for the US Decennial Census"
collection: papers
category: privacy
permalink: /papers/2026-02-24-A-refreshment-stirred-not-shaken-Invariant-preserving-deployments-of-differential-privacy-for-the-US-Decennial-Census
date: 2026-02-24
venue: 'Harvard Data Science Review'
authors_short: '!!me!!, R Gong, XL Meng'
authors_long: '!!me!!, Ruobin Gong, Xiao-Li Meng'
citation: 'James Bailie, Ruobin Gong and Xiao-Li Meng (2026). “A Refreshment Stirred, Not Shaken: Invariant-preserving Deployments of Differential Privacy for the US Decennial Census”. <i>Harvard Data Science Review</i>, Special Issue 6, doi: <a href="https://doi.org/10.1162/99608f92.dab78690" target="_blank">10.1162/99608f92.dab78690</a>'
abstract: "Protecting an individual’s privacy when releasing their data is inherently an exercise in relativity, regardless of how privacy is qualified or quantified. This is because we can only limit the gain in information about an individual relative to what could be derived from other sources. This framing is the essence of differential privacy (DP), through which this article examines two statistical disclosure control (SDC) methods for the United States Decennial Census: the Permutation Swapping Algorithm (PSA), which resembles the 2010 Census’s disclosure avoidance system (DAS), and the TopDown Algorithm (TDA), which was used in the 2020 DAS. To varying degrees, both methods leave unaltered certain statistics of the confidential data—their invariants—and hence neither can be readily reconciled with DP, at least as originally conceived. Nevertheless, we show how invariants can naturally be integrated into DP and use this to establish that the PSA satisfies pure DP subject to the invariants it necessarily induces, thereby proving that this traditional SDC method can, in fact, be understood from the perspective of DP. By a similar modification to zero-concentrated DP, we also provide a DP specification for the TDA. Finally, as a point of comparison, we consider a counterfactual scenario in which the PSA was adopted for the 2020 Census, resulting in a reduction in the nominal protection loss budget but at the cost of releasing many more invariants. This highlights the pervasive danger of comparing budgets without accounting for the other dimensions on which DP formulations vary (such as the invariants they permit). Therefore, while our results articulate the mathematical guarantees of SDC provided by the PSA, the TDA, and the 2020 DAS in general, care must be taken in translating these guarantees into actual privacy protection—just as is the case for any DP deployment."
version_history: 'The trio of papers (of which this article is the second part) were originally presented together as the working paper <a href="/papers/2023-05-04-Can-swapping-be-differentially-private-A-refreshment-stirred-not-shaken" target="_blank">Can Swapping be Differentially Private? A Refreshment Stirred, not Shaken</a>.'
bibtex_url: 'true'
paper_url: 'true'
arxiv_url: 'https://arxiv.org/abs/2501.08449'
publisher_url: 'https://hdsr.mitpress.mit.edu/pub/a1bpffpz/'
talk_url: '/talks/2024-09-14-Can-swapping-be-differentially-private-A-refreshment-stirred-not-shaken'
redirect_from: 
  - /papers/2025-01-14-A-refreshment-stirred-not-shaken-II-Invariant-preserving-deployments-of-differential-privacy-for-the-US-Decennial-Census
---

Due to HDSR's poor formatting of mathematical equations and tables, I recommend reading <a href="/files/papers/2026-02-24-A-refreshment-stirred-not-shaken-Invariant-preserving-deployments-of-differential-privacy-for-the-US-Decennial-Census.pdf" target="_blank">the paper PDF here</a>, rather than the HDSR publication. 

This article is Part II of a trio of papers. See <a href="/papers/2025-01-01-A-refreshment-stirred-not-shaken-I-Five-building-blocks-of-differential-privacy" target="_blank">Part I here</a> and <a href="/papers/2025-04-16-A-refreshment-stirred-not-shaken-III-Can-swapping-be-differentially-private" target="_blank">Part III here</a>.