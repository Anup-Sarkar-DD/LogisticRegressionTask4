<div style="text-align: center; margin-bottom: 20px;">
  <h1>Breast Cancer Prediction (Logistic Regression)</h1>
</div>

- Built a Logistic Regression model to classify tumors as benign or malignant using diagnostic features (radius, texture, perimeter, area, etc.).
- Prepared the dataset by:
    - Dropping non-informative columns (ID, Unnamed: 32) and encoding the diagnosis as a binary label.
    - Checking and confirming absence of missing values for all relevant features.
    - Standardizing numerical features using scikit-learn’s StandardScaler.
- Split the data:
    - Used an 80:20 train-test split to evaluate prediction performance.
- Trained the model using scikit-learn’s LogisticRegression implementation.
- Evaluated model performance with key metrics:
    - Accuracy on test set: 0.97 (very high)
    - Precision, recall, and F1-score: Macro average 0.97, strong for both classes
    - ROC-AUC score: 0.97 (excellent discriminator between classes)
- Visualized results:
    - Plotted class distribution (malignant/benign) to check balance.
    - Plotted ROC curve to illustrate model’s performance.
    - Conducted threshold analysis for robust classification performance.
- Conclusions:
    - The logistic regression model is highly effective at distinguishing between malignant and benign tumors in this dataset.
    - This notebook establishes a strong standardized baseline for cancer outcome prediction using classical machine learning, with opportunities for feature analysis and further model improvements.

This approach offers a transparent, reproducible foundation for medical ML pipelines, suitable for both interpretability and further benchmarking.
