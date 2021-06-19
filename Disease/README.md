# About disease file dataset
**File Name** - "disease_name.json"

    Note:- Do note change the keys in the file. It has to be same all around the files.

## Terms in the file
- Diagnosis: Will be used in diagnosing of a patient
  - sysmptom_count: no. of symptoms disease has
  - symptoms: Array of symptoms
  - rarity: No. of cases per year in india
  - gender: F(Female), M(Male), N(Gender Neutral)
  - Female: Conditions that female patients could have
    - Menstruation: Is disease related to menstruation
    - Pregnancy: Is disease related to pregnancy
  - Age: Age limits for a disease
    - Start: Starting age limit (lower limit)
    - End: Ending age limit (upper limit)
  - STD: Is disease sexually transmitter
  - Family_Related: Can past family cases of this disease can effect present patient
  - Fever: Is fever H(High), L(Low) or 0(No Fever)
  - Smoking: Can smoking cause this disease
  - Alcohol: Can Alcohol consumption cause this disease
- Treatment: Will be used in treatment of the patient
  - Lab_Test_Count: No. of lab test required
  - Lab_Tests: Array of lab test required
  - Medicine_Count: No. of medicines required
  - Medicine: Array of medicines
  - Self_Care_Count: No. of self care measures
  - Self_Care: Array of self care measures