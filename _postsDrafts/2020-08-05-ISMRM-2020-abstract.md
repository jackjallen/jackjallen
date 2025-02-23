---
layout: post
title: ISMRM 2020 abstract
date: 2020-08-05
description: Improved image quality for 3D LGE scar imaging in patients with fast and variable heart rate: a simulation study.
tags: 3D LGE simulation abstract ISMRM2020
categories: 3D LGE simulation abstract ISMRM2020
---

My colleagues and I submitted research to the 2020 annual meeting of the International Society of Magnetic Resonance in Medicine (ISMRM):

Abstract title:
Improved Image Quality for 3D LGE Scar Imaging in Patients with Fast and Variable Heart Rate: a Simulation Study.

Authors:
Jack Allen[1,2], Peter Gatehouse[1,2], Rick Wage[1], David Firmin[1,2], and Jennifer Keegan[1,2].
1: Cardiovascular Magnetic Resonance Unit, Royal Brompton and Harefield NHS Trust, London, United Kingdom,
2: National Heart and Lung Institute, Imperial College London, London, United Kingdom

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
