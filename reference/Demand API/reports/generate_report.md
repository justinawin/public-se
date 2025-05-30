---
title: Generate Report
excerpt: >-
  Generate reports in asynchronous pattern. Response includes a request
  identifier that can be used to track the request progress.  Response also
  includes a `report_url` that can be used to download the report when the
  request is complete. User can select if report needs to be generated for
  entire account or project or one or multiple target groups.

  <table>
        <tr><th> Report Name</th><th>Level</th><th>Multiple selection</th><th>Comments</th></tr>
        <tr><td>Completes</td><td>Account, BU, Project and Target group</td><td>Yes</td><td>Except account, user can select multiple values for BU, Project, Targetgroup</td></tr>
        <tr><td>Reconciliation Eligible RIDs</td><td>Project and Target group</td><td>Yes</td><td>Only multiple target groups selection is possible. Project is restricted to only 1 project at a time</td></tr>
        <tr><td>Reconciliation status</td><td>Account, Project and Target group</td><td>Yes</td><td>Except account, user can select multiple values for Project, Targetgroup</td></tr>
        <tr><td>Respondent Analysis</td><td>Project and Target group</td><td>Yes</td><td>Only Target group can be multiselect. Project is restricted to only 1 project at a time</td></tr>
        <tr><td>Sample bought</td><td>Account, BU, Project and Target group</td><td>Yes</td><td>Except account, user can select multiple values for BU, Project, Targetgroup</td></tr>
        <tr><td>Termination details</td><td>Target group</td><td>No</td><td>Only 1 Target group is allowed to be selected</td></tr>
  </table>
api:
  file: specspeakeasycom-cinttest-sdkdemand-api-with-code-samples.json
  operationId: generate_report
hidden: false
---