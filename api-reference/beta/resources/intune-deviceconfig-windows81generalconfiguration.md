---
title: "windows81GeneralConfiguration resource type"
description: "This topic provides descriptions of the declared methods, properties and relationships exposed by the windows81GeneralConfiguration resource."
author: "jaiprakashmb"
ms.localizationpriority: medium
ms.subservice: "intune"
doc_type: resourcePageType
ms.date: 08/01/2024
---

# windows81GeneralConfiguration resource type

Namespace: microsoft.graph

> **Important:** Microsoft supports Intune /beta APIs, but they are subject to more frequent change. Microsoft recommends using version v1.0 when possible. Check an API's availability in version v1.0 using the Version selector.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

This topic provides descriptions of the declared methods, properties and relationships exposed by the windows81GeneralConfiguration resource.


Inherits from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)

## Methods
|Method|Return Type|Description|
|:---|:---|:---|
|[List windows81GeneralConfigurations](../api/intune-deviceconfig-windows81generalconfiguration-list.md)|[windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md) collection|List properties and relationships of the [windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md) objects.|
|[Get windows81GeneralConfiguration](../api/intune-deviceconfig-windows81generalconfiguration-get.md)|[windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md)|Read properties and relationships of the [windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md) object.|
|[Create windows81GeneralConfiguration](../api/intune-deviceconfig-windows81generalconfiguration-create.md)|[windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md)|Create a new [windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md) object.|
|[Delete windows81GeneralConfiguration](../api/intune-deviceconfig-windows81generalconfiguration-delete.md)|None|Deletes a [windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md).|
|[Update windows81GeneralConfiguration](../api/intune-deviceconfig-windows81generalconfiguration-update.md)|[windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md)|Update the properties of a [windows81GeneralConfiguration](../resources/intune-deviceconfig-windows81generalconfiguration.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|Key of the entity. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|lastModifiedDateTime|DateTimeOffset|DateTime the object was last modified. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|roleScopeTagIds|String collection|List of Scope Tags for this Entity instance. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|supportsScopeTags|Boolean|Indicates whether or not the underlying Device Configuration supports the assignment of scope tags. Assigning to the ScopeTags property is not allowed when this value is false and entities will not be visible to scoped users. This occurs for Legacy policies created in Silverlight and can be resolved by deleting and recreating the policy in the Azure Portal. This property is read-only. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsEdition|[deviceManagementApplicabilityRuleOsEdition](../resources/intune-deviceconfig-devicemanagementapplicabilityruleosedition.md)|The OS edition applicability for this Policy. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleOsVersion|[deviceManagementApplicabilityRuleOsVersion](../resources/intune-deviceconfig-devicemanagementapplicabilityruleosversion.md)|The OS version applicability rule for this Policy. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|deviceManagementApplicabilityRuleDeviceMode|[deviceManagementApplicabilityRuleDeviceMode](../resources/intune-deviceconfig-devicemanagementapplicabilityruledevicemode.md)|The device mode applicability rule for this Policy. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|createdDateTime|DateTimeOffset|DateTime the object was created. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|description|String|Admin provided description of the Device Configuration. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|displayName|String|Admin provided name of the device configuration. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|version|Int32|Version of the device configuration. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|accountsBlockAddingNonMicrosoftAccountEmail|Boolean|Indicates whether or not to Block the user from adding email accounts to the device that are not associated with a Microsoft account.|
|applyOnlyToWindows81|Boolean|Value indicating whether this policy only applies to Windows 8.1. This property is read-only.|
|browserBlockAutofill|Boolean|Indicates whether or not to block auto fill.|
|browserBlockAutomaticDetectionOfIntranetSites|Boolean|Indicates whether or not to block automatic detection of Intranet sites.|
|browserBlockEnterpriseModeAccess|Boolean|Indicates whether or not to block enterprise mode access.|
|browserBlockJavaScript|Boolean|Indicates whether or not to Block the user from using JavaScript.|
|browserBlockPlugins|Boolean|Indicates whether or not to block plug-ins.|
|browserBlockPopups|Boolean|Indicates whether or not to block popups.|
|browserBlockSendingDoNotTrackHeader|Boolean|Indicates whether or not to Block the user from sending the do not track header.|
|browserBlockSingleWordEntryOnIntranetSites|Boolean|Indicates whether or not to block a single word entry on Intranet sites.|
|browserRequireSmartScreen|Boolean|Indicates whether or not to require the user to use the smart screen filter.|
|browserEnterpriseModeSiteListLocation|String|The enterprise mode site list location. Could be a local file, local network or http location.|
|browserInternetSecurityLevel|[internetSiteSecurityLevel](../resources/intune-deviceconfig-internetsitesecuritylevel.md)|The internet security level. Possible values are: `userDefined`, `medium`, `mediumHigh`, `high`.|
|browserIntranetSecurityLevel|[siteSecurityLevel](../resources/intune-deviceconfig-sitesecuritylevel.md)|The Intranet security level. Possible values are: `userDefined`, `low`, `mediumLow`, `medium`, `mediumHigh`, `high`.|
|browserLoggingReportLocation|String|The logging report location.|
|browserRequireHighSecurityForRestrictedSites|Boolean|Indicates whether or not to require high security for restricted sites.|
|browserRequireFirewall|Boolean|Indicates whether or not to require a firewall.|
|browserRequireFraudWarning|Boolean|Indicates whether or not to require fraud warning.|
|browserTrustedSitesSecurityLevel|[siteSecurityLevel](../resources/intune-deviceconfig-sitesecuritylevel.md)|The trusted sites security level. Possible values are: `userDefined`, `low`, `mediumLow`, `medium`, `mediumHigh`, `high`.|
|cellularBlockDataRoaming|Boolean|Indicates whether or not to block data roaming.|
|diagnosticsBlockDataSubmission|Boolean|Indicates whether or not to block diagnostic data submission.|
|passwordBlockPicturePasswordAndPin|Boolean|Indicates whether or not to Block the user from using a pictures password and pin.|
|passwordExpirationDays|Int32|Password expiration in days.|
|passwordMinimumLength|Int32|The minimum password length.|
|passwordMinutesOfInactivityBeforeScreenTimeout|Int32|The minutes of inactivity before the screen times out.|
|passwordMinimumCharacterSetCount|Int32|The number of character sets required in the password.|
|passwordPreviousPasswordBlockCount|Int32|The number of previous passwords to prevent re-use of. Valid values 0 to 24|
|passwordRequiredType|[requiredPasswordType](../resources/intune-deviceconfig-requiredpasswordtype.md)|The required password type. Possible values are: `deviceDefault`, `alphanumeric`, `numeric`.|
|passwordSignInFailureCountBeforeFactoryReset|Int32|The number of sign in failures before factory reset.|
|storageRequireDeviceEncryption|Boolean|Indicates whether or not to require encryption on a mobile device.|
|minimumAutoInstallClassification|[updateClassification](../resources/intune-deviceconfig-updateclassification.md)|The minimum update classification to install automatically. Possible values are: `userDefined`, `recommendedAndImportant`, `important`, `none`.|
|updatesMinimumAutoInstallClassification|[updateClassification](../resources/intune-deviceconfig-updateclassification.md)|The minimum update classification to install automatically. Possible values are: `userDefined`, `recommendedAndImportant`, `important`, `none`.|
|updatesRequireAutomaticUpdates|Boolean|Indicates whether or not to require automatic updates.|
|userAccountControlSettings|[windowsUserAccountControlSettings](../resources/intune-deviceconfig-windowsuseraccountcontrolsettings.md)|The user account control settings. Possible values are: `userDefined`, `alwaysNotify`, `notifyOnAppChanges`, `notifyOnAppChangesWithoutDimming`, `neverNotify`.|
|workFoldersUrl|String|The work folders url.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|groupAssignments|[deviceConfigurationGroupAssignment](../resources/intune-deviceconfig-deviceconfigurationgroupassignment.md) collection|The list of group assignments for the device configuration profile. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|assignments|[deviceConfigurationAssignment](../resources/intune-deviceconfig-deviceconfigurationassignment.md) collection|The list of assignments for the device configuration profile. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|deviceStatuses|[deviceConfigurationDeviceStatus](../resources/intune-deviceconfig-deviceconfigurationdevicestatus.md) collection|Device configuration installation status by device. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|userStatuses|[deviceConfigurationUserStatus](../resources/intune-deviceconfig-deviceconfigurationuserstatus.md) collection|Device configuration installation status by user. Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|deviceStatusOverview|[deviceConfigurationDeviceOverview](../resources/intune-deviceconfig-deviceconfigurationdeviceoverview.md)|Device Configuration devices status overview Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|userStatusOverview|[deviceConfigurationUserOverview](../resources/intune-deviceconfig-deviceconfigurationuseroverview.md)|Device Configuration users status overview Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|
|deviceSettingStateSummaries|[settingStateDeviceSummary](../resources/intune-deviceconfig-settingstatedevicesummary.md) collection|Device Configuration Setting State Device Summary Inherited from [deviceConfiguration](../resources/intune-shared-deviceconfiguration.md)|

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windows81GeneralConfiguration"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windows81GeneralConfiguration",
  "id": "String (identifier)",
  "lastModifiedDateTime": "String (timestamp)",
  "roleScopeTagIds": [
    "String"
  ],
  "supportsScopeTags": true,
  "deviceManagementApplicabilityRuleOsEdition": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsEdition",
    "osEditionTypes": [
      "String"
    ],
    "name": "String",
    "ruleType": "String"
  },
  "deviceManagementApplicabilityRuleOsVersion": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsVersion",
    "minOSVersion": "String",
    "maxOSVersion": "String",
    "name": "String",
    "ruleType": "String"
  },
  "deviceManagementApplicabilityRuleDeviceMode": {
    "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleDeviceMode",
    "deviceMode": "String",
    "name": "String",
    "ruleType": "String"
  },
  "createdDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "version": 1024,
  "accountsBlockAddingNonMicrosoftAccountEmail": true,
  "applyOnlyToWindows81": true,
  "browserBlockAutofill": true,
  "browserBlockAutomaticDetectionOfIntranetSites": true,
  "browserBlockEnterpriseModeAccess": true,
  "browserBlockJavaScript": true,
  "browserBlockPlugins": true,
  "browserBlockPopups": true,
  "browserBlockSendingDoNotTrackHeader": true,
  "browserBlockSingleWordEntryOnIntranetSites": true,
  "browserRequireSmartScreen": true,
  "browserEnterpriseModeSiteListLocation": "String",
  "browserInternetSecurityLevel": "String",
  "browserIntranetSecurityLevel": "String",
  "browserLoggingReportLocation": "String",
  "browserRequireHighSecurityForRestrictedSites": true,
  "browserRequireFirewall": true,
  "browserRequireFraudWarning": true,
  "browserTrustedSitesSecurityLevel": "String",
  "cellularBlockDataRoaming": true,
  "diagnosticsBlockDataSubmission": true,
  "passwordBlockPicturePasswordAndPin": true,
  "passwordExpirationDays": 1024,
  "passwordMinimumLength": 1024,
  "passwordMinutesOfInactivityBeforeScreenTimeout": 1024,
  "passwordMinimumCharacterSetCount": 1024,
  "passwordPreviousPasswordBlockCount": 1024,
  "passwordRequiredType": "String",
  "passwordSignInFailureCountBeforeFactoryReset": 1024,
  "storageRequireDeviceEncryption": true,
  "minimumAutoInstallClassification": "String",
  "updatesMinimumAutoInstallClassification": "String",
  "updatesRequireAutomaticUpdates": true,
  "userAccountControlSettings": "String",
  "workFoldersUrl": "String"
}
```