---
external help file: Microsoft.SharePoint.PowerShell.dll-help.xml
Module Name: Microsoft.SharePoint.Powershell
online version: https://docs.microsoft.com/powershell/module/sharepoint-server/get-spappstateupdateinterval
Applicable: SharePoint Server Subscription edition
title: Get-SPAppStateUpdateInterval
schema: 2.0.0
author: techwriter40
ms.author: pamgreen
ms.reviewer:
---

# Get-SPAppStateUpdateInterval

## SYNOPSIS

Returns the interval in hours between updates of the app state update job.

## SYNTAX

```
Get-SPAppStateUpdateInterval [-AssignmentCollection <SPAssignmentCollection>] [<CommonParameters>]
```

## DESCRIPTION
Use the Get-SPAppStateUpdateInterval cmdlet to return the interval in hours between updates of the app state update job.
The app state update job updates the app states, including app updates, in SharePoint based on information in the SharePoint Store.

For permissions and the most current information about Windows PowerShell for SharePoint Products, see the online documentation at [SharePoint Server Cmdlets](https://docs.microsoft.com/powershell/sharepoint/sharepoint-server/sharepoint-server-cmdlets).

## EXAMPLES

### ------------EXAMPLE------- 
```
Get-SPAppStateUpdateInterval
```

This example returns the app state update timer job invocation interval in hours.

## PARAMETERS

### -AssignmentCollection
Manages objects for the purpose of proper disposal.
Use of objects, such as SPWeb or SPSite, can use large amounts of memory and use of these objects in Windows PowerShell scripts requires proper memory management.
Using the SPAssignment object, you can assign objects to a variable and dispose of the objects after they are needed to free up memory.
When SPWeb, SPSite, or SPSiteAdministration objects are used, the objects are automatically disposed of if an assignment collection or the Global parameter is not used.

When the Global parameter is used, all objects are contained in the global store.
If objects are not immediately used, or disposed of by using the Stop-SPAssignment command, an out-of-memory scenario can occur.

```yaml
Type: SPAssignmentCollection
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server Subscription edition

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Set-SPAppStateUpdateInterval](Set-SPAppStateUpdateInterval.md)
