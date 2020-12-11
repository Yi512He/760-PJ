<h1>Data Preprocess Scheme</h1>

<table style="width:100%">
  <tr>
    <th>Column Names</th>
    <th>Issue</th>
    <th>Action</th>
  </tr>
  <tr>
    <td>death_yn</td>
    <td>Missing Data: y value</td>
    <td>Trim all tuples with missing data</td>
  </tr>
  <tr>
    <td>current_status</td>
    <td>Unrelevant Caregory: probable case</td>
    <td>Trim all tuples of probable case</td>
  </tr>
  <tr>
    <td>cdc_report_dt, on_set_dt, pos_spec_dt, current_status
</td>
    <td>Unrelated Columns</td>
    <td>Discard all four columns</td>
  </tr>
  <tr>
    <td>age_group, race/ethnicity, sex, hosp_yn, icu_yn</td>
    <td>Missing Data</td>
    <td>Trim all tuples with missing data</td>
  </tr>
</table>
