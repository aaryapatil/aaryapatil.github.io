---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Publications
------------

### Peer-Reviewed Journal Articles


In preparation:
Patil, A. A.; Bovy, J.; & Jaimungal, S. "Decoding the Age-Metallicity Structure of the Milky Way disk: An application of Copulas and Elicitable Maps". To be submitted to the Monthly Notices of the Royal Astronomical Society.

Sun, J.; Patil, A. A.; Guo, J.; & Zhou, S. "A Case Study of an Open-Source Scientific Software". To be submitted to the ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering ESEC/FSE 2023. https://2023.esec-fse.org/

Submitted:
Patil, A. A.; Eadie, G.; Speagle, J.; & Thomson, D. "Multitaper Spectral Estimation in Asteroseismology". Submitted to The Astronomical Journal.

Published:
The Astropy Collaboration, Price-Whelan, A. M.; Lim, P. L.; Earl, N.; Starkman, N.; Bradley, L.; Shupe, D. L.; Patil, A. A. et al. (2022). "The Astropy Project: Sustaining and Growing a Community-oriented Open-source Project and the Latest Major Release (v5. 0) of the Core Package". The Astrophysical Journal, Volume 935, Issue 2, article id 167, 20pp. https://arxiv.org/abs/2206.14220 [12 citations]

Patil, A. A.; Bovy, J.; Eadie, G.; & Jaimungal, S. (2022). "Functional Data Analysis for Extracting the Intrinsic Dimensionality of Spectra: Application to Chemical Homogeneity in the Open Cluster M67". The Astrophysical Journal, Volume 926, Issue 1, article id. 51, 24pp. https://arxiv.org/abs/2109.10891 [1 citation]

Astropy Collaboration et al. including Patil, A. A. (2018). "The Astropy Project: Building an Open-science Project and Status of the v2.0 Core Package". The Astronomical Journal, Volume 156, Issue 3, article id. 123, 19 pp. https://arxiv.org/abs/1801.02634 [3985 citations]

### Non-Peer-Reviewed Articles

Cruz, K.;  Günther, H. M.;  Patil, A.;  Swinbank, J.; &  Tollerud, E. (2022). "Astropy Proposal for Enhancement 19: Distributing Astropy Project Funding (APE19)". Technical Report, Zenodo. https://doi.org/10.5281/zenodo.6312048

Patil, A.; Bovy, J.; & Eadie G. (2020). "Likelihood-free Inference of Chemical Homogeneity in Open Clusters". 2020 Joint Statistical Meetings (JSM) Proceedings, American Statistical Association (ASA), pp 1838-1844. ![link to pdf](./files/JSM_Proceedings_2020.pdf)
\\


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


*My research lies at the intersection of astrophysics and statistics by developing novel data-driven tools that guide mathematical models of the Milky Way (MW) Galaxy.*

The Basics
----------
Galaxies are the fundamental building blocks in the structure of the Universe. Not only do their observations help us in understanding our own galaxy, the MW, but they also lend themselves as giant and powerful laboratories to study the fundamental laws of physics. The *Big Bang Theory* of the origin of the universe and the existence of *Dark Matter* are some of the biggest breakthroughs in physics and they arose through studies of galaxies [1]. Understanding galaxies is therefore an important astrophysical pursuit, and we now have petabytes of observational data to fully do so.  The only remaining element which I will address head-on is to accelerate our understanding through the development and application of modern statistical techniques.

Also, galaxies are beautiful!

<p align="center">
  <img width="500" height="50" src="https://aaryapatil.github.io/images/galaxy.jpg">
</p>

Research Question
-----------------
The mechanisms that govern galaxy formation and evolution are encoded in the history of star formation and chemical enrichment within a galaxy. In the MW, we can decode these mechanisms using million-star photometric and spectroscopic surveys of unprecedented quality and scope [2, 3]. My goal is to use these *Big Data* observations to estimate the age-metallicity distribution of stars in different parts of the MW disk, and compare this distribution to Galactic chemo-dynamical models [4, 5]. Particularly, I will test and refine models of *Radial Migration* in the Galaxy, the migration of a star inward or outward from its radius of birth due to changes in its orbit's angular momentum [6, 7].

I follow a bottom-up approach to estimate the age-metallicity distribution of the MW disk. I first develop methods to measure the ages and chemistry of simple populations of stars in the disk, i.e., open clusters. Stars in an open cluster are assumed to have formed simultaneously from the same homogeneous gas cloud, and are expected to have similar ages and chemistry [8, 9, 10]. These assumptions make open clusters ideal for testing age and chemical estimation methods. They are also important for understanding the theory of star formation and evolution, and their role in MW evolution.

Patil et al. (2022 a) performs accurate and precise estimation of stellar chemical abundances using *Functional Data Analysis* [11] and *Likelihood-free Inference* [12], and constrains the chemical homogeneity in open cluster M67. Patil el al. (2022 b) estimates precise asteroseismic stellar ages using *Multitaper Spectral Analysis* [13] [14].

References
----------
[1] Binney, J., & Tremaine, S. 2008, Galactic Dynamics: Second Edition\
[2] Gaia Collaboration, Brown, A. G. A., Vallenari, A., et al. 2016, 595, A2\
[3] Majewski, S. R., Schiavon, R. P., Frinchaboy, P. M., et al. 2017, 154, 94\
[4] Edvardsson, B., Andersen, J., Gustafsson, B., et al. 1993, 500, 391\
[5] Feuillet, D. K., Frankel, N., Lind, K., et al. 2019, 489, 1742\
[6] Sellwood, J. A., & Binney, J. J. 2002, 336, 785\
[7] Frankel, N., Rix, H.-W., Ting, Y.-S., Ness, M., & Hogg, D. W. 2018, 865, 96\
[8] Lada, C. J., & Lada, E. A. 2003, 41, 57\
[9] Shu, F. H., Adams, F. C., & Lizano, S. 1987, 25, 23\
[10] Feng, Y., & Krumholz, M. 2014, Nature, 513\
[11] Ramsay, J., & Silverman, B. 2006, Functional Data Analysis, Springer Series in Statistics (Springer New York).\
[12] Papamakarios, G., & Murray, I. 2016, in Advances in Neural Information Processing Systems 29, ed. D. D. Lee, M. Sugiyama, U. V. Luxburg, I. Guyon, & R. Garnett (Curran Associates, Inc.), 1028–1036\
[13] Thomson, D. J. 1982, IEEE Proceedings, 70, 1055 [17] Springford, A., Eadie, G. M., & Thomson, D. J. 2020, 159, 205\
[14] Kjeldsen, H., Christensen-Dalsgaard, J., Handberg, R., et al. 2010, Astronomische Nachrichten, 331, 966