# AI/ML in Parkinson's Disease (PD) Research | Literature Review

## Table of Contents
- [Accessible, At-Home Detection of Parkinson's Disease via Multi-task Video Analysis](#accessible-at-home-detection-of-parkinsons-disease-via-multi-task-video-analysis)
- [Unmasking Parkinson’s Disease with Smiles: An AI-enabled Screening Framework](#unmasking-parkinsons-disease-with-smiles-an-ai-enabled-screening-framework)
- [A Novel Fusion Architecture for PD Detection Using Semi-Supervised Speech Embeddings](#a-novel-fusion-architecture-for-pd-detection-using-semi-supervised-speech-embeddings)
- [A User-Centered Framework to Empower People with Parkinson’s Disease](#a-user-centered-framework-to-empower-people-with-parkinsons-disease)
- [Body-worn sensors for Parkinson's disease management: A European perspective](#body-worn-sensors-for-parkinsons-disease-management-a-european-perspective)
- [Using AI to Measure Parkinson’s Disease Severity at Home](#using-ai-to-measure-parkinsons-disease-severity-at-home)
- [Monitoring gait at home with radio waves in Parkinson’s disease: A marker of severity, progression, and medication response](#monitoring-gait-at-home-with-radio-waves-in-parkinsons-disease-a-marker-of-severity-progression-and-medication-response)
- [Artificial intelligence-enabled detection and assessment of Parkinson’s disease using nocturnal breathing signals](#artificial-intelligence-enabled-detection-and-assessment-of-parkinsons-disease-using-nocturnal-breathing-signals)
- [Analyzing Head Pose in Remotely Collected Videos of People with Parkinson’s Disease](#analyzing-head-pose-in-remotely-collected-videos-of-people-with-parkinsons-disease)
- [Detecting Parkinson Disease Using a Web-Based Speech Task: Observational Study](#detecting-parkinson-disease-using-a-web-based-speech-task-observational-study)
- [An Intelligent Mobile-Enabled System for Diagnosing Parkinson Disease: Development and Validation of a Speech Impairment Detection System](#an-intelligent-mobile-enabled-system-for-diagnosing-parkinson-disease-development-and-validation-of-a-speech-impairment-detection-system)
- [Diagnosing Parkinson Disease Through Facial Expression Recognition: Video Analysis](#diagnosing-parkinson-disease-through-facial-expression-recognition-video-analysis)

<hr>

## [Accessible, At-Home Detection of Parkinson's Disease via Multi-task Video Analysis](https://arxiv.org/abs/2406.14856)

**Publication Date:** 13 Dec, 2024 (Preprint)  
**Journal:** arXiv  

**Abstract:**  
Limited accessibility to neurological care leads to underdiagnosed Parkinson's Disease (PD), preventing early intervention. Existing AI-based PD detection methods primarily focus on unimodal analysis of motor or speech tasks, overlooking the multifaceted nature of the disease. To address this, we introduce a large-scale, multi-task video dataset consisting of 1102 sessions (each containing videos of finger tapping, facial expression, and speech tasks captured via webcam) from 845 participants (272 with PD). We propose a novel Uncertainty-calibrated Fusion Network (UFNet) that leverages this multimodal data to enhance diagnostic accuracy. UFNet employs independent task-specific networks, trained with Monte Carlo Dropout for uncertainty quantification, followed by self-attended fusion of features, with attention weights dynamically adjusted based on task-specific uncertainties. To ensure patient-centered evaluation, the participants were randomly split into three sets: 60% for training, 20% for model selection, and 20% for final performance evaluation. UFNet significantly outperformed single-task models in terms of accuracy, area under the ROC curve (AUROC), and sensitivity while maintaining non-inferior specificity. Withholding uncertain predictions further boosted the performance, achieving 88.0+-0.3%$ accuracy, 93.0+-0.2% AUROC, 79.3+-0.9% sensitivity, and 92.6+-0.3% specificity, at the expense of not being able to predict for 2.3+-0.3% data (+- denotes 95% confidence interval). Further analysis suggests that the trained model does not exhibit any detectable bias across sex and ethnic subgroups and is most effective for individuals aged between 50 and 80. Requiring only a webcam and microphone, our approach facilitates accessible home-based PD screening, especially in regions with limited healthcare resources.
  
**Link:** [https://arxiv.org/abs/2406.14856](https://arxiv.org/abs/2406.14856) 

<br>

## [Unmasking Parkinson’s Disease with Smiles: An AI-enabled Screening Framework](https://arxiv.org/abs/2308.02588)
**Publication Date:** 18 November, 2024  
**Journal:** arXiv  

**Abstract:**  
We present an efficient and accessible Parkinson's Disease (PD) screening method by leveraging AI-driven models enabled by the largest video dataset of facial expressions from 1,059 unique participants. This dataset includes 256 individuals with PD (165 clinically diagnosed and 91 self-reported). Participants used webcams to record themselves mimicking three facial expressions (smile, disgust, and surprise) from diverse sources encompassing their homes across multiple countries, a US clinic, and a PD wellness center in the US. Facial landmarks are automatically tracked from the recordings to extract features related to hypomimia, a prominent PD symptom characterized by reduced facial expressions. Machine learning algorithms are trained on these features to distinguish between individuals with and without PD. The model was tested for generalizability on external (unseen during training) test videos collected from a US clinic and Bangladesh. An ensemble of machine learning models trained on smile videos achieved an accuracy of 87.9+-0.1% (95% Confidence Interval) with an AUROC of 89.3+-0.3% as evaluated on held-out data (using k-fold cross-validation). In external test settings, the ensemble model achieved 79.8+-0.6% accuracy with 81.9+-0.3% AUROC on the clinical test set and 84.9+-0.4% accuracy with 81.2+-0.6% AUROC on participants from Bangladesh. In every setting, the model was free from detectable bias across sex and ethnic subgroups, except in the cohorts from Bangladesh, where the model performed significantly better for female participants than males. Smiling videos can effectively differentiate between individuals with and without PD, offering a potentially easy, accessible, and cost-efficient way to screen for PD, especially when a clinical diagnosis is difficult to access.  

**Link:** [https://arxiv.org/abs/2308.02588](https://arxiv.org/abs/2308.02588)  

<br>

## [A Novel Fusion Architecture for PD Detection Using Semi-Supervised Speech Embeddings](https://arxiv.org/abs/2405.17206) 
**Publication Date:** 18 November, 2024  
**Journal:** arXiv  

**Abstract:**  
We present a framework to recognize Parkinson's Disease (PD) through an English pangram utterance speech collected using a web application from diverse recording settings and environments, including participants' homes. Our dataset includes a global cohort of 1306 participants, including 392 diagnosed with PD. Leveraging the diversity of the dataset, spanning various demographic properties (such as age, sex, and ethnicity), we used deep learning embeddings derived from semi-supervised models such as Wav2Vec 2.0, WavLM, and ImageBind representing the speech dynamics associated with PD. Our novel fusion model for PD classification, which aligns different speech embeddings into a cohesive feature space, demonstrated superior performance over standard concatenation-based fusion models and other baselines (including models built on traditional acoustic features). In a randomized data split configuration, the model achieved an Area Under the Receiver Operating Characteristic Curve (AUROC) of 88.94% and an accuracy of 85.65%. Rigorous statistical analysis confirmed that our model performs equitably across various demographic subgroups in terms of sex, ethnicity, and age, and remains robust regardless of disease duration. Furthermore, our model, when tested on two entirely unseen test datasets collected from clinical settings and from a PD care center, maintained AUROC scores of 82.12% and 78.44%, respectively. This affirms the model's robustness and its potential to enhance accessibility and health equity in real-world applications.  

**Link:** [https://arxiv.org/abs/2405.17206](https://arxiv.org/abs/2405.17206)  

<br>

## [A User-Centered Framework to Empower People with Parkinson’s Disease](https://dl.acm.org/doi/10.1145/3631430)
**Publication Date:** 12 January, 2024  
**Journal:** Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies  

**Abstract:**  
We present a user-centric validation of a teleneurology platform, assessing its effectiveness in conveying screening information, facilitating user queries, and offering resources to enhance user empowerment. This validation process is implemented in the setting of Parkinson's disease (PD), in collaboration with a neurology department of a major medical center in the USA. Our intention is that with this platform, anyone globally with a webcam and microphone-equipped computer can carry out a series of speech, motor, and facial mimicry tasks. Our validation method demonstrates to users a mock PD risk assessment and provides access to relevant resources, including a chatbot driven by GPT, locations of local neurologists, and actionable and scientifically-backed PD prevention and management recommendations. We share findings from 91 participants (48 with PD, 43 without) aimed at evaluating the user experience and collecting feedback. Our framework was rated positively by 80.85% (standard deviation ± 8.92%) of the participants, and it achieved an above-average 70.42 (standard deviation ± 13.85) System-Usability-Scale (SUS) score. We also conducted a thematic analysis of open-ended feedback to further inform our future work. When given the option to ask any questions to the chatbot, participants typically asked for information about neurologists, screening results, and the community support group. We also provide a roadmap of how the knowledge generated in this paper can be generalized to screening frameworks for other diseases through designing appropriate recording environments, appropriate tasks, and tailored user-interfaces.  

**Link:** [https://dl.acm.org/doi/10.1145/3631430](https://dl.acm.org/doi/10.1145/3631430)  

<br>

## [Body-worn sensors for Parkinson's disease management: A European perspective](https://www.nature.com/articles/s41531-023-00585-y)  
**Publication Date:** 2 November, 2023  
**Journal:** Nature  

**Abstract:**  
Parkinson's disease (PD) affects about 1.2 million patients in Europe with a prevalence expected to increase exponentially in the coming decades. This epidemiological trend will be challenged by the limited number of neurologists available to provide expert PD care. As PD becomes better recognized, patients increasingly demand rigorous symptom control and therapeutic education. The highly variable nature of symptoms between patients and fluctuations within individual patients necessitates innovative tools to monitor the disease in daily living environments and optimize treatment adaptation. Currently, various body-worn sensors (BWS) are being developed to monitor parkinsonian clinical features including motor fluctuations, dyskinesia, tremor, bradykinesia, freezing of gait (FoG), and other gait disturbances. These BWS serve as supplementary tools for patient management and research. This work presents a practical anthology summarizing the characteristics of the most widely used BWS for PD patients in Europe, focusing on their role in improving treatment management. The discussion also includes considerations for using technology to monitor non-motor symptoms. While BWS offer significant opportunities to enhance PD management strategies, their precise role in routine clinical care requires further clarification.  

**Link:** [https://www.nature.com/articles/s41531-023-00585-y](https://www.nature.com/articles/s41531-023-00585-y)

<br>

## [Using AI to Measure Parkinson’s Disease Severity at Home](https://www.nature.com/articles/s41746-023-00905-9)  
**Publication Date:** 23 August, 2023  
**Journal:** Nature Digital Medicine  

**Abstract:**  
We present an artificial intelligence (AI) system to remotely assess the motor performance of individuals with Parkinson's disease (PD). In our study, 250 global participants performed a standardized motor task involving finger-tapping in front of a webcam. To establish the severity of Parkinsonian symptoms based on the finger-tapping task, three expert neurologists independently rated the recorded videos on a scale of 0 to 4, following the Movement Disorder Society Unified Parkinson's Disease Rating Scale (MDS-UPDRS). The inter-rater reliability was excellent, with an intra-class correlation coefficient (ICC) of 0.88. We developed computer algorithms to obtain objective measurements that align with the MDS-UPDRS guideline and are strongly correlated with the neurologists' ratings. Our machine learning model trained on these measures outperformed two MDS-UPDRS certified raters, with a mean absolute error (MAE) of 0.58 points compared to the raters' average MAE of 0.83 points. However, the model performed slightly worse than the expert neurologists (0.53 MAE). The methodology can be replicated for similar motor tasks, providing the possibility of evaluating individuals with PD and other movement disorders remotely, objectively, and in areas with limited access to neurological care.  

**Link:** [https://www.nature.com/articles/s41746-023-00905-9](https://www.nature.com/articles/s41746-023-00905-9)  

<br>


## [Monitoring gait at home with radio waves in Parkinson’s disease: A marker of severity, progression, and medication response](https://www.science.org/doi/10.1126/scitranslmed.adc9669)  
**Publication Date:** 21 September, 2022  
**Journal:** Science Translational Medicine  

**Abstract:**  
Parkinson’s disease (PD) is the fastest-growing neurological disease in the world. A key challenge in PD is tracking disease severity, progression, and medication response. Existing methods are semisubjective and require visiting the clinic. In this work, we demonstrate an effective approach for assessing PD severity, progression, and medication response at home, in an objective manner. We used a radio device located in the background of the home. The device detected and analyzed the radio waves that bounce off people’s bodies and inferred their movements and gait speed. We continuously monitored 50 participants, with and without PD, in their homes for up to 1 year. We collected over 200,000 gait speed measurements. Cross-sectional analysis of the data shows that at-home gait speed strongly correlates with gold-standard PD assessments, as evaluated by the Movement Disorder Society-Sponsored Revision of the Unified Parkinson’s Disease Rating Scale (MDS-UPDRS) part III subscore and total score. At-home gait speed also provides a more sensitive marker for tracking disease progression over time than the widely used MDS-UPDRS. Further, the monitored gait speed was able to capture symptom fluctuations in response to medications and their impact on patients’ daily functioning. Our study shows the feasibility of continuous, objective, sensitive, and passive assessment of PD at home and hence has the potential of improving clinical care and drug clinical trials.  

**Link:** [https://www.science.org/doi/10.1126/scitranslmed.adc9669](https://www.science.org/doi/10.1126/scitranslmed.adc9669)

<br>

## [Artificial intelligence-enabled detection and assessment of Parkinson’s disease using nocturnal breathing signals](https://www.nature.com/articles/s41591-022-01932-x)  
**Publication Date:** 22 August, 2022  
**Journal:** Nature Medicine  

**Abstract:**  
There are currently no effective biomarkers for diagnosing Parkinson's disease (PD) or tracking its progression. Here, we developed an artificial intelligence (AI) model to detect PD and track its progression from nocturnal breathing signals. The model was evaluated on a large dataset comprising 7,671 individuals, using data from several hospitals in the United States, as well as multiple public datasets. The AI model can detect PD with an area-under-the-curve of 0.90 and 0.85 on held-out and external test sets, respectively. The AI model can also estimate PD severity and progression in accordance with the Movement Disorder Society Unified Parkinson's Disease Rating Scale (R = 0.94, P = 3.6 × 10⁻²⁵). The AI model uses an attention layer that allows for interpreting its predictions with respect to sleep and electroencephalogram. Moreover, the model can assess PD in the home setting in a touchless manner, by extracting breathing from radio waves that bounce off a person's body during sleep. Our study demonstrates the feasibility of objective, noninvasive, at-home assessment of PD, and also provides initial evidence that this AI model may be useful for risk assessment before clinical diagnosis.  

**Link:** [https://www.nature.com/articles/s41591-022-01932-x](https://www.nature.com/articles/s41591-022-01932-x)

<br>

## [Analyzing Head Pose in Remotely Collected Videos of People with Parkinson’s Disease](https://dl.acm.org/doi/10.1145/3459669)  
**Publication Date:** 14 September, 2021  
**Journal:** ACM Transactions on Computing for Healthcare  

**Abstract:**  
We developed an intelligent web interface that guides users to perform several Parkinson's disease (PD) motion assessment tests in front of their webcam. After gathering data from 329 participants (N = 199 with PD, N = 130 without PD), we developed a methodology for measuring head motion randomness based on the frequency distribution of the motion. We found PD is associated with significantly higher randomness in side-to-side head motion as measured by the variance and number of large frequency components compared to the age-matched non-PD control group (p = 0.001, d = 0.13). Additionally, in participants taking levodopa (N = 151), the most common drug to treat Parkinson's, the degree of random side-to-side head motion was found to follow an exponential-decay activity model following the time of the last dose taken (r = -0.404, p = 6e-5). A logistic regression model for classifying PD vs. non-PD groups identified that higher frequency components are more associated with PD. Our findings could potentially be useful toward objectively quantifying differences in head motions that may be due to either PD or PD medications.  

**Link:** [https://dl.acm.org/doi/10.1145/3459669](https://dl.acm.org/doi/10.1145/3459669)

<br>

## [Detecting Parkinson Disease Using a Web-Based Speech Task: Observational Study](https://www.jmir.org/2021/10/e26305/)  
**Publication Date:** 19 February, 2021  
**Journal:** JMIR  

**Concise Abstract:**  
This study addresses global neurological care disparities by developing a web-based PD screening tool using speech analysis. Researchers collected pangram utterances ("the quick brown fox jumps...") from 726 participants (36% with PD) across varied environments, comparing laboratory and home recordings. The system extracted both traditional acoustic features (MFCCs, jitter/shimmer) and deep learning embeddings, with XGBoost achieving 0.753 AUC for PD detection. Key findings showed MFCCs and validated dysphonia features were most predictive, with consistent performance across environments, ages, and genders. This accessible approach enables remote PD screening worldwide using basic audio devices, potentially helping bridge the neurological care gap, particularly in underserved regions facing severe neurologist shortages.  

**Link:** [https://www.jmir.org/2021/10/e26305/](https://www.jmir.org/2021/10/e26305/)

<br>

## [An Intelligent Mobile-Enabled System for Diagnosing Parkinson Disease: Development and Validation of a Speech Impairment Detection System](https://medinform.jmir.org/2020/9/e18689/)  
**Publication Date:** 12 March, 2020  
**Journal:** JMIR  

**Concise Abstract:**  
This study developed a mobile-enabled AI system for PD diagnosis and severity assessment through speech analysis, combining traditional and novel signal processing techniques to extract both linear and nonlinear dysphonia features. The system achieved 88.74% accuracy and 97.03% recall in diagnosis tasks, with a mean absolute error of 3.7699 for severity assessment, demonstrating strong clinical potential. Implemented in the mobile app "No Pa", the solution enables accessible telediagnosis and telemonitoring while supporting clinical decision-making. The research validates speech-based analysis as an effective digital biomarker for PD, addressing critical needs in neurological care accessibility through mobile technology.  

**Link:** [https://medinform.jmir.org/2020/9/e18689/](https://medinform.jmir.org/2020/9/e18689/)

<br>

## [Diagnosing Parkinson Disease Through Facial Expression Recognition: Video Analysis](https://www.jmir.org/2020/7/e18697/)  
**Publication Date:** 12 March, 2020  
**Journal:** JMIR  

**Concise Abstract:**  
This study explores artificial intelligence-based facial expression recognition for Parkinson's disease (PD) diagnosis using video analysis of patients and controls. By extracting facial expression features (amplitude and muscle group movements) from facial key points, the research compared traditional machine learning and deep learning approaches. The long short-term memory model achieved 86% precision and 75% F1-score using positional features, while a support vector machine reached 99% F1-score when analyzing expression amplitude and muscle group shaking. These results demonstrate the potential of facial expression analysis for digital PD diagnosis, offering possibilities for remote monitoring and assisting clinical assessments. The validated model provides insights into disease dynamics that could enhance both in-person and remote neurological evaluations.  

**Link:** [https://www.jmir.org/2020/7/e18697/](https://www.jmir.org/2020/7/e18697/)
