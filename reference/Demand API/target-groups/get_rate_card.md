---
title: Find a Rate Card based on the provided parameters
excerpt: >-
  Rate Cards predefine the prices that a buyer will be charged for sessions on a
  Target Group that fits the equivalent IR and LOI metrics. Buyers can
  understand the interaction of the active Rate Card on a Target Group with the
  statistics, price changes and available configurations such as maximum prices
  and price boost via help documents and guides. This API allows buyers to look
  up a Rate Card based on the provided search parameters. The Rate Card is
  returned as a 2D array where each row array is LOI (with the number and value
  of the rows defined by the length_of_interview_minutes) and each column (index
  within a row array) is IR in percentage with the values defined by the
  incidence_rate_percents field.
api:
  file: specspeakeasycom-cinttest-sdkdemand-api-with-code-samples.json
  operationId: get_rate_card
hidden: false
---