---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

*My research lies at the intersection of astrophysics and statistics by developing novel data-driven tools that guide mathematical models of the Milky Way (MW) Galaxy.*

The Basics
----------
Galaxies are the fundamental building blocks in the structure of the Universe. Not only do their observations help us in understanding our own galaxy, the MW, but they also lend themselves as giant and powerful laboratories to study the fundamental laws of physics. The *Big Bang Theory* of the origin of the universe and the existence of *Dark Matter* are some of the biggest breakthroughs in physics and they arose through studies of galaxies [1]. Understanding galaxies is therefore an important astrophysical pursuit, and we now have petabytes of observational data to fully do so.  The only remaining element which I will address head-on is to accelerate our understanding through the development and application of modern statistical techniques.

Also, galaxies are beautiful!

<p align="center">
  <img width="500" height="50" src="https://aaryapatil.github.io/images/galaxy.jpg">
</p>

Thesis Topic
------------
The mechanisms that govern galaxy formation and evolution are encoded in the history of star formation and chemical enrichment within a galaxy. In the MW, we can decode these mechanisms using million-star photometric and spectroscopic surveys of unprecedented quality and scope [2, 3]. My goal is to use these *Big Data* observations to estimate the age-metallicity distribution of stars in different parts of the MW disk, and compare this distribution to Galactic chemo-dynamical models [4, 5]. Particularly, I will test and refine models of *Radial Migration* in the Galaxy, the migration of a star inward or outward from its radius of birth due to changes in its orbit's angular momentum [6, 7].

I follow a bottom-up approach to estimate the age-metallicity distribution of the MW disk. I first develop methods to measure the ages and chemistry of simple populations of stars in the disk, i.e., open clusters. Stars in an open cluster are assumed to have formed simultaneously from the same homogeneous gas cloud, and are expected to have similar ages and chemistry [8, 9, 10]. These assumptions make open clusters ideal for testing age and chemical estimation methods. They are also important for understanding the theory of star formation and evolution, and their role in MW evolution.

I recently submitted a paper, Patil et al., 2021, on the accurate and precise estimation of stellar chemical abundances using *Functional Data Analysis* [11] and *Likelihood-free Inference* [12], and constrained the chemical homogeneity in open cluster M67. I am currently working on *Multitaper Spectral Analysis* [13] to estimate precise stellar ages given asteroseismic time-series data [14].

Publications
------------

### Peer-Reviewed Journal Articles

**Functional data analysis for extracting the intrinsic dimensionality of spectra
Application: chemical homogeneity in open cluster M67**\
Aarya A. Patil, Jo Bovy, Gwendolyn Eadie, & Sebastian Jaimungal, The Astrophysical Journal (ApJ)., submitted (2021)

**The Astropy Project: Building an Open-science Project and Status of the v2.0 Core Package**\
Astropy Collaboration et al. including A. A. Patil, The Astronomical Journal (AJ), Volume 156, Issue 3, article id. 123, 19 pp. (2018) [2840 citations](https://scholar.google.com/scholar?oi=bibs&hl=en&cites=18004325045591676525)

### Conference Proceedings

**Likelihood-free Inference of Chemical Homogeneity in Open Clusters**\
Aarya A. Patil, Jo Bovy, & Gwendolyn Eadie, Joint Statistical Meetings (JSM) Proceedings, American Statistical Association (ASA), pp 1838-1844 (2020)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


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