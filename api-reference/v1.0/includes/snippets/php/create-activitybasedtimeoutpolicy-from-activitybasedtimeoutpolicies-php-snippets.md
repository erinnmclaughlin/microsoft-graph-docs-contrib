---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new ActivityBasedTimeoutPolicy();
$requestBody->setDefinition(['definition-value', 	]);

$requestBody->setDisplayName('displayName-value');

$requestBody->setIsOrganizationDefault(true);



$result = $graphServiceClient->policies()->activityBasedTimeoutPolicies()->post($requestBody);


```