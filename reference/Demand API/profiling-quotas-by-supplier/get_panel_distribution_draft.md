---
title: Get supplier distribution for draft target group profile conditions
excerpt: >-
  Supplier distribution enables the prediction of quota allocations for each
  profile condition, based on historical data trends.  For draft profiles, you
  must POST the full profile JSON for the system to properly predict appropriate
  distribution.

  Note that there is no storage or persistence behind this endpoint; POST Is
  used to allow requestors to send full payload and generate the supplier
  distribution structure.  The resulting output values should be used for
  specific quota numbers in your profile JSON before saving and launching your
  draft.
api:
  file: specspeakeasycom-cinttest-sdkdemand-api-with-code-samples.json
  operationId: get_panel_distribution_draft
hidden: false
---