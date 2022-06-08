# Glycemic Health Monitoring for Prediabetes via Noninvasive Smartwatches 

## Dataset 
The datasets were generated from [this study by Bent et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8172541/) *Files will soon be available for download on PhysioNet.*

## Description of Dataset
This data was collected in a study that aimed to evaluate the feasibility and effectiveness of wearables devices in detecting early physiological changes prior to prediabetes development. The researchers generated digital biomarkers for prediabetes and hyperglycemia risk to identify individuals that should undergo further clinical testing.

Using the Dexcom G6 continuous glucose monitor and the Empatica E4 wrist-worn wearable devices, data was collected from 16 study participants over 8-10 days. Features include interstitial glucose concentration, tri-axial accelerometry, blood volume pulse, electrodermal activity, heart rate, interbeat interval, and skin temperature. Note that all data is time shifted.

## Citing this Dataset
Please cite the original paper by Bent et al. (2021) when using this dataset.  
> Bent B, Cho PJ, Henriquez M, et al. Engineering digital biomarkers of interstitial glucose from noninvasive smartwatches. NPJ Digit Med. 2021;4(1):89. Published 2021 Jun 2. doi:10.1038/s41746-021-00465-w

## Analyzing this Dataset
[cgmquantify](https://github.com/DigitalBiomarkerDiscoveryPipeline/cgmquantify) is a Python package provided by the DBDP for
analyzing glucose and glucose variability. The package is also [available in R](https://cran.r-project.org/web/packages/cgmquantify/index.html).

Please cite the DBDP for use of the above packages:

> Bent, B., Wang, K., Grzesiak, E., Jiang, C., Qi, Y., Jiang, Y., Cho, P., Zingler, K., Ogbeide, F.I., Zhao, A., Runge, R., Sim, I., Dunn, J. (2020). The Digital Biomarker      Discovery Pipeline: An open source software platform for the development of digital biomarkers using mHealth and wearables data. Journal of Clinical and Translational Science, 1-28. doi:10.1017/cts.2020.511 ([Link to Open Access Article](https://www.cambridge.org/core/journals/journal-of-clinical-and-translational-science/article/digital-biomarker-discovery-pipeline-an-open-source-software-platform-for-the-development-of-digital-biomarkers-using-mhealth-and-wearables-data/A6696CEF138247077B470F4800090E63))

## Previous Studies utilizing Dataset
This data has only been used in the study by Bent et al.

## Additional Usage Information
Further use of this dataset may involve, but is not limited to, the analysis of measurements from a research-grade wrist-worn wearable device or glycemic variability correlation with physical activity.