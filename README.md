<img src="https://user-images.githubusercontent.com/43549914/106479048-e0c7ac00-6477-11eb-900b-45843e4f9554.jpg" alt="dhdr logo" width="900" id="top"/>

# Digital Health Data Repository (DHDR)

The DHDR (Digital Health Data Repository) is a repository with sample data for use with the DBDP.

We welcome contributions to the DHDR! If your data is too large to upload here, please consider linking a repo here to another data repository (PhysioNet, UCI ML) while we are working on getting the full DHDR up and running!

# Available Datasets
* [Cardiovascular](#cardiovascular)
* [Activity](#activity)
* [Mental Health](#mental-health)
* [Nutrition](#coming-soon)


## Cardiovascular
| Dataset | Description |
| ------ | ------ |
| [STEP](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Dataset_STEP) | This dataset contains time-synced data from 6 wearable sensors and ECG over 4 activities with skin tone recorded  |

### Electrocardiogram (ECG)
| Dataset | Description |
| ------ | ------ |
|[MHEALTH](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Electrocardiogram%20(ECG)/Dataset_MHEALTH)| Body motion and vital signs recordings for ten volunteers while performing several physical activities. Includes acceleration, rate of turn and magnetic field orientation data as measured at various body positions, and 2-lead ECG measurements.
| [ANSI/AAMI EC13 Test Waveforms](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Electrocardiogram%20(ECG)/Dataset_ANSI_AAMI_EC13_Test_Waveforms) | Synthetic and real waveform recordings that can be used for testing a variety of devices that monitor the electrocardiogram. |
[European ST-T Database](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Electrocardiogram%20(ECG)/Dataset_European_ST_T) | The European ST-T Database is intended to be used for evaluation of algorithms for analysis of ST and T-wave changes. This database consists of 90 annotated excerpts of ambulatory ECG recordings from 79 subjects.|
[Long Term ST Database](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Electrocardiogram%20(ECG)/Dataset_Long_Term_ST) | 86 lengthy ECG recordings of 80 human subjects, chosen to exhibit a variety of events of ST segment changes, including ischemic ST episodes, axis-related non-ischemic ST episodes, episodes of slow ST level drift, and episodes containing mixtures of these phenomena. |
[MIT-BIH Arrythmia Database](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Electrocardiogram%20(ECG)/Dataset_MIT_BIH_Arrhythmia) | 48 half-hour excerpts of two-channel ambulatory ECG recordings, obtained from 47 subjects. |
[MIT-BIH Noise Stress Test Database](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Electrocardiogram%20(ECG)/Dataset_MIT_BIH_Noise_Stress_Test) | 12 half-hour ECG recordings & 3 half-hour recordings of noise typical in ambulatory ECG recordings. |
[STAFF III Database](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Electrocardiogram%20(ECG)/Dataset_STAFF_III) | ECG recordings from 104 patients.

### Continuous Glucose Monitoring (CGM)
| Dataset | Description |
| ------ | ------ |
|[Smartwatch Prediabetes](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Continuous%20Glucose%20Monitoring%20(CGM)/Dataset_GlycemiaWatch)|Data from 16 study participants wearing research-grade wearable devices. Includes glucose concentration, accelerometry, blood volume pulse, electrodermal activity, heart rate, interbeat interval, and skin temperature measurements over 8-10 days.
|[JCHR Diabetes](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Continuous%20Glucose%20Monitoring%20(CGM)/Dataset_Jaeb-T1DEx-Diabetes)|Diabetes-related datasets and their corresponding protocol from 2010 to 2020. *(Recent additions include ReCGM, CITY, WISDM, SENCE, and JDRF.)*
|[REPLACE-BG](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Continuous%20Glucose%20Monitoring%20(CGM)/Dataset_REPLACE-BG)|Data from a 26-week randomized clinical trial of participants who have had T1D for at least one year.

### Blood Oxygen Saturation (SpO2)
| Dataset | Description |
| ------ | ------ |
|[BIDMC_SpO2](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Blood%20Oxygen%20Saturation%20(SpO2)/Dataset_BIDMC_SpO2)|Two annotators manually annotated individual breaths in each recording using the impedance respiratory signal. The 53 recordings within the dataset, each of 8-minute duration.|
|[OxygenSaturationVariability](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Blood%20Oxygen%20Saturation%20(SpO2)/Dataset_OxygenSaturationVariability)|This database contains one-hour oxygen saturation measurements of 36 patients, used for the analysis of oxygen saturation variability. The sampling frequency (SF) used to be 1kHz, but through preprocessing, the SF of the saved data is 1Hz.|

### Photoplethysmogram (PPG)
| Dataset | Description |
| ------ | ------ |
|[PPG-DaLiA](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Photoplethysmogram%20(PPG)/Dataset_PPG-DaLiA)|This multimodal dataset features physiological and motion data, recorded from both a wrist- and a chest-worn device, of 15 subjects while performing a wide range of activities under close to real-life conditions.|
|[WristPPGDuringExercise](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Photoplethysmogram%20(PPG)/Dataset_WristPPGDuringExercise)|This database contains wrist PPGs recorded during walking, running and bike riding. Simultaneous motion estimates and A reference chest ECG are included as well.|

### remote Photoplethysmogram (rPPG)
| Dataset | Description |
| ------ | ------ |
|[UCLA-rPPG](http://visual.ee.ucla.edu/rppg_avatars.htm/)|A largest rPPG dataset of its kind (UCLA-rPPG) with a diverse presence of subject skin tones, in the hope that this could serve as a benchmark dataset for different skin tones in this area and ensure that advances of the technique can benefit all people for healthcare equity.|

### COVID19
| Dataset | Description |
| ------ | ------ |
|[Welltory HRV COVID19 Dataset](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Cardiovascular/Dataset_Welltory_hrv_covid19)|Welltory launched an open research project aimed at identifying diagnostic patterns of coronavirus-inflicted disease detection, progression, and recovery. People with the virus are invited to participate in this study by tracking their symptoms, heart rate variability, and data from wearables such as Apple Watch, Garmin, or Fitbit with the Welltory app.|

## Activity
### Wearables Data
| Dataset | Description |
| ------ | ------ |
| [Stanford Wearables](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Activity/Dataset_StanfordWearables)|HR, accelerometer, steps, activity, skin temperature, calories, and SpO<sub>2</sub> data from 7 wearables|

## Mental Health
### Electroencephalogram (EEG)
| Dataset | Description |
| ------ | ------ |
| [AdolescentsSchizophrenia](https://github.com/DigitalBiomarkerDiscoveryPipeline/Digital_Health_Data_Repository/tree/main/Mental%20Health/Dataset_AdolescentsSchizophrenia)|The subjects were adolescents who had been screened by psychiatrist and divided into two groups: healthy (n = 39) and with symptoms of schizophrenia (n = 45).|

## *Coming Soon*

### *Nutrition*


[back to top](#top)
