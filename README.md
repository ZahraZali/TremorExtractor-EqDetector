# TremorExtractor-EqDetector  
[![DOI](https://zenodo.org/badge/490198425.svg)](https://zenodo.org/badge/latestdoi/490198425)  

**Volcanic Tremor Extraction and Earthquake Detection Using Music Information Retrieval Algorithms**  

---

## Overview  

**TremorExtractor-EqDetector** is a Python-based algorithm for:  
- Extracting **harmonic tremor signals** from seismic waveforms  
- Detecting **transient signals** such as earthquakes  

The method is particularly useful in **volcano seismology**, where separating tremor and earthquakes is essential for monitoring eruptive activity.  

---

## Repository Structure  

This repository contains two main modules:  

1. **Harmonic Tremor Extraction**  
   - Python codes for extracting tremor signals from seismic waveforms, preserving phase information  
   - Example dataset: one-day seismic waveform from the **Holuhraun 2014–2015 eruption** in Iceland (station FLUR, network 7Z, White 2010)  
   - Example outputs:  
     - Spectrogram of the raw waveform, extracted tremor, and transient signals  
     - Extracted harmonic tremor as an `.mseed` file  

2. **Transient Signal Detection**  
   - Python codes for transient (earthquake) detection  
   - Earthquake timing using a characteristic function  
   - Example outputs:  
     - Marker file of detected earthquakes  
     - Marker file of P-wave arrivals  

---

## Citations and Links  

When using this algorithm, please cite:  

**Zali, Z., Ohrnberger, M., Scherbaum, F., Cotton, F., & Eibl, E. P.** (2021).  
*Volcanic tremor extraction and earthquake detection using music information retrieval algorithms.*  
*Seismological Research Letters, 92*(6), 3668–3681.  
[https://doi.org/10.1785/0220210016](https://doi.org/10.1785/0220210016)  

---

## Contact  

**Author:** Zahra Zali  
Email: zali@gfz.de  
