---
title: Get the applicable Rate Card for the provided Target Group
excerpt: >-
  Depending on the state of the Target Group, this may be a predicted Rate Card,
  which may be replaced by a new version before the Target Group collects
  completes or the actual Rate Card which is permanently associated with the
  Target Group. This association is made when the Target Group first goes live.
  Rate Cards predefine the prices that a buyer will be charged for sessions on a
  Target Group that fits the equivalent IR and LOI metrics. Buyers can
  understand the interaction of the active Rate Card on a Target Group with the
  statistics, price changes and available configurations such as maximum prices
  and price boost via help documents and guides. The Rate Card is returned as a
  2D array where each row array is LOI (with the number and value of the rows
  defined by the length_of_interview_minutes) and each column (index within a
  row array) is IR in percentage with the values defined by the
  incidence_rate_percents field.
api:
  file: specspeakeasycom-cinttest-sdkdemand-api-with-code-samples.json
  operationId: get_target_group_rate_card
hidden: false
---