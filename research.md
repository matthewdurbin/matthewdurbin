---
layout: default
title: Research
---
# Current Research
## Gamma Ray Source Localization
<p align="justify">
Based largely on subtle differences in solid angle and array self-occlusion, a point-like gamma ray source will give an approximately unique distribution of counts across an array of stationary detectors. By analyzing these subtle differences, a source can then theoretically be localized. In non-trivial environments, sources of scatter, attenuation, varying background radiation, and other sources of noise can greatly complicate the localization process. This project focuses on using various machine learning algorithms and techniques to improve overall localization capabilities. One algorithmic approach in recent literature involves comparisons to prepopulated reference tables. Preliminary results indicate that machine learning can better capture the relationship between the detector array response and gamma ray source location. These methods have the potential to be applied to various nuclear and homeland security applications, including urban radiation source search and cargo screenings. 
</p>
## Detecting Missing Radioactive material
<p align="justify">
For many safeguard and material accountancy applications, it is advantageous to be able to verify that all material within a sample is accounted for. If material is missing, it is also advantageous to identify the location within a sample that the missing material should be. For example, it is necessary to verify a lack of diversion in spent nuclear fuel assemblies and knowing which specific fuel rod or pin is missing can provide more context and more efficient secondary inspection efforts. One technique to detect for material unaccounted for (MUF) involves analyzing gamma ray spectroscopy measurements. This analysis can be complicated due to various sources of noise and predicting the location within a sample from which material is missing is not necessarily intuitive or straight forward. This project investigates various machine learning algorithms to investigate their potential use in this domain. Simple models of spent fuel assemblies were developed, including an array of sources to collect laboratory data. Machine learning algorithms showed promise in various diversion scenarios even when significant variance was introduced into the testing data, not accounted for in training data. Additionally, algorithms performed well when trained on a simulated array and tested on the laboratory array. 
</p>

## Pulse Shape Discrimination
<p align="justify">
Many detector types, like organic scintillators, are sensitive to both neutron and gamma rays. An individual pulse can theoretically be distinguished by looking into the florescent decay scheme, a process called pulse shape discrimination (PSD). While there are many investigations into machine learning and PSD, most (if not all) methods are supervised classification. This means that training pulses need to be labeled as neutrons or gamma rays prior to the machine learning phase. This calls for a separate PSD routine, which can introduce label bias. This project involves a novel regression approach, in which an k-nearest neighbors (kNN) algorithm is trained to regress upon conventionally calculated pulse shape parameters based on various input features extracted from the raw waveform. This allows for direct comparison to tradition methods by way of a figure of merit (FOM), without the burden of label bias. Datasets of pulses were gathered using various scintillators and light sensors (SiPMs and PMTs) of varying levels of innate PSD capabilities. Results showed that that not only can the FOM be improved over a large light output window, but the light output at which statistical separation of particle clusters can be achieved is lowed with the kNN regression method.
</p>

# Past Research
## Radiation Dammage in Gallium Nitride (GaN)

## Gamma-Gamma Coincidence Detection

## Rotation Based Neutron Detection
