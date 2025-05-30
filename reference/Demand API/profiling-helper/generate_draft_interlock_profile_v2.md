---
title: Generate draft interlocked profile
excerpt: >
  This endpoint provices a helper for api integratores.  Given a JSON document
  representing a set of 2 or more profiles with various options selected and
  grouped, this enpoint will return the JSON you can insert into your draft
  profile to generate the  interlocked profiles.

      Note that there is no storage or persistence behind this endpoint; POST is used to allow requestors to send full payload and generate the desired interlocked profile structure.  You must save and launch a target group with the given interlocked structure in order to utlize it.
api:
  file: specspeakeasycom-cinttest-sdkdemand-api-with-code-samples.json
  operationId: generate_draft_interlock_profile_v2
hidden: false
---