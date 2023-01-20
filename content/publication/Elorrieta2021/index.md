---
abstract: In several disciplines, it is common to find time series measured at irregular observational times. In particular, in astronomy there are a large number of surveys that gather information over irregular time gaps and in more than one passband. Some examples are Pan-STARRS, ZTF, and also the LSST. However, current commonly used time series models that estimate the time dependence in astronomical light curves consider the information of each band separately (e.g, CIAR, IAR, and CARMA models) disregarding the dependence that might exist between different passbands. In this paper, we propose a novel bivariate model for irregularly sampled time series, called the Bivariate Irregular Autoregressive (BIAR) model. The BIAR model assumes an autoregressive structure on each time series; it is stationary, and it allows to estimate the autocorrelation, the cross-correlation and the contemporary correlation between two unequally spaced time series. We implemented the BIAR model on light curves, in the g and r bands, obtained from the ZTF alerts processed by the ALeRCE broker. We show that if the light curves of the two bands are highly correlated, the model has more accurate forecast and prediction using the bivariate model than a similar method that uses only univariate information. Further, the estimated parameters of the BIAR are useful to characterize long-period variable stars and to distinguish between classes of stochastic objects, providing promising features that can be used for classification purposes
authors:
- admin
- Eyheramendy, Susana
- Palma, Wilfredo
- Ojeda, Cesar
date: "2021-05-04T00:00:00Z"
doi: 10.1093/mnras/stab1216
featured: true
projects: [Astro-Statistics]
publication: '*Monthly Notices of the Royal Astronomical Society, 505*(1)'
publication_short: ""
publication_types:
- "2"
publishDate: "2021-05-04T00:00:00Z"
tags:
- Astro-Statistics
title: A novel bivariate autoregressive model for predicting and forecasting irregularly observed time series
url_code: https://doi.org/10.1093/mnras/stab1216
url_dataset: ""
url_pdf: https://academic.oup.com/mnras/article-pdf/505/1/1105/38391762/stab1216.pdf
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
