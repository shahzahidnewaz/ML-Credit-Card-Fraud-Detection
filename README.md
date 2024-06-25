# ML-Credit-Card-Fraud-Detection

<h2>Setup and Data Loading</h2>
<p>This section imports necessary libraries, mounts Google Drive, and loads the credit card dataset. It then displays basic information about the data, including the first few rows, shape, and null value counts.</p>

<h2>Data Visualization</h2>
<p>The code visualizes the distribution of normal and fraudulent transactions using a bar plot. It then separates the data into fraud and normal transactions, and plots the distribution of transaction amounts for both classes.</p>

<h2>Correlation Analysis</h2>
<p>A correlation matrix is created and visualized using a heatmap to show relationships between different features.</p>

<h2>Data Preparation</h2>
<p>The dataset is split into features (X) and target (y). A train-test split is performed, and SMOTE is applied to oversample the minority class in the training data.</p>

<h2>Isolation Forest Model</h2>
<p>An Isolation Forest model is trained on the resampled data and used to make predictions on the test set. The model's performance is evaluated using various metrics.</p>

<h2>One-Class SVM Model</h2>
<p>A One-Class SVM model is trained and evaluated similarly to the Isolation Forest model.</p>

<h2>PyCaret Model</h2>
<p>The code sets up a PyCaret classification experiment, compares different models, tunes the best model, and finalizes it. The final model is used to make predictions on the test set, and its performance is evaluated.</p>

<h2>Model Evaluation</h2>
<p>For each model (Isolation Forest, One-Class SVM, and PyCaret's best model), the code prints various evaluation metrics including accuracy, ROC AUC score, classification report, and confusion matrix.</p>
