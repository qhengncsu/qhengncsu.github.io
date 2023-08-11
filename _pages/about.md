---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a final-year PhD student in Statistics at North Carolina State University. Before coming to NC State, I received my Bachelor's degree from Shanghai University of Finance and Economics (SUFE). During my PhD, I primarily worked with Dr. [Eric C. Chi](https://www.ericchi.com/) (currently at Rice) on numerical optimization and Bayesian computation in statistical learning problems. 


# 🔥 News
- *2023.06*: &nbsp; I will join Department of Computational Medicine, UCLA as a postdocral scholar this fall, primarily working with Dr. [Kenneth Lange](https://www.pnas.org/doi/10.1073/pnas.2308441120) and Dr. [Hua Zhou](https://hua-zhou.github.io/).

# 📝 Featured Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technometrics</div><img src='images/landscape.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Robust Low-rank Tensor Decomposition with the L2 Criterion**

**Qiang Heng**, Eric C. Chi, Yufeng Liu

*Technometrics, in press*

- A nonconvex, differentiable formulation of robust Tucker decomposition that exhibits stronger recovery capabilities in more challenging high-rank scenarios.  [\[paper\]](https://www.tandfonline.com/doi/full/10.1080/00401706.2023.2200541)[\[code\]](https://github.com/qhengncsu/TuckerL2E/)[\[arXiv\]](https://arxiv.org/pdf/2208.11806.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCGS</div><img src='images/pbtf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bayesian Trend Filtering via Proximal Markov Chain Monte Carlo**

**Qiang Heng**, Hua Zhou, Eric C. Chi

*Journal of Computational and Graphical Statistics, in press*

- A novel MCMC methodology which uses epigrahph priors and Moreau envelopes to sample from nonsmooth posterior density functions with applications in Bayesian trend filtering.  [\[paper\]](https://www.tandfonline.com/doi/full/10.1080/10618600.2023.2170089)[\[code\]](https://github.com/qhengncsu/ProxBTF.jl)[\[arXiv\]](https://arxiv.org/pdf/2201.00092)
</div>
</div>

# 📝 Other Publications 

- **FreeMatch: Self-adaptive Thresholding for Semi-supervised Learning** [\[arXiv\]](https://arxiv.org/pdf/2205.07246.pdf) Yidong Wang, Hao Chen, **Qiang Heng**, Wenxin Hou, Yue Fan, Zhen Wu, Jindong Wang, Marios Savvides, Takahiro Shinozaki, Bhiksha Raj, Bernt Schiele, Xing Xie. *The Eleventh International Conference on Learning Representations (ICLR 2023), to appear*.

# 📖 Educations
- *2019.08 - present*, Ph.D. Statistics, North Carolina State University.
- *2015.09 - 2019.06*, B.S. Statistics, Shanghai University of Finance and Economics.

# 🎖 Honors and Awards
- *2020.08*, Gertrude Cox Achievement Award for outstanding PhD qualifier exam, North Carolina State University.
- *2019.05*, Academic Achievement Award, Shanghai University of Finance and Economics.

# 💬 Presentations
- *2023.07 Brown University*, Anderson Accelerated Operator Splitting for Convex-nonconvex Regularization, *Poster Presentation*, Acceleration and Extrapolation Methods workshop at ICERM
- *2022.07 Lehigh University*, Bayesian Trend Filtering via Proximal Markov Chain Monte Carlo, *Invited Talk*, ICCOPT 2022