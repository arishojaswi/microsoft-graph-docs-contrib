---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

from msgraph_beta import GraphServiceClient
from msgraph_beta.generated.models.application import Application
from msgraph_beta.generated.models.authentication_behaviors import AuthenticationBehaviors

graph_client = GraphServiceClient(credentials, scopes)

request_body = Application(
	authentication_behaviors = AuthenticationBehaviors(
		block_azure_a_d_graph_access = False,
	),
)

result = await graph_client.applications.by_application_id('application-id').patch(request_body)


```