<h1>Logistic Regression</h1>

<h2>Tested Environment</h2>

<p>Python Version: <code>3.9.0</code></p>

<p>Computation Environment: <code>Jupyter Notebook</code></p>

<p>Packages Used For Analysis: </p>

<ul>
  <li><code>pandas</code></li>
  <li><code>numpy</code></li>
  <li><code>sklearn</code></li>
  <li><code>imblearn</code></li>
</ul>

<p>Packages Used For Visualization:</p>

<ul>
  <li><code>pyplot</code></li>
  <li><code>seaborn</code></li>
</ul>

<h2>Run the Notebook</h2>

<p>To run the jyputer notebook, please enter the following commands under current directory: </p>

<pre><code>jupyter notebook</code></pre>

<h2>Encoding Scheme</h2>

<p>Logistic Regression requires binary encoding variables to process wheareas the original data are categorical. Slightly different from what we did in homework, we modified the features by split all possible choices.</p> 
<p>For example, for age_group, I split that feature into 9 features: age_group_0_to_9, age_group_10_to_19, etc. 
1 for True and 0 for False.</p>

<table style="width:100%">
  <tr>
    <th>Column_Name</th>
    <th>Distribution</th>
    <th>New Column_Name</th>
    <th>Actions</th>
  </tr>
  <tr>
    <td>death_yn</td>
    <td>Bernoulli</td>
    <th>Nothing Changed</th>
    <td>Yes: 1, No: 0</td>
  </tr>
  <tr>
    <td>hosp_yn, icu_yn, medcond_yn</td>
    <td>Bernoulli</td>
    <th>(Column_Name)_Yes, (Column_Name)_No
        <br>For example: "hosp_yn_Yes", "hosp_yn_No"</th>
    <td>Yes: 1, No: 0</td>
  </tr>
  <tr>
    <td>Gender</td>
    <td>Bernoulli</td>
    <th>Gender_Female, Gender_Male</th>
    <td>Yes: 1, No: 0</td>
  </tr>
  <tr>
    <td>Age Group, Race/Ethnical Group</td>
    <td>Normal</td>
    <th>(Column_Name)_(Group_Name).
        <br>For example: "age_group_20 - 29 Years"</th>
    <td>Yes: 1, No: 0</td>
  </tr>
</table>
