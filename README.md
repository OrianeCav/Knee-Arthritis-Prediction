# Knee-Arthritis-Prediction
Osteoarthritis (OA), the prevalent form of knee arthritis affecting individuals aged 50 and above, leads to the gradual deterioration of knee joint cartilage. This deterioration results in pain during routine activities such as walking. OA, primarily impacting knees and hips, is on the rise globally due to aging populations and the obesity epidemic. The condition not only limits physical activity, contributing to significant joint pain, but also elevates the risk of cardiovascular disease. The irreversible damage caused by OA has a detrimental impact on the quality of life. Treatment options include physiotherapy, weight loss, painkillers, anti-inflammatory steroids, and knee replacement surgery.

While age and overweight/obesity are common risk factors for both frequent knee pain and knee OA, not everyone with these characteristics develops the condition. Hence, early identification of significant risk factors is crucial to managing the progression of wear and tear.

## Objective of the project
Our project aims to predict the likelihood of a patient developing knee osteoarthritis in the next five years. We leverage physiological observations (age, body mass, knee pain, etc.) and comprehensive information from the patient's medical history (previous surgery, comorbidities, etc.) to achieve this objective.

## Results 
This objective poses a considerable challenge, given the difficulty of human diagnosis for this disease. The baseline model accuracy, predicting that every patient is not sick, is 55%. Employing a gradient boosting classifier, we achieved the highest accuracy at 63.37%. Notably, clustering patients based on their physical characteristics and fine-tuning a logistic regression model produced promising results, with an average accuracy of 62.55% and a peak accuracy of 74.65%.

To further enhance these results, potential strategies include exploring more complex models like neural networks and incorporating an image recognition model based on knee magnetic resonance imaging (IRM).

A significant challenge in this project is the gradual onset and hard-to-define threshold of knee arthritis. Diagnosis difficulty and subjectivity arise as physicians determine the target, emphasizing the need to account for a certain level of subjectivity in the evaluation process.
