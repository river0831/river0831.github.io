---
layout: page
title: RTP
description: Reactive Compound Transformation Profiler
img: assets/img/proj_rtp.png
importance: 4
category: collaboration
---

<div class="row">
    <div style="margin-left: auto; margin-right: auto;">
        {% include figure.html path="assets/img/proj_overview_rtp.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Illustration of the RTP workflow and the matching algorithm for identifying potential reaction products, with five substeps: (1) peak pair picking and adduct annotation, (2) core structure mass definition, (3) reaction database search, (4) results print-out, and (5) MS2 confirmation. (<a href="https://pubs.acs.org/doi/abs/10.1021/acs.est.1c05262">Click for source image</a>)
</div>

<p class="justify">
Reactive compounds, such as covalent toxicants/drugs, have their ubiquitous occurrences and are known to react with protein or DNA in human beings, but their reactions with endogenous metabolites are rarely understood. Currently, a viable platform is demanded for discovering their reaction products since their efficacy/toxicity may be altered after the reaction. We aim to develop a platform for identifying unknown abiotic or biotransformation products for these reactive compounds. Based on stable isotope-labeling (SIL) metabolomics, we have developed a novel and robust analytical platform, reactive compound transformation profiler (RTP), which can automatically analyze preannotated high-resolution mass spectrometry (LC-HRMS) data sets and uncover probable transformation products. Generally, RTP consists of four complementary steps: (1) selecting peak pairs of light and heavy-labeled products, (2) defining the “core structure mass” for possible reaction search, (3) constructing an endogenous metabolite reaction database, and (4) developing algorithms to propose the potential transformation products by searching against the database with a single-/multiple-site reaction. Its performance was validated using the reactive plasticizer bisphenol A diglycidyl ether (BADGE) in several sample matrices. This platform enabled the identification of novel transformation products while also demonstrating its capacity to filter out the false-positive signals and provide product annotation.
</p>

<p class="justify">
I'm responsible for the development of the platform using C++ and Qt with graphical user interfaces to input data, run algorithm, and view results.
</p>

<p class="justify">
<strong>Background knowledge:</strong> C++, Qt, multi-thread, user interface/interaction design.
</p>