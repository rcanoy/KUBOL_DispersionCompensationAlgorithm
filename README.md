# KUBOL_DispersionCompensationAlgorithm
Dispersion compensation algorithm which is based on the optimisation of the coefficient of variation of a cross-sectional Optical Coherence Microscope images.

Note:
These codes were written during my Master of Engineering in Biomicrosystem Engineering degree at the Korea University Biomedical Optics Laboratory (2020-2022) under the supervision of Professor Beop-Min Kim.
For questions or suggestions to improve the codes, please email recanoy@alum.up.edu.ph.

### Files:

* **Dataset - Tape Phantom:**
  * BACKDATA: reference arm intensity
  * RAW: spectrometer-collected intensity
* **Functions:**
  * `bin2mat.m`: This function converts binary files to a MATLAB matrix
  * `kLinearization.m`: This function performs  k-dependent linearization on the reference intensity images 
  * `dispersion_optimization.m`: This function performs a dispersion compensation on the processed cross-sectional images
* **Dispersion Compensation Pipeline**
  * `dispersion_compensation_pipeline.m`


### References:

[1] [YG Kang, RJE Canoy, et al., *Biomed. Opt. Express* **14**, 2 (2023).](https://opg.optica.org/boe/fulltext.cfm?uri=boe-14-2-577&id=524732)

[2] [RJE Canoy, *An analysis of a split-spectrum-based functional Optical Coherence technique as a quantitative tool to monitor cellular behaviors (DCOLL211009)000000269071 [Master's thesis*, Korea University, Seoul, South Korea], pp. 13-19, (2022).](https://dcollection.korea.ac.kr/public_resource/pdf/000000269071_20230221150939.pdf)
