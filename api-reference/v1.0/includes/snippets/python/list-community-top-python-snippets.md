---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

from msgraph import GraphServiceClient
from msgraph.generated.employee_experience.communities.communities_request_builder import CommunitiesRequestBuilder
from kiota_abstractions.base_request_configuration import RequestConfiguration

graph_client = GraphServiceClient(credentials, scopes)

query_params = CommunitiesRequestBuilder.CommunitiesRequestBuilderGetQueryParameters(
		top = 2,
)

request_configuration = RequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.employee_experience.communities.get(request_configuration = request_configuration)


```