# Speech Biomarker for Diagnosing Alzheimer's Disease with Topological Data Analysis 
This repository connects to a pilot study in speech biomarkers for diagnosing Alzheimer's disease (AD).
The pilot study aims to use speech in predicting AD diagnosis by developing some standard measurements. 
These measurements are numerical scores connecting to a particular acoustic feature of the soundwave.
Therefore, it has a general score to summarise those measurements.

This repository aims to document the introduce a topological data analysis (TDA) approach to improve the measurement score in the pilot study.
In this repository, the speech data is obtained from a pilot project of a start-up in Warszawa, Poland.
The speech data consists of 10 soundwaves (.wav file) of a vowel 'a' sound. Unfortunately, the .wav data is not open-source.

In this repository, you will find the following:
1) ```feature_extraction```: The first step. A code to convert the raw dataset into all TDA features. Resulting in a file *result_tda.tsv* which will be used in the next step.
2) ```analysing_tda_feature```: The second step. A code to analyse the TDA features in improving the general score from the pilot study.
3) ```comparing_vcd_mci_hc```: a code to get more insights about differences in each group.
