---
title: "Wave and turbulence separation using dynamic mode decomposition"
collection: publications
permalink: /publication/2024-03-01-Wave_and_turbulence_separation_using_dynamic_mode_decomposition
excerpt: 'This paper is about wave turbulence separation using dynamic mode decomposition in different data sets.'
date: 2024-03-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2403.00223'
citation: 'Chavez-Dorado, J., Scherl, I., DiBenedetto, M. (2024). &quot;Wave and turbulence separation using dynamic mode decomposition.&quot; <i>arXiv:2403.00223</i>.'
---

Separating the effects of waves and turbulence in oceanographic time series is an ongoing challenge because surface wave motion and turbulence fluctuations can occur at overlapping frequencies. As a result, simple bandpass filters cannot effectively separate their dynamics. While more advanced decomposition techniques have been developed, they often entail restrictive assumptions about the wave and turbulence interactions, require synchronized measurements, and/or only decompose the signal spectrally without a time-series reconstruction. To overcome these restrictions, we aim to apply modern data-driven methods to this classical problem by using dynamic mode decomposition (DMD). In this study, we present our new wave-turbulence decomposition technique which uses DMD. The technique is designed to be signal-agnostic such that it can be applied to any generic time series. Our approach requires minimal tuning, where the main user input is the wave frequency range of interest. To demonstrate the method, we apply it to synthetic, field, and laboratory data, and compare the results to other published methods in the literature. We conduct a sensitivity analysis on the synthetic data and find that the most sensitive parameter to the accuracy is the rank truncation in the DMD. Additionally, because of the accuracy of our decomposition technique, we demonstrate how we are able to analyze the velocity autocorrelation of the separated turbulence time series with minimal contamination by the waves. Overall, we find that our decomposition method outperforms the other time-series decomposition methods and provides for robust separation of the waves and turbulence, demonstrating that it is a promising technique with wide application to ocean signal processing. 
