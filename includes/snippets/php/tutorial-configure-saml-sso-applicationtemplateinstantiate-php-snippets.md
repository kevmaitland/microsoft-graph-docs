---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestBody = new InstantiatePostRequestBody();
$requestBody->setDisplayName('AWS Contoso');



$result = $graphServiceClient->applicationTemplatesById('applicationTemplate-id')->instantiate()->post($requestBody);


```