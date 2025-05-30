---
title: Create a profile
excerpt: >
  Creates a new profile on a launched target group by defining its questions +
  options 

  sourced from the question-translation endpoint.  

  Duplicate calls with the same payload will be no-ops (no second profile is
  created).  

  **This endpoint only handles initial creation—it does _not_**:
    - Update an existing profile’s conditions  
    - Create / Manage quotas  

  **To assign or update quotas**, call:  
    - `POST /profiles/{id}/enableQuota`  
    - `PUT /profiles/{id}/updateFillingGoal`  

  **To update a profile’s conditions**, call:  
    - `PUT /profiles/{id}/updateConditions`
api:
  file: specspeakeasycom-cinttest-sdkdemand-api-with-code-samples.json
  operationId: create-profile
hidden: false
---