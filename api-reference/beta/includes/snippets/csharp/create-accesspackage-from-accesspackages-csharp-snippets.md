---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

var graphClient = new GraphServiceClient(requestAdapter);

var requestBody = new AccessPackage
{
	CatalogId = "aa2f6514-3232-46e7-a08a-2411ad8d7128",
	DisplayName = "sales reps",
	Description = "outside sales representatives",
};
var result = await graphClient.IdentityGovernance.EntitlementManagement.AccessPackages.PostAsync(requestBody);


```