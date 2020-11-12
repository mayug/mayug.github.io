---
title: "Phase retrieval for Fourier Ptychography under varying amount of measurements"
collection: publications
permalink: /publication/2018-deep-fpm
excerpt: 'Deep learning based prior to improve phase retieval in Fourier Ptychography Microscopy. Accepted as spotlight paper at British Machine Vision Conference 2018.'
date: 2018-10-01
venue: 'British Machine Vision Conference'
paperurl: 'http://academicpages.github.io/files/deep_fpm_paper.pdf'
citation: ' L. Boominathan, M. Maniparambil, H. Gupta, R. Baburajan, and K. Mitra, “Phase retrieval for fourier ptychography under varying amount of
measurements,” arXiv preprint arXiv:1805.03593, 2018'
---

## Abstract
Fourier Ptychography is a recently proposed imaging technique that yields high-resolution images by computationally transcending the diffraction blur of an optical system. At the crux of this method is the phase retrieval algorithm, which is used for computationally stitching together low-resolution images taken under varying illumination angles of a coherent light source. However, the traditional iterative phase retrieval technique relies heavily on the initialization and also need a good amount of overlap in the Fourier domain for the successively captured low-resolution images, thus increasing the acquisition time and data. We show that an auto-encoder based architecture can be adaptively trained for phase retrieval under both low overlap, where traditional techniques completely fail, and at higher levels of overlap. For the low overlap case we show that a supervised deep learning technique using an autoencoder generator is a good choice for solving the Fourier ptychography problem. And for the high overlap case, we show that optimizing the generator for reducing the forward model error is an appropriate choice. Using simulations for the challenging case of uncorrelated phase and amplitude, we show that our method outperforms many of the previously proposed Fourier ptychography phase retrieval techniques.


## Project website:
http://www.ee.iitm.ac.in/comp_photolab/project-fpm.html


## [Download paper here](http://mayug.github.io/files/deep_fpm_paper.pdf)

