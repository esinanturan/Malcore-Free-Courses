<p align="center">
    <img src="../.github/winapi.png" height="256" width="256">
</p>

# What is this?

This is an attempt to add all exported functions from the Windows DLL files located in `System32` and `sysWOW64`. This
will be an ongoing project and will probably take a long time to do.

# System32

### DLL Files List

- [ztrace_maps](#ztrace_maps.dll)
- [aadauthhelper](#aadauthhelper.dll)
- [aadcloudap](#aadcloudap.dll)
- [aadjcsp](#aadjcsp.dll)
- [aadtb](#aadtb.dll)
- [aadWamExtension](#aadwamextension.dll)
- [AarSvc](#aarsvc.dll)
- [AboutSettingsHandlers](#aboutsettingshandlers.dll)
- [AboveLockAppHost](#abovelockapphost.dll)
- [accessibilitycpl](#accessibilitycpl.dll)
- [accountaccessor](#accountaccessor.dll)
- [AccountsRt](#accountsrt.dll)
- [AcGenral](#acgenral.dll)
- [AcLayers](#aclayers.dll)
- [acledit](#acledit.dll)
- [aclui](#aclui.dll)
- [acmigration](#acmigration.dll)
- [ACPBackgroundManagerPolicy](#acpbackgroundmanagerpolicy.dll)
- [acppage](#acppage.dll)

## ztrace_maps.dll

#### Export table:

```
1   0x000032a0 0x1800032a0 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceClose
2   0x00003340 0x180003340 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceEnabledHelper
3   0x00003390 0x180003390 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceHelper
4   0x000033d0 0x1800033d0 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceHelperNoThis
5   0x00003410 0x180003410 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceHelperV
6   0x00003450 0x180003450 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceHelperVC
7   0x000036d0 0x1800036d0 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceInit
8   0x000036f0 0x1800036f0 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportIgnore
9   0x00003720 0x180003720 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportIgnoreC
10  0x00003730 0x180003730 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportIgnoreNoThis
11  0x000037c0 0x1800037c0 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportOrigination
12  0x00003800 0x180003800 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportOriginationC
13  0x00003840 0x180003840 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportOriginationNoThis
14  0x00003880 0x180003880 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportPropagation
15  0x000038c0 0x1800038c0 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportPropagationC
16  0x00003900 0x180003900 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceReportPropagationNoThis
17  0x00003940 0x180003940 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceTestCopyTrace
18  0x00003980 0x180003980 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceTestForceClose
19  0x000039c0 0x1800039c0 GLOBAL FUNC 0    ZTrace_Maps.dll ZTraceTestInit
```

#### Functions and Documentation

| Exported Function             | Documentation Link |
|-------------------------------|--------------------|
| ZTraceClose                   | N/A                |
| ZTraceEnabledHelper           | N/A                |
| ZTraceHelper                  | N/A                |
| ZTraceHelperNoThis            | N/A                |
| ZTraceHelperV                 | N/A                |
| ZTraceHelperVC                | N/A                |
| ZTraceInit                    | N/A                |
| ZTraceReportIgnore            | N/A                |
| ZTraceReportIgnoreC           | N/A                |
| ZTraceReportIgnoreNoThis      | N/A                |
| ZTraceReportOrigination       | N/A                |
| ZTraceReportOriginationC      | N/A                |
| ZTraceReportOriginationNoThis | N/A                |
| ZTraceReportPropagation       | N/A                |
| ZTraceReportPropagationC      | N/A                |
| ZTraceReportPropagationNoThis | N/A                |
| ZTraceTestCopyTrace           | N/A                |
| ZTraceTestForceClose          | N/A                |
| ZTraceTestInit                | N/A                |

---

## aadauthhelper.dll

#### Export table:

```
1   0x00004350 0x180004350 GLOBAL FUNC 0    AADAUTHHELPER.DLL CloseFidoAuthenticationSession
2   0x00004440 0x180004440 GLOBAL FUNC 0    AADAUTHHELPER.DLL CreateAuthBuffer
3   0x00004450 0x180004450 GLOBAL FUNC 0    AADAUTHHELPER.DLL CreateResourceAccountAuthBuffer
4   0x00004460 0x180004460 GLOBAL FUNC 0    AADAUTHHELPER.DLL CreateTokenAuthBuffer
5   0x00004480 0x180004480 GLOBAL FUNC 0    AADAUTHHELPER.DLL CreateTokenAuthBufferEx
6   0x000045d0 0x1800045d0 GLOBAL FUNC 0    AADAUTHHELPER.DLL GetFidoAuthenticationSessionStatus
7   0x000046e0 0x1800046e0 GLOBAL FUNC 0    AADAUTHHELPER.DLL GetSerializedAuthBuffer
8   0x00004980 0x180004980 GLOBAL FUNC 0    AADAUTHHELPER.DLL StartChangingFidoPin
9   0x00004a80 0x180004a80 GLOBAL FUNC 0    AADAUTHHELPER.DLL StartFidoAuthenticationSession
10  0x00004b90 0x180004b90 GLOBAL FUNC 0    AADAUTHHELPER.DLL StartSigningFidoClientData
```

#### Functions and Documentation

| Exported Function                  | Documentation Link |
|------------------------------------|--------------------|
| CloseFidoAuthenticationSession     | N/A                |
| CreateAuthBuffer                   | N/A                |
| CreateResourceAccountAuthBuffer    | N/A                |
| CreateTokenAuthBuffer              | N/A                |
| CreateTokenAuthBufferEx            | N/A                |
| GetFidoAuthenticationSessionStatus | N/A                |
| GetSerializedAuthBuffer            | N/A                |
| StartChangingFidoPin               | N/A                |
| StartFidoAuthenticationSession     | N/A                |
| StartSigningFidoClientData         | N/A                |

---

## aadcloudap.dll

#### Export table:

```
1   0x00005d30 0x180005d30 GLOBAL FUNC 0    AADCLOUDAP.dll CloudAPPluginInitialize
2   0x00006160 0x180006160 GLOBAL FUNC 0    AADCLOUDAP.dll DllRegisterServer
3   0x00006160 0x180006160 GLOBAL FUNC 0    AADCLOUDAP.dll DllUnregisterServer
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                              |
|-------------------------|-----------------------------------------------------------------------------------------------------------------|
| CloudAPPluginInitialize | N/A                                                                                                             |
| DllRegisterServer       | [DllRegisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllregisterserver)     |
| DllUnregisterServer     | [DllUnregisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllunregisterserver) |

---

## aadjcsp.dll

#### Export table:

```
1   0x000046e0 0x1800046e0 GLOBAL FUNC 0    AADJCSP.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function | Documentation Link                                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| DllGetClassObject | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## aadtb.dll

#### Export table:

```
1   0x0000cdc0 0x18000d9c0 GLOBAL FUNC 0    AADTB.dll AADTBAcquireToken
2   0x0000d150 0x18000dd50 GLOBAL FUNC 0    AADTB.dll AADTBAcquireTokenEx
3   0x0000d4a0 0x18000e0a0 GLOBAL FUNC 0    AADTB.dll AADTBFreeString
4   0x0000d510 0x18000e110 GLOBAL FUNC 0    AADTB.dll AADTBFreeStruct
5   0x0002a300 0x18002af00 GLOBAL FUNC 0    AADTB.dll DllCanUnloadNow
6   0x0002a100 0x18002ad00 GLOBAL FUNC 0    AADTB.dll DllGetActivationFactory
7   0x0002a1d0 0x18002add0 GLOBAL FUNC 0    AADTB.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                                  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| AADTBAcquireToken       | N/A                                                                                                                 |
| AADTBAcquireTokenEx     | N/A                                                                                                                 |
| AADTBFreeString         | N/A                                                                                                                 |
| AADTBFreeStruct         | N/A                                                                                                                 |
| DllCanUnloadNow         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory | N/A                                                                                                                 |
| DllGetClassObject       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## aadWamExtension.dll

#### Export table:

```
1   0x000080e0 0x1800080e0 GLOBAL FUNC 0    aadWamExtension.dll DllCanUnloadNow
2   0x00008140 0x180008140 GLOBAL FUNC 0    aadWamExtension.dll DllGetActivationFactory
3   0x00008340 0x180008340 GLOBAL FUNC 0    aadWamExtension.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                                  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory | N/A                                                                                                                 |
| DllGetClassObject       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## AarSvc.dll

#### Export table:

```
1   0x000054a0 0x1800054a0 GLOBAL FUNC 0    AarSvc.dll DllCanUnloadNow
2   0x00005190 0x180005190 GLOBAL FUNC 0    AarSvc.dll DllGetActivationFactory
3   0x00005390 0x180005390 GLOBAL FUNC 0    AarSvc.dll DllGetClassObject
4   0x000055f0 0x1800055f0 GLOBAL FUNC 0    AarSvc.dll ServiceMain
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                                  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory | N/A                                                                                                                 |
| DllGetClassObject       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| ServiceMain             | [ServiceMain](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-servicemain)                     |

---

## AboutSettingsHandlers.dll

#### Export table:

```
1   0x00003b00 0x180003b00 GLOBAL FUNC 0    AboutSettingsHandlers.dll GetSetting
```

#### Functions and Documentation

| Exported Function | Documentation Link |
|-------------------|--------------------|
| GetSetting        | N/A                |

---

## AboveLockAppHost.dll

#### Export table:

```
1   0x00009300 0x180009300 GLOBAL FUNC 0    AboveLockAppHost.dll DllCanUnloadNow
2   0x00017370 0x180017370 GLOBAL FUNC 0    AboveLockAppHost.dll DllGetActivationFactory
3   0x00009370 0x180009370 GLOBAL FUNC 0    AboveLockAppHost.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                                  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory | N/A                                                                                                                 |
| DllGetClassObject       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) | 

---

## accessibilitycpl.dll

#### Export table:

```
1   0x00002e30 0x180002e30 GLOBAL FUNC 0    ACCESSIBILITYCPL.dll DllCanUnloadNow
2   0x00002e50 0x180002e50 GLOBAL FUNC 0    ACCESSIBILITYCPL.dll DllGetClassObject
3   0x00002ee0 0x180002ee0 GLOBAL FUNC 0    ACCESSIBILITYCPL.dll DllInstall
4   0x00002ef0 0x180002ef0 GLOBAL FUNC 0    ACCESSIBILITYCPL.dll DllMain
5   0x00003070 0x180003070 GLOBAL FUNC 0    ACCESSIBILITYCPL.dll DllRegisterServer
6   0x00003070 0x180003070 GLOBAL FUNC 0    ACCESSIBILITYCPL.dll DllUnregisterServer
```

#### Functions and Documentation

| Exported Function   | Documentation Link                                                                                                  |
|---------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow     | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject   | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| DllInstall          | N/A                                                                                                                 |
| DllMain             | N/A                                                                                                                 |
| DllRegisterServer   | [DllRegisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllregisterserver)         |
| DllUnregisterServer | [DllUnregisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllunregisterserver)     |

---

## accountaccessor.dll

#### Export table:

```
1   0x000103f0 0x1800103f0 GLOBAL FUNC 0    AccountAccessor.dll GetConversationSyncEnabled
2   0x00010a00 0x180010a00 GLOBAL FUNC 0    AccountAccessor.dll GetUnifiedInboxEnabled
3   0x00010ae0 0x180010ae0 GLOBAL FUNC 0    AccountAccessor.dll GetUnifiedInboxServerValue
4   0x00010310 0x180010310 GLOBAL FUNC 0    AccountAccessor.dll SetConversationSyncEnabled
5   0x00010920 0x180010920 GLOBAL FUNC 0    AccountAccessor.dll SetUnifiedInboxEnabled
6   0x00010300 0x180010300 GLOBAL FUNC 0    AccountAccessor.dll CreateDefaultWindowsLiveAccount
7   0x00006eb0 0x180006eb0 GLOBAL FUNC 0    AccountAccessor.dll DllCanUnloadNow
8   0x00006ef0 0x180006ef0 GLOBAL FUNC 0    AccountAccessor.dll DllGetClassObject
9   0x00013710 0x180013710 GLOBAL FUNC 0    AccountAccessor.dll FindMatchingPartnership
10  0x000106b0 0x1800106b0 GLOBAL FUNC 0    AccountAccessor.dll GetConversationSyncDateFilter
11  0x00010810 0x180010810 GLOBAL FUNC 0    AccountAccessor.dll IsExtendedConversationSyncDateFiltersSupported
12  0x00013570 0x180013570 GLOBAL FUNC 0    AccountAccessor.dll LoadGoldenPartnershipAccessor
13  0x00010530 0x180010530 GLOBAL FUNC 0    AccountAccessor.dll SetConversationSyncDateFilter
14  0x000142d0 0x1800142d0 GLOBAL FUNC 0    AccountAccessor.dll UnenrollAndMarkAccountForDeletion
15  0x00015c70 0x180015c70 GLOBAL FUNC 0    AccountAccessor.dll UpdateGoogleAccountConversationFlags
16  0x00015cd0 0x180015cd0 GLOBAL FUNC 0    AccountAccessor.dll UpdateGoogleAccountServerSendsMeetingProp
17  0x000150d0 0x1800150d0 GLOBAL FUNC 0    AccountAccessor.dll UpdateWebDavAccountProperties
```

#### Functions and Documentation

| Exported Function                              | Documentation Link                                                                                                  |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| GetConversationSyncEnabled                     | N/A                                                                                                                 |
| GetUnifiedInboxEnabled                         | N/A                                                                                                                 |
| GetUnifiedInboxServerValue                     | N/A                                                                                                                 |
| SetConversationSyncEnabled                     | N/A                                                                                                                 |
| SetUnifiedInboxEnabled                         | N/A                                                                                                                 |
| CreateDefaultWindowsLiveAccount                | N/A                                                                                                                 |
| DllCanUnloadNow                                | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject                              | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| FindMatchingPartnership                        | N/A                                                                                                                 |
| GetConversationSyncDateFilter                  | N/A                                                                                                                 |
| IsExtendedConversationSyncDateFiltersSupported | N/A                                                                                                                 |
| LoadGoldenPartnershipAccessor                  | N/A                                                                                                                 |
| SetConversationSyncDateFilter                  | N/A                                                                                                                 |
| UnenrollAndMarkAccountForDeletion              | N/A                                                                                                                 |
| UpdateGoogleAccountConversationFlags           | N/A                                                                                                                 |
| UpdateGoogleAccountServerSendsMeetingProp      | N/A                                                                                                                 |
| UpdateWebDavAccountProperties                  | N/A                                                                                                                 |

---

## AccountsRt.dll

#### Export table:

```
1   0x0002eed0 0x18002eed0 GLOBAL FUNC 0    AccountsRT.dll DllCanUnloadNow
2   0x0000cc60 0x18000cc60 GLOBAL FUNC 0    AccountsRT.dll DllGetActivationFactory
3   0x0002ef40 0x18002ef40 GLOBAL FUNC 0    AccountsRT.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                                  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory | N/A                                                                                                                 |
| DllGetClassObject       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## AcGenral.dll

#### Export table:

```
1   0x00004d30 0x180004d30 GLOBAL FUNC 0    AcGenral.dll GetHookAPIs
2   0x00004de0 0x180004de0 GLOBAL FUNC 0    AcGenral.dll NotifyShims
```

#### Functions and Documentation

| Exported Function | Documentation Link |
|-------------------|--------------------|
| GetHookAPIs       | N/A                |
| NotifyShims       | N/A                |

---

## AcLayers.dll

#### Export table:

```
1   0x00001250 0x180001250 GLOBAL FUNC 0    AcLayers.dll GetHookAPIs
2   0x000023c0 0x1800023c0 GLOBAL FUNC 0    AcLayers.dll NotifyShims
```

#### Functions and Documentation

| Exported Function | Documentation Link |
|-------------------|--------------------|
| GetHookAPIs       | N/A                |
| NotifyShims       | N/A                |

---

## acledit.dll

#### Export table:

```
1   0x00001980 0x180001980 GLOBAL FUNC 0    ACLEDIT.dll EditAuditInfo
2   0x000019a0 0x1800019a0 GLOBAL FUNC 0    ACLEDIT.dll EditOwnerInfo
3   0x000019c0 0x1800019c0 GLOBAL FUNC 0    ACLEDIT.dll EditPermissionInfo
4   0x000019e0 0x1800019e0 GLOBAL FUNC 0    ACLEDIT.dll FMExtensionProcW
5   0x00001ad0 0x180001ad0 GLOBAL FUNC 0    ACLEDIT.dll DllMain
6   0x00001b10 0x180001b10 GLOBAL FUNC 0    ACLEDIT.dll SedDiscretionaryAclEditor
7   0x00001b30 0x180001b30 GLOBAL FUNC 0    ACLEDIT.dll SedSystemAclEditor
8   0x00001b50 0x180001b50 GLOBAL FUNC 0    ACLEDIT.dll SedTakeOwnership
```

#### Functions and Documentation

| Exported Function         | Documentation Link |
|---------------------------|--------------------|
| EditAuditInfo             | N/A                |
| EditOwnerInfo             | N/A                |
| EditPermissionInfo        | N/A                |
| FMExtensionProcW          | N/A                |
| DllMain                   | N/A                |
| SedDiscretionaryAclEditor | N/A                |
| SedSystemAclEditor        | N/A                |
| SedTakeOwnership          | N/A                |

---

## aclui.dll

#### Export table:

```
1   0x0004c340 0x18004c340 GLOBAL FUNC 0    ACLUI.dll CreateSecurityPage
2   0x0004c490 0x18004c490 GLOBAL FUNC 0    ACLUI.dll EditSecurity
3   0x0001e5d0 0x18001e5d0 GLOBAL FUNC 0    ACLUI.dll EditSecurityAdvanced
4   0x00040b70 0x180040b70 GLOBAL FUNC 0    ACLUI.dll EditResourceCondition
5   0x00040630 0x180040630 GLOBAL FUNC 0    ACLUI.dll EditConditionalAceClaims
6   0x0001b3b0 0x18001b3b0 GLOBAL FUNC 0    ACLUI.dll GetLocalizedStringForCondition
7   0x0000c430 0x18000c430 GLOBAL FUNC 0    ACLUI.dll GetTlsIndexForClaimDictionary
8   0x00000000 0x180000000 GLOBAL FUNC 0    ACLUI.dll Ordinal_8
9   0x00000000 0x180000000 GLOBAL FUNC 0    ACLUI.dll Ordinal_9
10  0x00000000 0x180000000 GLOBAL FUNC 0    ACLUI.dll Ordinal_10
11  0x00000000 0x180000000 GLOBAL FUNC 0    ACLUI.dll Ordinal_11
12  0x00000000 0x180000000 GLOBAL FUNC 0    ACLUI.dll Ordinal_12
13  0x00000000 0x180000000 GLOBAL FUNC 0    ACLUI.dll Ordinal_13
14  0x00000000 0x180000000 GLOBAL FUNC 0    ACLUI.dll Ordinal_14
15  0x00000000 0x180000000 GLOBAL FUNC 0    ACLUI.dll Ordinal_15
16  0x0006c4e0 0x18006c4e0 GLOBAL FUNC 0    ACLUI.dll IID_ISecurityInformation
```

#### Functions and Documentation

| Exported Function              | Documentation Link |
|--------------------------------|--------------------|
| CreateSecurityPage             | N/A                |
| EditSecurity                   | N/A                |
| EditSecurityAdvanced           | N/A                |
| EditResourceCondition          | N/A                |
| EditConditionalAceClaims       | N/A                |
| GetLocalizedStringForCondition | N/A                |
| GetTlsIndexForClaimDictionary  | N/A                |
| Ordinal_8                      | N/A                |
| Ordinal_9                      | N/A                |
| Ordinal_10                     | N/A                |
| Ordinal_11                     | N/A                |
| Ordinal_12                     | N/A                |
| Ordinal_13                     | N/A                |
| Ordinal_14                     | N/A                |
| Ordinal_15                     | N/A                |
| IID_ISecurityInformation       | N/A                |

---

## acmigration.dll

#### Export table:

```
1   0x00030240 0x180030240 GLOBAL FUNC 0    acmigration.dll AcmEngineApply
2   0x0002efd0 0x18002efd0 GLOBAL FUNC 0    acmigration.dll AcmEngineCollect
3   0x0002e690 0x18002e690 GLOBAL FUNC 0    acmigration.dll AcmEngineCreate
4   0x0002e750 0x18002e750 GLOBAL FUNC 0    acmigration.dll AcmEngineDelete
5   0x0002ee50 0x18002ee50 GLOBAL FUNC 0    acmigration.dll AcmEngineGenerateMigXml
6   0x0002e790 0x18002e790 GLOBAL FUNC 0    acmigration.dll AcmEngineGetCapabilityList
7   0x0002eb80 0x18002eb80 GLOBAL FUNC 0    acmigration.dll AcmEngineSetBaseWorkingDirectory
8   0x0002e660 0x18002e660 GLOBAL FUNC 0    acmigration.dll AcmMatchPluginExecute
9   0x00001f00 0x180001f00 GLOBAL FUNC 0    acmigration.dll ApplyMigrationShimsW
```

#### Functions and Documentation

| Exported Function                | Documentation Link |
|----------------------------------|--------------------|
| AcmEngineApply                   | N/A                |
| AcmEngineCollect                 | N/A                |
| AcmEngineCreate                  | N/A                |
| AcmEngineDelete                  | N/A                |
| AcmEngineGenerateMigXml          | N/A                |
| AcmEngineGetCapabilityList       | N/A                |
| AcmEngineSetBaseWorkingDirectory | N/A                |
| AcmMatchPluginExecute            | N/A                |
| ApplyMigrationShimsW             | N/A                |

---

## ACPBackgroundManagerPolicy.dll

#### Export table:

```
1   0x00018810 0x180018810 GLOBAL FUNC 0    ACPBackgroundManagerPolicy.dll DllCanUnloadNow
2   0x000050f0 0x1800050f0 GLOBAL FUNC 0    ACPBackgroundManagerPolicy.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function | Documentation Link                                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow   | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## acppage.dll

#### Export table:

```
1   0x00008e90 0x180008e90 GLOBAL FUNC 0    acppage.dll DllCanUnloadNow
2   0x00008ef0 0x180008ef0 GLOBAL FUNC 0    acppage.dll DllGetClassObject
3   0x00010660 0x180010660 GLOBAL FUNC 0    acppage.dll GetExeFromLnk
```

#### Functions and Documentation

| Exported Function | Documentation Link                                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow   | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| GetExeFromLnk     | N/A                                                                                                                 |

---