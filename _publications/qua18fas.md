---
title: "Fast uncertainty quantification of activation sequences in patient-specific cardiac electrophysiology meeting clinical time constraints"
collection: publications
category: manuscripts
permalink: /publication/2018-07-01-fast-uncertainty-quantification
excerpt: 'We present a fast, patient-specific methodology for uncertainty quantification in electrophysiology, aimed at meeting the time constraints of clinical practitioners. We focus on computing the statistics of the activation map, given the uncertainties associated with the conductivity tensor modeling the fiber orientation in the heart. We use a fast parallel solution method implemented on a graphics processing unit for the eikonal approximation, in order to compute the activation map and to sample the random fiber field with correlation on the basis of geodesic distances. While this enables to perform uncertainty quantification studies with a manageable computational effort, the required time frame still exceeds clinically suitable time expectations. In order to reduce it further by 2 orders of magnitude, we rely on Bayesian multifidelity methods. In particular, we propose a low-fidelity model that is patient-specific and free from the additional training cost associated with reduced models. This is achieved by a sound physics–based simplification of the full eikonal model. The low-fidelity output is then corrected by the standard multifidelity framework. In practice, the complete procedure only requires approximately 100 new runs of our eikonal graphics processing unit solver for producing the sought estimates and their associated credible intervals, enabling a full online analysis in less than 5 minutes.'
date: 2018-07-01
venue: 'International Journal for Numerical Methods in Biomedical Engineering'
paperurl: 'https://doi.org/10.1002/cnm.2985'
citation: 'A. Quaglino, S. Pezzuto, P. Koutsourelakis, A. Auricchio, and R. Krause. (2018). &quot;Fast uncertainty quantification of activation sequences in patient-specific cardiac electrophysiology meeting clinical time constraints.&quot; <i>International Journal for Numerical Methods in Biomedical Engineering</i>, 34(7).'
---
