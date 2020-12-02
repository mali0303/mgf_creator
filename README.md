# mgf_creator
Creates individual MGF files of metabolites of interests for identification purposes from a collection of mass spectrometry data files.

In metabolomics mass spectrometry experiments, individual mgf files of significant metabolites have to be manually searched and created which is later loaded in NIST libraries for identification. This is a laborius and time consuming process.

This program automates the process of mgf creation. It requires a list of significant features along with their m/z values and retention time. It then extracts each feature from the sample files loaded in the "samples" folder. The sample files in the "samples" folder are generated through autoMSn and exported in .mgf format.

The program creates folder for each feature and subfolder for each sample from which the mgf file was extracted. It also creates a "Results.csv" which list the properties of mgf files created for a quick view.
