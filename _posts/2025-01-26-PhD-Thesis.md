---
layout: post
title: 2019 PhD Thesis
date: 2025-01-26
description: "An Optimisation Framework for Magnetic Resonance Fingerprinting"
tags: PhD DPhil Thesis MRF T2 T2
categories: MRF T1 T2
---

In the summer of 2019, I finished my PhD in Biomedical Imaging at the University of Oxford.  I worked in the Physics group at the Centre for Functional MRI of the Brain (FMRIB), aiming to develop fast and reliable quantitative MRI-based in vivo measurements of magnetisation relaxation parameters T1 and T2.

Thesis title: “An Optimisation Framework for Magnetic Resonance Fingerprinting“.

The document is available online via this link:

https://ora.ox.ac.uk/objects/uuid:14c92874-7b00-4f79-abce-87b05f9cb4d4

**Abstract:**

Magnetic Resonance Fingerprinting (MRF) is an efficient quantitative MRI technique for simultaneously mapping multiple tissue or system properties. This thesis presents a framework for optimising the acquisition parameter schedules of a SpinEcho (SE) Echo Planar Imaging (EPI) MRF pulse sequence, with a view to an application to tracking oedema in acute stroke. Reference quantitative MRI methods were implemented and used for validations of the SE EPI MRF acquisitions. For this purpose a custom phantom was built with relaxation parameters spanning those typical of in vivo grey and white matter. Inversion recovery and spin-echo sequences were used to provide gold standard maps of T1 and T2, respectively. A 3D DREAM protocol was used for B+ 1 mapping and gradient-echo sequences provided B0 off-resonance measurements. Balanced SSFP and FISP MRF sequences were also implemented, with spiral readouts and acquisition parameters similar to those of literature examples. The framework was designed to optimise the SE EPI MRF excitation flip angles, repetition times and the temporal positioning of inversion pulses. Many of the optimisation parameters were flexible and user-specified, such as the targeted T1 and T2 and the evaluation metric. Single-slice and 10-slice schedules were optimised using fmincon and genetic algorithms from MATLAB toolboxes and custom cost functions based on Monte Carlo error simulations. Ten-slice SE EPI MRF schedules requiring 8 seconds and 20 seconds per slice were compared experimentally, with the longer schedules providing the better T1 and T2 accuracy and precision. However, both sets of schedules were unable to fit B+ 1 accurately, necessitating the use of a separately acquired B+ 1 map to correct the dictionary flip angles. Experimental phantom results with B+ 1 correction demonstrated agreement with the theoretical accuracy improvements predicted for the optimised schedules but undesired reductions in precision were observed. Those phantom results suggested that the fmincon schedule marginally outperformed the corresponding genetic algorithm schedule, showing maximum biases of 16.5% for T1 and 4.6% for T2 and maximum spreads of 16.3% for T1 and 14.3% for T2. The FISP MRF sequence provided the best all-round performance


