# EEG Artifact Detection using Ensemble Learning

## 📌 Overview
This project focuses on *EEG artifact detection* to improve the quality of brain signal analysis.  
EEG signals are often corrupted by noise such as *eye blinks, muscle movements, and electrical interference, which can lead to incorrect interpretations in **clinical diagnosis, **brain-computer interfaces (BCIs), and **neuroscience research*.

We propose an *ensemble model* combining three machine learning algorithms:  
- *Support Vector Machine (SVM)* – Finds optimal decision boundaries.  
- *Random Forest (RF)* – Handles complex nonlinear data and reduces overfitting.  
- *Naïve Bayes (NB)* – Provides probabilistic classification.  

These models are integrated using a *Voting Classifier, leveraging their strengths to achieve **97% accuracy*, outperforming individual classifiers and traditional filtering methods.

---

## 🚀 Features
- Detects multiple EEG artifacts accurately.  
- Combines three classifiers for better performance and generalization.  
- Evaluates using *accuracy, **precision, **recall, **F1-score, and **ROC curves*.  
- Supports healthcare, BCI, and neuroscience applications.

---

## 🧪 Methods Used
1. *Data Collection:* EEG datasets with clean and artifact-contaminated signals.  
2. *Preprocessing:* Filtering, normalization, and segmentation into epochs.  
3. *Feature Extraction:*  
   - Time-domain features (mean, variance, RMS).  
   - Frequency-domain features (power spectral density).  
   - Wavelet-based features for transient detection.  
4. *Model Training & Testing:* Dataset split into training and testing sets.  
5. *Evaluation Metrics:* Accuracy, precision, recall, F1-score, and ROC curves.

---

## 🛠 Tools & Technologies
- *Language:* Python  
- *Libraries:*  
  - Scikit-learn – for ML models and Voting Classifier  
  - NumPy & Pandas – data preprocessing  
  - Matplotlib & Seaborn – visualization  
- *IDE:* Jupyter Notebook / VS Code

---

## 📊 Results
- *Ensemble Model Accuracy:* 97%  
- Outperforms individual classifiers like SVM, RF, and NB alone.  
- Demonstrates robustness and reliability for EEG analysis.

---

## 📂 Applications
- Clinical diagnosis of neurological disorders.  
- Brain-Computer Interfaces (BCIs).  
- Mental health monitoring (stress, fatigue, etc.).  
- Cognitive research and neuroscience experiments.

---

## ⚠ Limitations
- Real-time detection can be computationally intensive.  
- Overlapping artifacts are difficult to separate.  
- Model generalization depends on diverse datasets.  

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributors
- *Your Name*  
- Open for contributions! Fork this repository and submit a pull request.

---

## 💡 Future Work
- Implement real-time EEG artifact detection.  
- Incorporate deep learning models like CNNs or LSTMs.  
- Optimize system for wearable EEG devices.
