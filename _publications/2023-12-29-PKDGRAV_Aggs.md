---
title: "An Efficient Numerical Approach to Modeling the Effects of Particle Shape on Rubble-pile Dynamics"
collection: publications
category: manuscripts
permalink: /publication/2023-12-29
excerpt: ''
date: 2023-12-29
venue: 'The Planetary Science Journal'
paperurl: 'https://jdema.github.io/files/Marohnic23.pdf'
---
Recommended Citation: 

Marohnic, J. C., **DeMartini, J. V.**, Richardson, D. C., Zhang, Y., & Walsh, K. J. (2023). An Efficient Numerical Approach to Modeling the Effects of Particle Shape on Rubble-pile Dynamics. _Planetary Science Journal_, 4(12), 245.

DOI: [10.3847/PSJ/ad0467](https://doi.org/10.3847/PSJ/ad0467)

ADS: [An Efficient Numerical Approach to Modeling the Effects of Particle Shape on Rubble-pile Dynamics](https://ui.adsabs.harvard.edu/abs/2023PSJ.....4..245M/abstract)

Abstract:

We present an approach for the inclusion of nonspherical constituents in high-resolution N-body discrete element 
method (DEM) simulations. We use aggregates composed of bonded spheres to model nonspherical components. Though the 
method may be applied more generally, we detail our implementation in the existing N-body code pkdgrav. It has long 
been acknowledged that nonspherical grains confer additional shear strength and resistance to ﬂow when compared 
with spheres. As a result, we expect that rubble-pile asteroids will also exhibit these properties and may behave 
differently than comparable rubble piles composed of idealized spheres. Since spherical particles avoid some 
signiﬁcant technical challenges, most DEM gravity codes have used only spherical particles or have been conﬁned to 
relatively low resolutions. We also discuss the work that has gone into improving performance with nonspherical 
grains, building on pkdgravʼs existing leading-edge computational efﬁciency among DEM gravity codes. This allows 
for the addition of nonspherical shapes while maintaining the efﬁciencies afforded by pkdgravʼs tree implementation 
and parallelization. As a test, we simulated the gravitational collapse of 25,000 nonspherical bodies in parallel. 
In this case, the efﬁciency improvements allowed for an increase in speed by nearly a factor of 3 when compared 
with the naive implementation. Without these enhancements, large runs with nonspherical components would remain 
prohibitively expensive. Finally, we present the results of several small-scale tests: spin-up due to the YORP 
effect, tidal encounters, and the Brazil nut effect. In all cases, we ﬁnd that the inclusion of nonspherical 
constituents has a measurable impact on simulation outcomes.
