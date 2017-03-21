---
title: Statistics.GetNumberOfVisitors
permalink: /backend-api/statistics/get-number-of-visitors
redirect_from: "/display/DOC/GetNumberOfVisitors"
---

## Description

Returns the number of visitors (based on sessions, not unique visitors) for a Flipbook in a given time period.

## Parameters

| Name    | Value
|---------|-------------------------------------------------------
| paperID | The ID of the Flipbook to retrieve data from
| from	  | When should data be returned from? Format: YYYY-MM-DD
| to 	  | When should data be returned to? Format: YYYY-MM-DD


## Sample Response
```xml
<?xml version="1.0" encoding="utf-8"?>
<result>
  <code><![CDATA[SUCCESS]]></code>
  <message><![CDATA[Visitor count returned.]]></message>
  <data>
    <visitors count="8" />
  </data>
</result>
```

## Return Codes

* SUCCESS
* ERROR