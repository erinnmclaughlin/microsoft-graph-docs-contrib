---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new UpdateAudienceByIdPostRequestBody();
$requestBody->setMemberEntityType('String');

$requestBody->setAddMembers(['String', 	]);

$requestBody->setRemoveMembers(['String', 	]);

$requestBody->setAddExclusions(['String', 	]);

$requestBody->setRemoveExclusions(['String', 	]);



$graphServiceClient->admin()->windows()->updates()->deployments()->byDeploymentId('deployment-id')->audience()->microsoftGraphWindowsUpdatesUpdateAudienceById()->post($requestBody);


```