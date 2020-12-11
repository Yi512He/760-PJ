<h1>Aanalyzing CDC COVID-19 Public Data to Predict Fatality</h1>

<h2>Overview</h2>

<p>In this project, we use three different Machine Learning models to analyze the CDC COVID-19 public data to predict fatality. </p>

<p>There models are: </p>
<ul>
  <li>Logistic Regression</li>
  <li>Balnaced Random Forest</li>
  <li>Naive Bayes</li>
</ul>

<p>For measurement, we use <code>10 fold cross validations</code>. </p>

<h2>Directory Structure</h2>

<p><code>data</code> contains two sub folders: </p>

<ul>
  <li><code>raw</code>: data source</li>
  <li><code>processed</code>: 
    <ul>
      <li><code>trim_samll_data.csv</code>: prepossed data used in this project</li>
      <li>preprocess scheme</li>
    </ul>
  </li>
</ul>

<p><code>src</code> contains three sub folders:</p>

<ul>
  <li><code>model1</code>: <code>logreg.ipynb</code></li>
  <li><code>model2</code>: <code>Balanced_random_forest.ipynb</code></li>
  <li><code>model3</code>: <code>bayes.ipynb</code></li>
</ul>
