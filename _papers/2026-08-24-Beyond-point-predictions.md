---
title: "Beyond point predictions: Uncertainty-aware satellite poverty mapping for public policy"
collection: papers
category: sustainable_development
permalink: /papers/2026-08-24-Beyond-point-predictions
date: 2026-08-24
venue: 'Preprint'
authors_short: 'M B Pettersson, !!me!!, M Kakooei, E Meng, A Daoud'
authors_long: 'Markus B Pettersson, !!me!!, Mohammad Kakooei, Eagon Meng, Adel Daoud'
citation: 'Markus B. Pettersson, James Bailie, Mohammad Kakooei, Eagon Meng and Adel Daoud (2026).
“Beyond Point Predictions: Uncertainty-Aware Satellite Poverty Mapping for Public Policy”.
doi: <a href="https://doi.org/10.48550/arXiv.2608.23322" target="_blank">10.48550/arXiv.2608.23322</a>'
abstract: "Despite their critical importance for policy and research, high-resolution poverty data remain limited across much of Africa. Machine learning (ML) with earth observation (EO) imagery has recently emerged as a way to supplement these data by predicting (i.e., estimating) poverty where it has not been directly measured. Yet to be used reliably, decision-makers and analysts need assurances that they will not be misled by the errors in these predictions. To meet this need, we develop an uncertainty-aware EO-ML method for poverty mapping based on simultaneous quantile regression and a novel form of conformal prediction. Using a spatiotemporal transformer trained on sequences of Landsat and nighttime-light images, we produce prediction intervals for neighborhood-level International Wealth Index estimates across Africa that are statistically guaranteed to achieve their desired coverage rates. While our method’s point-prediction performance matches the state of the art, its prediction intervals are wider than might be expected given its high \\(R^2\\) of 0.75. However, other models of similar accuracy likely suffer from comparable uncertainty, pointing to an inherent limitation: Even with its remarkably high explanatory power, EO-ML cannot naively be relied upon for policy-making, such as when designing poverty-targeting programs. To handle this challenge, we develop a procedure to efficiently allocate aid using both ground-truth surveys and model predictions while provably ensuring the risk of excluding eligible neighborhoods remains below a prespecified level. In simulations, this approach delivers substantially more aid per eligible recipient than other strategies, thereby demonstrating that EO-ML can indeed be a reliable supplement to traditional data sources—as long as methods are tailored to the problem at hand. Taken together, this work establishes how survey estimates and EO-ML predictions can be combined to achieve efficiency gains beyond what is possible with either data source alone, without compromising the reliability of the resulting decisions."
bibtex_url: 'true'
preprint_url: 'true'
arxiv_url: 'https://arxiv.org/abs/2608.23322'
---