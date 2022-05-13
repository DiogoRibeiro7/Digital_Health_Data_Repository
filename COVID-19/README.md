# Real-time alerting system for COVID-19 and other stress events using wearable data

## Description of Dataset
The pre-processing stage provides consistency between different sources (that is, Fitbit and Apple Watch) and handles missing data. The resolution of the retrieved distinct raw heart rates and steps data from Fitbit and Apple Watch differs. To calculate the RHR overnight for different devices, first we consider the heart rate records where steps are zero and then aggregate the RHR values by calculating the average RHR during nighttime (that is, 24:00 to 7:00).

## Citing this Dataset
Please cite the original study:
> Prof. N.N. Gorbachevskaya, Ph.D. S.V. Borisov. EEG of healthy adolescents and adolescents with symptoms of schizophrenia. (https://www.nature.com/articles/s41591-021-01593-2#data-availability).

Please also cite the DBDP if you are using any module from Digital Biomarker Discovery Pipeline:

> Bent, B., Wang, K., Grzesiak, E., Jiang, C., Qi, Y., Jiang, Y., Cho, P., Zingler, K., Ogbeide, F.I., Zhao, A., Runge, R., Sim, I., Dunn, J. (2020). The Digital Biomarker      Discovery Pipeline: An open source software platform for the development of digital biomarkers using mHealth and wearables data. Journal of Clinical and Translational Science, 1-28. doi:10.1017/cts.2020.511 ([Link to Open Access Article](https://www.cambridge.org/core/journals/journal-of-clinical-and-translational-science/article/digital-biomarker-discovery-pipeline-an-open-source-software-platform-for-the-development-of-digital-biomarkers-using-mhealth-and-wearables-data/A6696CEF138247077B470F4800090E63))

## Dataset

De-identified raw heart rate and steps data used in this study can be downloaded at the following publicly available link: (https://storage.googleapis.com/gbsc-gcp-project-ipop_public/COVID-19-Phase2/COVID-19-Phase2-Wearables.zip)


## Useful DBDP Modules
The DBDP provides code to help analyze this dataset:

* [Pre-processing module](https://github.com/DigitalBiomarkerDiscoveryPipeline/Pre-process)
* [wearablecompute](https://github.com/DigitalBiomarkerDiscoveryPipeline/wearablecompute)
