---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

You can find my refereed (incl. submitted) publications on [ADS](https://ui.adsabs.harvard.edu/public-libraries/7Ek22n9ERuaEYfrwLQfFCA).

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