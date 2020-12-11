<h1>Balanced Random Forest</h1>

<h2>Environment</h2>
  
<p>Python Version: <code>2.7.16</code></p>
  
<p>Computation Environment: <code>Jupyter Notebook</code></p>
  
<p>Package Used: </p>

<ul>
  <li><code>turicreate</code></li>
  <li><code>copy</code></li>
  <li><code>numpy</code></li>
</ul>

<h2>Run the Notebook</h2>

<p>To run the jyputer notebook, please enter the following commands under current directory: </p>

<pre><code>jupyter notebook</code></pre>

<h2>Encoding Scheme</h2>

<p>The decision tree built in this experiment only processes binary encoding variables. </p>
<p>Hence, I transform all features and output into binary variables. Originally, they are all categorical variables.</p>

<table style="width:100%">
  <tr>
    <th>Column Name</th>
    <th>Distribution</th>
    <th>Actions</th>
  </tr>
  <tr>
    <td>death_yn, hosp_yn, icu_yn, medcond_yn</td>
    <td>Bernoulli</td>
    <td><ul><li>Yes: 1</li><li>No: 0</li></ul></td>
  </tr>
  <tr>
    <td>Gender</td>
    <td>Bernoulli</td>
    <td><ul><li>Female: 1</li><li>Male: 0</li></ul></td>
  </tr>
  <tr>
    <td>Age Group</td>
    <td>Normal</td>
    <td><ul><li>&lt 40: 1</li><li>&#8805 40: 0</li></ul></td>
  </tr>
  <tr>
    <td>Race/Ethnical Group</td>
    <td>Normal</td>
    <td><ul><li>White: 1</li><li>Non-White: 0</li></ul></td>
  </tr>
</table>

