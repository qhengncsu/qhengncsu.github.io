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

I am a fourth year PhD student in Statistics at North Carolina State University. Before coming to NC State, I received my Bachelor's degree from Shanghai University of Finance and Economics. I primarily work with Dr. [\[Eric C. Chi\]](https://www.ericchi.com/) (currently at Rice) on numerical optimization and Bayesian computation in statistical learning problems. I am also interested in semi-supervised/long-tail deep learning.  


# 🔥 News
- *2023.01*: &nbsp;🎉🎉 Our paper FreeMatch: Self-adaptive Thresholding for Semi-supervised Learning has been accepted by ICLR 2023. 
- *2023.01*: &nbsp;🎉🎉 Our paper Bayesian Trend Filtering via Proximal Markov Chain Monte Carlo has been accepted by JCGS.  

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCGS</div><img src='images/pbtf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bayesian Trend Filtering via Proximal Markov Chain Monte Carlo**

**Qiang Heng**, Hua Zhou, Eric C. Chi

*Journal of Computational and Graphical Statistics, in press*

- A novel MCMC methodology which uses epigrahph priors and Moreau envelopes to sample from nonsmooth posterior density functions with applications in Bayesian trend filtering.  [\[paper\]](https://www.tandfonline.com/doi/full/10.1080/10618600.2023.2170089)[\[code\]](https://github.com/qhengncsu/ProxBTF.jl)[\[arXiv\]](https://arxiv.org/pdf/2201.00092)
</div>
</div>

- **FreeMatch: Self-adaptive Thresholding for Semi-supervised Learning** [\[arXiv\]](https://arxiv.org/pdf/2205.07246.pdf) Yidong Wang, Hao Chen, **Qiang Heng**, Wenxin Hou, Yue Fan, Zhen Wu, Jindong Wang, Marios Savvides, Takahiro Shinozaki, Bhiksha Raj, Bernt Schiele, Xing Xie. *The Eleventh International Conference on Learning Representations (ICLR 2023), to appear*.

# 📝 Preprints

- **Tucker-L2E: Robust Low-rank Tensor Decomposition with the L2 Criterion** [\[arXiv\]](https://arxiv.org/pdf/2208.11806.pdf) **Qiang Heng**, Eric. C. Chi, Yufeng Liu. *In Revision*.

# 📖 Educations
- *2019.08 - present*, Ph.D. Statistics, North Carolina State University.
- *2015.09 - 2019.06*, B.S. Statistics, Shanghai University of Finance and Economics.

# 🎖 Honors and Awards
- *2020.08* Gertrude Cox Achievement Award for outstanding PhD qualifier exam, North Carolina State University.
- *2019.05* Academic Achievement Award, Shanghai University of Finance and Economics.

# 💬 Invited Talks
- *2022.07*, Bayesian Trend Filtering via Proximal Markov Chain Monte Carlo, ICCOPT 2022

# 💻 Internships
- *2022.05 - 2022.08*, Applied Scientist Inter, Amazon CoreAI
- *2021.05 - 2021.08*, Applied Scientist Inter, Amazon Advertising