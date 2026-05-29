---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m Max Kurzner, a PhD candidate in astrophysics at the University of Victoria studying galaxy morphology and evolution in the Virgo Cluster. My research combines large-scale astronomical imaging, statistical modeling, and machine learning to characterize galaxy structure, evaluate classification systems, and understand their limitations under heterogeneous data quality and distribution shift. Much of my research involves building reproducible data pipelines, cleaning and validating complex datasets, defining derived metrics, and evaluating model performance under noisy labels, limited supervision, and domain shift. I am especially interested in applying this experience to data science, analytics engineering, machine learning evaluation, and AI-enabled decision systems. I am an expert in sifting through complex, messy and unstructure data and turning into real insights and understanding. Please get in touch if you would like to discuss anything related to galaxy evolution as well as data science and data insights for the greater good!


Visual and Quantitative Morphologies of the Virgo Cluster: Large-Scale Scientific Data Catalogues
======
I led a comprehensive study of galaxy morphologies in the Virgo Cluster using imaging from the [Next Generation Virgo Cluster Survey (NGVS)](https://www.ngvs-astro.org/). This work combines traditional visual classifications with a broad suite of catalog measurements, including magnitudes, colours, sizes, and environmental density, alongside non-parametric morphology metrics measured with [statmorph](https://statmorph.readthedocs.io/en/latest/).

Together, these data provide a homogeneous morphological census of Virgo galaxies across a wide range of stellar masses, surface brightnesses, and environments. The project is both an astrophysical study of galaxy structure and a large-scale data-curation effort: it required building consistent sample definitions, validating classifications, comparing external catalogues, and producing reusable data products for future work on galaxy evolution and machine learning.

The NGVS Morphology Paper was accepted to *The Astrophysical Journal*, and is available [here](https://iopscience.iop.org/article/10.3847/1538-3881/ae1616).


Machine Learning Applications to Galaxy Morphology
------
My thesis also explores how machine learning can be used to classify galaxy morphology in large astronomical surveys. This work combines structured catalogue data and galaxy imaging to evaluate both classical machine-learning models and image-based deep-learning approaches, including transfer learning with convolutional neural networks.
A central goal of this project is not simply to maximize classification accuracy, but to understand when model predictions are reliable. I focus on model behaviour under noisy labels, limited training data, rare classes, domain shift, and heterogeneous image quality. This includes comparing model outputs to human classifications and external catalogues, identifying systematic failure modes, and asking which predictions are trustworthy enough for downstream scientific analysis.
This work is motivated by the next generation of large surveys, including Euclid, Rubin/LSST, and Roman, where automated morphology measurements will be essential but must be carefully validated against high-quality local benchmark data sets such as the NGVS. I am currently developing this thesis work into a manuscript on practical machine-learning applications to galaxy morphology in the local Universe.


Statistical Modelling and Population-Level Inference of Nuclear Star Clusters
------

I also study nuclear star clusters (NSCs): compact stellar systems found at the centres of many galaxies. NSCs are important tracers of galaxy formation and evolution because they sit at the interface between star clusters, galactic nuclei, and their host galaxies. Their presence, absence, masses, colours, and structural properties provide clues about how galaxies build their central stellar components through processes such as in-situ star formation, globular-cluster inspiral, dynamical friction, mergers, and environmental transformation.
My NSC work uses the NGVS to build a large, homogeneous census of nucleated galaxies in the Virgo Cluster and to study how nucleation depends on host-galaxy mass, morphology, colour, and environment. This project combines visual classification, photometric measurements, statistical modelling, and uncertainty-aware population analysis.
A major goal is to understand why some galaxies form or retain nuclear star clusters while others do not, and how these trends connect to broader patterns in galaxy structure and evolution. In my thesis and recently submitted NSC paper, I use the NGVS sample to measure nucleation fractions, compare them with previous Virgo studies, and examine how morphology modulates the relationship between stellar mass and nuclear-cluster occupation.



<div style="text-align:center;">
  <img src="/images/max_nsc_fractions_virgo.png" alt="NSC fractions in Virgo" style="width:50%; max-width:100%; height:auto;">
</div>

Colour Images for Virgo Cluster Galaxies
------
As part of my work in determining visual morphologies of galaxies in the Virgo cluster I have created colour images with the ugi images for the entire NGVS. At the moment, these images are only available by request, but in the near future, they will be made accessible to all members of the NGVS team. In the meantime, should you be interested in using any of these images in your research or a talk, feel free to get in touch!

![Colour Image](/images/NGC4501_VCC1401.jpeg)



