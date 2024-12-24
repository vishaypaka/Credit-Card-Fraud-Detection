<h1>Credit Card Fraud Detection</h1>

<p>This repository implements a Credit Card Fraud Detection system using machine learning and web-based visualization. The project integrates a Flask application with data analysis and modeling pipelines to detect fraudulent transactions and visualize results.</p>

<h2>Project Overview</h2>
<p>The project uses a dataset of credit card transactions (<code>creditcard.csv</code>) to develop and evaluate a K-Nearest Neighbors (KNN) classification model. It includes features for data preprocessing, machine learning, and web-based interaction. Users can visualize the data, test sample transactions, and view performance metrics through a Flask web application.</p>

<h2>Key Components</h2>
<ul>
  <li><strong>Dataset:</strong>
    <p>The <code>creditcard.csv</code> file contains anonymized credit card transaction data, including time, amount, and class labels (<code>0</code> for normal and <code>1</code> for fraudulent transactions).</p>
  </li>
  <li><strong>Machine Learning Pipeline:</strong>
    <p>Implemented in <code>KNNCreditCardFraudDetection.ipynb</code>, this pipeline preprocesses the data, splits it into training and testing sets, and trains a KNN classifier. It evaluates the model using metrics such as accuracy, precision, recall, and F1 score.</p>
  </li>
  <li><strong>Flask Application:</strong>
    <p>The <code>app.py</code> file powers a web application that allows users to:</p>
    <ul>
      <li>Visualize the dataset with histograms, scatter plots, and other statistical summaries.</li>
      <li>Predict transaction outcomes (fraudulent or normal) by testing predefined inputs.</li>
      <li>View model performance metrics through an interactive interface.</li>
    </ul>
  </li>
</ul>

<h2>Features</h2>
<ul>
  <li><strong>Data Visualizations:</strong> Histograms and scatter plots (2D and 3D) to explore the distribution of transaction data.</li>
  <li><strong>Interactive Web Interface:</strong> Powered by Flask and Bootstrap, enabling user-friendly navigation.</li>
  <li><strong>Real-Time Predictions:</strong> Test transactions to classify them as normal or fraudulent using the trained KNN model.</li>
</ul>

<h2>How to Use</h2>
<ol>
  <li>Install the required dependencies from <code>requirements.txt</code>.</li>
  <li>Run the Flask application:</li>
  <pre><code>python app.py</code></pre>
  <li>Access the web interface at <a href="http://127.0.0.1:5000/" target="_blank">http://127.0.0.1:5000/</a>.</li>
</ol>

<h2>Notes</h2>
<ul>
  <li>The repository includes visualization scripts commented out in <code>app.py</code> for performance reasons.</li>
  <li>Large files like <code>creditcard.csv</code> may require Git LFS or external storage due to GitHub's size limitations.</li>
</ul>

<p>This project demonstrates a complete workflow for detecting and analyzing credit card fraud while offering interactive features for exploration and real-time testing.</p>
