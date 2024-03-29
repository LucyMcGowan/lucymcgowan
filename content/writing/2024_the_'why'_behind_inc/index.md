---
## Generated by the R package lazyapero
## Do not edit directly, edit the Google Sheet [id = 1HPQDH3tOXtZb1DV--8wR9CKAzUz5aywWc2vM3OQ5SrU]
title: "The 'Why' behind including 'Y' in your imputation model"
author: "**Lucy D'Agostino McGowan**, Sarah Lotspeich, Staci Hepler"
date: 1709942400
link_out: false
i: NA
categories:
 - Peer Reviewed Article
links:



- icon: link
  icon_pack: fas
  name: preprint
  url: https://arxiv.org/abs/2310.17434

---

Missing data is a common challenge when analyzing epidemiological data, and imputation is often used to address this issue. Here, we investigate the scenario where a covariate used in an analysis has missingness and will be imputed. There are recommendations to include the outcome from the analysis model in the imputation model for missing covariates, but it is not necessarily clear if this recommendation always holds and why this is sometimes true. We examine deterministic imputation (i.e., single imputation with fixed values) and stochastic imputation (i.e., single or multiple imputation with random values) methods and their implications for estimating the relationship between the imputed covariate and the outcome. We mathematically demonstrate that including the outcome variable in imputation models is not just a recommendation but a requirement to achieve unbiased results when using stochastic imputation methods. Moreover, we dispel common misconceptions about deterministic imputation models and demonstrate why the outcome should not be included in these models. This paper aims to bridge the gap between imputation in theory and in practice, providing mathematical derivations to explain common statistical recommendations. We offer a better understanding of the considerations involved in imputing missing covariates and emphasize when it is necessary to include the outcome variable in the imputation model.

