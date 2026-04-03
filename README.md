**Diabetes Risk & Clinical Evaluation**

**Project Overview**
An end-to-end data science pipeline analyzing 100,000 clinical records to predict diabetes risk. This project bridges the gap between nursing intuition and machine learning by evaluating model performance through a clinical lens.

**Key Features**

**1) Data Exploration (EDA):** I analysed the distribution of HbA1c and Blood Glucose levels, identifying the "borderline" diagnostic zones.

**2) Feature Engineering:** I implemented One-Hot Encoding for lifestyle factors like smoking history and gender.

**3) Model Development:** I built a Random Forest Classifier optimized for healthcare settings.

**4) Advanced Evaluation:** I utilised Confusion Matrices and Class Weighting to prioritise Recall, ensuring high-risk patients aren't missed (minimizing False Negatives).

**Technical Stack**

**-Language:** Python (Pandas, NumPy)

**-Visuals:** Seaborn, Matplotlib

**-ML Library:** Scikit-Learn

**My Nurse's Edge:** Most models prioritize accuracy. In this project, I argue for the prioritization of Recall (Sensitivity), as a False Negative in a diabetic screening carries a higher clinical cost than a False Positive.
