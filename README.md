# ELEC 384: Machine Learning for Biomedical Time Series

**Instructor:**  
Nishal P. Shah  
**Office:** BRC 863  
**Email:** ns157@rice.edu  

**Class hours:** 4:00PM - 5:15PM, Tuesdays and Thursdays  
**Class location:** Main Campus | Howard Keck Hall | Room 101

---

## Announcement

There will be no class on Tuesday, 09/02/2025. Video recordings and slides are shared on Canvas, and you can email course instructor for the materials if needed.

---

## Summary
Biomedical signals representing physiological processes help advance scientific understanding of the human body as well as enable translational/therapeutic applications. This course will introduce signal processing and machine learning methods for analyzing biomedical time series.  

First, students will gain an understanding of how common biological signals such as neural activity and muscle activity are generated and the typical issues with recording them (signal dispersion, recording instabilities, data scarcity, individual variability, etc).  

Second, they will learn commonly used statistical methods used to extract useful information from these biomedical signals. Methods will span spectral analysis, unsupervised discovery & latent variable models to identify structure in data, and supervised methods to decode task-relevant information. While we focus on neurophysiological signal processing applications, the concepts are broadly applicable.

---

## Learning Objectives
Students will:  
- Understand the biological basis of physiological and neuro-physiological signals such as neural activity, muscle activity, cardiac signals, etc.  
- Understand challenges in physiological signal recordings such as recording drifts, non-stationarity, limited and intermittent data, individual variability, participant compliance, etc.  
- Gain knowledge about fundamental signal processing/machine learning methods used to model and understand biomedical data.  
- Gain practical experience in processing and analysing biomedical data.  
- Learn tradeoffs in data/compute complexity with different methods, and when/how to use different methods for a given problem.  

---

## Prerequisites
**Recommended:**  
- ELEC 242 Signals, Systems and Transforms  
- ELEC 303 Random Signals, probability or equivalent  
- ELEC 378 Fundamentals of Machine Learning, or equivalent  

---

## Grade Policies
- **25%:** Biweekly homeworks  
- **10%:** In-class short quizzes  
- **20%:** Project/competition applying different methods taught in the class on a publicly available dataset  
- **20%:** Mid-term exam  
- **25%:** Final exam  

---

## Syllabus Outline (may be modified)

**Week 1**  
- Biological origin of neural, muscle, and cardiac signals  
- Challenges with signal recording/quality  

**Week 2**  
- Preprocessing: filtering, thresholding, binning, whitening  
- Debugging recording problems  
- *Application:* preprocess raw neural signals  

**Week 3**  
- Signal representation: spectral methods  
- *Application:* EEG, ECoG, intracranial neural activity, LFP signals  

**Week 4**  
- Signal representation: point process methods  
- *Application:* spiking neural activity  

**Week 5**  
- Supervised methods, encoding models: correlation analysis, tuning curves, GLMs  
- *Application:* neural encoding in visual system  

**Week 6**  
- Supervised methods, decoding models: LDA, Naive Bayes, deep learning methods  
- *Application:* decode hand gestures/typing data from EMG  

**Week 7**  
- Unsupervised methods: PCA, Factor Analysis  
- *Application:* dimensionality reduction for neural spike trains  

**Week 8**  
- Unsupervised methods: Mixture Models, Expectation-Maximization  
- *Application:* spike sorting for neural and EMG signals  

**Weeks 9–10**  
- Unsupervised methods: HMM, State-space models, Kalman filters  
- *Application:* motor decoding  

**Week 11**  
- Cross-signal relationships: CCA, representational similarity analysis  
- *Application:* across neural & EMG / multiple participants / brain regions  

**Week 12-13**
- Deep learning methods: RNN, TCN, Transformers, Deep SSMs
- *Application:* Brain computer interface applications with a lot of data. 

**Week 14**  
- Best practices: selecting appropriate methods  
- Possible Case studies:  
  - Spike sorting with drifts (Neuropixels)  
  - Intracortical BCI decoding with non-stationarity and limited data  
  - EEG/intracranial decoding with low SNR  

---

## Policies

### Absence
Class attendance is mandatory. Health guidelines (masking, distancing, etc.) follow [Rice guidelines](https://coronavirus.rice.edu/).  

### Rice Honor Code
All students are held to the [Rice Honor Code](http://honor.rice.edu/honor-system-handbook/).  

### Disability Accommodations
Students with documented disabilities should contact the Disabilities Resource Center (Allen Center 111, adarice@rice.edu).  

### Mental Health
Rice offers cost-free services through the Wellbeing and Counseling Center (713-348-3311, available 24/7).  

### Title IX
As a responsible employee, the instructor must report incidents of harassment, discrimination, or interpersonal violence. Support: [The SAFE Office](https://safe.rice.edu) or email titleixsupport@rice.edu.  

### Religious Accommodations
Instructors will make reasonable accommodations for religious observances. Students should provide notice in advance.  

### Generative AI
Students may use generative AI (e.g., ChatGPT, DALL-E) if aligned with course objectives and properly cited. Students are responsible for ensuring submissions meet academic honesty standards.  

---
