---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php
use Microsoft\Graph\GraphServiceClient;


$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$result = $graphServiceClient->copilot()->users()->byAiUserId('aiUser-id')->interactionHistory()->getAllEnterpriseInteractions()->get()->wait();

```