# ecg-playground
- [mathworks/physionet_ECG_data: This repository contains human electrocardiogram data (ECG) data used in Wavelet Toolbox machine and deep learning examples](https://github.com/mathworks/physionet_ECG_data/tree/main)
- R-peak tracking 
- [AD8232](https://cdn.sparkfun.com/datasheets/Sensors/Biometric/AD8232.pdf)
- ```
  The AD8232 is suitable for basic heart rate and R-peak tracking in DIY, academic, and IoT projects, but it is unsuitable for professional clinical diagnosis. [1] (https://rsdjournal.org/rsd/article/download/33778/28574/378419), [2] (https://www.academia.edu/101091937/A_comparative_study_between_single_lead_AD8232_heart_rate_monitor_and_standard_electrocardiograh_to_acquire_electrocardiographic_data_for_cardiac_autonomic_function_testing)
  
  Accuracy and Performance
  
  • Heart Rate Correlation: Studies show a strong statistical correlation (r = 0.9, p ≤ 0.001) for general heart rate and R-interval measurements compared to medical-grade ECG monitors. [1] (https://indjst.org/articles/a-comparative-study-between-single-lead-ad8232-heart-rate-monitor-and-standard-electrocardiograh-to-acquire-electrocardiographic-data-for-cardiac-autonomic-function-testing), [2] (https://www.academia.edu/101091937/A_comparative_study_between_single_lead_AD8232_heart_rate_monitor_and_standard_electrocardiograh_to_acquire_electrocardiographic_data_for_cardiac_autonomic_function_testing)
  • Single-Lead Limitation: It captures only a single-lead ECG (PQRST complex), which lacks the multi-lead data needed to diagnose complex cardiac conditions like myocardial infarctions. [1] (https://www.researchgate.net/publication/398266791_Affordable_Heart_Health_Monitoring_System_Using_ESP32_AD8232_and_MAX30102), [2] (https://rsdjournal.org/rsd/article/download/33778/28574/378419)
  • High Noise Sensitivity: The signal is easily disrupted by motion artifacts, muscle contractions, body position changes, skin hair, and poor electrode contact. [1] (https://community.element14.com/challenges-projects/design-challenges/design-for-a-cause-2021/b/blog/posts/vital-care---04-ecg-ad8232-single-lead), [2] (https://rsdjournal.org/rsd/article/download/33778/28574/378419), [3] (https://www.researchgate.net/publication/398266791_Affordable_Heart_Health_Monitoring_System_Using_ESP32_AD8232_and_MAX30102)
  • High Measurement Variability: Repeated measurements show greater baseline drift and variance than clinical-grade hardware (such as biopac/MP160 systems). [1] (https://ieeexplore.ieee.org/document/11103617/)
  
  Best Use Cases
  
  • Prototyping & Education: Great for learning ECG signal conditioning, Arduino/ESP32 integration, and basic heart-rate or HRV (heart rate variability) experiments. [1] (https://ieeexplore.ieee.org/document/11103617/), [2] (https://rsdjournal.org/rsd/article/download/33778/28574/378419)
  • Machine Learning Demos: Frequently paired with microcontrollers or simple neural networks for hobbyist arrhythmia or emotion-monitoring projects, though not certified for medical use. [1] (https://www.ije.ir/article_162873.html), [2] (https://pmc.ncbi.nlm.nih.gov/articles/PMC11959012/), [3] (https://rsdjournal.org/rsd/article/download/33778/28574/378419)
  Are you planning to build a hobby/Arduino project or looking for medical-grade health monitoring? Let me know and I can suggest the right tools or hardware setup.

  ```
