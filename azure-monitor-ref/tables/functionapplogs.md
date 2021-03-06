---
title: Azure Monitor Logs reference - FunctionAppLogs
description: Reference for FunctionAppLogs table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: robb
author: rboucher
ms.date: 3/16/2020
---

# FunctionAppLogs

 Logs generated by a Function App.

## Categories

- Azure Resources
## Solutions

- LogManagement
## Resource types

- App Service




## Columns

|Column|Type|Description|
|---|---|---|
|TenantId|string||
|SourceSystem|string||
|TimeGenerated|datetime|The timestamp (UTC) of the log.|
|Category|string|The log category name.|
|Location|string|The location of the server that processed the request (e.g., South Central US).|
|Message|string|The log message.|
|HostVersion|string|The Functions host version.|
|FunctionInvocationId|string|The invocation id that logged the message.|
|FunctionName|string|The name of the function that logged the message.|
|HostInstanceId|string|The host instance id.|
|ActivityId|string|The activity id that logged the message.|
|Level|string|The log level.|
|ExceptionDetails|string|The exception details.|
|ExceptionMessage|string|The exception message.|
|ExceptionType|string|The exception type.|
|Type|string||
|_ResourceId|string||
