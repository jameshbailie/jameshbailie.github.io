---
title: "Can swapping be differentially private? A refreshment stirred, not shaken"
collection: papers
permalink: /papers/2023-05-04-Can-swapping-be-differentially-private-A-refreshment-stirred-not-shaken
date: 2023-05-04
venue: 'Working Paper'
authors_short: '!!me!!, R Gong, XL Meng'
authors_long: '!!me!!, Ruobin Gong, Xiao-Li Meng'
citation: 'James Bailie, Ruobin Gong and Xiao-Li Meng (2025). “Can Swapping Be Differentially Private? A Refreshment Stirred, Not Shaken”. <i>Data Privacy Protection and the Conduct of Applied Research: Methods, Approaches and their Consequences</i>, p. 55. url: <a href="https://conference.nber.org/conf_papers/f178188.pdf" target="_blank">conference.nber.org/conf_papers/f178188.pdf</a>'
abstract: "This paper presents a formal privacy analysis of data swapping, a family of statistical disclosure control (SDC) methods which were used in the 1990, 2000 and 2010 US Decennial Census disclosure avoidance systems (DAS). Like all swapping algorithms, the method we examine has invariants – statistics calculated from the confidential database which remain unchanged. We prove that our swapping method satisfies the classic notion of pure differential privacy (\\(\\varepsilon\\)-DP) when conditioning on these invariants. To support this privacy analysis, we provide a framework which unifies many different types of DP while simultaneously explicating the nuances that differentiate these types. This framework additionally supplies a DP definition for the TopDown algorithm (TDA) which also has invariants and was used as the SDC method for the 2020 Census Redistricting Data (P.L. 94-171) Summary and the Demographic and Housing Characteristics Files. To form a comparison with the privacy of the TDA, we compute the budget (along with the other DP components) in the counterfactual scenario that our swapping method was used for the 2020 Decennial Census. By examining swapping in the light of formal privacy, this paper aims to reap the benefits of DP - formal privacy guarantees and algorithmic transparency - without sacrificing the advantages of traditional SDC. This examination also reveals an array of subtleties and traps in using DP for theoretically benchmarking privacy protection methods in general. Using swapping as a demonstration, our optimistic hope is to inspire formal and rigorous framing and analysis of other SDC techniques in the future, as well as to promote nuanced assessments of DP implementations which go beyond discussion of the privacy loss budget \\(\\varepsilon\\)."
bibtex_url: 'true'
paper_url: 'true'
publisher_url: 'https://conference.nber.org/conf_papers/f178188.pdf'
talk_url: '/talks/2024-09-14-Can-swapping-be-differentially-private-A-refreshment-stirred-not-shaken'
---

This working paper was developed into a trio of papers: <a href="/papers/2025-01-01-A-refreshment-stirred-not-shaken-I-Five-building-blocks-of-differential-privacy" target="_blank">Part I</a>, <a href="/papers/2025-01-14-A-refreshment-stirred-not-shaken-II-Invariant-preserving-deployments-of-differential-privacy-for-the-US-Decennial-Census" target="_blank">Part II</a>, <a href="/papers/2025-04-16-A-refreshment-stirred-not-shaken-III-Can-swapping-be-differentially-private" target="_blank">Part III</a>.
