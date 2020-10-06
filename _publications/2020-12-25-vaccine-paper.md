---
title: "Optimizing Vaccine Allocation to Combat the COVID-19 Pandemic"
collection: publications
permalink: /publication/2020-12-25-vaccine-paper
excerpt: 'Paper describing a coordinate descent algorithm that iterates between optimizing vaccine allocations (e.g. based on the population's risk classes) and simulating the dynamics of the pandemic (using an extension of the DELPHI epidemiological model) in order to reduce the number of deaths given a certain allocated budget.'
date: 2020-12-25
venue: 'ArXiV (under review)'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'D. Bertsimas et al. (2020), Optimizing Vaccine Allocation to Combat the COVID-19 Pandemic, under review.'
---
The outbreak of COVID-19 has spurred extensive research worldwide to develop a vaccine. However, when a vaccine becomes available, limited production and distribution capabilities will likely lead to another challenge: who to prioritize for vaccination to mitigate the near-end impact of the pandemic? To tackle that question, this paper first expands a state-of-the-art epidemiological model, called DELPHI, to capture the effects of vaccinations and the variability in mortality rates across subpopulations. It then integrates this predictive model into a prescriptive model to optimize vaccine allocation, formulated as a bilinear non-convex program. To solve this model, this paper proposes a coordinate descent algorithm that iterates between optimizing vaccine allocations and simulating the dynamics of the pandemic. We implement the model and algorithm using real-world data in the United States. All else equal, the optimized vaccine allocation prioritizes states with a large number of projected cases and subpopulations facing higher risks (e.g., older ones). Ultimately, the optimized vaccine allocation can reduce the death toll of the pandemic by an estimated 10-25%, or 10,000-20,000 deaths over a three-month period in the United States alone.

[(Paper)](http://academicpages.github.io/files/paper3.pdf) [(Code)](https://github.com/jivanhoe/optimal-vaccine-allocation)

Recommended citation: D. Bertsimas et al. (2020), Optimizing Vaccine Allocation to Combat the COVID-19 Pandemic, under review.
