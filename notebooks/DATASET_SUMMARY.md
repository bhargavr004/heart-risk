Dataset Characteristics

Shape: 4240 rows × 16 columns

Features:

Demographics: male, age, education

Lifestyle: currentSmoker, cigsPerDay

Medical history: BPMeds, prevalentStroke, prevalentHyp, diabetes

Clinical measurements: totChol, sysBP, diaBP, BMI, heartRate, glucose

Target: TenYearCHD (1 = risk of heart disease within 10 years, 0 = no risk)

Data types:

Mostly numerical (int64, float64).

Some categorical variables represented as numeric (e.g., male, currentSmoker, diabetes).

Initial Observations

Mean age: ~50 years (range 32–70).

Gender balance: ~43% male.

Smoking: ~49% current smokers; cigsPerDay highly skewed (most = 0, some up to 70/day).

Blood pressure: Mean systolic ~132 mmHg; some extreme cases up to 295 mmHg.

Cholesterol: Mean ~237 mg/dL; maximum recorded = 696 (possible outlier).

BMI: Average ~26 (borderline overweight).

Glucose: Mean ~82 mg/dL, but some very high values (up to 394, possible diabetic cases).

Outcome (TenYearCHD): ~15% positive cases → dataset is imbalanced.