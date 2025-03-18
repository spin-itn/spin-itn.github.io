---
layout: page
title: Mohammad
parent: PhD Candidates
permalink: /candidates/ESR1_4
nav_order: 4
has_children: false
---

## SPIN ESR 1.4: Ocean floor seismological and environmental monitoring

---

__Name__: Mohammad Amin Aminian        <img src="/candidates/files/esr1_4_1.jpg" alt="drawing" width="300" style="float:right"/>   

__Institution__: Institut de Physique du Globe de Paris (IPGP)

__Email__: aminian@ipgp.fr

__PhD title and defense date__: Quantitative Analysis of Oceanic Crust Shear Velocity Structure Using Seafloor Compliance Measurement Data, December 11, 2024.

---
__Introduction__

I am Mohammad-Amin, originally from Yazd, Iran, and currently pursuing a Ph.D. in the Paris Institute of Planetary Physics in Paris, France. I completed my bachelor's degree in Pure Physics at Yazd University and a master's degree in Exploration Geophysics at the University of Tehran.  During my previous research, I focused on retrieving valuable information from coherent noise in seismic reflection and achieved a 12% improvement in real data quality. Currently, my research is centered on ocean bottom seismology, utilizing multi-sensor data.  My research interests primarily revolve around mathematics and code development for geophysical purposes. I have expertise in using image and signal processing tools to create useful toolboxes for denoising and measuring seismic data.  I am also working on retrieving velocity models  from real data for the earth's crust and oceanic crust using earth response analysis method. 

---
__Publication__

Aminian, Mohammad Amin & Riahi, Mohammad Ali. (2021). Multiple seismic reflections attenuation using parabolic Radon transform. 

Aminian, Mohammad Amin & Riahi, Mohammad Ali. (2022). Enhanced data fidelity after ground roll attenuation using conditional standard deviation clustering obtained from the GARCH model. Exploration Geophysics. 54. 1-17. 10.1080/08123985.2022.2135430. 

---
__Research progress__

I utilized data from the Rhum-Rum Project, a year-long deployment of 57 ocean bottom stations (OBS) near La Reunion Island in 2013. To begin, I employed a comb function to detect and eliminate glitches, or noise caused by the OBS internal system. Next, I removed stacked noise by applying a known period to the data and removed global earthquakes through the use of global catalogs. Recursive STA/LTA was then utilized to remove local events such as storms and hurricanes.

To eliminate the tilt effect, which results in noise in the vertical channel of the seismometer and is primarily caused by ocean currents and fluctuations, I employed variance minimization combined with transfer function methods. Using an innovative clustering method, I was able to isolate the most valuable data based on my specific research goals. 

Finally, I combined the denoised vertical channel with pressure channel data to compute the sea floor compliance function, which measures the response of the seafloor to various frequencies of ocean waves and physical forces. I then employed the Metropolitan-Hasting Monte Carlo inversion algorithm to retrieve the shear velocity of the earth.

{: style="text-align: justify;"}
![](/candidates/files/esr1_4_2.png)
<span>*Map of the Rhum-Rum Project deployment area near La Réunion island, showing the locations of the 57 ocean bottom stations (OBS) used in the study.*</span>
{: style="text-align: justify;"}

{: style="text-align: justify;"}
![](/candidates/files/esr1_4_3.png)
<span>*The power spectra of station RR38 for a period of one month are displayed, illustrating the evolution  of preprocessing steps in different colors.*</span>
{: style="text-align: justify;"}

{: style="text-align: justify;"}
![](/candidates/files/esr1_4_4.png)
<span>*Power spectra and functions for Station RR38. (a) Power spectral density (PSD) of the vertical acceleration channel. (b) PSD of the pressure channel. (c) Coherence function between the vertical and pressure channels. (d) Compliance function.*</span>
{: style="text-align: justify;"}
