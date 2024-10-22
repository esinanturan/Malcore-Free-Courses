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
- [acproxy](#acproxy.dll)
- [acspecfs](#acspecfc.dll)
- [actioncenter](#actioncenter.dll)
- [actioncentercpl](#actioncentercpl.dll)
- [actionqueue](#actionqueue.dll)
- [actionqueue](#actionqueue.dll)
- [activationclient](#activationclient.dll)
- [activationmanager](#activationmanager.dll)
- [activesynccsp](#activesynccsp.dll)
- [activesyncprovider](#activesyncprovider.dll)
- [actxprxy](#actxprxy.dll)
- [AcWinRT](#acwinrt.dll)
- [AcXtrnal](#acxtrnal.dll)
- [adal](#adal.dll)
- [AdaptiveCards](#adaptivecards.dll)
- [AddressParser](#addressparser.dll)
- [adhapi](#adhapi.dll)
- [adhsvc](#adhsvc.dll)
- [adprovider](#adprovider.dll)
- [adsldp](#adsldp.dll)
- [adsldpc](#adsldpc.dll)
- [adsmsext](#adsmsext.dll)
- [adsnt](#adsnt.dll)
- [AdvancedEmojiDS](#advancedemojids.dll)

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

## acproxy.dll

#### Export table:

```
1   0x00001a30 0x180001a30 GLOBAL FUNC 0    ACPROXY.dll PerformAutochkOperations
```

#### Functions and Documentation

| Exported Function        | Documentation Link |
|--------------------------|--------------------|
| PerformAutochkOperations | N/A                |

---

## AcSpecfc.dll

#### Export table:

```
1   0x00009a60 0x180009a60 GLOBAL FUNC 0    AcSpecfc.dll GetHookAPIs
2   0x00009b10 0x180009b10 GLOBAL FUNC 0    AcSpecfc.dll NotifyShims
```

#### Functions and Documentation

| Exported Function | Documentation Link |
|-------------------|--------------------|
| GetHookAPIs       | N/A                |
| NotifyShims       | N/A                |

---

## ActionCenter.dll

#### Export table:

```
1   0x00002300 0x180002300 GLOBAL FUNC 0    ACTIONCENTER.dll DllCanUnloadNow
2   0x000094c0 0x1800094c0 GLOBAL FUNC 0    ACTIONCENTER.dll DllGetClassObject
```

## ActionCenterCPL.dll

#### Export table:

```
1   0x00006250 0x180006250 GLOBAL FUNC 0    ACTIONCENTERCPL.dll DllCanUnloadNow
2   0x00006270 0x180006270 GLOBAL FUNC 0    ACTIONCENTERCPL.dll DllGetClassObject
3   0x000063a0 0x1800063a0 GLOBAL FUNC 0    ACTIONCENTERCPL.dll DllRegisterServer
4   0x000063a0 0x1800063a0 GLOBAL FUNC 0    ACTIONCENTERCPL.dll DllUnregisterServer
```

#### Functions and Documentation

| Exported Function | Documentation Link                                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow   | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## ActionQueue.dll

#### Export table:

```
1   0x00007550 0x180007550 GLOBAL FUNC 0    ActionQueue.dll GenerateActionQueue
2   0x00006320 0x180006320 GLOBAL FUNC 0    ActionQueue.dll ProcessActionQueue
```

#### Functions and Documentation

| Exported Function   | Documentation Link                                                                                                  |
|---------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow     | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject   | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| DllRegisterServer   | [DllRegisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllregisterserver)         |
| DllUnregisterServer | [DllUnregisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllunregisterserver)     |

---

## ActivationClient.dll

#### Export table:

```
1   0x00005c70 0x180005c70 GLOBAL FUNC 0    ActivationClient.dll DllCanUnloadNow
2   0x00005ce0 0x180005ce0 GLOBAL FUNC 0    ActivationClient.dll DllGetActivationFactory
3   0x00005ee0 0x180005ee0 GLOBAL FUNC 0    ActivationClient.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function   | Documentation Link |
|---------------------|--------------------|
| GenerateActionQueue | N/A                |
| ProcessActionQueue  | N/A                |

---

## ActivationManager.dll

#### Export table:

```
1   0x00096620 0x180096620 GLOBAL FUNC 0    ActivationManager.dll DisableAppXDebuggingForPackage
2   0x000156e0 0x1800156e0 GLOBAL FUNC 0    ActivationManager.dll DllCanUnloadNow
3   0x0006df20 0x18006df20 GLOBAL FUNC 0    ActivationManager.dll DllGetActivationFactory
4   0x0002f0a0 0x18002f0a0 GLOBAL FUNC 0    ActivationManager.dll DllGetClassObject
5   0x000966d0 0x1800966d0 GLOBAL FUNC 0    ActivationManager.dll EnableAppXDebuggingForPackage
6   0x00096880 0x180096880 GLOBAL FUNC 0    ActivationManager.dll FreeAppXLaunchContext
7   0x00097360 0x180097360 GLOBAL FUNC 0    ActivationManager.dll GetPackageExecutionContextForAumid
8   0x00018720 0x180018720 GLOBAL FUNC 0    ActivationManager.dll GetPackageExecutionContextForAumidAndUser
9   0x00055ef0 0x180055ef0 GLOBAL FUNC 0    ActivationManager.dll GetPackageExecutionContextForPackageByFamilyNameAndUser
10  0x0001c450 0x18001c450 GLOBAL FUNC 0    ActivationManager.dll GetPackageExecutionContextForPackageByFullName
11  0x000968b0 0x1800968b0 GLOBAL FUNC 0    ActivationManager.dll PostCreateProcessAppXActivation
12  0x00096c70 0x180096c70 GLOBAL FUNC 0    ActivationManager.dll PrepareAppXActivation
13  0x00097050 0x180097050 GLOBAL FUNC 0    ActivationManager.dll RegisterAppXPackageIfNecessary
14  0x00097130 0x180097130 GLOBAL FUNC 0    ActivationManager.dll RegisterAppXPackageIfNecessary2
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                                  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory | N/A                                                                                                                 |
| DllGetClassObject       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

#### Functions and Documentation

| Exported Function                                       | Documentation Link                                                                                                  |
|---------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| DisableAppXDebuggingForPackage                          | N/A                                                                                                                 |
| DllCanUnloadNow                                         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory                                 | N/A                                                                                                                 |
| DllGetClassObject                                       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| EnableAppXDebuggingForPackage                           | N/A                                                                                                                 |
| FreeAppXLaunchContext                                   | N/A                                                                                                                 |
| GetPackageExecutionContextForAumid                      | N/A                                                                                                                 |
| GetPackageExecutionContextForAumidAndUser               | N/A                                                                                                                 |
| GetPackageExecutionContextForPackageByFamilyNameAndUser | N/A                                                                                                                 |
| GetPackageExecutionContextForPackageByFullName          | N/A                                                                                                                 |
| PostCreateProcessAppXActivation                         | N/A                                                                                                                 |
| PrepareAppXActivation                                   | N/A                                                                                                                 |
| RegisterAppXPackageIfNecessary                          | N/A                                                                                                                 |
| RegisterAppXPackageIfNecessary2                         | N/A                                                                                                                 |

---

## ActiveSyncCsp.dll

#### Export table:

```
1   0x00006ce0 0x180006ce0 GLOBAL FUNC 0    ActiveSyncCsp.dll DllCanUnloadNow
2   0x00006d20 0x180006d20 GLOBAL FUNC 0    ActiveSyncCsp.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function | Documentation Link                                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow   | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## ActiveSyncProvider.dll

#### Export table:

```
1   0x00079be0 0x180079be0 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_1
2   0x000b7f10 0x1800b7f10 GLOBAL FUNC 0    ActiveSyncProvider.dll IsEnabledForSync
3   0x000108a0 0x1800108a0 GLOBAL FUNC 0    ActiveSyncProvider.dll CreateMassObject
4   0x000d23c0 0x1800d23c0 GLOBAL FUNC 0    ActiveSyncProvider.dll CreateSyncServiceLayer
5   0x0000c010 0x18000c010 GLOBAL FUNC 0    ActiveSyncProvider.dll DllCanUnloadNow
6   0x0000c050 0x18000c050 GLOBAL FUNC 0    ActiveSyncProvider.dll DllGetClassObject
7   0x00067e20 0x180067e20 GLOBAL FUNC 0    ActiveSyncProvider.dll DownloadEmailAttachment
8   0x000681f0 0x1800681f0 GLOBAL FUNC 0    ActiveSyncProvider.dll DownloadEmailBody
9   0x000abee0 0x1800abee0 GLOBAL FUNC 0    ActiveSyncProvider.dll GetActiveSyncServerProbeInstance
10  0x000abf90 0x1800abf90 GLOBAL FUNC 0    ActiveSyncProvider.dll GetConversationSyncEnabled
11  0x0006eb90 0x18006eb90 GLOBAL FUNC 0    ActiveSyncProvider.dll GetOutlookExtensionSupportForAccount
12  0x0006ec90 0x18006ec90 GLOBAL FUNC 0    ActiveSyncProvider.dll GetOutlookExtensionSupportFromAccessor
13  0x000d3cd0 0x1800d3cd0 GLOBAL FUNC 0    ActiveSyncProvider.dll GetUserInfoForUnconfiguredAccount
14  0x000ac960 0x1800ac960 GLOBAL FUNC 0    ActiveSyncProvider.dll HandleEasMeetingResponseForAppointment
15  0x000acbf0 0x1800acbf0 GLOBAL FUNC 0    ActiveSyncProvider.dll HandleEasMeetingResponseForMeetingNotification
16  0x000ae080 0x1800ae080 GLOBAL FUNC 0    ActiveSyncProvider.dll IsErrorCatastrophic
17  0x0006eed0 0x18006eed0 GLOBAL FUNC 0    ActiveSyncProvider.dll IsValidOutlookExtensionVersion
18  0x0007bfd0 0x18007bfd0 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_18
19  0x000482d0 0x1800482d0 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_19
20  0x000ae2d0 0x1800ae2d0 GLOBAL FUNC 0    ActiveSyncProvider.dll MarkPeopleFolderForResync
21  0x0000c2f0 0x18000c2f0 GLOBAL FUNC 0    ActiveSyncProvider.dll OneStopFactory
22  0x0006c690 0x18006c690 GLOBAL FUNC 0    ActiveSyncProvider.dll SyncGetMAPISession
23  0x0006c710 0x18006c710 GLOBAL FUNC 0    ActiveSyncProvider.dll SyncGetMessageStore
24  0x0006c7b0 0x18006c7b0 GLOBAL FUNC 0    ActiveSyncProvider.dll SyncGetSpecialFolder
25  0x00079c90 0x180079c90 GLOBAL FUNC 0    ActiveSyncProvider.dll SyncMgrPurgeFolderProvider
26  0x00079ca0 0x180079ca0 GLOBAL FUNC 0    ActiveSyncProvider.dll SyncMgrPurgeProviderStore
27  0x00079d90 0x180079d90 GLOBAL FUNC 0    ActiveSyncProvider.dll SyncMgrRemovePolicy
28  0x000ae310 0x1800ae310 GLOBAL FUNC 0    ActiveSyncProvider.dll UpdateEasTrackingSchema
29  0x0007c010 0x18007c010 GLOBAL FUNC 0    ActiveSyncProvider.dll WriteStoreCapabilityProps
30  0x0007ca30 0x18007ca30 GLOBAL FUNC 0    ActiveSyncProvider.dll WriteStoreContentTypesProps
31  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_31
32  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_32
33  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_33
34  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_34
35  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_35
36  0x00079ab0 0x180079ab0 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_36
37  0x00079db0 0x180079db0 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_37
38  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_38
39  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_39
40  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_40
41  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_41
42  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_42
43  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_43
44  0x00047e70 0x180047e70 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_44
45  0x00047c40 0x180047c40 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_45
46  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_46
47  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_47
48  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_48
49  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_49
50  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_50
51  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_51
52  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_52
53  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_53
54  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_54
55  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_55
56  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_56
57  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_57
58  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_58
59  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_59
60  0x00000000 0x180000000 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_60
61  0x000ae0c0 0x1800ae0c0 GLOBAL FUNC 0    ActiveSyncProvider.dll Ordinal_61
62  0x000052d0 0x1800052d0 GLOBAL FUNC 0    ActiveSyncProvider.dll InitializeSyncStatus
63  0x000052e0 0x1800052e0 GLOBAL FUNC 0    ActiveSyncProvider.dll SyncSqmUpdateStats
```

#### Functions and Documentation

| Exported Function                              | Documentation Link                                                                                                  |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Ordinal_1                                      | N/A                                                                                                                 |
| IsEnabledForSync                               | N/A                                                                                                                 |
| CreateMassObject                               | N/A                                                                                                                 |
| CreateSyncServiceLayer                         | N/A                                                                                                                 |
| DllCanUnloadNow                                | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject                              | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| DownloadEmailAttachment                        | N/A                                                                                                                 |
| DownloadEmailBody                              | N/A                                                                                                                 |
| GetActiveSyncServerProbeInstance               | N/A                                                                                                                 |
| GetConversationSyncEnabled                     | N/A                                                                                                                 |
| GetOutlookExtensionSupportForAccount           | N/A                                                                                                                 |
| GetOutlookExtensionSupportFromAccessor         | N/A                                                                                                                 |
| GetUserInfoForUnconfiguredAccount              | N/A                                                                                                                 |
| HandleEasMeetingResponseForAppointment         | N/A                                                                                                                 |
| HandleEasMeetingResponseForMeetingNotification | N/A                                                                                                                 |
| IsErrorCatastrophic                            | N/A                                                                                                                 |
| IsValidOutlookExtensionVersion                 | N/A                                                                                                                 |
| Ordinal_18                                     | N/A                                                                                                                 |
| Ordinal_19                                     | N/A                                                                                                                 |
| MarkPeopleFolderForResync                      | N/A                                                                                                                 |
| OneStopFactory                                 | N/A                                                                                                                 |
| SyncGetMAPISession                             | N/A                                                                                                                 |
| SyncGetMessageStore                            | N/A                                                                                                                 |
| SyncGetSpecialFolder                           | N/A                                                                                                                 |
| SyncMgrPurgeFolderProvider                     | N/A                                                                                                                 |
| SyncMgrPurgeProviderStore                      | N/A                                                                                                                 |
| SyncMgrRemovePolicy                            | N/A                                                                                                                 |
| UpdateEasTrackingSchema                        | N/A                                                                                                                 |
| WriteStoreCapabilityProps                      | N/A                                                                                                                 |
| WriteStoreContentTypesProps                    | N/A                                                                                                                 |
| Ordinal_31                                     | N/A                                                                                                                 |
| Ordinal_32                                     | N/A                                                                                                                 |
| Ordinal_33                                     | N/A                                                                                                                 |
| Ordinal_34                                     | N/A                                                                                                                 |
| Ordinal_35                                     | N/A                                                                                                                 |
| Ordinal_36                                     | N/A                                                                                                                 |
| Ordinal_37                                     | N/A                                                                                                                 |
| Ordinal_38                                     | N/A                                                                                                                 |
| Ordinal_39                                     | N/A                                                                                                                 |
| Ordinal_40                                     | N/A                                                                                                                 |
| Ordinal_41                                     | N/A                                                                                                                 |
| Ordinal_42                                     | N/A                                                                                                                 |
| Ordinal_43                                     | N/A                                                                                                                 |
| Ordinal_44                                     | N/A                                                                                                                 |
| Ordinal_45                                     | N/A                                                                                                                 |
| Ordinal_46                                     | N/A                                                                                                                 |
| Ordinal_47                                     | N/A                                                                                                                 |
| Ordinal_48                                     | N/A                                                                                                                 |
| Ordinal_49                                     | N/A                                                                                                                 |
| Ordinal_50                                     | N/A                                                                                                                 |
| Ordinal_51                                     | N/A                                                                                                                 |
| Ordinal_52                                     | N/A                                                                                                                 |
| Ordinal_53                                     | N/A                                                                                                                 |
| Ordinal_54                                     | N/A                                                                                                                 |
| Ordinal_55                                     | N/A                                                                                                                 |
| Ordinal_56                                     | N/A                                                                                                                 |
| Ordinal_57                                     | N/A                                                                                                                 |
| Ordinal_58                                     | N/A                                                                                                                 |
| Ordinal_59                                     | N/A                                                                                                                 |
| Ordinal_60                                     | N/A                                                                                                                 |
| Ordinal_61                                     | N/A                                                                                                                 |
| InitializeSyncStatus                           | N/A                                                                                                                 |
| SyncSqmUpdateStats                             | N/A                                                                                                                 |

---

## actxprxy.dll

#### Export table:

```
3   0x00005990 0x180005990 GLOBAL FUNC 0    SWEEPRX.dll GetProxyDllInfo
4   0x000042d0 0x1800042d0 GLOBAL FUNC 0    SWEEPRX.dll DllCanUnloadNow
5   0x00004270 0x180004270 GLOBAL FUNC 0    SWEEPRX.dll DllGetClassObject
6   0x00005930 0x180005930 GLOBAL FUNC 0    SWEEPRX.dll DllRegisterServer
7   0x00005960 0x180005960 GLOBAL FUNC 0    SWEEPRX.dll DllUnregisterServer
```

#### Functions and Documentation

| Exported Function   | Documentation Link                                                                                                  |
|---------------------|---------------------------------------------------------------------------------------------------------------------|
| GetProxyDllInfo     | N/A                                                                                                                 |
| DllCanUnloadNow     | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject   | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| DllRegisterServer   | [DllRegisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllregisterserver)         |
| DllUnregisterServer | [DllUnregisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllunregisterserver)     |

---

## AcWinRT.dll

#### Export table:

```
1   0x00006680 0x180006680 GLOBAL FUNC 0    AcWinRT.dll GetHookAPIs
2   0x00006790 0x180006790 GLOBAL FUNC 0    AcWinRT.dll NotifyShims
```

#### Functions and Documentation

| Exported Function | Documentation Link |
|-------------------|--------------------|
| GetHookAPIs       | N/A                |
| NotifyShims       | N/A                |

---

## AcXtrnal.dll

#### Export table:

```
1   0x000023b0 0x1800023b0 GLOBAL FUNC 0    AcXtrnal.dll GetHookAPIs
2   0x00002460 0x180002460 GLOBAL FUNC 0    AcXtrnal.dll NotifyShims
```

#### Functions and Documentation

| Exported Function | Documentation Link |
|-------------------|--------------------|
| GetHookAPIs       | N/A                |
| NotifyShims       | N/A                |

---

## adal.dll

#### Export table:

```
1   0x0002cc50 0x18002d850 GLOBAL FUNC 0    adal.dll ADALAcquireToken
2   0x0002ceb0 0x18002dab0 GLOBAL FUNC 0    adal.dll ADALAddClientCapability
3   0x0002d070 0x18002dc70 GLOBAL FUNC 0    adal.dll ADALCreateAuthenticationContext
4   0x0002d130 0x18002dd30 GLOBAL FUNC 0    adal.dll ADALCreateAuthenticationContextNoUI
5   0x0002d1d0 0x18002ddd0 GLOBAL FUNC 0    adal.dll ADALDeleteRequest
6   0x0002d210 0x18002de10 GLOBAL FUNC 0    adal.dll ADALDeserializeAuthenticationContext
7   0x0002d260 0x18002de60 GLOBAL FUNC 0    adal.dll ADALGetAccessToken
8   0x0002d350 0x18002df50 GLOBAL FUNC 0    adal.dll ADALGetAccessTokenExpirationTime
9   0x0002d3f0 0x18002dff0 GLOBAL FUNC 0    adal.dll ADALGetAccountType
10  0x0002d510 0x18002e110 GLOBAL FUNC 0    adal.dll ADALGetAuthority
11  0x0002d660 0x18002e260 GLOBAL FUNC 0    adal.dll ADALGetClaimsChallenge
12  0x0002d7a0 0x18002e3a0 GLOBAL FUNC 0    adal.dll ADALGetClientSecret
13  0x0002d8b0 0x18002e4b0 GLOBAL FUNC 0    adal.dll ADALGetContext
14  0x0002d8f0 0x18002e4f0 GLOBAL FUNC 0    adal.dll ADALGetContextAtIndex
15  0x0002da80 0x18002e680 GLOBAL FUNC 0    adal.dll ADALGetContextCollection
16  0x0002dc10 0x18002e810 GLOBAL FUNC 0    adal.dll ADALGetContextCollectionSize
17  0x0002dcb0 0x18002e8b0 GLOBAL FUNC 0    adal.dll ADALGetDisplayableUserId
18  0x0002de00 0x18002ea00 GLOBAL FUNC 0    adal.dll ADALGetErrorCode
19  0x0002df20 0x18002eb20 GLOBAL FUNC 0    adal.dll ADALGetErrorDescription
20  0x0002e070 0x18002ec70 GLOBAL FUNC 0    adal.dll ADALGetFamilyName
21  0x0002e1c0 0x18002edc0 GLOBAL FUNC 0    adal.dll ADALGetFormalAuthority
22  0x0002e4b0 0x18002f0b0 GLOBAL FUNC 0    adal.dll ADALGetGivenName
23  0x0002e600 0x18002f200 GLOBAL FUNC 0    adal.dll ADALGetIdTokenValue
24  0x0002e800 0x18002f400 GLOBAL FUNC 0    adal.dll ADALGetIsExtendedLifetimeToken
25  0x0002e890 0x18002f490 GLOBAL FUNC 0    adal.dll ADALGetLoginHint
26  0x0002e9d0 0x18002f5d0 GLOBAL FUNC 0    adal.dll ADALGetNetworkConnectionType
27  0x0002eaf0 0x18002f6f0 GLOBAL FUNC 0    adal.dll ADALGetOption
28  0x0002ec20 0x18002f820 GLOBAL FUNC 0    adal.dll ADALGetPasswordChangeUrl
29  0x0002ed40 0x18002f940 GLOBAL FUNC 0    adal.dll ADALGetPasswordExpiryDays
30  0x0002ede0 0x18002f9e0 GLOBAL FUNC 0    adal.dll ADALGetRefreshToken
31  0x0002ef10 0x18002fb10 GLOBAL FUNC 0    adal.dll ADALGetRequestStatus
32  0x0002ef90 0x18002fb90 GLOBAL FUNC 0    adal.dll ADALGetResponseBody
33  0x0002f0b0 0x18002fcb0 GLOBAL FUNC 0    adal.dll ADALGetResponseHeader
34  0x0002f100 0x18002fd00 GLOBAL FUNC 0    adal.dll ADALGetSuberrorCode
35  0x0002f220 0x18002fe20 GLOBAL FUNC 0    adal.dll ADALGetTenantId
36  0x0002f370 0x18002ff70 GLOBAL FUNC 0    adal.dll ADALGetUniqueUserId
37  0x0002f4c0 0x1800300c0 GLOBAL FUNC 0    adal.dll ADALIsCapabilityPresent
38  0x0002f540 0x180030140 GLOBAL FUNC 0    adal.dll ADALIsModified
39  0x0002f5c0 0x1800301c0 GLOBAL FUNC 0    adal.dll ADALIsWAMUsed
40  0x0002f630 0x180030230 GLOBAL FUNC 0    adal.dll ADALMigrateContextToSharedCache
41  0x0002f6a0 0x1800302a0 GLOBAL FUNC 0    adal.dll ADALReleaseAuthenticationContext
42  0x0002f7a0 0x1800303a0 GLOBAL FUNC 0    adal.dll ADALReleaseContextCollection
43  0x0002f8a0 0x1800304a0 GLOBAL FUNC 0    adal.dll ADALRenewToken
44  0x0002fa00 0x180030600 GLOBAL FUNC 0    adal.dll ADALSerializeAuthenticationContext
45  0x0002fb90 0x180030790 GLOBAL FUNC 0    adal.dll ADALSetAccountType
46  0x0002fc80 0x180030880 GLOBAL FUNC 0    adal.dll ADALSetAdditionalHttpHeaders
47  0x0002fd90 0x180030990 GLOBAL FUNC 0    adal.dll ADALSetAdditionalQueryParams
48  0x0002feb0 0x180030ab0 GLOBAL FUNC 0    adal.dll ADALSetClaimsChallenge
49  0x00030080 0x180030c80 GLOBAL FUNC 0    adal.dll ADALSetClientAssertionUsingCertificateContext
50  0x00030180 0x180030d80 GLOBAL FUNC 0    adal.dll ADALSetClientAssertionUsingCertificateThumbprint
51  0x00030280 0x180030e80 GLOBAL FUNC 0    adal.dll ADALSetClientSecret
52  0x00030430 0x180031030 GLOBAL FUNC 0    adal.dll ADALSetLogOptions
53  0x000304e0 0x1800310e0 GLOBAL FUNC 0    adal.dll ADALSetNetworkConnectionType
54  0x000305d0 0x1800311d0 GLOBAL FUNC 0    adal.dll ADALSetOption
55  0x000308b0 0x1800314b0 GLOBAL FUNC 0    adal.dll ADALSetRedirectUri
56  0x00030a00 0x180031600 GLOBAL FUNC 0    adal.dll ADALSetRefreshToken
57  0x00030a90 0x180031690 GLOBAL FUNC 0    adal.dll ADALSetSilentLogonOptions
58  0x00030b70 0x180031770 GLOBAL FUNC 0    adal.dll ADALSetTelemetryDispatchFunction
59  0x00030be0 0x1800317e0 GLOBAL FUNC 0    adal.dll ADALUICancelWAM
60  0x00030d10 0x180031910 GLOBAL FUNC 0    adal.dll ADALUICreateHostServiceProvider
61  0x00030f40 0x180031b40 GLOBAL FUNC 0    adal.dll ADALUICreateHostUIHandler
62  0x000310e0 0x180031ce0 GLOBAL FUNC 0    adal.dll ADALUICreateHostWindow
63  0x000315b0 0x1800321b0 GLOBAL FUNC 0    adal.dll ADALUIGetHostRequirements
64  0x00031710 0x180032310 GLOBAL FUNC 0    adal.dll ADALUIGetWebBrowser
65  0x000317e0 0x1800323e0 GLOBAL FUNC 0    adal.dll ADALUIUseWAM
66  0x00031980 0x180032580 GLOBAL FUNC 0    adal.dll ADALUIUseWebBrowser
67  0x00031af0 0x1800326f0 GLOBAL FUNC 0    adal.dll ADALUseClientCredential
68  0x00031bc0 0x1800327c0 GLOBAL FUNC 0    adal.dll ADALUseClientCredentialWithUserToken
69  0x00031ca0 0x1800328a0 GLOBAL FUNC 0    adal.dll ADALUseSAMLAssertion
70  0x00031d90 0x180032990 GLOBAL FUNC 0    adal.dll ADALUseUsernamePassword
71  0x00031e80 0x180032a80 GLOBAL FUNC 0    adal.dll ADALUseWindowsAuthentication
```

#### Functions and Documentation

| Exported Function                                | Documentation Link |
|--------------------------------------------------|--------------------|
| ADALAcquireToken                                 | N/A                |
| ADALAddClientCapability                          | N/A                |
| ADALCreateAuthenticationContext                  | N/A                |
| ADALCreateAuthenticationContextNoUI              | N/A                |
| ADALDeleteRequest                                | N/A                |
| ADALDeserializeAuthenticationContext             | N/A                |
| ADALGetAccessToken                               | N/A                |
| ADALGetAccessTokenExpirationTime                 | N/A                |
| ADALGetAccountType                               | N/A                |
| ADALGetAuthority                                 | N/A                |
| ADALGetClaimsChallenge                           | N/A                |
| ADALGetClientSecret                              | N/A                |
| ADALGetContext                                   | N/A                |
| ADALGetContextAtIndex                            | N/A                |
| ADALGetContextCollection                         | N/A                |
| ADALGetContextCollectionSize                     | N/A                |
| ADALGetDisplayableUserId                         | N/A                |
| ADALGetErrorCode                                 | N/A                |
| ADALGetErrorDescription                          | N/A                |
| ADALGetFamilyName                                | N/A                |
| ADALGetFormalAuthority                           | N/A                |
| ADALGetGivenName                                 | N/A                |
| ADALGetIdTokenValue                              | N/A                |
| ADALGetIsExtendedLifetimeToken                   | N/A                |
| ADALGetLoginHint                                 | N/A                |
| ADALGetNetworkConnectionType                     | N/A                |
| ADALGetOption                                    | N/A                |
| ADALGetPasswordChangeUrl                         | N/A                |
| ADALGetPasswordExpiryDays                        | N/A                |
| ADALGetRefreshToken                              | N/A                |
| ADALGetRequestStatus                             | N/A                |
| ADALGetResponseBody                              | N/A                |
| ADALGetResponseHeader                            | N/A                |
| ADALGetSuberrorCode                              | N/A                |
| ADALGetTenantId                                  | N/A                |
| ADALGetUniqueUserId                              | N/A                |
| ADALIsCapabilityPresent                          | N/A                |
| ADALIsModified                                   | N/A                |
| ADALIsWAMUsed                                    | N/A                |
| ADALMigrateContextToSharedCache                  | N/A                |
| ADALReleaseAuthenticationContext                 | N/A                |
| ADALReleaseContextCollection                     | N/A                |
| ADALRenewToken                                   | N/A                |
| ADALSerializeAuthenticationContext               | N/A                |
| ADALSetAccountType                               | N/A                |
| ADALSetAdditionalHttpHeaders                     | N/A                |
| ADALSetAdditionalQueryParams                     | N/A                |
| ADALSetClaimsChallenge                           | N/A                |
| ADALSetClientAssertionUsingCertificateContext    | N/A                |
| ADALSetClientAssertionUsingCertificateThumbprint | N/A                |
| ADALSetClientSecret                              | N/A                |
| ADALSetLogOptions                                | N/A                |
| ADALSetNetworkConnectionType                     | N/A                |
| ADALSetOption                                    | N/A                |
| ADALSetRedirectUri                               | N/A                |
| ADALSetRefreshToken                              | N/A                |
| ADALSetSilentLogonOptions                        | N/A                |
| ADALSetTelemetryDispatchFunction                 | N/A                |
| ADALUICancelWAM                                  | N/A                |
| ADALUICreateHostServiceProvider                  | N/A                |
| ADALUICreateHostUIHandler                        | N/A                |
| ADALUICreateHostWindow                           | N/A                |
| ADALUIGetHostRequirements                        | N/A                |
| ADALUIGetWebBrowser                              | N/A                |
| ADALUIUseWAM                                     | N/A                |
| ADALUIUseWebBrowser                              | N/A                |
| ADALUseClientCredential                          | N/A                |
| ADALUseClientCredentialWithUserToken             | N/A                |
| ADALUseSAMLAssertion                             | N/A                |
| ADALUseUsernamePassword                          | N/A                |
| ADALUseWindowsAuthentication                     | N/A                |

---

## AdaptiveCards.dll

#### Export table:

```
1   0x000020b0 0x1800020b0 GLOBAL FUNC 0    AdaptiveCards.dll DllCanUnloadNow
2   0x00002010 0x180002010 GLOBAL FUNC 0    AdaptiveCards.dll DllGetActivationFactory
3   0x000046e0 0x1800046e0 GLOBAL FUNC 0    AdaptiveCards.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                                  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory | N/A                                                                                                                 |
| DllGetClassObject       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## AddressParser.dll

#### Export table:

```
1   0x00001c30 0x180001c30 GLOBAL FUNC 0    AddressParser.Dll DestroyAddressParser
2   0x00001c60 0x180001c60 GLOBAL FUNC 0    AddressParser.Dll GetCity
3   0x00001c90 0x180001c90 GLOBAL FUNC 0    AddressParser.Dll GetCountryName
4   0x00001cc0 0x180001cc0 GLOBAL FUNC 0    AddressParser.Dll GetCountryStringFromIndex
5   0x00001d10 0x180001d10 GLOBAL FUNC 0    AddressParser.Dll GetFullAddress
6   0x00001d30 0x180001d30 GLOBAL FUNC 0    AddressParser.Dll GetNewAddressParser
7   0x00001d60 0x180001d60 GLOBAL FUNC 0    AddressParser.Dll GetPostalCode
8   0x00001d90 0x180001d90 GLOBAL FUNC 0    AddressParser.Dll GetState
9   0x00001dc0 0x180001dc0 GLOBAL FUNC 0    AddressParser.Dll GetStreet
10  0x00001df0 0x180001df0 GLOBAL FUNC 0    AddressParser.Dll ParseAddress
11  0x00001f50 0x180001f50 GLOBAL FUNC 0    AddressParser.Dll RebuildAddress
12  0x00001f60 0x180001f60 GLOBAL FUNC 0    AddressParser.Dll SetCity
13  0x00001f90 0x180001f90 GLOBAL FUNC 0    AddressParser.Dll SetCountryName
14  0x000020a0 0x1800020a0 GLOBAL FUNC 0    AddressParser.Dll SetFullAddress
15  0x000020d0 0x1800020d0 GLOBAL FUNC 0    AddressParser.Dll SetPostalCode
16  0x00002100 0x180002100 GLOBAL FUNC 0    AddressParser.Dll SetState
17  0x00002130 0x180002130 GLOBAL FUNC 0    AddressParser.Dll SetStreet
18  0x00002160 0x180002160 GLOBAL FUNC 0    AddressParser.Dll UpdateDefCountry
```

#### Functions and Documentation

| Exported Function         | Documentation Link |
|---------------------------|--------------------|
| DestroyAddressParser      | N/A                |
| GetCity                   | N/A                |
| GetCountryName            | N/A                |
| GetCountryStringFromIndex | N/A                |
| GetFullAddress            | N/A                |
| GetNewAddressParser       | N/A                |
| GetPostalCode             | N/A                |
| GetState                  | N/A                |
| GetStreet                 | N/A                |
| ParseAddress              | N/A                |
| RebuildAddress            | N/A                |
| SetCity                   | N/A                |
| SetCountryName            | N/A                |
| SetFullAddress            | N/A                |
| SetPostalCode             | N/A                |
| SetState                  | N/A                |
| SetStreet                 | N/A                |
| UpdateDefCountry          | N/A                |

---

## adhapi.dll

#### Export table:

```
1   0x00001980 0x180001980 GLOBAL FUNC 0    AdhApi.dll AdhEngineClose
2   0x00001bb0 0x180001bb0 GLOBAL FUNC 0    AdhApi.dll AdhEngineOpen
3   0x00001dd0 0x180001dd0 GLOBAL FUNC 0    AdhApi.dll AdhGetConfig
4   0x00002060 0x180002060 GLOBAL FUNC 0    AdhApi.dll AdhGetEvidenceCollectorResult
5   0x00002270 0x180002270 GLOBAL FUNC 0    AdhApi.dll AdhStatusEventSubscribe
6   0x000026b0 0x1800026b0 GLOBAL FUNC 0    AdhApi.dll AdhStatusEventUnsubscribe
7   0x00003150 0x180003150 GLOBAL FUNC 0    AdhApi.dll DllMain
```

#### Functions and Documentation

| Exported Function             | Documentation Link |
|-------------------------------|--------------------|
| AdhEngineClose                | N/A                |
| AdhEngineOpen                 | N/A                |
| AdhGetConfig                  | N/A                |
| AdhGetEvidenceCollectorResult | N/A                |
| AdhStatusEventSubscribe       | N/A                |
| AdhStatusEventUnsubscribe     | N/A                |
| DllMain                       | N/A                |

---

## adhsvc.dll

#### Export table:

```
1   0x00001bc0 0x180001bc0 GLOBAL FUNC 0    adhsvc.dll SubServiceScmNotification
2   0x000022c0 0x1800022c0 GLOBAL FUNC 0    adhsvc.dll SubServiceStart
3   0x00009740 0x180009740 GLOBAL FUNC 0    adhsvc.dll SubServiceStop
```

#### Functions and Documentation

| Exported Function         | Documentation Link |
|---------------------------|--------------------|
| SubServiceScmNotification | N/A                |
| SubServiceStart           | N/A                |
| SubServiceStop            | N/A                |

---

## adprovider.dll

#### Export table:

```
1   0x00002e40 0x180002e40 GLOBAL FUNC 0    CAPIProvider.dll DllCanUnloadNow
2   0x00002e80 0x180002e80 GLOBAL FUNC 0    CAPIProvider.dll DllGetClassObject
3   0x00003110 0x180003110 GLOBAL FUNC 0    CAPIProvider.dll DllRegisterServer
4   0x00003230 0x180003230 GLOBAL FUNC 0    CAPIProvider.dll DllUnregisterServer
```

#### Functions and Documentation

| Exported Function   | Documentation Link                                                                                                  |
|---------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow     | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject   | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |
| DllRegisterServer   | [DllRegisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllregisterserver)         |
| DllUnregisterServer | [DllUnregisterServer](https://learn.microsoft.com/en-us/windows/win32/api/unknwn/nf-unknwn-dllunregisterserver)     |

---

## adsldp.dll

#### Export table:

```
1   0x0002ba10 0x18002ba10 GLOBAL FUNC 0    adsldp.dll DllCanUnloadNow
2   0x00003f10 0x180003f10 GLOBAL FUNC 0    adsldp.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function | Documentation Link                                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow   | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## adsldpc.dll

#### Export table:

```
1   0x000146e0 0x1800146e0 GLOBAL FUNC 0    adsldpc.dll ??0CLexer@@QEAA@XZ
2   0x00014710 0x180014710 GLOBAL FUNC 0    adsldpc.dll ??1CLexer@@QEAA@XZ
3   0x00003f70 0x180003f70 GLOBAL FUNC 0    adsldpc.dll ADSIPrint
4   0x00018a60 0x180018a60 GLOBAL FUNC 0    adsldpc.dll ADsAbandonSearch
5   0x00018ae0 0x180018ae0 GLOBAL FUNC 0    adsldpc.dll ADsCloseSearchHandle
6   0x00016e20 0x180016e20 GLOBAL FUNC 0    adsldpc.dll ADsCreateAttributeDefinition
7   0x00016e30 0x180016e30 GLOBAL FUNC 0    adsldpc.dll ADsCreateClassDefinition
8   0x000043c0 0x1800043c0 GLOBAL FUNC 0    adsldpc.dll ADsCreateDSObject
9   0x000043f0 0x1800043f0 GLOBAL FUNC 0    adsldpc.dll ADsCreateDSObjectExt
10  0x00016e40 0x180016e40 GLOBAL FUNC 0    adsldpc.dll ADsDeleteAttributeDefinition
11  0x00016e40 0x180016e40 GLOBAL FUNC 0    adsldpc.dll ADsDeleteClassDefinition
12  0x00004730 0x180004730 GLOBAL FUNC 0    adsldpc.dll ADsDeleteDSObject
13  0x00016e50 0x180016e50 GLOBAL FUNC 0    adsldpc.dll ADsEnumAttributes
14  0x000172a0 0x1800172a0 GLOBAL FUNC 0    adsldpc.dll ADsEnumClasses
15  0x00018df0 0x180018df0 GLOBAL FUNC 0    adsldpc.dll ADsExecuteSearch
16  0x00019520 0x180019520 GLOBAL FUNC 0    adsldpc.dll ADsFreeColumn
17  0x000196e0 0x1800196e0 GLOBAL FUNC 0    adsldpc.dll ADsGetColumn
18  0x00019cb0 0x180019cb0 GLOBAL FUNC 0    adsldpc.dll ADsGetFirstRow
19  0x0001a5c0 0x18001a5c0 GLOBAL FUNC 0    adsldpc.dll ADsGetNextColumnName
20  0x0001a7e0 0x18001a7e0 GLOBAL FUNC 0    adsldpc.dll ADsGetNextRow
21  0x000047f0 0x1800047f0 GLOBAL FUNC 0    adsldpc.dll ADsGetObjectAttributes
22  0x0001abc0 0x18001abc0 GLOBAL FUNC 0    adsldpc.dll ADsGetPreviousRow
23  0x0001b090 0x18001b090 GLOBAL FUNC 0    adsldpc.dll ADsHelperGetCurrentRowMessage
24  0x00014730 0x180014730 GLOBAL FUNC 0    adsldpc.dll ADsObject
25  0x00004fb0 0x180004fb0 GLOBAL FUNC 0    adsldpc.dll ADsSetObjectAttributes
26  0x0001b0d0 0x18001b0d0 GLOBAL FUNC 0    adsldpc.dll ADsSetSearchPreference
27  0x00016e20 0x180016e20 GLOBAL FUNC 0    adsldpc.dll ADsWriteAttributeDefinition
28  0x00016e30 0x180016e30 GLOBAL FUNC 0    adsldpc.dll ADsWriteClassDefinition
29  0x00013530 0x180013530 GLOBAL FUNC 0    adsldpc.dll AdsTypeToLdapTypeCopyConstruct
30  0x00013660 0x180013660 GLOBAL FUNC 0    adsldpc.dll AdsTypeToLdapTypeCopyDNWithBinary
31  0x000137f0 0x1800137f0 GLOBAL FUNC 0    adsldpc.dll AdsTypeToLdapTypeCopyDNWithString
32  0x00013940 0x180013940 GLOBAL FUNC 0    adsldpc.dll AdsTypeToLdapTypeCopyGeneralizedTime
33  0x00013df0 0x180013df0 GLOBAL FUNC 0    adsldpc.dll AdsTypeToLdapTypeCopyTime
34  0x0000eee0 0x18000eee0 GLOBAL FUNC 0    adsldpc.dll BerBvFree
35  0x0001c3d0 0x18001c3d0 GLOBAL FUNC 0    adsldpc.dll BerEncodingQuotaControl
36  0x00015750 0x180015750 GLOBAL FUNC 0    adsldpc.dll BuildADsParentPath
37  0x00015880 0x180015880 GLOBAL FUNC 0    adsldpc.dll BuildADsParentPathFromObjectInfo2
38  0x00015920 0x180015920 GLOBAL FUNC 0    adsldpc.dll BuildADsParentPathFromObjectInfo
39  0x00015c50 0x180015c50 GLOBAL FUNC 0    adsldpc.dll BuildADsPathFromLDAPPath2
40  0x00015e90 0x180015e90 GLOBAL FUNC 0    adsldpc.dll BuildADsPathFromLDAPPath
41  0x00016380 0x180016380 GLOBAL FUNC 0    adsldpc.dll BuildADsPathFromParent
42  0x000167b0 0x1800167b0 GLOBAL FUNC 0    adsldpc.dll BuildLDAPPathFromADsPath2
43  0x00016a10 0x180016a10 GLOBAL FUNC 0    adsldpc.dll BuildLDAPPathFromADsPath
44  0x00016bd0 0x180016bd0 GLOBAL FUNC 0    adsldpc.dll ChangeSeparator
45  0x00014960 0x180014960 GLOBAL FUNC 0    adsldpc.dll Component
46  0x00018400 0x180018400 GLOBAL FUNC 0    adsldpc.dll ConvertSidToString
47  0x000185e0 0x1800185e0 GLOBAL FUNC 0    adsldpc.dll ConvertSidToU2Trustee
48  0x00018880 0x180018880 GLOBAL FUNC 0    adsldpc.dll ConvertU2TrusteeToSid
49  0x00008670 0x180008670 GLOBAL FUNC 0    adsldpc.dll FindEntryInSearchTable
50  0x000086c0 0x1800086c0 GLOBAL FUNC 0    adsldpc.dll FindSearchTableIndex
51  0x00014a70 0x180014a70 GLOBAL FUNC 0    adsldpc.dll FreeObjectInfo
52  0x0001d7d0 0x18001d7d0 GLOBAL FUNC 0    adsldpc.dll GetDefaultServer
53  0x00014ab0 0x180014ab0 GLOBAL FUNC 0    adsldpc.dll GetDisplayName
54  0x0001d940 0x18001d940 GLOBAL FUNC 0    adsldpc.dll GetDomainDNSNameForDomain
55  0x00014c10 0x180014c10 GLOBAL FUNC 0    adsldpc.dll GetLDAPTypeName
56  0x000150d0 0x1800150d0 GLOBAL FUNC 0    adsldpc.dll ?GetNextToken@CLexer@@QEAAJPEAGPEAK@Z
57  0x0000f5d0 0x18000f5d0 GLOBAL FUNC 0    adsldpc.dll GetServerAndPort
58  0x0001e3e0 0x18001e3e0 GLOBAL FUNC 0    adsldpc.dll GetSyntaxOfAttribute
59  0x000150f0 0x1800150f0 GLOBAL FUNC 0    adsldpc.dll InitObjectInfo
60  0x000151b0 0x1800151b0 GLOBAL FUNC 0    adsldpc.dll ?InitializePath@CLexer@@QEAAJPEAG@Z
61  0x0000f800 0x18000f800 GLOBAL FUNC 0    adsldpc.dll IsGCNamespace
62  0x0000f8f0 0x18000f8f0 GLOBAL FUNC 0    adsldpc.dll LdapAddExtS
63  0x0000f950 0x18000f950 GLOBAL FUNC 0    adsldpc.dll LdapAddS
64  0x0000f9b0 0x18000f9b0 GLOBAL FUNC 0    adsldpc.dll LdapAttributeFree
65  0x0000fc20 0x18000fc20 GLOBAL FUNC 0    adsldpc.dll LdapCacheAddRef
66  0x0000fc30 0x18000fc30 GLOBAL FUNC 0    adsldpc.dll LdapCloseObject
67  0x0000fc80 0x18000fc80 GLOBAL FUNC 0    adsldpc.dll LdapCompareExt
68  0x0000fd30 0x18000fd30 GLOBAL FUNC 0    adsldpc.dll LdapControlFree
69  0x0000fd50 0x18000fd50 GLOBAL FUNC 0    adsldpc.dll LdapControlsFree
70  0x0000fd70 0x18000fd70 GLOBAL FUNC 0    adsldpc.dll LdapCountEntries
71  0x0000fd90 0x18000fd90 GLOBAL FUNC 0    adsldpc.dll LdapCrackUserDNtoNTLMUser2
72  0x0000ff70 0x18000ff70 GLOBAL FUNC 0    adsldpc.dll LdapCreatePageControl
73  0x0000ffc0 0x18000ffc0 GLOBAL FUNC 0    adsldpc.dll LdapDeleteExtS
74  0x00010020 0x180010020 GLOBAL FUNC 0    adsldpc.dll LdapDeleteS
75  0x00010080 0x180010080 GLOBAL FUNC 0    adsldpc.dll LdapFirstAttribute
76  0x000100f0 0x1800100f0 GLOBAL FUNC 0    adsldpc.dll LdapFirstEntry
77  0x00010160 0x180010160 GLOBAL FUNC 0    adsldpc.dll LdapGetDn
78  0x00010220 0x180010220 GLOBAL FUNC 0    adsldpc.dll LdapGetNextPageS
79  0x000177e0 0x1800177e0 GLOBAL FUNC 0    adsldpc.dll LdapGetSchemaObjectCount
80  0x00017850 0x180017850 GLOBAL FUNC 0    adsldpc.dll LdapGetSubSchemaSubEntryPath
81  0x000178d0 0x1800178d0 GLOBAL FUNC 0    adsldpc.dll LdapGetSyntaxIdOfAttribute
82  0x00017920 0x180017920 GLOBAL FUNC 0    adsldpc.dll LdapGetSyntaxOfAttributeOnServer
83  0x00010320 0x180010320 GLOBAL FUNC 0    adsldpc.dll LdapGetValues
84  0x000103c0 0x1800103c0 GLOBAL FUNC 0    adsldpc.dll LdapGetValuesLen
85  0x0001c740 0x18001c740 GLOBAL FUNC 0    adsldpc.dll LdapInitializeSearchPreferences
86  0x00017ab0 0x180017ab0 GLOBAL FUNC 0    adsldpc.dll LdapIsClassNameValidOnServer
87  0x00017b40 0x180017b40 GLOBAL FUNC 0    adsldpc.dll LdapMakeSchemaCacheObsolete
88  0x00010460 0x180010460 GLOBAL FUNC 0    adsldpc.dll LdapMemFree
89  0x00010480 0x180010480 GLOBAL FUNC 0    adsldpc.dll LdapModDnS
90  0x00010530 0x180010530 GLOBAL FUNC 0    adsldpc.dll LdapModifyExtS
91  0x00010590 0x180010590 GLOBAL FUNC 0    adsldpc.dll LdapModifyS
92  0x000105f0 0x1800105f0 GLOBAL FUNC 0    adsldpc.dll LdapMsgFree
93  0x00010610 0x180010610 GLOBAL FUNC 0    adsldpc.dll LdapNextAttribute
94  0x00010650 0x180010650 GLOBAL FUNC 0    adsldpc.dll LdapNextEntry
95  0x000110e0 0x1800110e0 GLOBAL FUNC 0    adsldpc.dll LdapOpenObject2
96  0x00011410 0x180011410 GLOBAL FUNC 0    adsldpc.dll LdapOpenObject
97  0x00011440 0x180011440 GLOBAL FUNC 0    adsldpc.dll LdapParsePageControl
98  0x00011490 0x180011490 GLOBAL FUNC 0    adsldpc.dll LdapParseResult
99  0x00011500 0x180011500 GLOBAL FUNC 0    adsldpc.dll LdapReadAttribute2
100 0x00011610 0x180011610 GLOBAL FUNC 0    adsldpc.dll LdapReadAttribute
101 0x00011660 0x180011660 GLOBAL FUNC 0    adsldpc.dll LdapReadAttributeFast
102 0x00011840 0x180011840 GLOBAL FUNC 0    adsldpc.dll LdapRenameExtS
103 0x000118b0 0x1800118b0 GLOBAL FUNC 0    adsldpc.dll LdapResult
104 0x000119f0 0x1800119f0 GLOBAL FUNC 0    adsldpc.dll LdapSearch
105 0x00011a80 0x180011a80 GLOBAL FUNC 0    adsldpc.dll LdapSearchAbandonPage
106 0x00011b80 0x180011b80 GLOBAL FUNC 0    adsldpc.dll LdapSearchExtS
107 0x00011df0 0x180011df0 GLOBAL FUNC 0    adsldpc.dll LdapSearchInitPage
108 0x00011ec0 0x180011ec0 GLOBAL FUNC 0    adsldpc.dll LdapSearchS
109 0x00011f20 0x180011f20 GLOBAL FUNC 0    adsldpc.dll LdapSearchST
110 0x0000eb90 0x18000eb90 GLOBAL FUNC 0    adsldpc.dll LdapTypeBinaryToString
111 0x0000ece0 0x18000ece0 GLOBAL FUNC 0    adsldpc.dll LdapTypeCopyConstruct
112 0x0000edc0 0x18000edc0 GLOBAL FUNC 0    adsldpc.dll LdapTypeFreeLdapModList
113 0x0000ee10 0x18000ee10 GLOBAL FUNC 0    adsldpc.dll LdapTypeFreeLdapModObject
114 0x0000ee70 0x18000ee70 GLOBAL FUNC 0    adsldpc.dll LdapTypeFreeLdapObjects
115 0x00005fe0 0x180005fe0 GLOBAL FUNC 0    adsldpc.dll LdapTypeToAdsTypeDNWithBinary
116 0x00005ff0 0x180005ff0 GLOBAL FUNC 0    adsldpc.dll LdapTypeToAdsTypeDNWithString
117 0x00006000 0x180006000 GLOBAL FUNC 0    adsldpc.dll LdapTypeToAdsTypeGeneralizedTime
118 0x000061e0 0x1800061e0 GLOBAL FUNC 0    adsldpc.dll LdapTypeToAdsTypeUTCTime
119 0x00011fd0 0x180011fd0 GLOBAL FUNC 0    adsldpc.dll LdapValueFree
120 0x00011ff0 0x180011ff0 GLOBAL FUNC 0    adsldpc.dll LdapValueFreeLen
121 0x00013320 0x180013320 GLOBAL FUNC 0    adsldpc.dll LdapcKeepHandleAround
122 0x00012010 0x180012010 GLOBAL FUNC 0    adsldpc.dll LdapcSetStickyServer
123 0x000154a0 0x1800154a0 GLOBAL FUNC 0    adsldpc.dll PathName
124 0x0000c8e0 0x18000c8e0 GLOBAL FUNC 0    adsldpc.dll ReadPagingSupportedAttr
125 0x0000da60 0x18000da60 GLOBAL FUNC 0    adsldpc.dll ReadSecurityDescriptorControlType
126 0x0000db10 0x18000db10 GLOBAL FUNC 0    adsldpc.dll ReadServerSupportsIsADAMControl
127 0x0000dbb0 0x18000dbb0 GLOBAL FUNC 0    adsldpc.dll ReadServerSupportsIsADControl
128 0x00017cc0 0x180017cc0 GLOBAL FUNC 0    adsldpc.dll SchemaAddRef
129 0x00017d20 0x180017d20 GLOBAL FUNC 0    adsldpc.dll SchemaClose
130 0x00017d60 0x180017d60 GLOBAL FUNC 0    adsldpc.dll SchemaGetClassInfo
131 0x00017dd0 0x180017dd0 GLOBAL FUNC 0    adsldpc.dll SchemaGetClassInfoByIndex
132 0x00017e00 0x180017e00 GLOBAL FUNC 0    adsldpc.dll SchemaGetObjectCount
133 0x00017e30 0x180017e30 GLOBAL FUNC 0    adsldpc.dll SchemaGetPropertyInfo
134 0x00017ee0 0x180017ee0 GLOBAL FUNC 0    adsldpc.dll SchemaGetPropertyInfoByIndex
135 0x00017f10 0x180017f10 GLOBAL FUNC 0    adsldpc.dll SchemaGetStringsFromStringTable
136 0x00018070 0x180018070 GLOBAL FUNC 0    adsldpc.dll SchemaGetSyntaxOfAttribute
137 0x00018170 0x180018170 GLOBAL FUNC 0    adsldpc.dll SchemaIsClassAContainer
138 0x000182d0 0x1800182d0 GLOBAL FUNC 0    adsldpc.dll SchemaOpen
139 0x00002990 0x180002990 GLOBAL FUNC 0    adsldpc.dll ?SetAtDisabler@CLexer@@QEAAXH@Z
140 0x000156b0 0x1800156b0 GLOBAL FUNC 0    adsldpc.dll ?SetExclaimnationDisabler@CLexer@@QEAAXH@Z
141 0x000156c0 0x1800156c0 GLOBAL FUNC 0    adsldpc.dll ?SetFSlashDisabler@CLexer@@QEAAXH@Z
142 0x0000df10 0x18000df10 GLOBAL FUNC 0    adsldpc.dll SortAndRemoveDuplicateOIDs
143 0x0001e4f0 0x18001e4f0 GLOBAL FUNC 0    adsldpc.dll UnMarshallLDAPToLDAPSynID
144 0x0000e990 0x18000e990 GLOBAL FUNC 0    adsldpc.dll intcmp
145 0x000038a0 0x1800038a0 GLOBAL FUNC 0    adsldpc.dll ADSIAbandonSearch
146 0x000038b0 0x1800038b0 GLOBAL FUNC 0    adsldpc.dll ADSICloseDSObject
147 0x000038e0 0x1800038e0 GLOBAL FUNC 0    adsldpc.dll ADSICloseSearchHandle
148 0x000038f0 0x1800038f0 GLOBAL FUNC 0    adsldpc.dll ADSICreateDSObject
149 0x00003930 0x180003930 GLOBAL FUNC 0    adsldpc.dll ADSIDeleteDSObject
150 0x00003950 0x180003950 GLOBAL FUNC 0    adsldpc.dll ADSIExecuteSearch
151 0x000039f0 0x1800039f0 GLOBAL FUNC 0    adsldpc.dll ADSIFreeColumn
152 0x00003a00 0x180003a00 GLOBAL FUNC 0    adsldpc.dll ADSIGetColumn
153 0x00003a40 0x180003a40 GLOBAL FUNC 0    adsldpc.dll ADSIGetFirstRow
154 0x00003a60 0x180003a60 GLOBAL FUNC 0    adsldpc.dll ADSIGetNextColumnName
155 0x00003a80 0x180003a80 GLOBAL FUNC 0    adsldpc.dll ADSIGetNextRow
156 0x00003aa0 0x180003aa0 GLOBAL FUNC 0    adsldpc.dll ADSIGetObjectAttributes
157 0x00003b40 0x180003b40 GLOBAL FUNC 0    adsldpc.dll ADSIGetPreviousRow
158 0x00003b60 0x180003b60 GLOBAL FUNC 0    adsldpc.dll ADSIModifyRdn
159 0x00003c60 0x180003c60 GLOBAL FUNC 0    adsldpc.dll ADSIOpenDSObject
160 0x00003e90 0x180003e90 GLOBAL FUNC 0    adsldpc.dll ADSISetObjectAttributes
161 0x00003f20 0x180003f20 GLOBAL FUNC 0    adsldpc.dll ADSISetSearchPreference
162 0x00003060 0x180003060 GLOBAL FUNC 0    adsldpc.dll ADsDecodeBinaryData
163 0x000031a0 0x1800031a0 GLOBAL FUNC 0    adsldpc.dll ADsEncodeBinaryData
164 0x000034e0 0x1800034e0 GLOBAL FUNC 0    adsldpc.dll ADsGetLastError
165 0x00003630 0x180003630 GLOBAL FUNC 0    adsldpc.dll ADsSetLastError
166 0x000063e0 0x1800063e0 GLOBAL FUNC 0    adsldpc.dll AdsTypeFreeAdsObjects
167 0x000016d0 0x1800016d0 GLOBAL FUNC 0    adsldpc.dll AllocADsMem
168 0x000015c0 0x1800015c0 GLOBAL FUNC 0    adsldpc.dll AllocADsStr
169 0x000016a0 0x1800016a0 GLOBAL FUNC 0    adsldpc.dll FreeADsMem
170 0x00001660 0x180001660 GLOBAL FUNC 0    adsldpc.dll FreeADsStr
171 0x000064d0 0x1800064d0 GLOBAL FUNC 0    adsldpc.dll LdapTypeToAdsTypeCopyConstruct
172 0x000056a0 0x1800056a0 GLOBAL FUNC 0    adsldpc.dll MapADSTypeToLDAPType
173 0x000056d0 0x1800056d0 GLOBAL FUNC 0    adsldpc.dll MapLDAPTypeToADSType
174 0x00003270 0x180003270 GLOBAL FUNC 0    adsldpc.dll ReallocADsMem
175 0x000032f0 0x1800032f0 GLOBAL FUNC 0    adsldpc.dll ReallocADsStr
```

#### Functions and Documentation

| Exported Function                          | Documentation Link |
|--------------------------------------------|--------------------|
| ??0CLexer@@QEAA@XZ                         | N/A                |
| ??1CLexer@@QEAA@XZ                         | N/A                |
| ADSIPrint                                  | N/A                |
| ADsAbandonSearch                           | N/A                |
| ADsCloseSearchHandle                       | N/A                |
| ADsCreateAttributeDefinition               | N/A                |
| ADsCreateClassDefinition                   | N/A                |
| ADsCreateDSObject                          | N/A                |
| ADsCreateDSObjectExt                       | N/A                |
| ADsDeleteAttributeDefinition               | N/A                |
| ADsDeleteClassDefinition                   | N/A                |
| ADsDeleteDSObject                          | N/A                |
| ADsEnumAttributes                          | N/A                |
| ADsEnumClasses                             | N/A                |
| ADsExecuteSearch                           | N/A                |
| ADsFreeColumn                              | N/A                |
| ADsGetColumn                               | N/A                |
| ADsGetFirstRow                             | N/A                |
| ADsGetNextColumnName                       | N/A                |
| ADsGetNextRow                              | N/A                |
| ADsGetObjectAttributes                     | N/A                |
| ADsGetPreviousRow                          | N/A                |
| ADsHelperGetCurrentRowMessage              | N/A                |
| ADsObject                                  | N/A                |
| ADsSetObjectAttributes                     | N/A                |
| ADsSetSearchPreference                     | N/A                |
| ADsWriteAttributeDefinition                | N/A                |
| ADsWriteClassDefinition                    | N/A                |
| AdsTypeToLdapTypeCopyConstruct             | N/A                |
| AdsTypeToLdapTypeCopyDNWithBinary          | N/A                |
| AdsTypeToLdapTypeCopyDNWithString          | N/A                |
| AdsTypeToLdapTypeCopyGeneralizedTime       | N/A                |
| AdsTypeToLdapTypeCopyTime                  | N/A                |
| BerBvFree                                  | N/A                |
| BerEncodingQuotaControl                    | N/A                |
| BuildADsParentPath                         | N/A                |
| BuildADsParentPathFromObjectInfo2          | N/A                |
| BuildADsParentPathFromObjectInfo           | N/A                |
| BuildADsPathFromLDAPPath2                  | N/A                |
| BuildADsPathFromLDAPPath                   | N/A                |
| BuildADsPathFromParent                     | N/A                |
| BuildLDAPPathFromADsPath2                  | N/A                |
| BuildLDAPPathFromADsPath                   | N/A                |
| ChangeSeparator                            | N/A                |
| Component                                  | N/A                |
| ConvertSidToString                         | N/A                |
| ConvertSidToU2Trustee                      | N/A                |
| ConvertU2TrusteeToSid                      | N/A                |
| FindEntryInSearchTable                     | N/A                |
| FindSearchTableIndex                       | N/A                |
| FreeObjectInfo                             | N/A                |
| GetDefaultServer                           | N/A                |
| GetDisplayName                             | N/A                |
| GetDomainDNSNameForDomain                  | N/A                |
| GetLDAPTypeName                            | N/A                |
| ?GetNextToken@CLexer@@QEAAJPEAGPEAK@Z      | N/A                |
| GetServerAndPort                           | N/A                |
| GetSyntaxOfAttribute                       | N/A                |
| InitObjectInfo                             | N/A                |
| ?InitializePath@CLexer@@QEAAJPEAG@Z        | N/A                |
| IsGCNamespace                              | N/A                |
| LdapAddExtS                                | N/A                |
| LdapAddS                                   | N/A                |
| LdapAttributeFree                          | N/A                |
| LdapCacheAddRef                            | N/A                |
| LdapCloseObject                            | N/A                |
| LdapCompareExt                             | N/A                |
| LdapControlFree                            | N/A                |
| LdapControlsFree                           | N/A                |
| LdapCountEntries                           | N/A                |
| LdapCrackUserDNtoNTLMUser2                 | N/A                |
| LdapCreatePageControl                      | N/A                |
| LdapDeleteExtS                             | N/A                |
| LdapDeleteS                                | N/A                |
| LdapFirstAttribute                         | N/A                |
| LdapFirstEntry                             | N/A                |
| LdapGetDn                                  | N/A                |
| LdapGetNextPageS                           | N/A                |
| LdapGetSchemaObjectCount                   | N/A                |
| LdapGetSubSchemaSubEntryPath               | N/A                |
| LdapGetSyntaxIdOfAttribute                 | N/A                |
| LdapGetSyntaxOfAttributeOnServer           | N/A                |
| LdapGetValues                              | N/A                |
| LdapGetValuesLen                           | N/A                |
| LdapInitializeSearchPreferences            | N/A                |
| LdapIsClassNameValidOnServer               | N/A                |
| LdapMakeSchemaCacheObsolete                | N/A                |
| LdapMemFree                                | N/A                |
| LdapModDnS                                 | N/A                |
| LdapModifyExtS                             | N/A                |
| LdapModifyS                                | N/A                |
| LdapMsgFree                                | N/A                |
| LdapNextAttribute                          | N/A                |
| LdapNextEntry                              | N/A                |
| LdapOpenObject2                            | N/A                |
| LdapOpenObject                             | N/A                |
| LdapParsePageControl                       | N/A                |
| LdapParseResult                            | N/A                |
| LdapReadAttribute2                         | N/A                |
| LdapReadAttribute                          | N/A                |
| LdapReadAttributeFast                      | N/A                |
| LdapRenameExtS                             | N/A                |
| LdapResult                                 | N/A                |
| LdapSearch                                 | N/A                |
| LdapSearchAbandonPage                      | N/A                |
| LdapSearchExtS                             | N/A                |
| LdapSearchInitPage                         | N/A                |
| LdapSearchS                                | N/A                |
| LdapSearchST                               | N/A                |
| LdapTypeBinaryToString                     | N/A                |
| LdapTypeCopyConstruct                      | N/A                |
| LdapTypeFreeLdapModList                    | N/A                |
| LdapTypeFreeLdapModObject                  | N/A                |
| LdapTypeFreeLdapObjects                    | N/A                |
| LdapTypeToAdsTypeDNWithBinary              | N/A                |
| LdapTypeToAdsTypeDNWithString              | N/A                |
| LdapTypeToAdsTypeGeneralizedTime           | N/A                |
| LdapTypeToAdsTypeUTCTime                   | N/A                |
| LdapValueFree                              | N/A                |
| LdapValueFreeLen                           | N/A                |
| LdapcKeepHandleAround                      | N/A                |
| LdapcSetStickyServer                       | N/A                |
| PathName                                   | N/A                |
| ReadPagingSupportedAttr                    | N/A                |
| ReadSecurityDescriptorControlType          | N/A                |
| ReadServerSupportsIsADAMControl            | N/A                |
| ReadServerSupportsIsADControl              | N/A                |
| SchemaAddRef                               | N/A                |
| SchemaClose                                | N/A                |
| SchemaGetClassInfo                         | N/A                |
| SchemaGetClassInfoByIndex                  | N/A                |
| SchemaGetObjectCount                       | N/A                |
| SchemaGetPropertyInfo                      | N/A                |
| SchemaGetPropertyInfoByIndex               | N/A                |
| SchemaGetStringsFromStringTable            | N/A                |
| SchemaGetSyntaxOfAttribute                 | N/A                |
| SchemaIsClassAContainer                    | N/A                |
| SchemaOpen                                 | N/A                |
| ?SetAtDisabler@CLexer@@QEAAXH@Z            | N/A                |
| ?SetExclaimnationDisabler@CLexer@@QEAAXH@Z | N/A                |
| ?SetFSlashDisabler@CLexer@@QEAAXH@Z        | N/A                |
| SortAndRemoveDuplicateOIDs                 | N/A                |
| UnMarshallLDAPToLDAPSynID                  | N/A                |
| intcmp                                     | N/A                |
| ADSIAbandonSearch                          | N/A                |
| ADSICloseDSObject                          | N/A                |
| ADSICloseSearchHandle                      | N/A                |
| ADSICreateDSObject                         | N/A                |
| ADSIDeleteDSObject                         | N/A                |
| ADSIExecuteSearch                          | N/A                |
| ADSIFreeColumn                             | N/A                |
| ADSIGetColumn                              | N/A                |
| ADSIGetFirstRow                            | N/A                |
| ADSIGetNextColumnName                      | N/A                |
| ADSIGetNextRow                             | N/A                |
| ADSIGetObjectAttributes                    | N/A                |
| ADSIGetPreviousRow                         | N/A                |
| ADSIModifyRdn                              | N/A                |
| ADSIOpenDSObject                           | N/A                |
| ADSISetObjectAttributes                    | N/A                |
| ADSISetSearchPreference                    | N/A                |
| ADsDecodeBinaryData                        | N/A                |
| ADsEncodeBinaryData                        | N/A                |
| ADsGetLastError                            | N/A                |
| ADsSetLastError                            | N/A                |
| AdsTypeFreeAdsObjects                      | N/A                |
| AllocADsMem                                | N/A                |
| AllocADsStr                                | N/A                |
| FreeADsMem                                 | N/A                |
| FreeADsStr                                 | N/A                |
| LdapTypeToAdsTypeCopyConstruct             | N/A                |
| MapADSTypeToLDAPType                       | N/A                |
| MapLDAPTypeToADSType                       | N/A                |
| ReallocADsMem                              | N/A                |
| ReallocADsStr                              | N/A                |

## adsmsext.dll

#### Export table:

```
1   0x0000f290 0x18000f290 GLOBAL FUNC 0    adsmsext.dll DllCanUnloadNow
2   0x0000f340 0x18000f340 GLOBAL FUNC 0    adsmsext.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function | Documentation Link                                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow   | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## adsnt.dll

#### Export table:

```
1   0x00003ce0 0x180003ce0 GLOBAL FUNC 0    ADSNT.dll DllCanUnloadNow
2   0x00003b30 0x180003b30 GLOBAL FUNC 0    ADSNT.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function | Documentation Link                                                                                                  |
|-------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow   | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetClassObject | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---

## AdvancedEmojiDS.dll

#### Export table:

```
1   0x0000da60 0x15090da60 GLOBAL FUNC 0    AdvancedEmojiDS.dll DllCanUnloadNow
2   0x0000d750 0x15090d750 GLOBAL FUNC 0    AdvancedEmojiDS.dll DllGetActivationFactory
3   0x0000d950 0x15090d950 GLOBAL FUNC 0    AdvancedEmojiDS.dll DllGetClassObject
```

#### Functions and Documentation

| Exported Function       | Documentation Link                                                                                                  |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| DllCanUnloadNow         | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllcanunloadnow)     |
| DllGetActivationFactory | N/A                                                                                                                 |
| DllGetClassObject       | [DllGetClassObject](https://learn.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-dllgetclassobject) |

---


