#Potential Data Quality Issues

Missing Values:

education (105 missing)

cigsPerDay (29 missing)

BPMeds (53 missing)

totChol (50 missing)

BMI (19 missing)

heartRate (1 missing)

glucose (388 missing → ~9.2% missing)

Outliers:

Very high cholesterol (up to 696).

Extremely high systolic BP (295).

Very high glucose (394).

Class Imbalance:

Only ~15% of patients developed heart disease → could affect model training.

#Potential Redundancies:

currentSmoker + cigsPerDay overlap (a non-smoker should have cigsPerDay = 0, but need to check consistency).

Data type issues:

education stored as float but represents categorical levels (1–4).

Binary indicators (male, currentSmoker, BPMeds, etc.) are numerical but categorical.