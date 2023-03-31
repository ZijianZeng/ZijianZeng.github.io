---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journal papers
* Ryan, C.T., **Zeng, Z.**, Chatterjee, S., Wall, M.J., Moon, M.R., Coselli, J.S., Rosengart T.K., Li, M., and Ghanta, R.K., (2022). Machine Learning for Dynamic and Early Prediction of Acute Kidney Injury after Cardiac Surgery. *Journal of Thoracic and Cardiovascular Surgery*, in press

* **Zeng, Z.**, Li, M. and Vannucci, M. (2022+). Bayesian Image-on-Scalar Regression with a Spatial Global-Local Spike-and-Slab Prior. *Bayesian Anaysis*, in press.

* **Zeng, Z.** and Li, M. (2021). Bayesian Median Autoregression for Robust Time Series Forecasting. *International Journal of Forecasting*, 37(2), 1000-1010
