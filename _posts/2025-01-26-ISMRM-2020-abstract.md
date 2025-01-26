---
layout: post
title: 2020 ISMRM abstract
date: 2020-08-05
description: Improved Image Quality for 3D LGE Scar Imaging in Patients with Fast and Variable Heart Rate: a Simulation Study.
tags: PhD DPhil Thesis MRF T2 T2
categories: MRF T1 T2
---

My colleagues and I submitted research to the 2020 annual meeting of the International Society of Magnetic Resonance in Medicine (ISMRM):

Improved Image Quality for 3D LGE Scar Imaging in Patients with Fast and Variable Heart Rate: a Simulation Study.
Jack Allen1,2, Peter Gatehouse1,2, Rick Wage1, David Firmin1,2, and Jennifer Keegan1,2
1Cardiovascular Magnetic Resonance Unit, Royal Brompton and Harefield NHS Trust, London, United Kingdom, 2National Heart and Lung Institute, Imperial College London, London, United Kingdom

We used numerical phantom simulations to compare three methods for choosing the Inversion Times (TIs) of Late Gadolinium-Enhanced (LGE) scans for patients with irregular heart rates.

Our summary of the work is provided below:

    3D LGE is used to assess scar in patients with atrial fibrillation. However, the fast and variable heart rate in these patients results in poor image quality. An existing dynamic-TI method varies inversion time on a beat-by-beat basis (according to the previous cardiac cycle length) to improve myocardial nulling, but blood signal variations are incompletely corrected and cause ghosting. We have developed an improved technique which bases the beat-by-beat TI on the history of RR intervals (rather than the previous one) and reduces blood signal variations while maintaining myocardial nulling. Simulations with patient RR interval distributions show significantly improved results.

The figure below shows an example of each method for a numerical phantom simulation, showing improved image clarity for the dynamic TI methods versus using a fixed TI. The ring represents a cross-section of myocardium around the blood pool. The small bright region represents myocardial scarring. The three images highlight that the new approach focuses on reducing image ghosting from the blood signal. Image intensity is shown in arbitrary units.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ISMRM2020abstract.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
</div>
