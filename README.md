### Snack Consumption and Stress Behavior - ML Project

In the original experiment I administered studies at NYU Stern's Center for Behavioral Research, tracking the consumption rate of snacks relative to stress simulated by computer tests.

Students were informed that better performance on the test would marginally increase participation scores, to draw their focus to scoring well, and remove the Hawthorne Effect* on the actual item being measured - snack consumption rate.

As this dataset is not available for public consumption, I utilized a similar Dataset on more recent Data by the NIH regarding COVID-19 pandemic psychological stress and emotional eating and implemented my hierarchical clustering algorithm on their dataset.

Study: https://pubmed.ncbi.nlm.nih.gov/25682365/

Dataset: https://data.mendeley.com/datasets/xs9fbf2j6r/1

#### Data Overview

- **Subjects**: The test subjects.
- **mYFAS 2.0**: The Modified Yale Food Addiction Scale 2.0 (Schulte & Gearhardt, 2017).
- **BMI**: Body Mass Index.
- **CSM score**: Coronavirus Stress Measure (CSM) (Arslan et al., 2021).
- **Negative Emotional Eating**: Calculated from the Emotional Eating Questionnaire (EMAQ) (Geliebter & Aversa, 2003).
- **Positive Emotional Eating**: Calculated from the Emotional Eating Questionnaire (EMAQ) (Geliebter & Aversa, 2003).
- **Simplified Food Diversity Questionnaire**: Based on the Nova classification system (Monteiro et al., 2016) and evaluates the consumption of unprocessed foods.
- **Nova Score for the Consumption of UPFs**: The Nova Score (Costa et al., 2021) is based on the Nova classification system (Monteiro et al., 2016) and evaluates the consumption of ultraprocessed foods (UPFs).

---

### Key Concepts

- **Hawthorne Effect** (also known as the "Observer Effect"): Testers may alter their original or candid behavior if they know they are being watched. In this experiment, students were informed that their performance would increase their participation score to minimize this effect.

---
### Results
The clustering revealed **distinct behavioral groups** among the students:

| Cluster Range  | Pattern Identified                         |
|:---------------|:-------------------------------------------|
| 1–4, 11–15     | High Stress, Low Negative Snacking         |
| 5              | High Stress, Moderate Negative Snacking    |
| 6–10           | Medium-High Stress, Low Negative Snacking  |
| 16–20          | Medium-High Stress, High Negative Snacking |
| 21–30          | Mostly High Stress, High Negative Snacking |

### Interpretation
A **significant portion** of students exhibited **high stress** levels.

However, their coping mechanisms with food varied:

- Some students under high stress **did not engage heavily** in negative emotional eating (Clusters 1–4, 11–15).

- Others showed **moderate to high levels** of negative emotional eating alongside stress (Clusters 16–30).

- **Cluster 5** was notable as a transitional group, where students had **high stress** and **moderate** snacking behavior.

- This suggests that **not all students use food as a primary coping strategy** for stress, but for those who do, there is a clear association between stress levels and increased negative emotional eating.

### Conclusions
Distinct behavioral profiles exist among students relating to stress and food behaviors.

High stress alone does not necessarily predict negative snacking, indicating individual differences in coping mechanisms.

These insights can be useful for designing targeted interventions:

Stress management programs could be paired with nutrition education.

Tailored support could be provided to students most at risk of stress-related emotional eating.

