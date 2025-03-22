# Problem 2: Balanced Training Data (No Biases)

## Client Need:

Developers want training data free of biases to improve AI model fairness/accuracy.

## Validation

1. How do you define "balanced" training data?

Answer:

Balanced training data has equal or fair representation across all categories or groups, preventing any bias toward a specific group.

2. What biases are you most concerned about in your training data?

Answer:

Class imbalance, gender bias, racial bias, socioeconomic bias, and age bias.

3. Should the system automatically flag biased data or provide reports for manual review?

Answer:

The system should automatically flag biased data but also provide reports for manual review to ensure accuracy.

4. How frequently should bias detection be performed?

Answer:

Bias detection should occur during data collection, before training, after updates, and regularly (e.g., monthly).

5. Should developers be able to adjust bias parameters manually?

Answer:

Yes, developers should be able to manually adjust bias parameters for flexibility and project-specific needs.

6. How do you currently validate whether a dataset is balanced? Do you have specific benchmarks for bias detection accuracy?

Answer:

We validate balance through class and feature distribution checks and model performance metrics. Bias detection accuracy is evaluated using fairness metrics like Demographic Parity.
---

## Functional Requirements:

1.	The system shall include a mechanism to detect and highlight biases in training data.
2.	The system shall generate reports on data balance and bias detection.
3.	Developers shall be able to adjust and fine-tune bias detection criteria.
---
## GitHub Issues for Problem 2

Issue #6: As a developer, I want the system to detect biases in the training data so that I can ensure fairness in the model training.

### Purpose:

Following discussions with the client, the client emphasized the importance of detecting and mitigating biases in the training data to ensure that the resulting model is fair and accurate.

Sub-Issues:
1.	Issue #22: Choose and implement a bias detection algorithm.
2.	Issue #23: Analyze and categorize training data for bias.

Issue #7: As a developer, I want the system to highlight biases in the training data so that I can ensure fairness in the model training.

### Purpose:

Following discussions with the client, the client emphasized the importance of detecting and mitigating biases in the training data to ensure that the resulting model is fair and accurate.

Sub-Issues:
1.	Issue #24: Create a visual indicator system to highlight biases in the data.
2.	Issue #25: Generate a bias report for the dataset.

Issue #8: As a developer, I want the system to generate reports on training data balance so that I can gain insights and improve the quality of the dataset.

### Purpose:

Following discussions with the client, it was recognized that generating comprehensive reports on the balance of the training data will provide valuable insights for improving dataset quality and ensuring fairness throughout the model training process.

Sub-Issues:
1.	Issue #30: Implement logic for analyzing the distribution of training data.
2.	Issue #31: Design a report generation system to compile balance insights.
3.	Issue #32: Implement a downloadable report feature for users.

Issue #9: As a developer, I want to be able to adjust datasets based on bias detection feedback so that I can address any imbalances efficiently.

### Purpose:

Following discussions with the client, it was agreed that enabling the adjustment of training datasets based on bias detection feedback would provide a more efficient way to address any imbalances identified during the training process.

Sub-Issues:
1.	Issue #33: Implement functionality for adjusting data based on bias feedback.
2.	Issue #34: Develop user controls to define how data adjustments should be made.
3.	Issue #35: Implement automated processes to adjust data according to set rules.
4.	Issue #36: Validate the effectiveness of data adjustments to ensure balanced datasets.

