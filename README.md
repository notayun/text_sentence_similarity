# Model Evaluation and TOPSIS Score Analysis
<image width="600px" src="img.png">

## 1. Data Collection
Fetched a subset of data from Hugging Face for model training.
[Link to Dataset](https://huggingface.co/datasets/nuvocare/WikiMedical_sentence_similarity/viewer/default/train)

## 2. Model Training
Trained five different models using the selected data subset.

## 3. Performance Evaluation
Calculated the following metrics for each model:
- Accuracy
- Precision
- Recall
- F1 Score
- Cohen's Kappa

## 4. TOPSIS Score Calculation
Utilized the custom 'Topsis-Rohan-102103108' package to compute TOPSIS scores based on the model performance metrics.
[Link to Topsis-Rohan-102103108 Package](https://pypi.org/project/Topsis-Rohan-102103108/)

## 5. Visualization
Plotted a bar graph to visually represent the TOPSIS scores of each model.

### Summary:
**Data Collection:**
- Subset of data obtained from Hugging Face for training.

**Model Training:**
- Five models trained on the selected data subset.

**Performance Evaluation:**
- Metrics calculated: accuracy, precision, recall, F1 score, Cohen's Kappa.

**TOPSIS Score Calculation:**
- Custom package used for TOPSIS score computation.
- [Link to Topsis-Rohan-102103108 Package](https://pypi.org/project/Topsis-Rohan-102103108/)

**Visualization:**
- Bar graph illustrating the TOPSIS scores of each model.

## How to Use
1. Install the 'Topsis-Rohan-102103108' package:
    ```bash
    pip install Topsis-Rohan-102103108
    ```

2. Run your model evaluation and TOPSIS score analysis using the provided code.

Feel free to contribute or raise issues!
