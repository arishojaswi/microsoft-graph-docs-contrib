---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

from msgraph import GraphServiceClient

graph_client = GraphServiceClient(credentials, scopes)


result = await graph_client.identity_governance.lifecycle_workflows.insights.microsoft_graph_identity_governance_top_workflows_processed_summary_with_start_date_time_with_end_date_time("{endDateTime}","{startDateTime}").get()


```