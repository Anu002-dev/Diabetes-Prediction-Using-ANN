# Diabetes-Prediction-Using-ANN


<h1>Diabetes Progression Prediction Using ANN</h1>

<h2>Project Overview</h2>
<p>
  This project uses an Artificial Neural Network (ANN) to predict diabetes
  progression using the Diabetes dataset available in Scikit-learn.
</p>

<h2>Dataset</h2>
<ul>
  <li>442 observations</li>
  <li>10 input features</li>
  <li>Target: Quantitative measure of diabetes progression</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>Pandas and NumPy</li>
  <li>Matplotlib and Seaborn</li>
  <li>Scikit-learn</li>
  <li>TensorFlow / Keras</li>
  <li>Google Colab</li>
</ul>

<h2>Project Workflow</h2>
<ol>
  <li>Data loading and exploration</li>
  <li>Missing value checking</li>
  <li>Data normalization and train-test splitting</li>
  <li>Building and training an ANN model</li>
  <li>Evaluating model performance using MSE and R² score</li>
  <li>Improving the model and comparing results</li>
</ol>

<h2>Model Performance</h2>
<table>
  <tr>
    <th>Metric</th>
    <th>Original ANN</th>
    <th>Improved ANN</th>
  </tr>
  <tr>
    <td>MSE</td>
    <td>3061.23</td>
    <td>2851.04</td>
  </tr>
  <tr>
    <td>R² Score</td>
    <td>0.4222</td>
    <td>0.4619</td>
  </tr>
</table>

<h2>Conclusion</h2>
<p>
  Increasing the number of neurons in the hidden layers reduced the MSE
  and improved the R² score on the test dataset.
</p>

<p>
  <strong>Note:</strong> This project predicts diabetes progression,
  not whether a person has diabetes.
</p>
