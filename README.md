# ORACLE
Code for numerical simulations of phase-cycled bSSFP profiles, code for processing phantom and in-vivo phase-cycled bSSFP data
**********
Matlab code to simulate phase-cycled bSSFP profiles (in presence of noise). Quantification of T1, T2, off-resonance and proton density using the ORACLE framework. Correction for aliasing effects in the DFT modes of bSSFP profiles. Code for reading out phantom raw data and in-vivo raw data. Code for coil combination using phase-cycled bSSFP. 

**********
Available codes: 

1) S1_ErrorAnalysis_ORACLE:

Contains the (Monte-Carlo simulation) code to simulate noisy bSSFP profiles and to determine the errors of ORACLE for T1, T2, PD and off-resonance quantification in presence of normal distributed complex noise.

2) S2_AliasingCorrection:

Contains the code to correct for the aliasing effects in modes obtained via a discrete Fourier transformation. The upper maximal error bound is calculated for different T1, T2 and off-resonance values in dependence of the number of sampled RF phase increments.

3) E1_ReadRawData_Phantom:

Contains the code to read out phase-cycled bSSFP raw data from Siemens scanners based on the data structure used for the phantom experiments. 

4) E2_ReadRawData_InVivo:

Contains the code to read out phase-cycled bSSFP raw data from Siemens scanners based on the data structure used for the in-vivo experiments. 

5) Coil_Combination

Contains a fast and easy code for coil combination using phase-cycles bSSFP data. To the best of our knowlegde this method is not published and if questions arise or further details for explaination are desired please do not hesitate to contact us. 

6) ORACLE

Contains the code using the analytical solution functions for a bSSFP profile and the proposed aliasing correction method.

***********
One complete phantom and volunteer data set is available for download in the following public zenodo repository: 

https://zenodo.org/records/10286634

***********

Contact:  
Nils MJ Plähn, Bern, Switzerland
E-mail: nils.plaehn@students.unibe.ch
Department of Diagnostic, Interventional and Pediatric Radiology (DIPR), Inselspital, Bern University Hospital, University of Bern, Switzerland
Translation Imaging Center (TIC), Swiss Institute for Translational and Entrepreneurial Medicine, Bern, Switzerland
