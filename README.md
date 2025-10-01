<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Cancer Prediction Project</title>
</head>
<body>
  <h1>🧬 Cancer Prediction – Cervical Cancer Classification</h1>

  <p>
    This project builds a machine learning pipeline to predict the likelihood of cervical cancer using patient medical data.
    The notebook includes complete data loading, preprocessing, visualization, and model training steps using Python libraries.
  </p>

  <h2>📁 Dataset</h2>
  <p>
    The dataset used is <strong>cervical_cancer.csv</strong>, which contains medical features collected from patients, including demographic and diagnostic attributes.
    Some features include age, number of pregnancies, smoking habits, STDs, and other gynecological data.
  </p>

  <h2>🧹 Data Preprocessing</h2>
  <ul>
    <li>Handled missing values</li>
    <li>Standardized feature formats</li>
    <li>Converted categorical variables where necessary</li>
    <li>Balanced classes if applicable (using techniques like undersampling/oversampling)</li>
  </ul>

  <h2>📊 Exploratory Data Analysis (EDA)</h2>
  <p>
    Interactive visualizations with <strong>Seaborn</strong> and <strong>Plotly</strong> were used to understand data distribution and correlations.
  </p>

  <h2>🤖 Modeling</h2>
  <ul>
    <li>Applied machine learning classifiers such as:
      <ul>
        <li><strong>XGBoost</strong></li>
        <li>Logistic Regression</li>
        <li>Random Forest (if used)</li>
      </ul>
    </li>
    <li>Hyperparameter tuning and model comparison</li>
    <li>Model evaluation using metrics:
      <ul>
        <li>Accuracy</li>
        <li>Precision</li>
        <li>Recall</li>
        <li>F1-Score</li>
        <li>Confusion Matrix</li>
      </ul>
    </li>
  </ul>

  <h2>📈 Results</h2>
  <p>
    The final model demonstrated high precision and recall for detecting patients with a high risk of cervical cancer.
    XGBoost achieved the best performance among the tested classifiers.
  </p>

  <h2>▶️ How to Run</h2>
  <ol>
    <li>Install required libraries using pip:</li>
  </ol>
  <pre>
  pip install pandas numpy seaborn plotly jupyterthemes xgboost
  </pre>

  <ol start="2">
    <li>Open the notebook in Jupyter or Colab</li>
    <li>Run all cells to reproduce results</li>
    <li>Ensure <code>cervical_cancer.csv</code> is in the same directory</li>
  </ol>

  <h2>📂 File Structure</h2>
  <ul>
    <li><code>Cancer Prediction.ipynb</code> - Main analysis notebook</li>
    <li><code>cervical_cancer.csv</code> - Input dataset</li>
  </ul>

  <h2>🙌 Acknowledgements</h2>
  <p>
    Thanks to the creators of open-source libraries used in this project and Associate Professor Dr. Milaan.
  </p>
</body>
</html>
