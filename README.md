# Neurobehavioral-Factors-in-Eating-Disorders<img width="1022" height="594" alt="Screenshot 2025-09-16 171205" src="https://github.com/user-attachments/assets/684e8a38-ca51-45e0-b90a-89779f177147" />
<img width="1015" height="594" alt="Screenshot 2025-09-16 171141" src="https://github.com/user-attachments/assets/3f22d74c-b042-4287-ba25-0f91036615b2" />


# Predicting Self-Perception of Eating Disorders using Machine Learning
# Overview

This project analyzes a dataset of 550 university students to identify key neurobehavioral factors that influence self-perception of eating disorders using machine learning. While the models achieved a consistent accuracy of 55%, the most significant finding was the 45% of unexplained variance, suggesting that nearly half of what drives self-perception lies beyond standard behavioral checklists.

#  Key Insights

- Consistent Predictive Signal: Multiple ML models (Random Forest, XGBoost, SVM and Logistic Regression) consistently achieved ~55% accuracy, indicating robust underlying patterns in behavioral data.
- The Missing 45%: The analysis reveals that factors like internal narrative, genetic predispositions, social media influence and unmeasured psychological variables likely play a crucial role.
- Clinical Relevance: Suggests that assessment tools relying solely on behavioral patterns may be missing nearly half of the clinical picture.

# Dataset

The dataset contains survey responses from 550 students, covering:
- Demographic factors (Age, Gender)
- Behavioral patterns (Emotional eating, body dissatisfaction)
- Self-perception of eating disorders (Target variable)

# Technical Implementation

## Models Used
1. Random Forest Classifier
2. XGBoost Classifier
3. Support Vector Machine (SVM)
4. Logistic Regression

# Techniques
- Data preprocessing and categorical encoding
- Feature importance analysis
- Model evaluation and comparison
- Cross-validation

# Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook

# Results
The analysis revealed that intermittent body dissatisfaction was a stronger predictor than constant behaviors, highlighting the importance of behavioral awareness in self-perception. Internal Narrative and Self concept plays a crucial role that surveys cannot capture.

Implications: 
Assessment tools rely solely on behavioral checklists that may miss nearly half of the clinical picture
Future diagnostic frameworks must integrate both observable behaviors and deeper psychological narratives

Limitations: 
Since the data is limited to single population that is self reported, accuracy is reduced
Future work could incorporate NLP's and better models
Validating these findings against clinical diagnoses rather than self-perception could improve the dataset.

Author : Ayesha Razakh




