---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php
use Microsoft\Graph\GraphServiceClient;


$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$result = $graphServiceClient->solutions()->virtualEvents()->townhalls()->byVirtualEventTownhallId('virtualEventTownhall-id')->sessions()->byVirtualEventSessionId('virtualEventSession-id')->attendanceReports()->byMeetingAttendanceReportId('meetingAttendanceReport-id')->get()->wait();

```