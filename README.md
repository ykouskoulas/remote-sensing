# Classification techniques for remotely sensing radar data

## What is this?

This repository contains a Ph.D. thesis and two peer-reviewed
publications describing the development of mathematics and software
tools for classifying short vegetation based on subtle structural
differences using synthetic aperature radar.

## Documentation

The first paper titled

*"A Computationally Efficient Multivariate Maximum-Entropy Density
Estimation (MEDE) Technique"*

was published in IEEE Transactions in Geoscience and Remote Sensing in
2004. It develops a novel statistical technique for density estimation
that improves on the accuraracy of existing techniques, and is
appropriate for polarimetric radar data.

Abstract:

Density estimation is the process of taking a set of multivariate data
and finding an estimate for the probability density function (pdf)
that produced it. One approach for obtaining an accurate estimate of
the true density is to use the polynomial-moment method with
Boltzmann–Shannon entropy. Although rigorous mathematically, the
method is difficult to implement in practice because the solution
involves a large set of simultaneous nonlinear integral equations, one
for each moment or joint moment constraint. Solutions available in the
literature are generally not easily applicable to multivariate data,
nor computationally efficient. In this paper, we take the functional
form that was developed in this problem and apply pointwise estimates
of the pdf as constraints. These pointwise estimates are transformed
into basis coefficients for a set of Legendre polynomials. The
procedure is mathematically similar to the multidimensional Fourier
transform, although with different basis functions. We apply this
technique, called the maximum-entropy density estimation (MEDE)
technique, to a series of multivariate datasets.

The second paper titled

*"The Bayesian Hierarchical Classifier (BHC) and Its Application to
Short Vegetation Using Multifrequency Polarimetric SAR"*

was also published in IEEE Transactions in Geoscience and Remote
Sensing in 2004. It describes the application of the statistical
technique described above to remotely sensed data and demonstrates the
ability to classify different types of short vegetation more
accurately -- despite variability in plant structure and differences
in plant development -- that previously available techniques.

Abstract:

Given an image of a scene comprised of a number
of distinct terrain classes, the optimum Bayesian classifier (OBC)
provides the highest possible classification accuracy of the imaged
scene, provided we have a priori knowledge of the probability den-
sity function (pdf) of the sensor’s output for each terrain class.
If the imaging sensor consists of multiple channels, application of
OBC requires knowledge of the joint pdf of the observations made
by all the channels. In practice, the volume of data needed in order
to generate an accurate multidimensional pdf far exceeds the size
of available datasets. The data-size requirement may be relaxed by
assuming the pdfs to be Gaussian in form, but such an assump-
tion leads to suboptimum classification performance. This paper
addresses the data size issue by 1) taking advantage of the max-
imum-entropy density estimation (MEDE) technique introduced
in a companion paper and 2) using marginal pdfs in a hierarchical
approach. Using multidate synthetic aperture radar observations,
it was shown that the Bayesian hierarchical classifier introduced
in this paper can classify short vegetation classes with an accuracy
of 93%, without retraining, compared with an accuracy of 84%
for the maximum-likelihood estimator (with Gaussian assumption)
and only 74% with ISODATA.

The Ph.D. thesis is titled

*"The Application of Maximum Entropy Density Estimation to the
Classification of Short Vegetation Using Multifrequency, Polarimetric
SAR"*

The dissertation was defended in September 2000 and published in
2001. It predates both papers and provides a full book-length tutorial
on remote sensing processes, the short vegetation problem, and
detailed descriptions of development of, application of, and
classification results from the statistical techniques discussed
above.

## About me

Work/projects: https://www.linkedin.com/in/ykouskoulas

Publications:  https://orcid.org/0000-0001-7347-7473

This repo:     https://github.com/ykouskoulas/remote-sensing
