<p align="center">
    <img src="../.github/winapi.png" height="256" width="256">
</p>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund 

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)**


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
- [advapi32](#advapi32.dll)
- [advpack](#advpack.dll)
- [aeinv](#aeinv.dll)
- [aepic](#aepic.dll)
- [agentactivationruntime](#agentactivationruntime.dll)

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

## advapi32.dll

#### Export table:

```
1000 0x00038f30 0x180038f30 GLOBAL FUNC 0    ADVAPI32.dll Ordinal_1000
1001 0x00046c30 0x180046c30 GLOBAL FUNC 0    ADVAPI32.dll I_ScGetCurrentGroupStateW
1002 0x000952da 0x1800952da GLOBAL FUNC 0    ADVAPI32.dll A_SHAFinal
1003 0x000952f5 0x1800952f5 GLOBAL FUNC 0    ADVAPI32.dll A_SHAInit
1004 0x00095311 0x180095311 GLOBAL FUNC 0    ADVAPI32.dll A_SHAUpdate
1005 0x00043b20 0x180043b20 GLOBAL FUNC 0    ADVAPI32.dll AbortSystemShutdownA
1006 0x00043bc0 0x180043bc0 GLOBAL FUNC 0    ADVAPI32.dll AbortSystemShutdownW
1007 0x00009200 0x180009200 GLOBAL FUNC 0    ADVAPI32.dll AccessCheck
1008 0x00047990 0x180047990 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckAndAuditAlarmA
1009 0x0002e2c0 0x18002e2c0 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckAndAuditAlarmW
1010 0x0002e600 0x18002e600 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckByType
1011 0x00047b50 0x180047b50 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckByTypeAndAuditAlarmA
1012 0x0002e340 0x18002e340 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckByTypeAndAuditAlarmW
1013 0x0002e580 0x18002e580 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckByTypeResultList
1014 0x00047d30 0x180047d30 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckByTypeResultListAndAuditAlarmA
1015 0x00047f10 0x180047f10 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckByTypeResultListAndAuditAlarmByHandleA
1016 0x0002e400 0x18002e400 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckByTypeResultListAndAuditAlarmByHandleW
1017 0x0002e4c0 0x18002e4c0 GLOBAL FUNC 0    ADVAPI32.dll AccessCheckByTypeResultListAndAuditAlarmW
1018 0x000082a0 0x1800082a0 GLOBAL FUNC 0    ADVAPI32.dll AddAccessAllowedAce
1019 0x00008e20 0x180008e20 GLOBAL FUNC 0    ADVAPI32.dll AddAccessAllowedAceEx
1020 0x0002e680 0x18002e680 GLOBAL FUNC 0    ADVAPI32.dll AddAccessAllowedObjectAce
1021 0x0002e6c0 0x18002e6c0 GLOBAL FUNC 0    ADVAPI32.dll AddAccessDeniedAce
1022 0x0002e6a0 0x18002e6a0 GLOBAL FUNC 0    ADVAPI32.dll AddAccessDeniedAceEx
1023 0x0002e6e0 0x18002e6e0 GLOBAL FUNC 0    ADVAPI32.dll AddAccessDeniedObjectAce
1024 0x00008d10 0x180008d10 GLOBAL FUNC 0    ADVAPI32.dll AddAce
1025 0x0002e720 0x18002e720 GLOBAL FUNC 0    ADVAPI32.dll AddAuditAccessAce
1026 0x0002e700 0x18002e700 GLOBAL FUNC 0    ADVAPI32.dll AddAuditAccessAceEx
1027 0x0002e740 0x18002e740 GLOBAL FUNC 0    ADVAPI32.dll AddAuditAccessObjectAce
1028 0x0004bcc0 0x18004bcc0 GLOBAL FUNC 0    ADVAPI32.dll AddConditionalAce
1029 0x0009559f 0x18009559f GLOBAL FUNC 0    ADVAPI32.dll AddMandatoryAce
1030 0x0002d350 0x18002d350 GLOBAL FUNC 0    ADVAPI32.dll AddUsersToEncryptedFile
1031 0x0002d3d0 0x18002d3d0 GLOBAL FUNC 0    ADVAPI32.dll AddUsersToEncryptedFileEx
1032 0x0002e760 0x18002e760 GLOBAL FUNC 0    ADVAPI32.dll AdjustTokenGroups
1033 0x00008d70 0x180008d70 GLOBAL FUNC 0    ADVAPI32.dll AdjustTokenPrivileges
1034 0x00006a80 0x180006a80 GLOBAL FUNC 0    ADVAPI32.dll AllocateAndInitializeSid
1035 0x0002e780 0x18002e780 GLOBAL FUNC 0    ADVAPI32.dll AllocateLocallyUniqueId
1036 0x0002e7a0 0x18002e7a0 GLOBAL FUNC 0    ADVAPI32.dll AreAllAccessesGranted
1037 0x0002e7c0 0x18002e7c0 GLOBAL FUNC 0    ADVAPI32.dll AreAnyAccessesGranted
1038 0x0002e7e0 0x18002e7e0 GLOBAL FUNC 0    ADVAPI32.dll AuditComputeEffectivePolicyBySid
1039 0x00030b40 0x180030b40 GLOBAL FUNC 0    ADVAPI32.dll AuditComputeEffectivePolicyByToken
1040 0x0002e800 0x18002e800 GLOBAL FUNC 0    ADVAPI32.dll AuditEnumerateCategories
1041 0x0002e820 0x18002e820 GLOBAL FUNC 0    ADVAPI32.dll AuditEnumeratePerUserPolicy
1042 0x0002e840 0x18002e840 GLOBAL FUNC 0    ADVAPI32.dll AuditEnumerateSubCategories
1043 0x0001ab50 0x18001ab50 GLOBAL FUNC 0    ADVAPI32.dll AuditFree
1044 0x00030ca0 0x180030ca0 GLOBAL FUNC 0    ADVAPI32.dll AuditLookupCategoryGuidFromCategoryId
1045 0x00030ce0 0x180030ce0 GLOBAL FUNC 0    ADVAPI32.dll AuditLookupCategoryIdFromCategoryGuid
1046 0x00030d50 0x180030d50 GLOBAL FUNC 0    ADVAPI32.dll AuditLookupCategoryNameA
1047 0x0002e860 0x18002e860 GLOBAL FUNC 0    ADVAPI32.dll AuditLookupCategoryNameW
1048 0x00030e00 0x180030e00 GLOBAL FUNC 0    ADVAPI32.dll AuditLookupSubCategoryNameA
1049 0x0002e880 0x18002e880 GLOBAL FUNC 0    ADVAPI32.dll AuditLookupSubCategoryNameW
1050 0x00030eb0 0x180030eb0 GLOBAL FUNC 0    ADVAPI32.dll AuditQueryGlobalSaclA
1051 0x0002e8a0 0x18002e8a0 GLOBAL FUNC 0    ADVAPI32.dll AuditQueryGlobalSaclW
1052 0x0001ab90 0x18001ab90 GLOBAL FUNC 0    ADVAPI32.dll AuditQueryPerUserPolicy
1053 0x0002e8c0 0x18002e8c0 GLOBAL FUNC 0    ADVAPI32.dll AuditQuerySecurity
1054 0x0001ab30 0x18001ab30 GLOBAL FUNC 0    ADVAPI32.dll AuditQuerySystemPolicy
1055 0x00030f70 0x180030f70 GLOBAL FUNC 0    ADVAPI32.dll AuditSetGlobalSaclA
1056 0x0002e8e0 0x18002e8e0 GLOBAL FUNC 0    ADVAPI32.dll AuditSetGlobalSaclW
1057 0x0002e900 0x18002e900 GLOBAL FUNC 0    ADVAPI32.dll AuditSetPerUserPolicy
1058 0x0002e920 0x18002e920 GLOBAL FUNC 0    ADVAPI32.dll AuditSetSecurity
1059 0x0002e940 0x18002e940 GLOBAL FUNC 0    ADVAPI32.dll AuditSetSystemPolicy
1060 0x00051b10 0x180051b10 GLOBAL FUNC 0    ADVAPI32.dll BackupEventLogA
1061 0x00051bb0 0x180051bb0 GLOBAL FUNC 0    ADVAPI32.dll BackupEventLogW
1062 0x00044140 0x180044140 GLOBAL FUNC 0    ADVAPI32.dll BaseRegCloseKey
1063 0x00044170 0x180044170 GLOBAL FUNC 0    ADVAPI32.dll BaseRegCreateKey
1064 0x000441e0 0x1800441e0 GLOBAL FUNC 0    ADVAPI32.dll BaseRegDeleteKeyEx
1065 0x00044220 0x180044220 GLOBAL FUNC 0    ADVAPI32.dll BaseRegDeleteValue
1066 0x00044260 0x180044260 GLOBAL FUNC 0    ADVAPI32.dll BaseRegFlushKey
1067 0x00044290 0x180044290 GLOBAL FUNC 0    ADVAPI32.dll BaseRegGetVersion
1068 0x000442d0 0x1800442d0 GLOBAL FUNC 0    ADVAPI32.dll BaseRegLoadKey
1069 0x00044310 0x180044310 GLOBAL FUNC 0    ADVAPI32.dll BaseRegOpenKey
1070 0x00044360 0x180044360 GLOBAL FUNC 0    ADVAPI32.dll BaseRegRestoreKey
1071 0x000443a0 0x1800443a0 GLOBAL FUNC 0    ADVAPI32.dll BaseRegSaveKeyEx
1072 0x000443e0 0x1800443e0 GLOBAL FUNC 0    ADVAPI32.dll BaseRegSetKeySecurity
1073 0x00044420 0x180044420 GLOBAL FUNC 0    ADVAPI32.dll BaseRegSetValue
1074 0x00044470 0x180044470 GLOBAL FUNC 0    ADVAPI32.dll BaseRegUnLoadKey
1075 0x0003dfa0 0x18003dfa0 GLOBAL FUNC 0    ADVAPI32.dll BuildExplicitAccessWithNameA
1076 0x00009010 0x180009010 GLOBAL FUNC 0    ADVAPI32.dll BuildExplicitAccessWithNameW
1077 0x0003dfd0 0x18003dfd0 GLOBAL FUNC 0    ADVAPI32.dll BuildImpersonateExplicitAccessWithNameA
1078 0x0003e010 0x18003e010 GLOBAL FUNC 0    ADVAPI32.dll BuildImpersonateExplicitAccessWithNameW
1079 0x0003f060 0x18003f060 GLOBAL FUNC 0    ADVAPI32.dll BuildImpersonateTrusteeA
1080 0x0003f080 0x18003f080 GLOBAL FUNC 0    ADVAPI32.dll BuildImpersonateTrusteeW
1081 0x0003e050 0x18003e050 GLOBAL FUNC 0    ADVAPI32.dll BuildSecurityDescriptorA
1082 0x000078e0 0x1800078e0 GLOBAL FUNC 0    ADVAPI32.dll BuildSecurityDescriptorW
1083 0x0003f0a0 0x18003f0a0 GLOBAL FUNC 0    ADVAPI32.dll BuildTrusteeWithNameA
1084 0x0003f0c0 0x18003f0c0 GLOBAL FUNC 0    ADVAPI32.dll BuildTrusteeWithNameW
1085 0x0003f0e0 0x18003f0e0 GLOBAL FUNC 0    ADVAPI32.dll BuildTrusteeWithObjectsAndNameA
1086 0x0003f140 0x18003f140 GLOBAL FUNC 0    ADVAPI32.dll BuildTrusteeWithObjectsAndNameW
1087 0x0003f1a0 0x18003f1a0 GLOBAL FUNC 0    ADVAPI32.dll BuildTrusteeWithObjectsAndSidA
1088 0x0003f230 0x18003f230 GLOBAL FUNC 0    ADVAPI32.dll BuildTrusteeWithObjectsAndSidW
1089 0x0003f2c0 0x18003f2c0 GLOBAL FUNC 0    ADVAPI32.dll BuildTrusteeWithSidA
1090 0x0001abb0 0x18001abb0 GLOBAL FUNC 0    ADVAPI32.dll BuildTrusteeWithSidW
1091 0x0003fa30 0x18003fa30 GLOBAL FUNC 0    ADVAPI32.dll CancelOverlappedAccess
1092 0x0002e960 0x18002e960 GLOBAL FUNC 0    ADVAPI32.dll ChangeServiceConfig2A
1093 0x0001c060 0x18001c060 GLOBAL FUNC 0    ADVAPI32.dll ChangeServiceConfig2W
1094 0x0002e980 0x18002e980 GLOBAL FUNC 0    ADVAPI32.dll ChangeServiceConfigA
1095 0x0001bee0 0x18001bee0 GLOBAL FUNC 0    ADVAPI32.dll ChangeServiceConfigW
1096 0x0001a5a0 0x18001a5a0 GLOBAL FUNC 0    ADVAPI32.dll CheckForHiberboot
1097 0x00008460 0x180008460 GLOBAL FUNC 0    ADVAPI32.dll CheckTokenMembership
1098 0x00051e40 0x180051e40 GLOBAL FUNC 0    ADVAPI32.dll ClearEventLogA
1099 0x00051ee0 0x180051ee0 GLOBAL FUNC 0    ADVAPI32.dll ClearEventLogW
1100 0x000067f0 0x1800067f0 GLOBAL FUNC 0    ADVAPI32.dll CloseCodeAuthzLevel
1101 0x0002d470 0x18002d470 GLOBAL FUNC 0    ADVAPI32.dll CloseEncryptedFileRaw
1102 0x000050b0 0x1800050b0 GLOBAL FUNC 0    ADVAPI32.dll CloseEventLog
1103 0x00008e70 0x180008e70 GLOBAL FUNC 0    ADVAPI32.dll CloseServiceHandle
1104 0x00062900 0x180062900 GLOBAL FUNC 0    ADVAPI32.dll CloseThreadWaitChainSession
1105 0x000092e0 0x1800092e0 GLOBAL FUNC 0    ADVAPI32.dll CloseTrace
1106 0x00003e50 0x180003e50 GLOBAL FUNC 0    ADVAPI32.dll CommandLineFromMsiDescriptor
1107 0x0000ad70 0x18000ad70 GLOBAL FUNC 0    ADVAPI32.dll ComputeAccessTokenFromCodeAuthzLevel
1108 0x0001ff20 0x18001ff20 GLOBAL FUNC 0    ADVAPI32.dll ControlService
1109 0x0002ea00 0x18002ea00 GLOBAL FUNC 0    ADVAPI32.dll ControlServiceExA
1110 0x0002ea20 0x18002ea20 GLOBAL FUNC 0    ADVAPI32.dll ControlServiceExW
1111 0x0001c900 0x18001c900 GLOBAL FUNC 0    ADVAPI32.dll ControlTraceA
1112 0x00009400 0x180009400 GLOBAL FUNC 0    ADVAPI32.dll ControlTraceW
1113 0x0003fab0 0x18003fab0 GLOBAL FUNC 0    ADVAPI32.dll ConvertAccessToSecurityDescriptorA
1114 0x0003fc40 0x18003fc40 GLOBAL FUNC 0    ADVAPI32.dll ConvertAccessToSecurityDescriptorW
1115 0x0004c570 0x18004c570 GLOBAL FUNC 0    ADVAPI32.dll ConvertSDToStringSDDomainW
1116 0x0004c600 0x18004c600 GLOBAL FUNC 0    ADVAPI32.dll ConvertSDToStringSDRootDomainA
1117 0x0004c780 0x18004c780 GLOBAL FUNC 0    ADVAPI32.dll ConvertSDToStringSDRootDomainW
1118 0x0003fce0 0x18003fce0 GLOBAL FUNC 0    ADVAPI32.dll ConvertSecurityDescriptorToAccessA
1119 0x0003fd30 0x18003fd30 GLOBAL FUNC 0    ADVAPI32.dll ConvertSecurityDescriptorToAccessNamedA
1120 0x0003fd80 0x18003fd80 GLOBAL FUNC 0    ADVAPI32.dll ConvertSecurityDescriptorToAccessNamedW
1121 0x0003fdd0 0x18003fdd0 GLOBAL FUNC 0    ADVAPI32.dll ConvertSecurityDescriptorToAccessW
1122 0x0004c800 0x18004c800 GLOBAL FUNC 0    ADVAPI32.dll ConvertSecurityDescriptorToStringSecurityDescriptorA
1123 0x0001ac10 0x18001ac10 GLOBAL FUNC 0    ADVAPI32.dll ConvertSecurityDescriptorToStringSecurityDescriptorW
1124 0x00004960 0x180004960 GLOBAL FUNC 0    ADVAPI32.dll ConvertSidToStringSidA
1125 0x00004e40 0x180004e40 GLOBAL FUNC 0    ADVAPI32.dll ConvertSidToStringSidW
1126 0x0004c970 0x18004c970 GLOBAL FUNC 0    ADVAPI32.dll ConvertStringSDToSDDomainA
1127 0x0004cab0 0x18004cab0 GLOBAL FUNC 0    ADVAPI32.dll ConvertStringSDToSDDomainW
1128 0x0004cb80 0x18004cb80 GLOBAL FUNC 0    ADVAPI32.dll ConvertStringSDToSDRootDomainA
1129 0x0004cc60 0x18004cc60 GLOBAL FUNC 0    ADVAPI32.dll ConvertStringSDToSDRootDomainW
1130 0x0004cce0 0x18004cce0 GLOBAL FUNC 0    ADVAPI32.dll ConvertStringSecurityDescriptorToSecurityDescriptorA
1131 0x0000dad0 0x18000dad0 GLOBAL FUNC 0    ADVAPI32.dll ConvertStringSecurityDescriptorToSecurityDescriptorW
1132 0x0004cdb0 0x18004cdb0 GLOBAL FUNC 0    ADVAPI32.dll ConvertStringSidToSidA
1133 0x0000f120 0x18000f120 GLOBAL FUNC 0    ADVAPI32.dll ConvertStringSidToSidW
1134 0x0002ea40 0x18002ea40 GLOBAL FUNC 0    ADVAPI32.dll ConvertToAutoInheritPrivateObjectSecurity
1135 0x00007400 0x180007400 GLOBAL FUNC 0    ADVAPI32.dll CopySid
1136 0x00037240 0x180037240 GLOBAL FUNC 0    ADVAPI32.dll CreateCodeAuthzLevel
1137 0x0001ff40 0x18001ff40 GLOBAL FUNC 0    ADVAPI32.dll CreatePrivateObjectSecurity
1138 0x0002ea60 0x18002ea60 GLOBAL FUNC 0    ADVAPI32.dll CreatePrivateObjectSecurityEx
1139 0x0002ea80 0x18002ea80 GLOBAL FUNC 0    ADVAPI32.dll CreatePrivateObjectSecurityWithMultipleInheritance
1140 0x0002eaa0 0x18002eaa0 GLOBAL FUNC 0    ADVAPI32.dll CreateProcessAsUserA
1141 0x00008f90 0x180008f90 GLOBAL FUNC 0    ADVAPI32.dll CreateProcessAsUserW
1142 0x0004b180 0x18004b180 GLOBAL FUNC 0    ADVAPI32.dll CreateProcessWithLogonW
1143 0x0004b200 0x18004b200 GLOBAL FUNC 0    ADVAPI32.dll CreateProcessWithTokenW
1144 0x000046b0 0x1800046b0 GLOBAL FUNC 0    ADVAPI32.dll CreateRestrictedToken
1145 0x0002eb20 0x18002eb20 GLOBAL FUNC 0    ADVAPI32.dll CreateServiceA
1146 0x0001caa0 0x18001caa0 GLOBAL FUNC 0    ADVAPI32.dll CreateServiceEx
1147 0x0002ebb0 0x18002ebb0 GLOBAL FUNC 0    ADVAPI32.dll CreateServiceW
1148 0x00096151 0x180096151 GLOBAL FUNC 0    ADVAPI32.dll CreateTraceInstanceId
1149 0x00009250 0x180009250 GLOBAL FUNC 0    ADVAPI32.dll CreateWellKnownSid
1150 0x0002ec40 0x18002ec40 GLOBAL FUNC 0    ADVAPI32.dll CredBackupCredentials
1151 0x0002ec60 0x18002ec60 GLOBAL FUNC 0    ADVAPI32.dll CredDeleteA
1152 0x0002ec80 0x18002ec80 GLOBAL FUNC 0    ADVAPI32.dll CredDeleteW
1153 0x0002eca0 0x18002eca0 GLOBAL FUNC 0    ADVAPI32.dll CredEncryptAndMarshalBinaryBlob
1154 0x0002ecc0 0x18002ecc0 GLOBAL FUNC 0    ADVAPI32.dll CredEnumerateA
1155 0x0002ece0 0x18002ece0 GLOBAL FUNC 0    ADVAPI32.dll CredEnumerateW
1156 0x0002ed00 0x18002ed00 GLOBAL FUNC 0    ADVAPI32.dll CredFindBestCredentialA
1157 0x0002ed20 0x18002ed20 GLOBAL FUNC 0    ADVAPI32.dll CredFindBestCredentialW
1158 0x0002ed40 0x18002ed40 GLOBAL FUNC 0    ADVAPI32.dll CredFree
1159 0x0002ed60 0x18002ed60 GLOBAL FUNC 0    ADVAPI32.dll CredGetSessionTypes
1160 0x0002ed80 0x18002ed80 GLOBAL FUNC 0    ADVAPI32.dll CredGetTargetInfoA
1161 0x0002eda0 0x18002eda0 GLOBAL FUNC 0    ADVAPI32.dll CredGetTargetInfoW
1162 0x00031320 0x180031320 GLOBAL FUNC 0    ADVAPI32.dll CredIsMarshaledCredentialA
1163 0x0002edc0 0x18002edc0 GLOBAL FUNC 0    ADVAPI32.dll CredIsMarshaledCredentialW
1164 0x0002ede0 0x18002ede0 GLOBAL FUNC 0    ADVAPI32.dll CredIsProtectedA
1165 0x0002ee00 0x18002ee00 GLOBAL FUNC 0    ADVAPI32.dll CredIsProtectedW
1166 0x0002ee20 0x18002ee20 GLOBAL FUNC 0    ADVAPI32.dll CredMarshalCredentialA
1167 0x0002ee40 0x18002ee40 GLOBAL FUNC 0    ADVAPI32.dll CredMarshalCredentialW
1168 0x0002ee80 0x18002ee80 GLOBAL FUNC 0    ADVAPI32.dll CredProfileLoaded
1169 0x0002ee60 0x18002ee60 GLOBAL FUNC 0    ADVAPI32.dll CredProfileLoadedEx
1170 0x0002eea0 0x18002eea0 GLOBAL FUNC 0    ADVAPI32.dll CredProfileUnloaded
1171 0x0002eec0 0x18002eec0 GLOBAL FUNC 0    ADVAPI32.dll CredProtectA
1172 0x0002eee0 0x18002eee0 GLOBAL FUNC 0    ADVAPI32.dll CredProtectW
1173 0x0002ef00 0x18002ef00 GLOBAL FUNC 0    ADVAPI32.dll CredReadA
1174 0x0002ef20 0x18002ef20 GLOBAL FUNC 0    ADVAPI32.dll CredReadByTokenHandle
1175 0x0002ef40 0x18002ef40 GLOBAL FUNC 0    ADVAPI32.dll CredReadDomainCredentialsA
1176 0x0002ef60 0x18002ef60 GLOBAL FUNC 0    ADVAPI32.dll CredReadDomainCredentialsW
1177 0x0002ef80 0x18002ef80 GLOBAL FUNC 0    ADVAPI32.dll CredReadW
1178 0x00031370 0x180031370 GLOBAL FUNC 0    ADVAPI32.dll CredRenameA
1179 0x000313a0 0x1800313a0 GLOBAL FUNC 0    ADVAPI32.dll CredRenameW
1180 0x0002efa0 0x18002efa0 GLOBAL FUNC 0    ADVAPI32.dll CredRestoreCredentials
1181 0x0002efc0 0x18002efc0 GLOBAL FUNC 0    ADVAPI32.dll CredUnmarshalCredentialA
1182 0x0002efe0 0x18002efe0 GLOBAL FUNC 0    ADVAPI32.dll CredUnmarshalCredentialW
1183 0x0002f000 0x18002f000 GLOBAL FUNC 0    ADVAPI32.dll CredUnprotectA
1184 0x0002f020 0x18002f020 GLOBAL FUNC 0    ADVAPI32.dll CredUnprotectW
1185 0x0002f040 0x18002f040 GLOBAL FUNC 0    ADVAPI32.dll CredWriteA
1186 0x0002f060 0x18002f060 GLOBAL FUNC 0    ADVAPI32.dll CredWriteDomainCredentialsA
1187 0x0002f080 0x18002f080 GLOBAL FUNC 0    ADVAPI32.dll CredWriteDomainCredentialsW
1188 0x0002f0a0 0x18002f0a0 GLOBAL FUNC 0    ADVAPI32.dll CredWriteW
1189 0x0002f0c0 0x18002f0c0 GLOBAL FUNC 0    ADVAPI32.dll CredpConvertCredential
1190 0x0002f0e0 0x18002f0e0 GLOBAL FUNC 0    ADVAPI32.dll CredpConvertOneCredentialSize
1191 0x0002f100 0x18002f100 GLOBAL FUNC 0    ADVAPI32.dll CredpConvertTargetInfo
1192 0x0002f120 0x18002f120 GLOBAL FUNC 0    ADVAPI32.dll CredpDecodeCredential
1193 0x0002f140 0x18002f140 GLOBAL FUNC 0    ADVAPI32.dll CredpEncodeCredential
1194 0x0002f160 0x18002f160 GLOBAL FUNC 0    ADVAPI32.dll CredpEncodeSecret
1195 0x00008cf0 0x180008cf0 GLOBAL FUNC 0    ADVAPI32.dll CryptAcquireContextA
1196 0x00008550 0x180008550 GLOBAL FUNC 0    ADVAPI32.dll CryptAcquireContextW
1197 0x0002f180 0x18002f180 GLOBAL FUNC 0    ADVAPI32.dll CryptContextAddRef
1198 0x00007350 0x180007350 GLOBAL FUNC 0    ADVAPI32.dll CryptCreateHash
1199 0x0002f1a0 0x18002f1a0 GLOBAL FUNC 0    ADVAPI32.dll CryptDecrypt
1200 0x0002f1c0 0x18002f1c0 GLOBAL FUNC 0    ADVAPI32.dll CryptDeriveKey
1201 0x00008400 0x180008400 GLOBAL FUNC 0    ADVAPI32.dll CryptDestroyHash
1202 0x00008530 0x180008530 GLOBAL FUNC 0    ADVAPI32.dll CryptDestroyKey
1203 0x0002f1e0 0x18002f1e0 GLOBAL FUNC 0    ADVAPI32.dll CryptDuplicateHash
1204 0x0001ff60 0x18001ff60 GLOBAL FUNC 0    ADVAPI32.dll CryptDuplicateKey
1205 0x0002f200 0x18002f200 GLOBAL FUNC 0    ADVAPI32.dll CryptEncrypt
1206 0x0002f220 0x18002f220 GLOBAL FUNC 0    ADVAPI32.dll CryptEnumProviderTypesA
1207 0x0002f240 0x18002f240 GLOBAL FUNC 0    ADVAPI32.dll CryptEnumProviderTypesW
1208 0x0002f260 0x18002f260 GLOBAL FUNC 0    ADVAPI32.dll CryptEnumProvidersA
1209 0x0002f280 0x18002f280 GLOBAL FUNC 0    ADVAPI32.dll CryptEnumProvidersW
1210 0x00007390 0x180007390 GLOBAL FUNC 0    ADVAPI32.dll CryptExportKey
1211 0x0002f2a0 0x18002f2a0 GLOBAL FUNC 0    ADVAPI32.dll CryptGenKey
1212 0x00008ef0 0x180008ef0 GLOBAL FUNC 0    ADVAPI32.dll CryptGenRandom
1213 0x0002f2c0 0x18002f2c0 GLOBAL FUNC 0    ADVAPI32.dll CryptGetDefaultProviderA
1214 0x000084f0 0x1800084f0 GLOBAL FUNC 0    ADVAPI32.dll CryptGetDefaultProviderW
1215 0x00007160 0x180007160 GLOBAL FUNC 0    ADVAPI32.dll CryptGetHashParam
1216 0x0002f2e0 0x18002f2e0 GLOBAL FUNC 0    ADVAPI32.dll CryptGetKeyParam
1217 0x0001ff80 0x18001ff80 GLOBAL FUNC 0    ADVAPI32.dll CryptGetProvParam
1218 0x0002f300 0x18002f300 GLOBAL FUNC 0    ADVAPI32.dll CryptGetUserKey
1219 0x00008440 0x180008440 GLOBAL FUNC 0    ADVAPI32.dll CryptHashData
1220 0x0002f320 0x18002f320 GLOBAL FUNC 0    ADVAPI32.dll CryptHashSessionKey
1221 0x00007370 0x180007370 GLOBAL FUNC 0    ADVAPI32.dll CryptImportKey
1222 0x00008e00 0x180008e00 GLOBAL FUNC 0    ADVAPI32.dll CryptReleaseContext
1223 0x0002f340 0x18002f340 GLOBAL FUNC 0    ADVAPI32.dll CryptSetHashParam
1224 0x0002f360 0x18002f360 GLOBAL FUNC 0    ADVAPI32.dll CryptSetKeyParam
1225 0x0002f380 0x18002f380 GLOBAL FUNC 0    ADVAPI32.dll CryptSetProvParam
1226 0x0002f3a0 0x18002f3a0 GLOBAL FUNC 0    ADVAPI32.dll CryptSetProviderA
1227 0x0002f3c0 0x18002f3c0 GLOBAL FUNC 0    ADVAPI32.dll CryptSetProviderExA
1228 0x0002f3e0 0x18002f3e0 GLOBAL FUNC 0    ADVAPI32.dll CryptSetProviderExW
1229 0x0002f400 0x18002f400 GLOBAL FUNC 0    ADVAPI32.dll CryptSetProviderW
1230 0x0002f420 0x18002f420 GLOBAL FUNC 0    ADVAPI32.dll CryptSignHashA
1231 0x0001ffa0 0x18001ffa0 GLOBAL FUNC 0    ADVAPI32.dll CryptSignHashW
1232 0x0002f440 0x18002f440 GLOBAL FUNC 0    ADVAPI32.dll CryptVerifySignatureA
1233 0x00009380 0x180009380 GLOBAL FUNC 0    ADVAPI32.dll CryptVerifySignatureW
1234 0x000967c6 0x1800967c6 GLOBAL FUNC 0    ADVAPI32.dll CveEventWrite
1235 0x0002d4a0 0x18002d4a0 GLOBAL FUNC 0    ADVAPI32.dll DecryptFileA
1236 0x0002d570 0x18002d570 GLOBAL FUNC 0    ADVAPI32.dll DecryptFileW
1237 0x000085d0 0x1800085d0 GLOBAL FUNC 0    ADVAPI32.dll DeleteAce
1238 0x0002f460 0x18002f460 GLOBAL FUNC 0    ADVAPI32.dll DeleteService
1239 0x00005560 0x180005560 GLOBAL FUNC 0    ADVAPI32.dll DeregisterEventSource
1240 0x0002f480 0x18002f480 GLOBAL FUNC 0    ADVAPI32.dll DestroyPrivateObjectSecurity
1241 0x0002d600 0x18002d600 GLOBAL FUNC 0    ADVAPI32.dll DuplicateEncryptionInfoFile
1242 0x00008d50 0x180008d50 GLOBAL FUNC 0    ADVAPI32.dll DuplicateToken
1243 0x000072b0 0x1800072b0 GLOBAL FUNC 0    ADVAPI32.dll DuplicateTokenEx
1244 0x000525d0 0x1800525d0 GLOBAL FUNC 0    ADVAPI32.dll ElfBackupEventLogFileA
1245 0x000526b0 0x1800526b0 GLOBAL FUNC 0    ADVAPI32.dll ElfBackupEventLogFileW
1246 0x00052790 0x180052790 GLOBAL FUNC 0    ADVAPI32.dll ElfChangeNotify
1247 0x00052880 0x180052880 GLOBAL FUNC 0    ADVAPI32.dll ElfClearEventLogFileA
1248 0x00052950 0x180052950 GLOBAL FUNC 0    ADVAPI32.dll ElfClearEventLogFileW
1249 0x000050e0 0x1800050e0 GLOBAL FUNC 0    ADVAPI32.dll ElfCloseEventLog
1250 0x00005590 0x180005590 GLOBAL FUNC 0    ADVAPI32.dll ElfDeregisterEventSource
1251 0x00052a10 0x180052a10 GLOBAL FUNC 0    ADVAPI32.dll ElfFlushEventLog
1252 0x00052a20 0x180052a20 GLOBAL FUNC 0    ADVAPI32.dll ElfNumberOfRecords
1253 0x00052af0 0x180052af0 GLOBAL FUNC 0    ADVAPI32.dll ElfOldestRecord
1254 0x00052bc0 0x180052bc0 GLOBAL FUNC 0    ADVAPI32.dll ElfOpenBackupEventLogA
1255 0x00052d30 0x180052d30 GLOBAL FUNC 0    ADVAPI32.dll ElfOpenBackupEventLogW
1256 0x00052ea0 0x180052ea0 GLOBAL FUNC 0    ADVAPI32.dll ElfOpenEventLogA
1257 0x00005e10 0x180005e10 GLOBAL FUNC 0    ADVAPI32.dll ElfOpenEventLogW
1258 0x000204e0 0x1800204e0 GLOBAL FUNC 0    ADVAPI32.dll ElfReadEventLogA
1259 0x000530c0 0x1800530c0 GLOBAL FUNC 0    ADVAPI32.dll ElfReadEventLogW
1260 0x000047c0 0x1800047c0 GLOBAL FUNC 0    ADVAPI32.dll ElfRegisterEventSourceA
1261 0x000051f0 0x1800051f0 GLOBAL FUNC 0    ADVAPI32.dll ElfRegisterEventSourceW
1262 0x00053480 0x180053480 GLOBAL FUNC 0    ADVAPI32.dll ElfReportEventA
1263 0x000538e0 0x1800538e0 GLOBAL FUNC 0    ADVAPI32.dll ElfReportEventAndSourceW
1264 0x00005890 0x180005890 GLOBAL FUNC 0    ADVAPI32.dll ElfReportEventW
1265 0x000075c0 0x1800075c0 GLOBAL FUNC 0    ADVAPI32.dll EnableTrace
1266 0x000437b0 0x1800437b0 GLOBAL FUNC 0    ADVAPI32.dll EnableTraceEx
1267 0x00008480 0x180008480 GLOBAL FUNC 0    ADVAPI32.dll EnableTraceEx2
1268 0x0002d6b0 0x18002d6b0 GLOBAL FUNC 0    ADVAPI32.dll EncryptFileA
1269 0x0002d770 0x18002d770 GLOBAL FUNC 0    ADVAPI32.dll EncryptFileW
1270 0x0002d800 0x18002d800 GLOBAL FUNC 0    ADVAPI32.dll EncryptedFileKeyInfo
1271 0x0002d890 0x18002d890 GLOBAL FUNC 0    ADVAPI32.dll EncryptionDisable
1272 0x00046c60 0x180046c60 GLOBAL FUNC 0    ADVAPI32.dll EnumDependentServicesA
1273 0x0002f4a0 0x18002f4a0 GLOBAL FUNC 0    ADVAPI32.dll EnumDependentServicesW
1274 0x0002f4c0 0x18002f4c0 GLOBAL FUNC 0    ADVAPI32.dll EnumDynamicTimeZoneInformation
1275 0x00046e20 0x180046e20 GLOBAL FUNC 0    ADVAPI32.dll EnumServiceGroupW
1276 0x000470f0 0x1800470f0 GLOBAL FUNC 0    ADVAPI32.dll EnumServicesStatusA
1277 0x00009740 0x180009740 GLOBAL FUNC 0    ADVAPI32.dll EnumServicesStatusExA
1278 0x00003de0 0x180003de0 GLOBAL FUNC 0    ADVAPI32.dll EnumServicesStatusExW
1279 0x00047340 0x180047340 GLOBAL FUNC 0    ADVAPI32.dll EnumServicesStatusW
1280 0x00006200 0x180006200 GLOBAL FUNC 0    ADVAPI32.dll EnumerateTraceGuids
1281 0x0001ab70 0x18001ab70 GLOBAL FUNC 0    ADVAPI32.dll EnumerateTraceGuidsEx
1282 0x0002f4e0 0x18002f4e0 GLOBAL FUNC 0    ADVAPI32.dll EqualDomainSid
1283 0x0002f500 0x18002f500 GLOBAL FUNC 0    ADVAPI32.dll EqualPrefixSid
1284 0x00008e90 0x180008e90 GLOBAL FUNC 0    ADVAPI32.dll EqualSid
1285 0x0002f520 0x18002f520 GLOBAL FUNC 0    ADVAPI32.dll EventAccessControl
1286 0x0002f540 0x18002f540 GLOBAL FUNC 0    ADVAPI32.dll EventAccessQuery
1287 0x0002f560 0x18002f560 GLOBAL FUNC 0    ADVAPI32.dll EventAccessRemove
1288 0x00096bde 0x180096bde GLOBAL FUNC 0    ADVAPI32.dll EventActivityIdControl
1289 0x00096c0b 0x180096c0b GLOBAL FUNC 0    ADVAPI32.dll EventEnabled
1290 0x00096c36 0x180096c36 GLOBAL FUNC 0    ADVAPI32.dll EventProviderEnabled
1291 0x00096c62 0x180096c62 GLOBAL FUNC 0    ADVAPI32.dll EventRegister
1292 0x00096c8d 0x180096c8d GLOBAL FUNC 0    ADVAPI32.dll EventSetInformation
1293 0x00096cba 0x180096cba GLOBAL FUNC 0    ADVAPI32.dll EventUnregister
1294 0x00096cde 0x180096cde GLOBAL FUNC 0    ADVAPI32.dll EventWrite
1295 0x00096d08 0x180096d08 GLOBAL FUNC 0    ADVAPI32.dll EventWriteEndScenario
1296 0x00096d34 0x180096d34 GLOBAL FUNC 0    ADVAPI32.dll EventWriteEx
1297 0x00096d62 0x180096d62 GLOBAL FUNC 0    ADVAPI32.dll EventWriteStartScenario
1298 0x00096d94 0x180096d94 GLOBAL FUNC 0    ADVAPI32.dll EventWriteString
1299 0x00096dc1 0x180096dc1 GLOBAL FUNC 0    ADVAPI32.dll EventWriteTransfer
1300 0x0002d8f0 0x18002d8f0 GLOBAL FUNC 0    ADVAPI32.dll FileEncryptionStatusA
1301 0x0002d9c0 0x18002d9c0 GLOBAL FUNC 0    ADVAPI32.dll FileEncryptionStatusW
1302 0x0002f580 0x18002f580 GLOBAL FUNC 0    ADVAPI32.dll FindFirstFreeAce
1303 0x0002da20 0x18002da20 GLOBAL FUNC 0    ADVAPI32.dll FlushEfsCache
1304 0x00043890 0x180043890 GLOBAL FUNC 0    ADVAPI32.dll FlushTraceA
1305 0x00020080 0x180020080 GLOBAL FUNC 0    ADVAPI32.dll FlushTraceW
1306 0x0002db00 0x18002db00 GLOBAL FUNC 0    ADVAPI32.dll FreeEncryptedFileKeyInfo
1307 0x0002db40 0x18002db40 GLOBAL FUNC 0    ADVAPI32.dll FreeEncryptedFileMetadata
1308 0x0002db50 0x18002db50 GLOBAL FUNC 0    ADVAPI32.dll FreeEncryptionCertificateHashList
1309 0x0003e1e0 0x18003e1e0 GLOBAL FUNC 0    ADVAPI32.dll FreeInheritedFromArray
1310 0x00008420 0x180008420 GLOBAL FUNC 0    ADVAPI32.dll FreeSid
1311 0x0003fe20 0x18003fe20 GLOBAL FUNC 0    ADVAPI32.dll GetAccessPermissionsForObjectA
1312 0x00040180 0x180040180 GLOBAL FUNC 0    ADVAPI32.dll GetAccessPermissionsForObjectW
1313 0x00008d30 0x180008d30 GLOBAL FUNC 0    ADVAPI32.dll GetAce
1314 0x00008f50 0x180008f50 GLOBAL FUNC 0    ADVAPI32.dll GetAclInformation
1315 0x0003e240 0x18003e240 GLOBAL FUNC 0    ADVAPI32.dll GetAuditedPermissionsFromAclA
1316 0x0003e2c0 0x18003e2c0 GLOBAL FUNC 0    ADVAPI32.dll GetAuditedPermissionsFromAclW
1317 0x0002d0e0 0x18002d0e0 GLOBAL FUNC 0    ADVAPI32.dll GetCurrentHwProfileA
1318 0x00008920 0x180008920 GLOBAL FUNC 0    ADVAPI32.dll GetCurrentHwProfileW
1319 0x0002f5a0 0x18002f5a0 GLOBAL FUNC 0    ADVAPI32.dll GetDynamicTimeZoneInformationEffectiveYears
1320 0x0003e370 0x18003e370 GLOBAL FUNC 0    ADVAPI32.dll GetEffectiveRightsFromAclA
1321 0x0003e3f0 0x18003e3f0 GLOBAL FUNC 0    ADVAPI32.dll GetEffectiveRightsFromAclW
1322 0x0002db90 0x18002db90 GLOBAL FUNC 0    ADVAPI32.dll GetEncryptedFileMetadata
1323 0x00004fb0 0x180004fb0 GLOBAL FUNC 0    ADVAPI32.dll GetEventLogInformation
1324 0x0003e4a0 0x18003e4a0 GLOBAL FUNC 0    ADVAPI32.dll GetExplicitEntriesFromAclA
1325 0x0002f5c0 0x18002f5c0 GLOBAL FUNC 0    ADVAPI32.dll GetExplicitEntriesFromAclW
1326 0x00048100 0x180048100 GLOBAL FUNC 0    ADVAPI32.dll GetFileSecurityA
1327 0x00009300 0x180009300 GLOBAL FUNC 0    ADVAPI32.dll GetFileSecurityW
1328 0x00037ba0 0x180037ba0 GLOBAL FUNC 0    ADVAPI32.dll GetInformationCodeAuthzLevelW
1329 0x0000ce80 0x18000ce80 GLOBAL FUNC 0    ADVAPI32.dll GetInformationCodeAuthzPolicyW
1330 0x0003e4c0 0x18003e4c0 GLOBAL FUNC 0    ADVAPI32.dll GetInheritanceSourceA
1331 0x0003e4d0 0x18003e4d0 GLOBAL FUNC 0    ADVAPI32.dll GetInheritanceSourceW
1332 0x000093e0 0x1800093e0 GLOBAL FUNC 0    ADVAPI32.dll GetKernelObjectSecurity
1333 0x00007330 0x180007330 GLOBAL FUNC 0    ADVAPI32.dll GetLengthSid
1334 0x00035670 0x180035670 GLOBAL FUNC 0    ADVAPI32.dll GetLocalManagedApplicationData
1335 0x000358e0 0x1800358e0 GLOBAL FUNC 0    ADVAPI32.dll GetLocalManagedApplications
1336 0x00035c00 0x180035c00 GLOBAL FUNC 0    ADVAPI32.dll GetManagedApplicationCategories
1337 0x00035c70 0x180035c70 GLOBAL FUNC 0    ADVAPI32.dll GetManagedApplications
1338 0x0003f2e0 0x18003f2e0 GLOBAL FUNC 0    ADVAPI32.dll GetMultipleTrusteeA
1339 0x0003f300 0x18003f300 GLOBAL FUNC 0    ADVAPI32.dll GetMultipleTrusteeOperationA
1340 0x0003f320 0x18003f320 GLOBAL FUNC 0    ADVAPI32.dll GetMultipleTrusteeOperationW
1341 0x0003f340 0x18003f340 GLOBAL FUNC 0    ADVAPI32.dll GetMultipleTrusteeW
1342 0x0003e5a0 0x18003e5a0 GLOBAL FUNC 0    ADVAPI32.dll GetNamedSecurityInfoA
1343 0x000402c0 0x1800402c0 GLOBAL FUNC 0    ADVAPI32.dll GetNamedSecurityInfoExA
1344 0x00040570 0x180040570 GLOBAL FUNC 0    ADVAPI32.dll GetNamedSecurityInfoExW
1345 0x00008d90 0x180008d90 GLOBAL FUNC 0    ADVAPI32.dll GetNamedSecurityInfoW
1346 0x00020280 0x180020280 GLOBAL FUNC 0    ADVAPI32.dll GetNumberOfEventLogRecords
1347 0x00051fb0 0x180051fb0 GLOBAL FUNC 0    ADVAPI32.dll GetOldestEventLogRecord
1348 0x000408b0 0x1800408b0 GLOBAL FUNC 0    ADVAPI32.dll GetOverlappedAccessResults
1349 0x0002f5e0 0x18002f5e0 GLOBAL FUNC 0    ADVAPI32.dll GetPrivateObjectSecurity
1350 0x0002f600 0x18002f600 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityDescriptorControl
1351 0x000086f0 0x1800086f0 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityDescriptorDacl
1352 0x0002f620 0x18002f620 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityDescriptorGroup
1353 0x0002f640 0x18002f640 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityDescriptorLength
1354 0x0001abd0 0x18001abd0 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityDescriptorOwner
1355 0x0002f660 0x18002f660 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityDescriptorRMControl
1356 0x00004c00 0x180004c00 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityDescriptorSacl
1357 0x00007740 0x180007740 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityInfo
1358 0x000409f0 0x1800409f0 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityInfoExA
1359 0x00040c70 0x180040c70 GLOBAL FUNC 0    ADVAPI32.dll GetSecurityInfoExW
1360 0x00047390 0x180047390 GLOBAL FUNC 0    ADVAPI32.dll GetServiceDisplayNameA
1361 0x0002f680 0x18002f680 GLOBAL FUNC 0    ADVAPI32.dll GetServiceDisplayNameW
1362 0x00047440 0x180047440 GLOBAL FUNC 0    ADVAPI32.dll GetServiceKeyNameA
1363 0x0001ffc0 0x18001ffc0 GLOBAL FUNC 0    ADVAPI32.dll GetServiceKeyNameW
1364 0x0002f6a0 0x18002f6a0 GLOBAL FUNC 0    ADVAPI32.dll GetSidIdentifierAuthority
1365 0x0001ffe0 0x18001ffe0 GLOBAL FUNC 0    ADVAPI32.dll GetSidLengthRequired
1366 0x00007440 0x180007440 GLOBAL FUNC 0    ADVAPI32.dll GetSidSubAuthority
1367 0x00007460 0x180007460 GLOBAL FUNC 0    ADVAPI32.dll GetSidSubAuthorityCount
1368 0x0004bfe0 0x18004bfe0 GLOBAL FUNC 0    ADVAPI32.dll GetStringConditionFromBinary
1369 0x00062990 0x180062990 GLOBAL FUNC 0    ADVAPI32.dll GetThreadWaitChain
1370 0x000068b0 0x1800068b0 GLOBAL FUNC 0    ADVAPI32.dll GetTokenInformation
1371 0x0009747e 0x18009747e GLOBAL FUNC 0    ADVAPI32.dll GetTraceEnableFlags
1372 0x000974af 0x1800974af GLOBAL FUNC 0    ADVAPI32.dll GetTraceEnableLevel
1373 0x000974e1 0x1800974e1 GLOBAL FUNC 0    ADVAPI32.dll GetTraceLoggerHandle
1374 0x0003f360 0x18003f360 GLOBAL FUNC 0    ADVAPI32.dll GetTrusteeFormA
1375 0x0003f380 0x18003f380 GLOBAL FUNC 0    ADVAPI32.dll GetTrusteeFormW
1376 0x0003f3a0 0x18003f3a0 GLOBAL FUNC 0    ADVAPI32.dll GetTrusteeNameA
1377 0x0003f3b0 0x18003f3b0 GLOBAL FUNC 0    ADVAPI32.dll GetTrusteeNameW
1378 0x0003f3c0 0x18003f3c0 GLOBAL FUNC 0    ADVAPI32.dll GetTrusteeTypeA
1379 0x0003f3e0 0x18003f3e0 GLOBAL FUNC 0    ADVAPI32.dll GetTrusteeTypeW
1380 0x00020170 0x180020170 GLOBAL FUNC 0    ADVAPI32.dll GetUserNameA
1381 0x000073b0 0x1800073b0 GLOBAL FUNC 0    ADVAPI32.dll GetUserNameW
1382 0x0002f6c0 0x18002f6c0 GLOBAL FUNC 0    ADVAPI32.dll GetWindowsAccountDomainSid
1383 0x000975aa 0x1800975aa GLOBAL FUNC 0    ADVAPI32.dll I_QueryTagInformation
1384 0x000975f8 0x1800975f8 GLOBAL FUNC 0    ADVAPI32.dll I_ScIsSecurityProcess
1385 0x00097646 0x180097646 GLOBAL FUNC 0    ADVAPI32.dll I_ScPnPGetServiceName
1386 0x00097695 0x180097695 GLOBAL FUNC 0    ADVAPI32.dll I_ScQueryServiceConfig
1387 0x000976ed 0x1800976ed GLOBAL FUNC 0    ADVAPI32.dll I_ScRegisterPreshutdownRestart
1388 0x0001cab0 0x18001cab0 GLOBAL FUNC 0    ADVAPI32.dll I_ScReparseServiceDatabase
1389 0x0009775c 0x18009775c GLOBAL FUNC 0    ADVAPI32.dll I_ScSendPnPMessage
1390 0x000977a3 0x1800977a3 GLOBAL FUNC 0    ADVAPI32.dll I_ScSendTSMessage
1391 0x0002f6e0 0x18002f6e0 GLOBAL FUNC 0    ADVAPI32.dll I_ScSetServiceBitsA
1392 0x0002f700 0x18002f700 GLOBAL FUNC 0    ADVAPI32.dll I_ScSetServiceBitsW
1393 0x00097816 0x180097816 GLOBAL FUNC 0    ADVAPI32.dll I_ScValidatePnPService
1394 0x00010970 0x180010970 GLOBAL FUNC 0    ADVAPI32.dll IdentifyCodeAuthzLevelW
1395 0x0002f720 0x18002f720 GLOBAL FUNC 0    ADVAPI32.dll ImpersonateAnonymousToken
1396 0x000095a0 0x1800095a0 GLOBAL FUNC 0    ADVAPI32.dll ImpersonateLoggedOnUser
1397 0x00020000 0x180020000 GLOBAL FUNC 0    ADVAPI32.dll ImpersonateNamedPipeClient
1398 0x000094e0 0x1800094e0 GLOBAL FUNC 0    ADVAPI32.dll ImpersonateSelf
1399 0x00008510 0x180008510 GLOBAL FUNC 0    ADVAPI32.dll InitializeAcl
1400 0x000084c0 0x1800084c0 GLOBAL FUNC 0    ADVAPI32.dll InitializeSecurityDescriptor
1401 0x00004bb0 0x180004bb0 GLOBAL FUNC 0    ADVAPI32.dll InitializeSid
1402 0x00043c40 0x180043c40 GLOBAL FUNC 0    ADVAPI32.dll InitiateShutdownA
1403 0x00019bc0 0x180019bc0 GLOBAL FUNC 0    ADVAPI32.dll InitiateShutdownW
1404 0x00043d80 0x180043d80 GLOBAL FUNC 0    ADVAPI32.dll InitiateSystemShutdownA
1405 0x00043ed0 0x180043ed0 GLOBAL FUNC 0    ADVAPI32.dll InitiateSystemShutdownExA
1406 0x000463f0 0x1800463f0 GLOBAL FUNC 0    ADVAPI32.dll InitiateSystemShutdownExW
1407 0x00044020 0x180044020 GLOBAL FUNC 0    ADVAPI32.dll InitiateSystemShutdownW
1408 0x00035c80 0x180035c80 GLOBAL FUNC 0    ADVAPI32.dll InstallApplication
1409 0x00006b10 0x180006b10 GLOBAL FUNC 0    ADVAPI32.dll IsTextUnicode
1410 0x0002f740 0x18002f740 GLOBAL FUNC 0    ADVAPI32.dll IsTokenRestricted
1411 0x000378c0 0x1800378c0 GLOBAL FUNC 0    ADVAPI32.dll IsTokenUntrusted
1412 0x0002f760 0x18002f760 GLOBAL FUNC 0    ADVAPI32.dll IsValidAcl
1413 0x000979f6 0x1800979f6 GLOBAL FUNC 0    ADVAPI32.dll IsValidRelativeSecurityDescriptor
1414 0x0002f780 0x18002f780 GLOBAL FUNC 0    ADVAPI32.dll IsValidSecurityDescriptor
1415 0x00007670 0x180007670 GLOBAL FUNC 0    ADVAPI32.dll IsValidSid
1416 0x0001c040 0x18001c040 GLOBAL FUNC 0    ADVAPI32.dll IsWellKnownSid
1417 0x000474f0 0x1800474f0 GLOBAL FUNC 0    ADVAPI32.dll LockServiceDatabase
1418 0x0004b730 0x18004b730 GLOBAL FUNC 0    ADVAPI32.dll LogonUserA
1419 0x0004ba10 0x18004ba10 GLOBAL FUNC 0    ADVAPI32.dll LogonUserExA
1420 0x0002f7a0 0x18002f7a0 GLOBAL FUNC 0    ADVAPI32.dll LogonUserExExW
1421 0x0004ba80 0x18004ba80 GLOBAL FUNC 0    ADVAPI32.dll LogonUserExW
1422 0x0004baf0 0x18004baf0 GLOBAL FUNC 0    ADVAPI32.dll LogonUserW
1423 0x000481e0 0x1800481e0 GLOBAL FUNC 0    ADVAPI32.dll LookupAccountNameA
1424 0x000074d0 0x1800074d0 GLOBAL FUNC 0    ADVAPI32.dll LookupAccountNameW
1425 0x00048740 0x180048740 GLOBAL FUNC 0    ADVAPI32.dll LookupAccountSidA
1426 0x00007090 0x180007090 GLOBAL FUNC 0    ADVAPI32.dll LookupAccountSidW
1427 0x00048e10 0x180048e10 GLOBAL FUNC 0    ADVAPI32.dll LookupPrivilegeDisplayNameA
1428 0x00049020 0x180049020 GLOBAL FUNC 0    ADVAPI32.dll LookupPrivilegeDisplayNameW
1429 0x000491d0 0x1800491d0 GLOBAL FUNC 0    ADVAPI32.dll LookupPrivilegeNameA
1430 0x00049390 0x180049390 GLOBAL FUNC 0    ADVAPI32.dll LookupPrivilegeNameW
1431 0x0001a9d0 0x18001a9d0 GLOBAL FUNC 0    ADVAPI32.dll LookupPrivilegeValueA
1432 0x0000f920 0x18000f920 GLOBAL FUNC 0    ADVAPI32.dll LookupPrivilegeValueW
1433 0x0003e650 0x18003e650 GLOBAL FUNC 0    ADVAPI32.dll LookupSecurityDescriptorPartsA
1434 0x0003e950 0x18003e950 GLOBAL FUNC 0    ADVAPI32.dll LookupSecurityDescriptorPartsW
1435 0x0002f820 0x18002f820 GLOBAL FUNC 0    ADVAPI32.dll LsaAddAccountRights
1436 0x000313d0 0x1800313d0 GLOBAL FUNC 0    ADVAPI32.dll LsaAddPrivilegesToAccount
1437 0x00031460 0x180031460 GLOBAL FUNC 0    ADVAPI32.dll LsaClearAuditLog
1438 0x00009460 0x180009460 GLOBAL FUNC 0    ADVAPI32.dll LsaClose
1439 0x000314f0 0x1800314f0 GLOBAL FUNC 0    ADVAPI32.dll LsaConfigureAutoLogonCredentials
1440 0x00031570 0x180031570 GLOBAL FUNC 0    ADVAPI32.dll LsaCreateAccount
1441 0x0002f830 0x18002f830 GLOBAL FUNC 0    ADVAPI32.dll LsaCreateSecret
1442 0x00031680 0x180031680 GLOBAL FUNC 0    ADVAPI32.dll LsaCreateTrustedDomain
1443 0x00033880 0x180033880 GLOBAL FUNC 0    ADVAPI32.dll LsaCreateTrustedDomainEx
1444 0x0002f840 0x18002f840 GLOBAL FUNC 0    ADVAPI32.dll LsaDelete
1445 0x00033a60 0x180033a60 GLOBAL FUNC 0    ADVAPI32.dll LsaDeleteTrustedDomain
1446 0x00031790 0x180031790 GLOBAL FUNC 0    ADVAPI32.dll LsaDisablePasswordLessCurrentUser
1447 0x00031810 0x180031810 GLOBAL FUNC 0    ADVAPI32.dll LsaDisableUserArso
1448 0x00031890 0x180031890 GLOBAL FUNC 0    ADVAPI32.dll LsaEnablePasswordLessCurrentUser
1449 0x00031910 0x180031910 GLOBAL FUNC 0    ADVAPI32.dll LsaEnableUserArso
1450 0x0002f850 0x18002f850 GLOBAL FUNC 0    ADVAPI32.dll LsaEnumerateAccountRights
1451 0x00031990 0x180031990 GLOBAL FUNC 0    ADVAPI32.dll LsaEnumerateAccounts
1452 0x0002f860 0x18002f860 GLOBAL FUNC 0    ADVAPI32.dll LsaEnumerateAccountsWithUserRight
1453 0x00031a70 0x180031a70 GLOBAL FUNC 0    ADVAPI32.dll LsaEnumeratePrivileges
1454 0x00031b50 0x180031b50 GLOBAL FUNC 0    ADVAPI32.dll LsaEnumeratePrivilegesOfAccount
1455 0x00031be0 0x180031be0 GLOBAL FUNC 0    ADVAPI32.dll LsaEnumerateTrustedDomains
1456 0x00033af0 0x180033af0 GLOBAL FUNC 0    ADVAPI32.dll LsaEnumerateTrustedDomainsEx
1457 0x000093a0 0x1800093a0 GLOBAL FUNC 0    ADVAPI32.dll LsaFreeMemory
1458 0x00031cd0 0x180031cd0 GLOBAL FUNC 0    ADVAPI32.dll LsaGetAppliedCAPIDs
1459 0x00034a50 0x180034a50 GLOBAL FUNC 0    ADVAPI32.dll LsaGetDeviceRegistrationInfo
1460 0x00031e50 0x180031e50 GLOBAL FUNC 0    ADVAPI32.dll LsaGetQuotasForAccount
1461 0x00031ee0 0x180031ee0 GLOBAL FUNC 0    ADVAPI32.dll LsaGetRemoteUserName
1462 0x000320e0 0x1800320e0 GLOBAL FUNC 0    ADVAPI32.dll LsaGetSystemAccessAccount
1463 0x0000d870 0x18000d870 GLOBAL FUNC 0    ADVAPI32.dll LsaGetUserName
1464 0x0002f870 0x18002f870 GLOBAL FUNC 0    ADVAPI32.dll LsaICLookupNames
1465 0x0002f8d0 0x18002f8d0 GLOBAL FUNC 0    ADVAPI32.dll LsaICLookupNamesWithCreds
1466 0x0002f950 0x18002f950 GLOBAL FUNC 0    ADVAPI32.dll LsaICLookupSids
1467 0x0002f960 0x18002f960 GLOBAL FUNC 0    ADVAPI32.dll LsaICLookupSidsWithCreds
1468 0x0001d620 0x18001d620 GLOBAL FUNC 0    ADVAPI32.dll LsaInvokeTrustScanner
1469 0x00032170 0x180032170 GLOBAL FUNC 0    ADVAPI32.dll LsaIsUserArsoAllowed
1470 0x00032200 0x180032200 GLOBAL FUNC 0    ADVAPI32.dll LsaIsUserArsoEnabled
1471 0x00032290 0x180032290 GLOBAL FUNC 0    ADVAPI32.dll LsaLookupNames
1472 0x0002f9e0 0x18002f9e0 GLOBAL FUNC 0    ADVAPI32.dll LsaLookupNames2
1473 0x00032420 0x180032420 GLOBAL FUNC 0    ADVAPI32.dll LsaLookupPrivilegeDisplayName
1474 0x00032730 0x180032730 GLOBAL FUNC 0    ADVAPI32.dll LsaLookupPrivilegeName
1475 0x0000fa50 0x18000fa50 GLOBAL FUNC 0    ADVAPI32.dll LsaLookupPrivilegeValue
1476 0x0002fa00 0x18002fa00 GLOBAL FUNC 0    ADVAPI32.dll LsaLookupSids
1477 0x0002f9f0 0x18002f9f0 GLOBAL FUNC 0    ADVAPI32.dll LsaLookupSids2
1478 0x00033be0 0x180033be0 GLOBAL FUNC 0    ADVAPI32.dll LsaManageSidNameMapping
1479 0x000069c0 0x1800069c0 GLOBAL FUNC 0    ADVAPI32.dll LsaNtStatusToWinError
1480 0x00032800 0x180032800 GLOBAL FUNC 0    ADVAPI32.dll LsaOpenAccount
1481 0x00009470 0x180009470 GLOBAL FUNC 0    ADVAPI32.dll LsaOpenPolicy
1482 0x00032910 0x180032910 GLOBAL FUNC 0    ADVAPI32.dll LsaOpenPolicySce
1483 0x0002fa30 0x18002fa30 GLOBAL FUNC 0    ADVAPI32.dll LsaOpenSecret
1484 0x00032a20 0x180032a20 GLOBAL FUNC 0    ADVAPI32.dll LsaOpenTrustedDomain
1485 0x00033d40 0x180033d40 GLOBAL FUNC 0    ADVAPI32.dll LsaOpenTrustedDomainByName
1486 0x00032b30 0x180032b30 GLOBAL FUNC 0    ADVAPI32.dll LsaProfileDeleted
1487 0x00032bb0 0x180032bb0 GLOBAL FUNC 0    ADVAPI32.dll LsaQueryCAPs
1488 0x00033e50 0x180033e50 GLOBAL FUNC 0    ADVAPI32.dll LsaQueryDomainInformationPolicy
1489 0x00033f00 0x180033f00 GLOBAL FUNC 0    ADVAPI32.dll LsaQueryForestTrustInformation
1490 0x0001d6b0 0x18001d6b0 GLOBAL FUNC 0    ADVAPI32.dll LsaQueryForestTrustInformation2
1491 0x00032d30 0x180032d30 GLOBAL FUNC 0    ADVAPI32.dll LsaQueryInfoTrustedDomain
1492 0x0000bc20 0x18000bc20 GLOBAL FUNC 0    ADVAPI32.dll LsaQueryInformationPolicy
1493 0x0002fa40 0x18002fa40 GLOBAL FUNC 0    ADVAPI32.dll LsaQuerySecret
1494 0x00032e10 0x180032e10 GLOBAL FUNC 0    ADVAPI32.dll LsaQuerySecurityObject
1495 0x00033fb0 0x180033fb0 GLOBAL FUNC 0    ADVAPI32.dll LsaQueryTrustedDomainInfo
1496 0x000340b0 0x1800340b0 GLOBAL FUNC 0    ADVAPI32.dll LsaQueryTrustedDomainInfoByName
1497 0x0002fa50 0x18002fa50 GLOBAL FUNC 0    ADVAPI32.dll LsaRemoveAccountRights
1498 0x00032ee0 0x180032ee0 GLOBAL FUNC 0    ADVAPI32.dll LsaRemovePrivilegesFromAccount
1499 0x0002fa60 0x18002fa60 GLOBAL FUNC 0    ADVAPI32.dll LsaRetrievePrivateData
1500 0x00032f80 0x180032f80 GLOBAL FUNC 0    ADVAPI32.dll LsaSetCAPs
1501 0x00034170 0x180034170 GLOBAL FUNC 0    ADVAPI32.dll LsaSetDomainInformationPolicy
1502 0x00034220 0x180034220 GLOBAL FUNC 0    ADVAPI32.dll LsaSetForestTrustInformation
1503 0x0001d770 0x18001d770 GLOBAL FUNC 0    ADVAPI32.dll LsaSetForestTrustInformation2
1504 0x0002fa70 0x18002fa70 GLOBAL FUNC 0    ADVAPI32.dll LsaSetInformationPolicy
1505 0x000330d0 0x1800330d0 GLOBAL FUNC 0    ADVAPI32.dll LsaSetInformationTrustedDomain
1506 0x000334a0 0x1800334a0 GLOBAL FUNC 0    ADVAPI32.dll LsaSetQuotasForAccount
1507 0x0002fa80 0x18002fa80 GLOBAL FUNC 0    ADVAPI32.dll LsaSetSecret
1508 0x00033530 0x180033530 GLOBAL FUNC 0    ADVAPI32.dll LsaSetSecurityObject
1509 0x00033690 0x180033690 GLOBAL FUNC 0    ADVAPI32.dll LsaSetSystemAccessAccount
1510 0x000342f0 0x1800342f0 GLOBAL FUNC 0    ADVAPI32.dll LsaSetTrustedDomainInfoByName
1511 0x000346e0 0x1800346e0 GLOBAL FUNC 0    ADVAPI32.dll LsaSetTrustedDomainInformation
1512 0x0002fb00 0x18002fb00 GLOBAL FUNC 0    ADVAPI32.dll LsaStorePrivateData
1513 0x00033720 0x180033720 GLOBAL FUNC 0    ADVAPI32.dll LsaValidateProcUniqueLuid
1514 0x000982cf 0x1800982cf GLOBAL FUNC 0    ADVAPI32.dll MD4Final
1515 0x000982e6 0x1800982e6 GLOBAL FUNC 0    ADVAPI32.dll MD4Init
1516 0x000982fe 0x1800982fe GLOBAL FUNC 0    ADVAPI32.dll MD4Update
1517 0x00098317 0x180098317 GLOBAL FUNC 0    ADVAPI32.dll MD5Final
1518 0x0009832e 0x18009832e GLOBAL FUNC 0    ADVAPI32.dll MD5Init
1519 0x00098346 0x180098346 GLOBAL FUNC 0    ADVAPI32.dll MD5Update
1520 0x00009040 0x180009040 GLOBAL FUNC 0    ADVAPI32.dll MIDL_user_free_Ext
1521 0x00030280 0x180030280 GLOBAL FUNC 0    ADVAPI32.dll MSChapSrvChangePassword
1522 0x000305b0 0x1800305b0 GLOBAL FUNC 0    ADVAPI32.dll MSChapSrvChangePassword2
1523 0x0001be60 0x18001be60 GLOBAL FUNC 0    ADVAPI32.dll MakeAbsoluteSD
1524 0x0002fb10 0x18002fb10 GLOBAL FUNC 0    ADVAPI32.dll MakeAbsoluteSD2
1525 0x0002fb30 0x18002fb30 GLOBAL FUNC 0    ADVAPI32.dll MakeSelfRelativeSD
1526 0x0002fb50 0x18002fb50 GLOBAL FUNC 0    ADVAPI32.dll MapGenericMask
1527 0x0001a970 0x18001a970 GLOBAL FUNC 0    ADVAPI32.dll NotifyBootConfigStatus
1528 0x00052040 0x180052040 GLOBAL FUNC 0    ADVAPI32.dll NotifyChangeEventLog
1529 0x0001ca90 0x18001ca90 GLOBAL FUNC 0    ADVAPI32.dll NotifyServiceStatusChange
1530 0x0002fb70 0x18002fb70 GLOBAL FUNC 0    ADVAPI32.dll NotifyServiceStatusChangeA
1531 0x0001c020 0x18001c020 GLOBAL FUNC 0    ADVAPI32.dll NotifyServiceStatusChangeW
1532 0x0004bb40 0x18004bb40 GLOBAL FUNC 0    ADVAPI32.dll NpGetUserName
1533 0x00049510 0x180049510 GLOBAL FUNC 0    ADVAPI32.dll ObjectCloseAuditAlarmA
1534 0x0002fb90 0x18002fb90 GLOBAL FUNC 0    ADVAPI32.dll ObjectCloseAuditAlarmW
1535 0x000495c0 0x1800495c0 GLOBAL FUNC 0    ADVAPI32.dll ObjectDeleteAuditAlarmA
1536 0x0002fbb0 0x18002fbb0 GLOBAL FUNC 0    ADVAPI32.dll ObjectDeleteAuditAlarmW
1537 0x00049670 0x180049670 GLOBAL FUNC 0    ADVAPI32.dll ObjectOpenAuditAlarmA
1538 0x0002fbd0 0x18002fbd0 GLOBAL FUNC 0    ADVAPI32.dll ObjectOpenAuditAlarmW
1539 0x00049830 0x180049830 GLOBAL FUNC 0    ADVAPI32.dll ObjectPrivilegeAuditAlarmA
1540 0x0002fc50 0x18002fc50 GLOBAL FUNC 0    ADVAPI32.dll ObjectPrivilegeAuditAlarmW
1541 0x00052080 0x180052080 GLOBAL FUNC 0    ADVAPI32.dll OpenBackupEventLogA
1542 0x000521a0 0x1800521a0 GLOBAL FUNC 0    ADVAPI32.dll OpenBackupEventLogW
1543 0x0002dce0 0x18002dce0 GLOBAL FUNC 0    ADVAPI32.dll OpenEncryptedFileRawA
1544 0x0002dda0 0x18002dda0 GLOBAL FUNC 0    ADVAPI32.dll OpenEncryptedFileRawW
1545 0x000202d0 0x1800202d0 GLOBAL FUNC 0    ADVAPI32.dll OpenEventLogA
1546 0x00004f40 0x180004f40 GLOBAL FUNC 0    ADVAPI32.dll OpenEventLogW
1547 0x00006eb0 0x180006eb0 GLOBAL FUNC 0    ADVAPI32.dll OpenProcessToken
1548 0x00009580 0x180009580 GLOBAL FUNC 0    ADVAPI32.dll OpenSCManagerA
1549 0x00008ed0 0x180008ed0 GLOBAL FUNC 0    ADVAPI32.dll OpenSCManagerW
1550 0x0002fc70 0x18002fc70 GLOBAL FUNC 0    ADVAPI32.dll OpenServiceA
1551 0x000091a0 0x1800091a0 GLOBAL FUNC 0    ADVAPI32.dll OpenServiceW
1552 0x00006ed0 0x180006ed0 GLOBAL FUNC 0    ADVAPI32.dll OpenThreadToken
1553 0x00062b80 0x180062b80 GLOBAL FUNC 0    ADVAPI32.dll OpenThreadWaitChainSession
1554 0x00043a30 0x180043a30 GLOBAL FUNC 0    ADVAPI32.dll OpenTraceA
1555 0x000092c0 0x1800092c0 GLOBAL FUNC 0    ADVAPI32.dll OpenTraceW
1556 0x00004440 0x180004440 GLOBAL FUNC 0    ADVAPI32.dll OperationEnd
1557 0x00004510 0x180004510 GLOBAL FUNC 0    ADVAPI32.dll OperationStart
1558 0x00001010 0x180001010 GLOBAL FUNC 0    ADVAPI32.dll PerfAddCounters
1559 0x000200b0 0x1800200b0 GLOBAL FUNC 0    ADVAPI32.dll PerfCloseQueryHandle
1560 0x00098673 0x180098673 GLOBAL FUNC 0    ADVAPI32.dll PerfCreateInstance
1561 0x000986c9 0x1800986c9 GLOBAL FUNC 0    ADVAPI32.dll PerfDecrementULongCounterValue
1562 0x0009872f 0x18009872f GLOBAL FUNC 0    ADVAPI32.dll PerfDecrementULongLongCounterValue
1563 0x000444f0 0x1800444f0 GLOBAL FUNC 0    ADVAPI32.dll PerfDeleteCounters
1564 0x0009879c 0x18009879c GLOBAL FUNC 0    ADVAPI32.dll PerfDeleteInstance
1565 0x00002da0 0x180002da0 GLOBAL FUNC 0    ADVAPI32.dll PerfEnumerateCounterSet
1566 0x00002fa0 0x180002fa0 GLOBAL FUNC 0    ADVAPI32.dll PerfEnumerateCounterSetInstances
1567 0x0009882b 0x18009882b GLOBAL FUNC 0    ADVAPI32.dll PerfIncrementULongCounterValue
1568 0x00098891 0x180098891 GLOBAL FUNC 0    ADVAPI32.dll PerfIncrementULongLongCounterValue
1569 0x00002bd0 0x180002bd0 GLOBAL FUNC 0    ADVAPI32.dll PerfOpenQueryHandle
1570 0x000017a0 0x1800017a0 GLOBAL FUNC 0    ADVAPI32.dll PerfQueryCounterData
1571 0x000010e0 0x1800010e0 GLOBAL FUNC 0    ADVAPI32.dll PerfQueryCounterInfo
1572 0x00003360 0x180003360 GLOBAL FUNC 0    ADVAPI32.dll PerfQueryCounterSetRegistrationInfo
1573 0x0009894c 0x18009894c GLOBAL FUNC 0    ADVAPI32.dll PerfQueryInstance
1574 0x000183a0 0x1800183a0 GLOBAL FUNC 0    ADVAPI32.dll PerfRegCloseKey
1575 0x00053bc0 0x180053bc0 GLOBAL FUNC 0    ADVAPI32.dll PerfRegEnumKey
1576 0x00053c20 0x180053c20 GLOBAL FUNC 0    ADVAPI32.dll PerfRegEnumValue
1577 0x00019490 0x180019490 GLOBAL FUNC 0    ADVAPI32.dll PerfRegQueryInfoKey
1578 0x00017a00 0x180017a00 GLOBAL FUNC 0    ADVAPI32.dll PerfRegQueryValue
1579 0x00053dc0 0x180053dc0 GLOBAL FUNC 0    ADVAPI32.dll PerfRegSetValue
1580 0x000989ff 0x1800989ff GLOBAL FUNC 0    ADVAPI32.dll PerfSetCounterRefValue
1581 0x00098a50 0x180098a50 GLOBAL FUNC 0    ADVAPI32.dll PerfSetCounterSetInfo
1582 0x00098aa3 0x180098aa3 GLOBAL FUNC 0    ADVAPI32.dll PerfSetULongCounterValue
1583 0x00098afd 0x180098afd GLOBAL FUNC 0    ADVAPI32.dll PerfSetULongLongCounterValue
1584 0x00098b50 0x180098b50 GLOBAL FUNC 0    ADVAPI32.dll PerfStartProvider
1585 0x00098b9a 0x180098b9a GLOBAL FUNC 0    ADVAPI32.dll PerfStartProviderEx
1586 0x00098be3 0x180098be3 GLOBAL FUNC 0    ADVAPI32.dll PerfStopProvider
1587 0x00020020 0x180020020 GLOBAL FUNC 0    ADVAPI32.dll PrivilegeCheck
1588 0x00049900 0x180049900 GLOBAL FUNC 0    ADVAPI32.dll PrivilegedServiceAuditAlarmA
1589 0x0002fc90 0x18002fc90 GLOBAL FUNC 0    ADVAPI32.dll PrivilegedServiceAuditAlarmW
1590 0x00030a10 0x180030a10 GLOBAL FUNC 0    ADVAPI32.dll ProcessIdleTasks
1591 0x00030aa0 0x180030aa0 GLOBAL FUNC 0    ADVAPI32.dll ProcessIdleTasksW
1592 0x00009340 0x180009340 GLOBAL FUNC 0    ADVAPI32.dll ProcessTrace
1593 0x0001c910 0x18001c910 GLOBAL FUNC 0    ADVAPI32.dll QueryAllTracesA
1594 0x00009500 0x180009500 GLOBAL FUNC 0    ADVAPI32.dll QueryAllTracesW
1595 0x0001cac0 0x18001cac0 GLOBAL FUNC 0    ADVAPI32.dll QueryLocalUserServiceName
1596 0x0002de20 0x18002de20 GLOBAL FUNC 0    ADVAPI32.dll QueryRecoveryAgentsOnEncryptedFile
1597 0x0002fcb0 0x18002fcb0 GLOBAL FUNC 0    ADVAPI32.dll QuerySecurityAccessMask
1598 0x0002fcd0 0x18002fcd0 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceConfig2A
1599 0x0001bfc0 0x18001bfc0 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceConfig2W
1600 0x0002fcf0 0x18002fcf0 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceConfigA
1601 0x000093c0 0x1800093c0 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceConfigW
1602 0x0002fd10 0x18002fd10 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceDynamicInformation
1603 0x00047590 0x180047590 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceLockStatusA
1604 0x00047720 0x180047720 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceLockStatusW
1605 0x0002fd30 0x18002fd30 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceObjectSecurity
1606 0x000094c0 0x1800094c0 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceStatus
1607 0x00008f30 0x180008f30 GLOBAL FUNC 0    ADVAPI32.dll QueryServiceStatusEx
1608 0x000438b0 0x1800438b0 GLOBAL FUNC 0    ADVAPI32.dll QueryTraceA
1609 0x0002fd50 0x18002fd50 GLOBAL FUNC 0    ADVAPI32.dll QueryTraceProcessingHandle
1610 0x000200a0 0x1800200a0 GLOBAL FUNC 0    ADVAPI32.dll QueryTraceW
1611 0x0001cad0 0x18001cad0 GLOBAL FUNC 0    ADVAPI32.dll QueryUserServiceName
1612 0x0001cae0 0x18001cae0 GLOBAL FUNC 0    ADVAPI32.dll QueryUserServiceNameForContext
1613 0x0002dea0 0x18002dea0 GLOBAL FUNC 0    ADVAPI32.dll QueryUsersOnEncryptedFile
1614 0x0002df20 0x18002df20 GLOBAL FUNC 0    ADVAPI32.dll ReadEncryptedFileRaw
1615 0x00052290 0x180052290 GLOBAL FUNC 0    ADVAPI32.dll ReadEventLogA
1616 0x00020360 0x180020360 GLOBAL FUNC 0    ADVAPI32.dll ReadEventLogW
1617 0x00006af0 0x180006af0 GLOBAL FUNC 0    ADVAPI32.dll RegCloseKey
1618 0x00044a10 0x180044a10 GLOBAL FUNC 0    ADVAPI32.dll RegConnectRegistryA
1619 0x00044a30 0x180044a30 GLOBAL FUNC 0    ADVAPI32.dll RegConnectRegistryExA
1620 0x00044ad0 0x180044ad0 GLOBAL FUNC 0    ADVAPI32.dll RegConnectRegistryExW
1621 0x00046540 0x180046540 GLOBAL FUNC 0    ADVAPI32.dll RegConnectRegistryW
1622 0x00044de0 0x180044de0 GLOBAL FUNC 0    ADVAPI32.dll RegCopyTreeA
1623 0x0002fd70 0x18002fd70 GLOBAL FUNC 0    ADVAPI32.dll RegCopyTreeW
1624 0x00044e60 0x180044e60 GLOBAL FUNC 0    ADVAPI32.dll RegCreateKeyA
1625 0x00004640 0x180004640 GLOBAL FUNC 0    ADVAPI32.dll RegCreateKeyExA
1626 0x00007790 0x180007790 GLOBAL FUNC 0    ADVAPI32.dll RegCreateKeyExW
1627 0x00044ef0 0x180044ef0 GLOBAL FUNC 0    ADVAPI32.dll RegCreateKeyTransactedA
1628 0x00006970 0x180006970 GLOBAL FUNC 0    ADVAPI32.dll RegCreateKeyTransactedW
1629 0x00008570 0x180008570 GLOBAL FUNC 0    ADVAPI32.dll RegCreateKeyW
1630 0x000045e0 0x1800045e0 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteKeyA
1631 0x0002fd90 0x18002fd90 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteKeyExA
1632 0x00020040 0x180020040 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteKeyExW
1633 0x000450e0 0x1800450e0 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteKeyTransactedA
1634 0x00003580 0x180003580 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteKeyTransactedW
1635 0x0002fdb0 0x18002fdb0 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteKeyValueA
1636 0x0001bf80 0x18001bf80 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteKeyValueW
1637 0x000071f0 0x1800071f0 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteKeyW
1638 0x0002fdd0 0x18002fdd0 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteTreeA
1639 0x0001c000 0x18001c000 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteTreeW
1640 0x00004c20 0x180004c20 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteValueA
1641 0x00009110 0x180009110 GLOBAL FUNC 0    ADVAPI32.dll RegDeleteValueW
1642 0x000091c0 0x1800091c0 GLOBAL FUNC 0    ADVAPI32.dll RegDisablePredefinedCache
1643 0x0002fdf0 0x18002fdf0 GLOBAL FUNC 0    ADVAPI32.dll RegDisablePredefinedCacheEx
1644 0x00030910 0x180030910 GLOBAL FUNC 0    ADVAPI32.dll RegDisableReflectionKey
1645 0x00030910 0x180030910 GLOBAL FUNC 0    ADVAPI32.dll RegEnableReflectionKey
1646 0x00009130 0x180009130 GLOBAL FUNC 0    ADVAPI32.dll RegEnumKeyA
1647 0x00004660 0x180004660 GLOBAL FUNC 0    ADVAPI32.dll RegEnumKeyExA
1648 0x00006740 0x180006740 GLOBAL FUNC 0    ADVAPI32.dll RegEnumKeyExW
1649 0x00006aa0 0x180006aa0 GLOBAL FUNC 0    ADVAPI32.dll RegEnumKeyW
1650 0x0002fe10 0x18002fe10 GLOBAL FUNC 0    ADVAPI32.dll RegEnumValueA
1651 0x00006e60 0x180006e60 GLOBAL FUNC 0    ADVAPI32.dll RegEnumValueW
1652 0x00009440 0x180009440 GLOBAL FUNC 0    ADVAPI32.dll RegFlushKey
1653 0x00009180 0x180009180 GLOBAL FUNC 0    ADVAPI32.dll RegGetKeySecurity
1654 0x0002fe60 0x18002fe60 GLOBAL FUNC 0    ADVAPI32.dll RegGetValueA
1655 0x00008f10 0x180008f10 GLOBAL FUNC 0    ADVAPI32.dll RegGetValueW
1656 0x0002fe80 0x18002fe80 GLOBAL FUNC 0    ADVAPI32.dll RegLoadAppKeyA
1657 0x0002fea0 0x18002fea0 GLOBAL FUNC 0    ADVAPI32.dll RegLoadAppKeyW
1658 0x0002fec0 0x18002fec0 GLOBAL FUNC 0    ADVAPI32.dll RegLoadKeyA
1659 0x0002fee0 0x18002fee0 GLOBAL FUNC 0    ADVAPI32.dll RegLoadKeyW
1660 0x0002ff00 0x18002ff00 GLOBAL FUNC 0    ADVAPI32.dll RegLoadMUIStringA
1661 0x0002ff20 0x18002ff20 GLOBAL FUNC 0    ADVAPI32.dll RegLoadMUIStringW
1662 0x000086d0 0x1800086d0 GLOBAL FUNC 0    ADVAPI32.dll RegNotifyChangeKeyValue
1663 0x00009420 0x180009420 GLOBAL FUNC 0    ADVAPI32.dll RegOpenCurrentUser
1664 0x00009270 0x180009270 GLOBAL FUNC 0    ADVAPI32.dll RegOpenKeyA
1665 0x000073e0 0x1800073e0 GLOBAL FUNC 0    ADVAPI32.dll RegOpenKeyExA
1666 0x000067d0 0x1800067d0 GLOBAL FUNC 0    ADVAPI32.dll RegOpenKeyExW
1667 0x00044f90 0x180044f90 GLOBAL FUNC 0    ADVAPI32.dll RegOpenKeyTransactedA
1668 0x00006b40 0x180006b40 GLOBAL FUNC 0    ADVAPI32.dll RegOpenKeyTransactedW
1669 0x00007180 0x180007180 GLOBAL FUNC 0    ADVAPI32.dll RegOpenKeyW
1670 0x0002ff40 0x18002ff40 GLOBAL FUNC 0    ADVAPI32.dll RegOpenUserClassesRoot
1671 0x00044fd0 0x180044fd0 GLOBAL FUNC 0    ADVAPI32.dll RegOverridePredefKey
1672 0x00004ab0 0x180004ab0 GLOBAL FUNC 0    ADVAPI32.dll RegQueryInfoKeyA
1673 0x000068d0 0x1800068d0 GLOBAL FUNC 0    ADVAPI32.dll RegQueryInfoKeyW
1674 0x0002ff60 0x18002ff60 GLOBAL FUNC 0    ADVAPI32.dll RegQueryMultipleValuesA
1675 0x0002ff80 0x18002ff80 GLOBAL FUNC 0    ADVAPI32.dll RegQueryMultipleValuesW
1676 0x00030920 0x180030920 GLOBAL FUNC 0    ADVAPI32.dll RegQueryReflectionKey
1677 0x000454f0 0x1800454f0 GLOBAL FUNC 0    ADVAPI32.dll RegQueryValueA
1678 0x00007420 0x180007420 GLOBAL FUNC 0    ADVAPI32.dll RegQueryValueExA
1679 0x00006720 0x180006720 GLOBAL FUNC 0    ADVAPI32.dll RegQueryValueExW
1680 0x00006f40 0x180006f40 GLOBAL FUNC 0    ADVAPI32.dll RegQueryValueW
1681 0x00045040 0x180045040 GLOBAL FUNC 0    ADVAPI32.dll RegRenameKey
1682 0x00045810 0x180045810 GLOBAL FUNC 0    ADVAPI32.dll RegReplaceKeyA
1683 0x00046560 0x180046560 GLOBAL FUNC 0    ADVAPI32.dll RegReplaceKeyW
1684 0x0002ffa0 0x18002ffa0 GLOBAL FUNC 0    ADVAPI32.dll RegRestoreKeyA
1685 0x0002ffc0 0x18002ffc0 GLOBAL FUNC 0    ADVAPI32.dll RegRestoreKeyW
1686 0x00045a80 0x180045a80 GLOBAL FUNC 0    ADVAPI32.dll RegSaveKeyA
1687 0x0002ffe0 0x18002ffe0 GLOBAL FUNC 0    ADVAPI32.dll RegSaveKeyExA
1688 0x00030000 0x180030000 GLOBAL FUNC 0    ADVAPI32.dll RegSaveKeyExW
1689 0x00045c60 0x180045c60 GLOBAL FUNC 0    ADVAPI32.dll RegSaveKeyW
1690 0x00030020 0x180030020 GLOBAL FUNC 0    ADVAPI32.dll RegSetKeySecurity
1691 0x00030040 0x180030040 GLOBAL FUNC 0    ADVAPI32.dll RegSetKeyValueA
1692 0x00020060 0x180020060 GLOBAL FUNC 0    ADVAPI32.dll RegSetKeyValueW
1693 0x00045e10 0x180045e10 GLOBAL FUNC 0    ADVAPI32.dll RegSetValueA
1694 0x00004940 0x180004940 GLOBAL FUNC 0    ADVAPI32.dll RegSetValueExA
1695 0x00008280 0x180008280 GLOBAL FUNC 0    ADVAPI32.dll RegSetValueExW
1696 0x00045f80 0x180045f80 GLOBAL FUNC 0    ADVAPI32.dll RegSetValueW
1697 0x00030060 0x180030060 GLOBAL FUNC 0    ADVAPI32.dll RegUnLoadKeyA
1698 0x00030080 0x180030080 GLOBAL FUNC 0    ADVAPI32.dll RegUnLoadKeyW
1699 0x00004750 0x180004750 GLOBAL FUNC 0    ADVAPI32.dll RegisterEventSourceA
1700 0x00005170 0x180005170 GLOBAL FUNC 0    ADVAPI32.dll RegisterEventSourceW
1701 0x000082c0 0x1800082c0 GLOBAL FUNC 0    ADVAPI32.dll RegisterIdleTask
1702 0x000300a0 0x1800300a0 GLOBAL FUNC 0    ADVAPI32.dll RegisterServiceCtrlHandlerA
1703 0x000300c0 0x1800300c0 GLOBAL FUNC 0    ADVAPI32.dll RegisterServiceCtrlHandlerExA
1704 0x0001bfa0 0x18001bfa0 GLOBAL FUNC 0    ADVAPI32.dll RegisterServiceCtrlHandlerExW
1705 0x00009560 0x180009560 GLOBAL FUNC 0    ADVAPI32.dll RegisterServiceCtrlHandlerW
1706 0x000994be 0x1800994be GLOBAL FUNC 0    ADVAPI32.dll RegisterTraceGuidsA
1707 0x000994ef 0x1800994ef GLOBAL FUNC 0    ADVAPI32.dll RegisterTraceGuidsW
1708 0x00062ca0 0x180062ca0 GLOBAL FUNC 0    ADVAPI32.dll RegisterWaitChainCOMCallback
1709 0x00045130 0x180045130 GLOBAL FUNC 0    ADVAPI32.dll RemoteRegEnumKeyWrapper
1710 0x000452a0 0x1800452a0 GLOBAL FUNC 0    ADVAPI32.dll RemoteRegEnumValueWrapper
1711 0x000453d0 0x1800453d0 GLOBAL FUNC 0    ADVAPI32.dll RemoteRegQueryInfoKeyWrapper
1712 0x00046100 0x180046100 GLOBAL FUNC 0    ADVAPI32.dll RemoteRegQueryMultipleValues2Wrapper
1713 0x00046280 0x180046280 GLOBAL FUNC 0    ADVAPI32.dll RemoteRegQueryMultipleValuesWrapper
1714 0x00045770 0x180045770 GLOBAL FUNC 0    ADVAPI32.dll RemoteRegQueryValueWrapper
1715 0x000995f0 0x1800995f0 GLOBAL FUNC 0    ADVAPI32.dll RemoveTraceCallback
1716 0x0002df50 0x18002df50 GLOBAL FUNC 0    ADVAPI32.dll RemoveUsersFromEncryptedFile
1717 0x00052330 0x180052330 GLOBAL FUNC 0    ADVAPI32.dll ReportEventA
1718 0x00005620 0x180005620 GLOBAL FUNC 0    ADVAPI32.dll ReportEventW
1719 0x00007140 0x180007140 GLOBAL FUNC 0    ADVAPI32.dll RevertToSelf
1720 0x000444b0 0x1800444b0 GLOBAL FUNC 0    ADVAPI32.dll SafeBaseRegGetKeySecurity
1721 0x000067f0 0x1800067f0 GLOBAL FUNC 0    ADVAPI32.dll SaferCloseLevel
1722 0x0000ad70 0x18000ad70 GLOBAL FUNC 0    ADVAPI32.dll SaferComputeTokenFromLevel
1723 0x00037240 0x180037240 GLOBAL FUNC 0    ADVAPI32.dll SaferCreateLevel
1724 0x00037ba0 0x180037ba0 GLOBAL FUNC 0    ADVAPI32.dll SaferGetLevelInformation
1725 0x0000ce80 0x18000ce80 GLOBAL FUNC 0    ADVAPI32.dll SaferGetPolicyInformation
1726 0x00010970 0x180010970 GLOBAL FUNC 0    ADVAPI32.dll SaferIdentifyLevel
1727 0x00039800 0x180039800 GLOBAL FUNC 0    ADVAPI32.dll SaferRecordEventLogEntry
1728 0x00039f00 0x180039f00 GLOBAL FUNC 0    ADVAPI32.dll SaferSetLevelInformation
1729 0x000386f0 0x1800386f0 GLOBAL FUNC 0    ADVAPI32.dll SaferSetPolicyInformation
1730 0x0003b260 0x18003b260 GLOBAL FUNC 0    ADVAPI32.dll SaferiChangeRegistryScope
1731 0x0000a3b0 0x18000a3b0 GLOBAL FUNC 0    ADVAPI32.dll SaferiCompareTokenLevels
1732 0x00038db0 0x180038db0 GLOBAL FUNC 0    ADVAPI32.dll SaferiIsDllAllowed
1733 0x0003ba20 0x18003ba20 GLOBAL FUNC 0    ADVAPI32.dll SaferiIsExecutableFileType
1734 0x0003b2a0 0x18003b2a0 GLOBAL FUNC 0    ADVAPI32.dll SaferiPopulateDefaultsInRegistry
1735 0x00039800 0x180039800 GLOBAL FUNC 0    ADVAPI32.dll SaferiRecordEventLogEntry
1736 0x00007690 0x180007690 GLOBAL FUNC 0    ADVAPI32.dll SaferiSearchMatchingHashRules
1737 0x000300e0 0x1800300e0 GLOBAL FUNC 0    ADVAPI32.dll SetAclInformation
1738 0x0002dfd0 0x18002dfd0 GLOBAL FUNC 0    ADVAPI32.dll SetEncryptedFileMetadata
1739 0x00040fb0 0x180040fb0 GLOBAL FUNC 0    ADVAPI32.dll SetEntriesInAccessListA
1740 0x00041000 0x180041000 GLOBAL FUNC 0    ADVAPI32.dll SetEntriesInAccessListW
1741 0x0003ec00 0x18003ec00 GLOBAL FUNC 0    ADVAPI32.dll SetEntriesInAclA
1742 0x00008f70 0x180008f70 GLOBAL FUNC 0    ADVAPI32.dll SetEntriesInAclW
1743 0x00041050 0x180041050 GLOBAL FUNC 0    ADVAPI32.dll SetEntriesInAuditListA
1744 0x00041090 0x180041090 GLOBAL FUNC 0    ADVAPI32.dll SetEntriesInAuditListW
1745 0x00049a10 0x180049a10 GLOBAL FUNC 0    ADVAPI32.dll SetFileSecurityA
1746 0x0001bfe0 0x18001bfe0 GLOBAL FUNC 0    ADVAPI32.dll SetFileSecurityW
1747 0x00039f00 0x180039f00 GLOBAL FUNC 0    ADVAPI32.dll SetInformationCodeAuthzLevelW
1748 0x000386f0 0x1800386f0 GLOBAL FUNC 0    ADVAPI32.dll SetInformationCodeAuthzPolicyW
1749 0x00009520 0x180009520 GLOBAL FUNC 0    ADVAPI32.dll SetKernelObjectSecurity
1750 0x0003ee80 0x18003ee80 GLOBAL FUNC 0    ADVAPI32.dll SetNamedSecurityInfoA
1751 0x000410d0 0x1800410d0 GLOBAL FUNC 0    ADVAPI32.dll SetNamedSecurityInfoExA
1752 0x00041560 0x180041560 GLOBAL FUNC 0    ADVAPI32.dll SetNamedSecurityInfoExW
1753 0x0001bf60 0x18001bf60 GLOBAL FUNC 0    ADVAPI32.dll SetNamedSecurityInfoW
1754 0x00030120 0x180030120 GLOBAL FUNC 0    ADVAPI32.dll SetPrivateObjectSecurity
1755 0x00030100 0x180030100 GLOBAL FUNC 0    ADVAPI32.dll SetPrivateObjectSecurityEx
1756 0x00030140 0x180030140 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityAccessMask
1757 0x00030160 0x180030160 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityDescriptorControl
1758 0x000084a0 0x1800084a0 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityDescriptorDacl
1759 0x00009360 0x180009360 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityDescriptorGroup
1760 0x00008eb0 0x180008eb0 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityDescriptorOwner
1761 0x00030180 0x180030180 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityDescriptorRMControl
1762 0x000301a0 0x1800301a0 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityDescriptorSacl
1763 0x00008de0 0x180008de0 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityInfo
1764 0x00041870 0x180041870 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityInfoExA
1765 0x00041cc0 0x180041cc0 GLOBAL FUNC 0    ADVAPI32.dll SetSecurityInfoExW
1766 0x000478b0 0x1800478b0 GLOBAL FUNC 0    ADVAPI32.dll SetServiceBits
1767 0x000301c0 0x1800301c0 GLOBAL FUNC 0    ADVAPI32.dll SetServiceObjectSecurity
1768 0x00009320 0x180009320 GLOBAL FUNC 0    ADVAPI32.dll SetServiceStatus
1769 0x00007650 0x180007650 GLOBAL FUNC 0    ADVAPI32.dll SetThreadToken
1770 0x00004a90 0x180004a90 GLOBAL FUNC 0    ADVAPI32.dll SetTokenInformation
1771 0x00099b03 0x180099b03 GLOBAL FUNC 0    ADVAPI32.dll SetTraceCallback
1772 0x0002dfe0 0x18002dfe0 GLOBAL FUNC 0    ADVAPI32.dll SetUserFileEncryptionKey
1773 0x0002e050 0x18002e050 GLOBAL FUNC 0    ADVAPI32.dll SetUserFileEncryptionKeyEx
1774 0x000301e0 0x1800301e0 GLOBAL FUNC 0    ADVAPI32.dll StartServiceA
1775 0x00030200 0x180030200 GLOBAL FUNC 0    ADVAPI32.dll StartServiceCtrlDispatcherA
1776 0x00009480 0x180009480 GLOBAL FUNC 0    ADVAPI32.dll StartServiceCtrlDispatcherW
1777 0x00009540 0x180009540 GLOBAL FUNC 0    ADVAPI32.dll StartServiceW
1778 0x0001c920 0x18001c920 GLOBAL FUNC 0    ADVAPI32.dll StartTraceA
1779 0x000094a0 0x1800094a0 GLOBAL FUNC 0    ADVAPI32.dll StartTraceW
1780 0x000438d0 0x1800438d0 GLOBAL FUNC 0    ADVAPI32.dll StopTraceA
1781 0x00030220 0x180030220 GLOBAL FUNC 0    ADVAPI32.dll StopTraceW
1782 0x00099be4 0x180099be4 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction001
1783 0x00099c12 0x180099c12 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction002
1784 0x00099c40 0x180099c40 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction003
1785 0x00099c6e 0x180099c6e GLOBAL FUNC 0    ADVAPI32.dll SystemFunction004
1786 0x00099c9c 0x180099c9c GLOBAL FUNC 0    ADVAPI32.dll SystemFunction005
1787 0x00099cca 0x180099cca GLOBAL FUNC 0    ADVAPI32.dll SystemFunction006
1788 0x00099cf6 0x180099cf6 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction007
1789 0x00099d22 0x180099d22 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction008
1790 0x00099d4e 0x180099d4e GLOBAL FUNC 0    ADVAPI32.dll SystemFunction009
1791 0x00099d7a 0x180099d7a GLOBAL FUNC 0    ADVAPI32.dll SystemFunction010
1792 0x00099da6 0x180099da6 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction011
1793 0x00099dd2 0x180099dd2 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction012
1794 0x00099dfe 0x180099dfe GLOBAL FUNC 0    ADVAPI32.dll SystemFunction013
1795 0x00099e2a 0x180099e2a GLOBAL FUNC 0    ADVAPI32.dll SystemFunction014
1796 0x00099e56 0x180099e56 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction015
1797 0x00099e82 0x180099e82 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction016
1798 0x00030ad0 0x180030ad0 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction017
1799 0x00099ec0 0x180099ec0 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction018
1800 0x00030b30 0x180030b30 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction019
1801 0x00099efe 0x180099efe GLOBAL FUNC 0    ADVAPI32.dll SystemFunction020
1802 0x00099f2a 0x180099f2a GLOBAL FUNC 0    ADVAPI32.dll SystemFunction021
1803 0x00099f56 0x180099f56 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction022
1804 0x00099f82 0x180099f82 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction023
1805 0x00099fae 0x180099fae GLOBAL FUNC 0    ADVAPI32.dll SystemFunction024
1806 0x00099fda 0x180099fda GLOBAL FUNC 0    ADVAPI32.dll SystemFunction025
1807 0x0009a006 0x18009a006 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction026
1808 0x0009a032 0x18009a032 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction027
1809 0x0009a05e 0x18009a05e GLOBAL FUNC 0    ADVAPI32.dll SystemFunction028
1810 0x0009a08c 0x18009a08c GLOBAL FUNC 0    ADVAPI32.dll SystemFunction029
1811 0x0009a0ba 0x18009a0ba GLOBAL FUNC 0    ADVAPI32.dll SystemFunction030
1812 0x0009a0e6 0x18009a0e6 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction031
1813 0x0009a112 0x18009a112 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction032
1814 0x0009a13e 0x18009a13e GLOBAL FUNC 0    ADVAPI32.dll SystemFunction033
1815 0x0009a16a 0x18009a16a GLOBAL FUNC 0    ADVAPI32.dll SystemFunction034
1816 0x0009a198 0x18009a198 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction035
1817 0x0009a1c7 0x18009a1c7 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction036
1818 0x0009a1f5 0x18009a1f5 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction040
1819 0x0009a223 0x18009a223 GLOBAL FUNC 0    ADVAPI32.dll SystemFunction041
1820 0x0009a24a 0x18009a24a GLOBAL FUNC 0    ADVAPI32.dll TraceEvent
1821 0x0009a274 0x18009a274 GLOBAL FUNC 0    ADVAPI32.dll TraceEventInstance
1822 0x0009a29d 0x18009a29d GLOBAL FUNC 0    ADVAPI32.dll TraceMessage
1823 0x0009a2c2 0x18009a2c2 GLOBAL FUNC 0    ADVAPI32.dll TraceMessageVa
1824 0x0009a2f0 0x18009a2f0 GLOBAL FUNC 0    ADVAPI32.dll TraceQueryInformation
1825 0x00030240 0x180030240 GLOBAL FUNC 0    ADVAPI32.dll TraceSetInformation
1826 0x0003ef20 0x18003ef20 GLOBAL FUNC 0    ADVAPI32.dll TreeResetNamedSecurityInfoA
1827 0x0001bd40 0x18001bd40 GLOBAL FUNC 0    ADVAPI32.dll TreeResetNamedSecurityInfoW
1828 0x0003ef30 0x18003ef30 GLOBAL FUNC 0    ADVAPI32.dll TreeSetNamedSecurityInfoA
1829 0x0003ef40 0x18003ef40 GLOBAL FUNC 0    ADVAPI32.dll TreeSetNamedSecurityInfoW
1830 0x00041fe0 0x180041fe0 GLOBAL FUNC 0    ADVAPI32.dll TrusteeAccessToObjectA
1831 0x00042250 0x180042250 GLOBAL FUNC 0    ADVAPI32.dll TrusteeAccessToObjectW
1832 0x00035c90 0x180035c90 GLOBAL FUNC 0    ADVAPI32.dll UninstallApplication
1833 0x00047900 0x180047900 GLOBAL FUNC 0    ADVAPI32.dll UnlockServiceDatabase
1834 0x00030ab0 0x180030ab0 GLOBAL FUNC 0    ADVAPI32.dll UnregisterIdleTask
1835 0x0009a42d 0x18009a42d GLOBAL FUNC 0    ADVAPI32.dll UnregisterTraceGuids
1836 0x000438f0 0x1800438f0 GLOBAL FUNC 0    ADVAPI32.dll UpdateTraceA
1837 0x00043910 0x180043910 GLOBAL FUNC 0    ADVAPI32.dll UpdateTraceW
1838 0x0002e150 0x18002e150 GLOBAL FUNC 0    ADVAPI32.dll UsePinForEncryptedFilesA
1839 0x0002e1f0 0x18002e1f0 GLOBAL FUNC 0    ADVAPI32.dll UsePinForEncryptedFilesW
1840 0x00030260 0x180030260 GLOBAL FUNC 0    ADVAPI32.dll WaitServiceState
1841 0x00059d70 0x180059d70 GLOBAL FUNC 0    ADVAPI32.dll WmiCloseBlock
1842 0x00059df0 0x180059df0 GLOBAL FUNC 0    ADVAPI32.dll WmiDevInstToInstanceNameA
1843 0x00059ee0 0x180059ee0 GLOBAL FUNC 0    ADVAPI32.dll WmiDevInstToInstanceNameW
1844 0x00059fd0 0x180059fd0 GLOBAL FUNC 0    ADVAPI32.dll WmiEnumerateGuids
1845 0x0005a1a0 0x18005a1a0 GLOBAL FUNC 0    ADVAPI32.dll WmiExecuteMethodA
1846 0x0005a2a0 0x18005a2a0 GLOBAL FUNC 0    ADVAPI32.dll WmiExecuteMethodW
1847 0x0005a620 0x18005a620 GLOBAL FUNC 0    ADVAPI32.dll WmiFileHandleToInstanceNameA
1848 0x0005a890 0x18005a890 GLOBAL FUNC 0    ADVAPI32.dll WmiFileHandleToInstanceNameW
1849 0x0005aaa0 0x18005aaa0 GLOBAL FUNC 0    ADVAPI32.dll WmiFreeBuffer
1850 0x0005c490 0x18005c490 GLOBAL FUNC 0    ADVAPI32.dll WmiMofEnumerateResourcesA
1851 0x0005c6d0 0x18005c6d0 GLOBAL FUNC 0    ADVAPI32.dll WmiMofEnumerateResourcesW
1852 0x0005aaf0 0x18005aaf0 GLOBAL FUNC 0    ADVAPI32.dll WmiNotificationRegistrationA
1853 0x0005ab80 0x18005ab80 GLOBAL FUNC 0    ADVAPI32.dll WmiNotificationRegistrationW
1854 0x0005ac10 0x18005ac10 GLOBAL FUNC 0    ADVAPI32.dll WmiOpenBlock
1855 0x0005ad10 0x18005ad10 GLOBAL FUNC 0    ADVAPI32.dll WmiQueryAllDataA
1856 0x0005ad90 0x18005ad90 GLOBAL FUNC 0    ADVAPI32.dll WmiQueryAllDataMultipleA
1857 0x0005ae20 0x18005ae20 GLOBAL FUNC 0    ADVAPI32.dll WmiQueryAllDataMultipleW
1858 0x0005b050 0x18005b050 GLOBAL FUNC 0    ADVAPI32.dll WmiQueryAllDataW
1859 0x0005b2d0 0x18005b2d0 GLOBAL FUNC 0    ADVAPI32.dll WmiQueryGuidInformation
1860 0x0005b390 0x18005b390 GLOBAL FUNC 0    ADVAPI32.dll WmiQuerySingleInstanceA
1861 0x0005b480 0x18005b480 GLOBAL FUNC 0    ADVAPI32.dll WmiQuerySingleInstanceMultipleA
1862 0x0005b630 0x18005b630 GLOBAL FUNC 0    ADVAPI32.dll WmiQuerySingleInstanceMultipleW
1863 0x0005b890 0x18005b890 GLOBAL FUNC 0    ADVAPI32.dll WmiQuerySingleInstanceW
1864 0x0005bb20 0x18005bb20 GLOBAL FUNC 0    ADVAPI32.dll WmiReceiveNotificationsA
1865 0x0005bba0 0x18005bba0 GLOBAL FUNC 0    ADVAPI32.dll WmiReceiveNotificationsW
1866 0x0005bc20 0x18005bc20 GLOBAL FUNC 0    ADVAPI32.dll WmiSetSingleInstanceA
1867 0x0005bd00 0x18005bd00 GLOBAL FUNC 0    ADVAPI32.dll WmiSetSingleInstanceW
1868 0x0005bee0 0x18005bee0 GLOBAL FUNC 0    ADVAPI32.dll WmiSetSingleItemA
1869 0x0005bfc0 0x18005bfc0 GLOBAL FUNC 0    ADVAPI32.dll WmiSetSingleItemW
1870 0x0002e290 0x18002e290 GLOBAL FUNC 0    ADVAPI32.dll WriteEncryptedFileRaw
```

#### Functions and Documentation

| Exported Function                                    | Documentation Link                                                                                                                                                            |
|------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ordinal_1000                                         | N/A                                                                                                                                                                           |
| I_ScGetCurrentGroupStateW                            | N/A                                                                                                                                                                           |
| A_SHAFinal                                           | N/A                                                                                                                                                                           |
| A_SHAInit                                            | N/A                                                                                                                                                                           |
| A_SHAUpdate                                          | N/A                                                                                                                                                                           |
| AbortSystemShutdownA                                 | [AbortSystemShutdownA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-abortsystemshutdowna)                                                             |
| AbortSystemShutdownW                                 | [AbortSystemShutdownW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-abortsystemshutdownw)                                                             |
| AccessCheck                                          | [AccessCheck](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-accesscheck)                                                             |
| AccessCheckAndAuditAlarmA                            | [AccessCheckAndAuditAlarmA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-accesscheckandauditalarma)                                                 |
| AccessCheckAndAuditAlarmW                            | [AccessCheckAndAuditAlarmW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-accesscheckandauditalarmw)                                                 |
| AccessCheckByType                                    | [AccessCheckByType](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-accesscheckbytype)                                                                   |
| AccessCheckByTypeAndAuditAlarmA                      | [AccessCheckByTypeAndAuditAlarmA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-accesscheckbytypeandauditalarma)                                     |
| AccessCheckByTypeAndAuditAlarmW                      | [AccessCheckByTypeAndAuditAlarmW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-accesscheckbytypeandauditalarmw)                                     |
| AccessCheckByTypeResultList                          | [AccessCheckByTypeResultList](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-accesscheckbytyperesultlist)                                               |
| AccessCheckByTypeResultListAndAuditAlarmA            | [AccessCheckByTypeResultListAndAuditAlarmA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-accesscheckbytyperesultlistandauditalarma)                 |
| AccessCheckByTypeResultListAndAuditAlarmByHandleA    | [AccessCheckByTypeResultListAndAuditAlarmByHandleA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-accesscheckbytyperesultlistandauditalarmbyhandlea) |
| AccessCheckByTypeResultListAndAuditAlarmByHandleW    | [AccessCheckByTypeResultListAndAuditAlarmByHandleW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-accesscheckbytyperesultlistandauditalarmbyhandlew) |
| AccessCheckByTypeResultListAndAuditAlarmW            | [AccessCheckByTypeResultListAndAuditAlarmW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-accesscheckbytyperesultlistandauditalarmw)                 |
| AddAccessAllowedAce                                  | [AddAccessAllowedAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addaccessallowedace)                                                               |
| AddAccessAllowedAceEx                                | [AddAccessAllowedAceEx](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addaccessallowedaceex)                                                           |
| AddAccessAllowedObjectAce                            | [AddAccessAllowedObjectAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addaccessallowedobjectace)                                                   |
| AddAccessDeniedAce                                   | [AddAccessDeniedAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addaccessdeniedace)                                                                 |
| AddAccessDeniedAceEx                                 | [AddAccessDeniedAceEx](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addaccessdeniedaceex)                                                             |
| AddAccessDeniedObjectAce                             | [AddAccessDeniedObjectAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addaccessdeniedobjectace)                                                     |
| AddAce                                               | [AddAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addace)                                                                                         |
| AddAuditAccessAce                                    | [AddAuditAccessAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addauditaccessace)                                                                   |
| AddAuditAccessAceEx                                  | [AddAuditAccessAceEx](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addauditaccessaceex)                                                               |
| AddAuditAccessObjectAce                              | [AddAuditAccessObjectAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addauditaccessobjectace)                                                       |
| AddConditionalAce                                    | [AddConditionalAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addconditionalace)                                                                   |
| AddMandatoryAce                                      | [AddMandatoryAce](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-addmandatoryace)                                                                       |
| AddUsersToEncryptedFile                              | [AddUsersToEncryptedFile](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-adduserstoencryptedfile)                                                       |
| AddUsersToEncryptedFileEx                            | [AddUsersToEncryptedFileEx](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-adduserstoencryptedfileex)                                                   |
| AdjustTokenGroups                                    | [AdjustTokenGroups](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-adjusttokengroups)                                                 |
| AdjustTokenPrivileges                                | [AdjustTokenPrivileges](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-adjusttokenprivileges)                                         |
| AllocateAndInitializeSid                             | [AllocateAndInitializeSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-allocateandinitializesid)                                   |
| AllocateLocallyUniqueId                              | [AllocateLocallyUniqueId](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-allocatelocallyuniqueid)                                     |
| AreAllAccessesGranted                                | [AreAllAccessesGranted](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-areallaccessesgranted)                                                           |
| AreAnyAccessesGranted                                | [AreAnyAccessesGranted](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-areanyaccessesgranted)                                                           |
| AuditComputeEffectivePolicyBySid                     | [AuditComputeEffectivePolicyBySid](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditcomputeeffectivepolicybysid)                                 |
| AuditComputeEffectivePolicyByToken                   | [AuditComputeEffectivePolicyByToken](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditcomputeeffectivepolicybytoken)                             |
| AuditEnumerateCategories                             | [AuditEnumerateCategories](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditenumeratecategories)                                                 |
| AuditEnumeratePerUserPolicy                          | [AuditEnumeratePerUserPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditenumerateperuserpolicy)                                           |
| AuditEnumerateSubCategories                          | [AuditEnumerateSubCategories](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditenumeratesubcategories)                                           |
| AuditFree                                            | [AuditFree](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditfree)                                                                               |
| AuditLookupCategoryGuidFromCategoryId                | [AuditLookupCategoryGuidFromCategoryId](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditlookupcategoryguidfromcategoryid)                       |
| AuditLookupCategoryIdFromCategoryGuid                | [AuditLookupCategoryIdFromCategoryGuid](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditlookupcategoryidfromcategoryguid)                       |
| AuditLookupCategoryNameA                             | [AuditLookupCategoryNameA](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditlookupcategorynamea)                                                 |
| AuditLookupCategoryNameW                             | [AuditLookupCategoryNameW](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditlookupcategorynamew)                                                 |
| AuditLookupSubCategoryNameA                          | [AuditLookupSubCategoryNameA](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditlookupsubcategorynamea)                                           |
| AuditLookupSubCategoryNameW                          | [AuditLookupSubCategoryNameW](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditlookupsubcategorynamew)                                           |
| AuditQueryGlobalSaclA                                | [AuditQueryGlobalSaclA](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditqueryglobalsacla)                                                       |
| AuditQueryGlobalSaclW                                | [AuditQueryGlobalSaclW](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditqueryglobalsaclw)                                                       |
| AuditQueryPerUserPolicy                              | [AuditQueryPerUserPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditqueryperuserpolicy)                                                   |
| AuditQuerySecurity                                   | [AuditQuerySecurity](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditquerysecurity)                                                             |
| AuditQuerySystemPolicy                               | [AuditQuerySystemPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditquerysystempolicy)                                                     |
| AuditSetGlobalSaclA                                  | [AuditSetGlobalSaclA](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditsetglobalsacla)                                                           |
| AuditSetGlobalSaclW                                  | [AuditSetGlobalSaclW](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditsetglobalsaclw)                                                           |
| AuditSetPerUserPolicy                                | [AuditSetPerUserPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditsetperuserpolicy)                                                       |
| AuditSetSecurity                                     | [AuditSetSecurity](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditsetsecurity)                                                                 |
| AuditSetSystemPolicy                                 | [AuditSetSystemPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-auditsetsystempolicy)                                                         |
| BackupEventLogA                                      | [BackupEventLogA](https://learn.microsoft.com/en-us/windows/win32/api/winevt/nf-winevt-backupeventloga)                                                                       |
| BackupEventLogW                                      | [BackupEventLogW](https://learn.microsoft.com/en-us/windows/win32/api/winevt/nf-winevt-backupeventlogw)                                                                       |
| BaseRegCloseKey                                      | N/A                                                                                                                                                                           |
| BaseRegCreateKey                                     | N/A                                                                                                                                                                           |
| BaseRegDeleteKeyEx                                   | N/A                                                                                                                                                                           |
| BaseRegDeleteValue                                   | N/A                                                                                                                                                                           |
| BaseRegFlushKey                                      | N/A                                                                                                                                                                           |
| BaseRegGetVersion                                    | N/A                                                                                                                                                                           |
| BaseRegLoadKey                                       | N/A                                                                                                                                                                           |
| BaseRegOpenKey                                       | N/A                                                                                                                                                                           |
| BaseRegRestoreKey                                    | N/A                                                                                                                                                                           |
| BaseRegSaveKeyEx                                     | N/A                                                                                                                                                                           |
| BaseRegSetKeySecurity                                | N/A                                                                                                                                                                           |
| BaseRegSetValue                                      | N/A                                                                                                                                                                           |
| BaseRegUnLoadKey                                     | N/A                                                                                                                                                                           |
| BuildExplicitAccessWithNameA                         | [BuildExplicitAccessWithNameA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildexplicitaccesswithnamea)                                             |
| BuildExplicitAccessWithNameW                         | [BuildExplicitAccessWithNameW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildexplicitaccesswithnamew)                                             |
| BuildImpersonateExplicitAccessWithNameA              | [BuildImpersonateExplicitAccessWithNameA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildimpersonateexplicitaccesswithnamea)                       |
| BuildImpersonateExplicitAccessWithNameW              | [BuildImpersonateExplicitAccessWithNameW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildimpersonateexplicitaccesswithnamew)                       |
| BuildImpersonateTrusteeA                             | [BuildImpersonateTrusteeA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildimpersonatetrusteea)                                                     |
| BuildImpersonateTrusteeW                             | [BuildImpersonateTrusteeW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildimpersonatetrusteew)                                                     |
| BuildSecurityDescriptorA                             | [BuildSecurityDescriptorA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildsecuritydescriptora)                                                     |
| BuildSecurityDescriptorW                             | [BuildSecurityDescriptorW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildsecuritydescriptorw)                                                     |
| BuildTrusteeWithNameA                                | [BuildTrusteeWithNameA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithnamea)                                                           |
| BuildTrusteeWithNameW                                | [BuildTrusteeWithNameW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithnamew)                                                           |
| BuildTrusteeWithObjectsAndNameA                      | [BuildTrusteeWithObjectsAndNameA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithobjectsandnamea)                                       |
| BuildTrusteeWithObjectsAndNameW                      | [BuildTrusteeWithObjectsAndNameW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithobjectsandnamew)                                       |
| BuildTrusteeWithObjectsAndSidA                       | [BuildTrusteeWithObjectsAndSidA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithobjectsandsida)                                         |
| BuildTrusteeWithObjectsAndSidW                       | [BuildTrusteeWithObjectsAndSidW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithobjectsandsidw)                                         |
| BuildTrusteeWithSidA                                 | [BuildTrusteeWithSidA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithsida)                                                             |
| BuildTrusteeWithSidW                                 | [BuildTrusteeWithSidW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-buildtrusteewithsidw)                                                             |
| CancelOverlappedAccess                               | [CancelOverlappedAccess](https://learn.microsoft.com/en-us/windows/win32/api/minwinbase/nf-minwinbase-canceloverlappedaccess)                                                 |
| ChangeServiceConfig2A                                | [ChangeServiceConfig2A](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-changeserviceconfig2a)                                                           |
| ChangeServiceConfig2W                                | [ChangeServiceConfig2W](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-changeserviceconfig2w)                                                           |
| ChangeServiceConfigA                                 | [ChangeServiceConfigA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-changeserviceconfiga)                                                             |
| ChangeServiceConfigW                                 | [ChangeServiceConfigW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-changeserviceconfigw)                                                             |
| CheckForHiberboot                                    | N/A                                                                                                                                                                           |
| CheckTokenMembership                                 | [CheckTokenMembership](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-checktokenmembership)                                           |
| ClearEventLogA                                       | [ClearEventLogA](https://learn.microsoft.com/en-us/windows/win32/api/winevt/nf-winevt-cleareventloga)                                                                         |
| ClearEventLogW                                       | [ClearEventLogW](https://learn.microsoft.com/en-us/windows/win32/api/winevt/nf-winevt-cleareventlogw)                                                                         |
| CloseCodeAuthzLevel                                  | [CloseCodeAuthzLevel](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-closecodeauthzlevel)                                                             |
| CloseEncryptedFileRaw                                | [CloseEncryptedFileRaw](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-closeencryptedfileraw)                                                         |
| CloseEventLog                                        | [CloseEventLog](https://learn.microsoft.com/en-us/windows/win32/api/winevt/nf-winevt-closeeventlog)                                                                           |
| CloseServiceHandle                                   | [CloseServiceHandle](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-closeservicehandle)                                                                 |
| CloseThreadWaitChainSession                          | [CloseThreadWaitChainSession](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-closethreadwaitchainsession)                                             |
| CloseTrace                                           | [CloseTrace](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-closetrace)                                                                             |
| CommandLineFromMsiDescriptor                         | N/A                                                                                                                                                                           |
| ComputeAccessTokenFromCodeAuthzLevel                 | N/A                                                                                                                                                                           |
| ControlService                                       | [ControlService](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-controlservice)                                                                         |
| ControlServiceExA                                    | [ControlServiceExA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-controlserviceexa)                                                                   |
| ControlServiceExW                                    | [ControlServiceExW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-controlserviceexw)                                                                   |
| ControlTraceA                                        | [ControlTraceA](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-controltracea)                                                                       |
| ControlTraceW                                        | [ControlTraceW](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-controltracew)                                                                       |
| ConvertAccessToSecurityDescriptorA                   | N/A                                                                                                                                                                           |
| ConvertAccessToSecurityDescriptorW                   | N/A                                                                                                                                                                           |
| ConvertSDToStringSDDomainW                           | N/A                                                                                                                                                                           |
| ConvertSDToStringSDRootDomainA                       | N/A                                                                                                                                                                           |
| ConvertSDToStringSDRootDomainW                       | N/A                                                                                                                                                                           |
| ConvertSecurityDescriptorToAccessA                   | N/A                                                                                                                                                                           |
| ConvertSecurityDescriptorToAccessNamedA              | N/A                                                                                                                                                                           |
| ConvertSecurityDescriptorToAccessNamedW              | N/A                                                                                                                                                                           |
| ConvertSecurityDescriptorToAccessW                   | N/A                                                                                                                                                                           |
| ConvertSecurityDescriptorToStringSecurityDescriptorA | [ConvertSecurityDescriptorToStringSecurityDescriptorA](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertsecuritydescriptortostringsecuritydescriptora) |
| ConvertSecurityDescriptorToStringSecurityDescriptorW | [ConvertSecurityDescriptorToStringSecurityDescriptorW](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertsecuritydescriptortostringsecuritydescriptorw) |
| ConvertSidToStringSidA                               | [ConvertSidToStringSidA](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertsidtosidstringa)                                                             |
| ConvertSidToStringSidW                               | [ConvertSidToStringSidW](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertsidtosidstringw)                                                             |
| ConvertStringSDToSDDomainA                           | N/A                                                                                                                                                                           |
| ConvertStringSDToSDDomainW                           | N/A                                                                                                                                                                           |
| ConvertStringSDToSDRootDomainA                       | N/A                                                                                                                                                                           |
| ConvertStringSDToSDRootDomainW                       | N/A                                                                                                                                                                           |
| ConvertStringSecurityDescriptorToSecurityDescriptorA | [ConvertStringSecurityDescriptorToSecurityDescriptorA](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertstringsecuritydescriptortosecuritydescriptora) |
| ConvertStringSecurityDescriptorToSecurityDescriptorW | [ConvertStringSecurityDescriptorToSecurityDescriptorW](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertstringsecuritydescriptortosecuritydescriptorw) |
| ConvertStringSidToSidA                               | [ConvertStringSidToSidA](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertstringsidtosida)                                                             |
| ConvertStringSidToSidW                               | [ConvertStringSidToSidW](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-convertstringsidtosidw)                                                             |
| ConvertToAutoInheritPrivateObjectSecurity            | [ConvertToAutoInheritPrivateObjectSecurity](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-converttoautoinheritprivateobjectsecurity)                   |
| CopySid                                              | [CopySid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-copysid)                                                                     |
| CreateCodeAuthzLevel                                 | [CreateCodeAuthzLevel](https://learn.microsoft.com/en-us/windows/win32/api/authz/nf-authz-createcodeauthzlevel)                                                               |
| CreatePrivateObjectSecurity                          | [CreatePrivateObjectSecurity](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-createprivateobjectsecurity)                                               |
| CreatePrivateObjectSecurityEx                        | [CreatePrivateObjectSecurityEx](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-createprivateobjectsecurityex)                                           |
| CreatePrivateObjectSecurityWithMultipleInheritance   | [CreatePrivateObjectSecurityWithMultipleInheritance](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-createprivateobjectsecuritywithmultipleinheritance) |
| CreateProcessAsUserA                                 | [CreateProcessAsUserA](https://learn.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessasusera)                                       |
| CreateProcessAsUserW                                 | [CreateProcessAsUserW](https://learn.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createprocessasuserw)                                       |
| CreateProcessWithLogonW                              | [CreateProcessWithLogonW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createprocesswithlogonw)                                                     |
| CreateProcessWithTokenW                              | [CreateProcessWithTokenW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createprocesswithtokenw)                                                     |
| CreateRestrictedToken                                | [CreateRestrictedToken](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-createrestrictedtoken)                                         |
| CreateServiceA                                       | [CreateServiceA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-createservicea)                                                                         |
| CreateServiceEx                                      | N/A                                                                                                                                                                           |
| CreateServiceW                                       | [CreateServiceW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-createservicew)                                                                         |
| CreateTraceInstanceId                                | [CreateTraceInstanceId](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-createtraceinstanceid)                                                       |
| CreateWellKnownSid                                   | [CreateWellKnownSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-createwellknownsid)                                               |
| CredBackupCredentials                                | [CredBackupCredentials](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credattributedata)                                                             |
| CredDeleteA                                          | [CredDeleteA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-creddeletea)                                                                             |
| CredDeleteW                                          | [CredDeleteW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-creddeletew)                                                                             |
| CredEncryptAndMarshalBinaryBlob                      | N/A                                                                                                                                                                           |
| CredEnumerateA                                       | [CredEnumerateA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credenumeratea)                                                                       |
| CredEnumerateW                                       | [CredEnumerateW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credenumeratew)                                                                       |
| CredFindBestCredentialA                              | N/A                                                                                                                                                                           |
| CredFindBestCredentialW                              | N/A                                                                                                                                                                           |
| CredFree                                             | [CredFree](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credfree)                                                                                   |
| CredGetSessionTypes                                  | N/A                                                                                                                                                                           |
| CredGetTargetInfoA                                   | [CredGetTargetInfoA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credgettargetinfoa)                                                               |
| CredGetTargetInfoW                                   | [CredGetTargetInfoW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credgettargetinfow)                                                               |
| CredIsMarshaledCredentialA                           | [CredIsMarshaledCredentialA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credismarshaledcredentiala)                                               |
| CredIsMarshaledCredentialW                           | [CredIsMarshaledCredentialW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credismarshaledcredentialw)                                               |
| CredIsProtectedA                                     | [CredIsProtectedA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credisprotecteda)                                                                   |
| CredIsProtectedW                                     | [CredIsProtectedW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credisprotectedw)                                                                   |
| CredMarshalCredentialA                               | [CredMarshalCredentialA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credmarshalcredentiala)                                                       |
| CredMarshalCredentialW                               | [CredMarshalCredentialW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credmarshalcredentialw)                                                       |
| CredProfileLoaded                                    | N/A                                                                                                                                                                           |
| CredProfileLoadedEx                                  | N/A                                                                                                                                                                           |
| CredProfileUnloaded                                  | N/A                                                                                                                                                                           |
| CredProtectA                                         | [CredProtectA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credprotecta)                                                                           |
| CredProtectW                                         | [CredProtectW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credprotectw)                                                                           |
| CredReadA                                            | [CredReadA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credreada)                                                                                 |
| CredReadByTokenHandle                                | N/A                                                                                                                                                                           |
| CredReadDomainCredentialsA                           | [CredReadDomainCredentialsA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credreaddomaincredentialsa)                                               |
| CredReadDomainCredentialsW                           | [CredReadDomainCredentialsW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credreaddomaincredentialsw)                                               |
| CredReadW                                            | [CredReadW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credreadw)                                                                                 |
| CredRenameA                                          | [CredRenameA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credenumeratea)                                                                          |
| CredRenameW                                          | [CredRenameW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credenumeratew)                                                                          |
| CredRestoreCredentials                               | N/A                                                                                                                                                                           |
| CredUnmarshalCredentialA                             | [CredUnmarshalCredentialA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credunmarshalcredentiala)                                                   |
| CredUnmarshalCredentialW                             | [CredUnmarshalCredentialW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credunmarshalcredentialw)                                                   |
| CredUnprotectA                                       | [CredUnprotectA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credunprotecta)                                                                       |
| CredUnprotectW                                       | [CredUnprotectW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credunprotectw)                                                                       |
| CredWriteA                                           | [CredWriteA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credwritea)                                                                               |
| CredWriteDomainCredentialsA                          | [CredWriteDomainCredentialsA](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credwritedomaincredentialsa)                                             |
| CredWriteDomainCredentialsW                          | [CredWriteDomainCredentialsW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credwritedomaincredentialsw)                                             |
| CredWriteW                                           | [CredWriteW](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credwritew)                                                                               |
| CryptAcquireContextA                                 | [CryptAcquireContextA](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptacquirecontexta)                                                         |
| CryptAcquireContextW                                 | [CryptAcquireContextW](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptacquirecontextw)                                                         |
| CryptContextAddRef                                   | [CryptContextAddRef](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptcontextaddref)                                                             |
| CryptCreateHash                                      | [CryptCreateHash](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptcreatehash)                                                                   |
| CryptDecrypt                                         | [CryptDecrypt](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptdecrypt)                                                                         |
| CryptDeriveKey                                       | [CryptDeriveKey](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptderivekey)                                                                     |
| CryptDestroyHash                                     | [CryptDestroyHash](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptdestroyhash)                                                                 |
| CryptDestroyKey                                      | [CryptDestroyKey](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptdestroykey)                                                                   |
| CryptDuplicateHash                                   | [CryptDuplicateHash](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptduplicatehash)                                                             |
| CryptDuplicateKey                                    | [CryptDuplicateKey](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptduplicatekey)                                                               |
| CryptEncrypt                                         | [CryptEncrypt](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptencrypt)                                                                         |
| CryptEnumProviderTypesA                              | [CryptEnumProviderTypesA](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptenumprovidertypesa)                                                   |
| CryptEnumProviderTypesW                              | [CryptEnumProviderTypesW](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptenumprovidertypesw)                                                   |
| CryptEnumProvidersA                                  | [CryptEnumProvidersA](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptenumprovidersa)                                                           |
| CryptEnumProvidersW                                  | [CryptEnumProvidersW](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptenumprovidersw)                                                           |
| CryptExportKey                                       | [CryptExportKey](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptexportkey)                                                                     |
| CryptGenKey                                          | [CryptGenKey](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgenkey)                                                                           |
| CryptGenRandom                                       | [CryptGenRandom](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgenrandom)                                                                     |
| CryptGetDefaultProviderA                             | [CryptGetDefaultProviderA](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetdefaultprovidera)                                                 |
| CryptGetDefaultProviderW                             | [CryptGetDefaultProviderW](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetdefaultproviderw)                                                 |
| CryptGetHashParam                                    | [CryptGetHashParam](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgethashparam)                                                               |
| CryptGetKeyParam                                     | [CryptGetKeyParam](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetkeyparam)                                                                 |
| CryptGetProvParam                                    | [CryptGetProvParam](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetprovparam)                                                               |
| CryptGetUserKey                                      | [CryptGetUserKey](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetuserkey)                                                                   |
| CryptHashData                                        | [CryptHashData](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-crypthashdata)                                                                       |
| CryptHashSessionKey                                  | [CryptHashSessionKey](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-crypthashsessionkey)                                                           |
| CryptImportKey                                       | [CryptImportKey](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptimportkey)                                                                     |
| CryptReleaseContext                                  | [CryptReleaseContext](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptreleasecontext)                                                           |
| CryptSetHashParam                                    | [CryptSetHashParam](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsethashparam)                                                               |
| CryptSetKeyParam                                     | [CryptSetKeyParam](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetkeyparam)                                                                 |
| CryptSetProvParam                                    | [CryptSetProvParam](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetprovparam)                                                               |
| CryptSetProviderA                                    | [CryptSetProviderA](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetprovidera)                                                               |
| CryptSetProviderExA                                  | [CryptSetProviderExA](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetproviderexa)                                                           |
| CryptSetProviderExW                                  | [CryptSetProviderExW](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetproviderexw)                                                           |
| CryptSetProviderW                                    | [CryptSetProviderW](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetproviderw)                                                               |
| CryptSignHashA                                       | [CryptSignHashA](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsignhasha)                                                                     |
| CryptSignHashW                                       | [CryptSignHashW](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsignhashw)                                                                     |
| CryptVerifySignatureA                                | [CryptVerifySignatureA](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifysignaturea)                                                       |
| CryptVerifySignatureW                                | [CryptVerifySignatureW](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifysignaturew)                                                       |
| CveEventWrite                                        | [CveEventWrite](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-cveeventwrite)                                                                       |
| DecryptFileA                                         | [DecryptFileA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-decryptfilea)                                                                           |
| DecryptFileW                                         | [DecryptFileW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-decryptfilew)                                                                           |
| DeleteAce                                            | [DeleteAce](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-deleteace)                                                                 |
| DeleteService                                        | [DeleteService](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-deleteservice)                                                                           |
| DeregisterEventSource                                | [DeregisterEventSource](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-deregistereventsource)                                                         |
| DestroyPrivateObjectSecurity                         | [DestroyPrivateObjectSecurity](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-destroyprivateobjectsecurity)                           |
| DuplicateEncryptionInfoFile                          | [DuplicateEncryptionInfoFile](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-duplicateencryptioninfofile)                                               |
| DuplicateToken                                       | [DuplicateToken](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-duplicatetoken)                                                       |
| DuplicateTokenEx                                     | [DuplicateTokenEx](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-duplicatetokenex)                                                   |
| ElfBackupEventLogFileA                               | [ElfBackupEventLogFileA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfbackupeventlogfilea)                                                       |
| ElfBackupEventLogFileW                               | [ElfBackupEventLogFileW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfbackupeventlogfilew)                                                       |
| ElfChangeNotify                                      | [ElfChangeNotify](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfchangenotify)                                                                     |
| ElfClearEventLogFileA                                | [ElfClearEventLogFileA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfcleareventlogfilea)                                                         |
| ElfClearEventLogFileW                                | [ElfClearEventLogFileW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfcleareventlogfilew)                                                         |
| ElfCloseEventLog                                     | [ElfCloseEventLog](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfcloseeventlog)                                                                   |
| ElfDeregisterEventSource                             | [ElfDeregisterEventSource](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfderegistereventsource)                                                   |
| ElfFlushEventLog                                     | [ElfFlushEventLog](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfflusheventlog)                                                                   |
| ElfNumberOfRecords                                   | [ElfNumberOfRecords](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfnumberofrecords)                                                               |
| ElfOldestRecord                                      | [ElfOldestRecord](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfoldestrecord)                                                                     |
| ElfOpenBackupEventLogA                               | [ElfOpenBackupEventLogA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfopenbackupeventloga)                                                       |
| ElfOpenBackupEventLogW                               | [ElfOpenBackupEventLogW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfopenbackupeventlogw)                                                       |
| ElfOpenEventLogA                                     | [ElfOpenEventLogA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfopeneventloga)                                                                   |
| ElfOpenEventLogW                                     | [ElfOpenEventLogW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfopeneventlogw)                                                                   |
| ElfReadEventLogA                                     | [ElfReadEventLogA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfreadeventloga)                                                                   |
| ElfReadEventLogW                                     | [ElfReadEventLogW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfreadeventlogw)                                                                   |
| ElfRegisterEventSourceA                              | [ElfRegisterEventSourceA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfregistereventsourcea)                                                     |
| ElfRegisterEventSourceW                              | [ElfRegisterEventSourceW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfregistereventsourcew)                                                     |
| ElfReportEventA                                      | [ElfReportEventA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfreporteventa)                                                                     |
| ElfReportEventAndSourceW                             | [ElfReportEventAndSourceW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfreporteventandsourcew)                                                   |
| ElfReportEventW                                      | [ElfReportEventW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-elfreporteventw)                                                                     |
| EnableTrace                                          | [EnableTrace](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-enabletrace)                                                                           |
| EnableTraceEx                                        | [EnableTraceEx](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-enabletraceex)                                                                       |
| EnableTraceEx2                                       | [EnableTraceEx2](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-enabletraceex2)                                                                     |
| EncryptFileA                                         | [EncryptFileA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-encryptfilea)                                                                           |
| EncryptFileW                                         | [EncryptFileW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-encryptfilew)                                                                           |
| EncryptedFileKeyInfo                                 | [EncryptedFileKeyInfo](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-encryptedfilekeyinfo)                                                             |
| EncryptionDisable                                    | [EncryptionDisable](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-encryptiondisable)                                                                   |
| EnumDependentServicesA                               | [EnumDependentServicesA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumdependentservicesa)                                                         |
| EnumDependentServicesW                               | [EnumDependentServicesW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumdependentservicesw)                                                         |
| EnumDynamicTimeZoneInformation                       | [EnumDynamicTimeZoneInformation](https://learn.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-enumdynamictimezoneinformation)                               |
| EnumServiceGroupW                                    | [EnumServiceGroupW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumservicegroupw)                                                                   |
| EnumServicesStatusA                                  | [EnumServicesStatusA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumservicesstatusa)                                                               |
| EnumServicesStatusExA                                | [EnumServicesStatusExA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumservicesstatusexa)                                                           |
| EnumServicesStatusExW                                | [EnumServicesStatusExW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumservicesstatusexw)                                                           |
| EnumServicesStatusW                                  | [EnumServicesStatusW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumservicesstatusw)                                                               |
| EnumerateTraceGuids                                  | [EnumerateTraceGuids](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-enumeratetraceguids)                                                           |
| EnumerateTraceGuidsEx                                | [EnumerateTraceGuidsEx](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-enumeratetraceguidsex)                                                       |
| EqualDomainSid                                       | [EqualDomainSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-equaldomainsid)                                                       |
| EqualPrefixSid                                       | [EqualPrefixSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-equalprefixsid)                                                       |
| EqualSid                                             | [EqualSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-equalsid)                                                                   |
| EventAccessControl                                   | [EventAccessControl](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventaccesscontrol)                                                             |
| EventAccessQuery                                     | [EventAccessQuery](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventaccessquery)                                                                 |
| EventAccessRemove                                    | [EventAccessRemove](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventaccessremove)                                                               |
| EventActivityIdControl                               | [EventActivityIdControl](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventactivityidcontrol)                                                     |
| EventEnabled                                         | [EventEnabled](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventenabled)                                                                         |
| EventProviderEnabled                                 | [EventProviderEnabled](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventproviderenabled)                                                         |
| EventRegister                                        | [EventRegister](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventregister)                                                                       |
| EventSetInformation                                  | [EventSetInformation](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventsetinformation)                                                           |
| EventUnregister                                      | [EventUnregister](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventunregister)                                                                   |
| EventWrite                                           | [EventWrite](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventwrite)                                                                             |
| EventWriteEndScenario                                | [EventWriteEndScenario](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventwriteendscenario)                                                       |
| EventWriteEx                                         | [EventWriteEx](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventwriteex)                                                                         |
| EventWriteStartScenario                              | [EventWriteStartScenario](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventwritestartscenario)                                                   |
| EventWriteString                                     | [EventWriteString](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventwritestring)                                                                 |
| EventWriteTransfer                                   | [EventWriteTransfer](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-eventwritetransfer)                                                             |
| FileEncryptionStatusA                                | [FileEncryptionStatusA](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-fileencryptionstatusa)                                                           |
| FileEncryptionStatusW                                | [FileEncryptionStatusW](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-fileencryptionstatusw)                                                           |
| FindFirstFreeAce                                     | [FindFirstFreeAce](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-findfirstfreeace)                                                   |
| FlushEfsCache                                        | [FlushEfsCache](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-flushefscache)                                                                           |
| FlushTraceA                                          | [FlushTraceA](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-flushtracea)                                                                           |
| FlushTraceW                                          | [FlushTraceW](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-flushtracew)                                                                           |
| FreeEncryptedFileKeyInfo                             | [FreeEncryptedFileKeyInfo](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-freeencryptedfilekeyinfo)                                                     |
| FreeEncryptedFileMetadata                            | [FreeEncryptedFileMetadata](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-freeencryptedfilemetadata)                                                   |
| FreeEncryptionCertificateHashList                    | [FreeEncryptionCertificateHashList](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-freeencryptioncertificatehashlist)                                   |
| FreeInheritedFromArray                               | [FreeInheritedFromArray](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-freeinheritedfromarray)                                                         |
| FreeSid                                              | [FreeSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-freesid)                                                                     |
| GetAccessPermissionsForObjectA                       | [GetAccessPermissionsForObjectA](https://learn.microsoft.com/en-us/windows/win32/api/aclui/nf-aclui-getaccesspermissionsforobjecta)                                           |
| GetAccessPermissionsForObjectW                       | [GetAccessPermissionsForObjectW](https://learn.microsoft.com/en-us/windows/win32/api/aclui/nf-aclui-getaccesspermissionsforobjectw)                                           |
| GetAce                                               | [GetAce](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getace)                                                                       |
| GetAclInformation                                    | [GetAclInformation](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getaclinformation)                                                 |
| GetAuditedPermissionsFromAclA                        | [GetAuditedPermissionsFromAclA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getauditedpermissionsfromacla)                                           |
| GetAuditedPermissionsFromAclW                        | [GetAuditedPermissionsFromAclW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getauditedpermissionsfromaclw)                                           |
| GetCurrentHwProfileA                                 | [GetCurrentHwProfileA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getcurrenthwprofilea)                                                           |
| GetCurrentHwProfileW                                 | [GetCurrentHwProfileW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getcurrenthwprofilew)                                                           |
| GetDynamicTimeZoneInformationEffectiveYears          | [GetDynamicTimeZoneInformationEffectiveYears](https://learn.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-getdynamictimezoneinformationeffectiveyears)     |
| GetEffectiveRightsFromAclA                           | [GetEffectiveRightsFromAclA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-geteffectiverightsfromacla)                                                 |
| GetEffectiveRightsFromAclW                           | [GetEffectiveRightsFromAclW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-geteffectiverightsfromaclw)                                                 |
| GetEncryptedFileMetadata                             | [GetEncryptedFileMetadata](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-getencryptedfilemetadata)                                                     |
| GetEventLogInformation                               | [GetEventLogInformation](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-geteventloginformation)                                                       |
| GetExplicitEntriesFromAclA                           | [GetExplicitEntriesFromAclA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getexplicitentriesfromacla)                                                 |
| GetExplicitEntriesFromAclW                           | [GetExplicitEntriesFromAclW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getexplicitentriesfromaclw)                                                 |
| GetFileSecurityA                                     | [GetFileSecurityA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getfilesecuritya)                                                                   |
| GetFileSecurityW                                     | [GetFileSecurityW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getfilesecurityw)                                                                   |
| GetInformationCodeAuthzLevelW                        | [GetInformationCodeAuthzLevelW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getinformationcodeauthzlevelw)                                         |
| GetInformationCodeAuthzPolicyW                       | [GetInformationCodeAuthzPolicyW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getinformationcodeauthzpolicyw)                                       |
| GetInheritanceSourceA                                | [GetInheritanceSourceA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getinheritancesourcea)                                                           |
| GetInheritanceSourceW                                | [GetInheritanceSourceW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getinheritancesourcew)                                                           |
| GetKernelObjectSecurity                              | [GetKernelObjectSecurity](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getkernelobjectsecurity)                                     |
| GetLengthSid                                         | [GetLengthSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getlengthsid)                                                           |
| GetLocalManagedApplicationData                       | [GetLocalManagedApplicationData](https://learn.microsoft.com/en-us/windows/win32/api/appmgmt/nf-appmgmt-getlocalmanagedapplicationdata)                                       |
| GetLocalManagedApplications                          | [GetLocalManagedApplications](https://learn.microsoft.com/en-us/windows/win32/api/appmgmt/nf-appmgmt-getlocalmanagedapplications)                                             |
| GetManagedApplicationCategories                      | [GetManagedApplicationCategories](https://learn.microsoft.com/en-us/windows/win32/api/appmgmt/nf-appmgmt-getmanagedapplicationcategories)                                     |
| GetManagedApplications                               | [GetManagedApplications](https://learn.microsoft.com/en-us/windows/win32/api/appmgmt/nf-appmgmt-getmanagedapplications)                                                       |
| GetMultipleTrusteeA                                  | [GetMultipleTrusteeA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getmultipletrusteea)                                                               |
| GetMultipleTrusteeOperationA                         | [GetMultipleTrusteeOperationA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getmultipletrusteeoperationa)                                             |
| GetMultipleTrusteeOperationW                         | [GetMultipleTrusteeOperationW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getmultipletrusteeoperationw)                                             |
| GetMultipleTrusteeW                                  | [GetMultipleTrusteeW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getmultipletrusteew)                                                               |
| GetNamedSecurityInfoA                                | [GetNamedSecurityInfoA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getnamedsecurityinfoa)                                                           |
| GetNamedSecurityInfoExA                              | [GetNamedSecurityInfoExA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getnamedsecurityinfoexa)                                                       |
| GetNamedSecurityInfoExW                              | [GetNamedSecurityInfoExW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getnamedsecurityinfoexw)                                                       |
| GetNamedSecurityInfoW                                | [GetNamedSecurityInfoW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getnamedsecurityinfow)                                                           |
| GetNumberOfEventLogRecords                           | [GetNumberOfEventLogRecords](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getnumberofeventlogrecords)                                               |
| GetOldestEventLogRecord                              | [GetOldestEventLogRecord](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getoldesteventlogrecord)                                                     |
| GetOverlappedAccessResults                           | [GetOverlappedAccessResults](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getoverlappedaccessresults)                                               |
| GetPrivateObjectSecurity                             | [GetPrivateObjectSecurity](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getprivateobjectsecurity)                                   |
| GetSecurityDescriptorControl                         | [GetSecurityDescriptorControl](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsecuritydescriptorcontrol)                           |
| GetSecurityDescriptorDacl                            | [GetSecurityDescriptorDacl](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsecuritydescriptordacl)                                 |
| GetSecurityDescriptorGroup                           | [GetSecurityDescriptorGroup](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsecuritydescriptorgroup)                               |
| GetSecurityDescriptorLength                          | [GetSecurityDescriptorLength](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsecuritydescriptorlength)                             |
| GetSecurityDescriptorOwner                           | [GetSecurityDescriptorOwner](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsecuritydescriptorowner)                               |
| GetSecurityDescriptorRMControl                       | [GetSecurityDescriptorRMControl](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsecuritydescriptorrmcontrol)                       |
| GetSecurityDescriptorSacl                            | [GetSecurityDescriptorSacl](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsecuritydescriptorsacl)                                 |
| GetSecurityInfo                                      | [GetSecurityInfo](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getsecurityinfo)                                                                       |
| GetSecurityInfoExA                                   | [GetSecurityInfoExA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getsecurityinfoexa)                                                                 |
| GetSecurityInfoExW                                   | [GetSecurityInfoExW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getsecurityinfoexw)                                                                 |
| GetServiceDisplayNameA                               | [GetServiceDisplayNameA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-getservicedisplaynamea)                                                         |
| GetServiceDisplayNameW                               | [GetServiceDisplayNameW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-getservicedisplaynamew)                                                         |
| GetServiceKeyNameA                                   | [GetServiceKeyNameA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-getservicekeynamea)                                                                 |
| GetServiceKeyNameW                                   | [GetServiceKeyNameW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-getservicekeynamew)                                                                 |
| GetSidIdentifierAuthority                            | [GetSidIdentifierAuthority](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsididentifierauthority)                                 |
| GetSidLengthRequired                                 | [GetSidLengthRequired](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsidlengthrequired)                                           |
| GetSidSubAuthority                                   | [GetSidSubAuthority](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsidsubauthority)                                               |
| GetSidSubAuthorityCount                              | [GetSidSubAuthorityCount](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getsidsubauthoritycount)                                     |
| GetStringConditionFromBinary                         | [GetStringConditionFromBinary](https://learn.microsoft.com/en-us/windows/win32/api/sddl/nf-sddl-getstringconditionfrombinary)                                                 |
| GetThreadWaitChain                                   | [GetThreadWaitChain](https://learn.microsoft.com/en-us/windows/win32/api/wct/nf-wct-getthreadwaitchain)                                                                       |
| GetTokenInformation                                  | [GetTokenInformation](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-gettokeninformation)                                             |
| GetTraceEnableFlags                                  | [GetTraceEnableFlags](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-gettraceenableflags)                                                           |
| GetTraceEnableLevel                                  | [GetTraceEnableLevel](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-gettraceenablelevel)                                                           |
| GetTraceLoggerHandle                                 | [GetTraceLoggerHandle](https://learn.microsoft.com/en-us/windows/win32/api/evntprov/nf-evntprov-gettraceloggerhandle)                                                         |
| GetTrusteeFormA                                      | [GetTrusteeFormA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-gettrusteeforma)                                                                       |
| GetTrusteeFormW                                      | [GetTrusteeFormW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-gettrusteeformw)                                                                       |
| GetTrusteeNameA                                      | [GetTrusteeNameA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-gettrusteenamea)                                                                       |
| GetTrusteeNameW                                      | [GetTrusteeNameW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-gettrusteenamw)                                                                        |
| GetTrusteeTypeA                                      | [GetTrusteeTypeA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-gettrusteetypea)                                                                       |
| GetTrusteeTypeW                                      | [GetTrusteeTypeW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-gettrusteetypew)                                                                       |
| GetUserNameA                                         | [GetUserNameA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getusernamea)                                                                           |
| GetUserNameW                                         | [GetUserNameW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getusernamew)                                                                           |
| GetWindowsAccountDomainSid                           | [GetWindowsAccountDomainSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getwindowsaccountdomainsid)                               |
| I_QueryTagInformation                                | [I_QueryTagInformation](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_querytaginformation)                                                           |
| I_ScIsSecurityProcess                                | [I_ScIsSecurityProcess](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scissecurityprocess)                                                           |
| I_ScPnPGetServiceName                                | [I_ScPnPGetServiceName](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scpnpgetservicename)                                                           |
| I_ScQueryServiceConfig                               | [I_ScQueryServiceConfig](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scqueryserviceconfig)                                                         |
| I_ScRegisterPreshutdownRestart                       | [I_ScRegisterPreshutdownRestart](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scregisterpreshutdownrestart)                                         |
| I_ScReparseServiceDatabase                           | [I_ScReparseServiceDatabase](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_screparseservicedatabase)                                                 |
| I_ScSendPnPMessage                                   | [I_ScSendPnPMessage](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scsendpnpmessage)                                                                 |
| I_ScSendTSMessage                                    | [I_ScSendTSMessage](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scsendtsmessage)                                                                   |
| I_ScSetServiceBitsA                                  | [I_ScSetServiceBitsA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scsetservicebitsa)                                                               |
| I_ScSetServiceBitsW                                  | [I_ScSetServiceBitsW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scsetservicebitsw)                                                               |
| I_ScValidatePnPService                               | [I_ScValidatePnPService](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-i_scvalidatepnpservice)                                                         |
| IdentifyCodeAuthzLevelW                              | [IdentifyCodeAuthzLevelW](https://learn.microsoft.com/en-us/windows/win32/api/authz/nf-authz-identifycodeauthzlevelw)                                                         |
| ImpersonateAnonymousToken                            | [ImpersonateAnonymousToken](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-impersonateanonymoustoken)                                 |
| ImpersonateLoggedOnUser                              | [ImpersonateLoggedOnUser](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-impersonateloggedonuser)                                     |
| ImpersonateNamedPipeClient                           | [ImpersonateNamedPipeClient](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-impersonatenamedpipeclient)                               |
| ImpersonateSelf                                      | [ImpersonateSelf](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-impersonateself)                                                     |
| InitializeAcl                                        | [InitializeAcl](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-initializeacl)                                                         |
| InitializeSecurityDescriptor                         | [InitializeSecurityDescriptor](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-initializesecuritydescriptor)                           |
| InitializeSid                                        | [InitializeSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-initializesid)                                                         |
| InitiateShutdownA                                    | [InitiateShutdownA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initiateshutdowna)                                                                 |
| InitiateShutdownW                                    | [InitiateShutdownW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initiateshutdownw)                                                                 |
| InitiateSystemShutdownA                              | [InitiateSystemShutdownA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initiatesystemshutdowna)                                                     |
| InitiateSystemShutdownExA                            | [InitiateSystemShutdownExA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initiatesystemshutdownexa)                                                 |
| InitiateSystemShutdownExW                            | [InitiateSystemShutdownExW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initiatesystemshutdownexw)                                                 |
| InitiateSystemShutdownW                              | [InitiateSystemShutdownW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initiatesystemshutdownw)                                                     |
| InstallApplication                                   | [InstallApplication](https://learn.microsoft.com/en-us/windows/win32/api/appmgmt/nf-appmgmt-installapplication)                                                               |
| IsTextUnicode                                        | [IsTextUnicode](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-istextunicode)                                                                         |
| IsTokenRestricted                                    | [IsTokenRestricted](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-istokenrestricted)                                                 |
| IsTokenUntrusted                                     | [IsTokenUntrusted](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-istokenuntrusted)                                                   |
| IsValidAcl                                           | [IsValidAcl](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-isvalidacl)                                                               |
| IsValidRelativeSecurityDescriptor                    | [IsValidRelativeSecurityDescriptor](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-isvalidrelativesecuritydescriptor)                 |
| IsValidSecurityDescriptor                            | [IsValidSecurityDescriptor](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-isvalidsecuritydescriptor)                                 |
| IsValidSid                                           | [IsValidSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-isvalidsid)                                                               |
| IsWellKnownSid                                       | [IsWellKnownSid](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-iswellknownsid)                                                       |
| LockServiceDatabase                                  | [LockServiceDatabase](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-lockservicedatabase)                                                               |
| LogonUserA                                           | [LogonUserA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-logonusera)                                                                               |
| LogonUserExA                                         | [LogonUserExA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-logonuserexa)                                                                           |
| LogonUserExExW                                       | [LogonUserExExW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-logonuserexexw)                                                                       |
| LogonUserExW                                         | [LogonUserExW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-logonuserexw)                                                                           |
| LogonUserW                                           | [LogonUserW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-logonuserw)                                                                               |
| LookupAccountNameA                                   | [LookupAccountNameA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupaccountnamea)                                                               |
| LookupAccountNameW                                   | [LookupAccountNameW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupaccountnamew)                                                               |
| LookupAccountSidA                                    | [LookupAccountSidA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupaccountsida)                                                                 |
| LookupAccountSidW                                    | [LookupAccountSidW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupaccountsidw)                                                                 |
| LookupPrivilegeDisplayNameA                          | [LookupPrivilegeDisplayNameA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegedisplaynamea)                                             |
| LookupPrivilegeDisplayNameW                          | [LookupPrivilegeDisplayNameW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegedisplaynamew)                                             |
| LookupPrivilegeNameA                                 | [LookupPrivilegeNameA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegenamea)                                                           |
| LookupPrivilegeNameW                                 | [LookupPrivilegeNameW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegenamew)                                                           |
| LookupPrivilegeValueA                                | [LookupPrivilegeValueA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegevaluea)                                                         |
| LookupPrivilegeValueW                                | [LookupPrivilegeValueW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-lookupprivilegevaluew)                                                         |
| LookupSecurityDescriptorPartsA                       | [LookupSecurityDescriptorPartsA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-lookupsecuritydescriptorpartsa)                                         |
| LookupSecurityDescriptorPartsW                       | [LookupSecurityDescriptorPartsW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-lookupsecuritydescriptorpartsw)                                         |
| LsaAddAccountRights                                  | [LsaAddAccountRights](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaaddaccountrights)                                                           |
| LsaAddPrivilegesToAccount                            | [LsaAddPrivilegesToAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaaddprivilegestoaccount)                                               |
| LsaClearAuditLog                                     | [LsaClearAuditLog](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaclearauditlog)                                                                 |
| LsaClose                                             | [LsaClose](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaclose)                                                                                 |
| LsaConfigureAutoLogonCredentials                     | [LsaConfigureAutoLogonCredentials](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaconfigureautologoncredentials)                                 |
| LsaCreateAccount                                     | [LsaCreateAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsacreateaccount)                                                                 |
| LsaCreateSecret                                      | [LsaCreateSecret](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsacreatesecret)                                                                   |
| LsaCreateTrustedDomain                               | [LsaCreateTrustedDomain](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsacreatetrusteddomain)                                                     |
| LsaCreateTrustedDomainEx                             | [LsaCreateTrustedDomainEx](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsacreatetrusteddomainex)                                                 |
| LsaDelete                                            | [LsaDelete](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsadelete)                                                                               |
| LsaDeleteTrustedDomain                               | [LsaDeleteTrustedDomain](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsadeletetrusteddomain)                                                     |
| LsaDisablePasswordLessCurrentUser                    | [LsaDisablePasswordLessCurrentUser](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsadisablepasswordlesscurrentuser)                               |
| LsaDisableUserArso                                   | [LsaDisableUserArso](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsadisableuserarso)                                                             |
| LsaEnablePasswordLessCurrentUser                     | [LsaEnablePasswordLessCurrentUser](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenablepasswordlesscurrentuser)                                 |
| LsaEnableUserArso                                    | [LsaEnableUserArso](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenableuserarso)                                                               |
| LsaEnumerateAccountRights                            | [LsaEnumerateAccountRights](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumerateaccountrights)                                               |
| LsaEnumerateAccounts                                 | [LsaEnumerateAccounts](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumerateaccounts)                                                         |
| LsaEnumerateAccountsWithUserRight                    | [LsaEnumerateAccountsWithUserRight](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumerateaccountswithuserright)                               |
| LsaEnumeratePrivileges                               | [LsaEnumeratePrivileges](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumerateprivileges)                                                     |
| LsaEnumeratePrivilegesOfAccount                      | [LsaEnumeratePrivilegesOfAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumerateprivilegesofaccount)                                   |
| LsaEnumerateTrustedDomains                           | [LsaEnumerateTrustedDomains](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumeratetrusteddomains)                                             |
| LsaEnumerateTrustedDomainsEx                         | [LsaEnumerateTrustedDomainsEx](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaenumeratetrusteddomainsex)                                         |
| LsaFreeMemory                                        | [LsaFreeMemory](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsafreememory)                                                                       |
| LsaGetAppliedCAPIDs                                  | [LsaGetAppliedCAPIDs](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsagetappliedcapids)                                                           |
| LsaGetDeviceRegistrationInfo                         | [LsaGetDeviceRegistrationInfo](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsagetdeviceregistrationinfo)                                         |
| LsaGetQuotasForAccount                               | [LsaGetQuotasForAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsagetquotasforaccount)                                                     |
| LsaGetRemoteUserName                                 | [LsaGetRemoteUserName](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsagetremoteusername)                                                         |
| LsaGetSystemAccessAccount                            | [LsaGetSystemAccessAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsagetsystemaccessaccount)                                               |
| LsaGetUserName                                       | [LsaGetUserName](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsagetusername)                                                                     |
| LsaICLookupNames                                     | [LsaICLookupNames](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupnames)                                                                   |
| LsaICLookupNamesWithCreds                            | [LsaICLookupNamesWithCreds](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupnameswithcreds)                                                 |
| LsaICLookupSids                                      | [LsaICLookupSids](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupsids)                                                                     |
| LsaICLookupSidsWithCreds                             | [LsaICLookupSidsWithCreds](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupsidswithcreds)                                                   |
| LsaInvokeTrustScanner                                | [LsaInvokeTrustScanner](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsainvoketrustscanner)                                                       |
| LsaIsUserArsoAllowed                                 | [LsaIsUserArsoAllowed](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaisuserarsoallowed)                                                         |
| LsaIsUserArsoEnabled                                 | [LsaIsUserArsoEnabled](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaisuserarsoenabled)                                                         |
| LsaLookupNames                                       | [LsaLookupNames](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupnames)                                                                     |
| LsaLookupNames2                                      | [LsaLookupNames2](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupnames2)                                                                   |
| LsaLookupPrivilegeDisplayName                        | [LsaLookupPrivilegeDisplayName](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupprivilegedisplayname)                                       |
| LsaLookupPrivilegeName                               | [LsaLookupPrivilegeName](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupprivilegename)                                                     |
| LsaLookupPrivilegeValue                              | [LsaLookupPrivilegeValue](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupprivilegevalue)                                                   |
| LsaLookupSids                                        | [LsaLookupSids](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupsids)                                                                       |
| LsaLookupSids2                                       | [LsaLookupSids2](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsalookupsids2)                                                                     |
| LsaManageSidNameMapping                              | [LsaManageSidNameMapping](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsamanagesidnamemapping)                                                   |
| LsaNtStatusToWinError                                | [LsaNtStatusToWinError](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsantstatustowinerror)                                                       |
| LsaOpenAccount                                       | [LsaOpenAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaopenaccount)                                                                     |
| LsaOpenPolicy                                        | [LsaOpenPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaopenpolicy)                                                                       |
| LsaOpenPolicySce                                     | [LsaOpenPolicySce](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaopenpolicysce)                                                                 |
| LsaOpenSecret                                        | [LsaOpenSecret](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaopensecret)                                                                       |
| LsaOpenTrustedDomain                                 | [LsaOpenTrustedDomain](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaopentrusteddomain)                                                         |
| LsaOpenTrustedDomainByName                           | [LsaOpenTrustedDomainByName](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaopentrusteddomainbyname)                                             |
| LsaProfileDeleted                                    | [LsaProfileDeleted](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaprofiledeleted)                                                               |
| LsaQueryCAPs                                         | [LsaQueryCAPs](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaquerycaps)                                                                         |
| LsaQueryDomainInformationPolicy                      | [LsaQueryDomainInformationPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaquerydomaininformationpolicy)                                   |
| LsaQueryForestTrustInformation                       | [LsaQueryForestTrustInformation](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaqueryforesttrustinformation)                                     |
| LsaQueryForestTrustInformation2                      | [LsaQueryForestTrustInformation2](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaqueryforesttrustinformation2)                                   |
| LsaQueryInfoTrustedDomain                            | [LsaQueryInfoTrustedDomain](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaqueryinfotrusteddomain)                                               |
| LsaQueryInformationPolicy                            | [LsaQueryInformationPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaqueryinformationpolicy)                                               |
| LsaQuerySecret                                       | [LsaQuerySecret](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaquerysecret)                                                                     |
| LsaQuerySecurityObject                               | [LsaQuerySecurityObject](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaquerysecurityobject)                                                     |
| LsaQueryTrustedDomainInfo                            | [LsaQueryTrustedDomainInfo](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaquerytrusteddomaininfo)                                               |
| LsaQueryTrustedDomainInfoByName                      | [LsaQueryTrustedDomainInfoByName](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaquerytrusteddomaininfobyname)                                   |
| LsaRemoveAccountRights                               | [LsaRemoveAccountRights](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaremoveaccountrights)                                                     |
| LsaRemovePrivilegesFromAccount                       | [LsaRemovePrivilegesFromAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaremoveprivilegesfromaccount)                                     |
| LsaRetrievePrivateData                               | [LsaRetrievePrivateData](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaretrieveprivatedata)                                                     |
| LsaSetCAPs                                           | [LsaSetCAPs](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetcaps)                                                                             |
| LsaSetDomainInformationPolicy                        | [LsaSetDomainInformationPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetdomaininformationpolicy)                                       |
| LsaSetForestTrustInformation                         | [LsaSetForestTrustInformation](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetforesttrustinformation)                                         |
| LsaSetForestTrustInformation2                        | [LsaSetForestTrustInformation2](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetforesttrustinformation2)                                       |
| LsaSetInformationPolicy                              | [LsaSetInformationPolicy](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetinformationpolicy)                                                   |
| LsaSetInformationTrustedDomain                       | [LsaSetInformationTrustedDomain](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetinformationtrusteddomain)                                     |
| LsaSetQuotasForAccount                               | [LsaSetQuotasForAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetquotasforaccount)                                                     |
| LsaSetSecret                                         | [LsaSetSecret](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetsecret)                                                                         |
| LsaSetSecurityObject                                 | [LsaSetSecurityObject](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasetsecurityobject)                                                         |
| LsaSetSystemAccessAccount                            | [LsaSetSystemAccessAccount](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lssetsystemaccessaccount)                                                |
| LsaSetTrustedDomainInfoByName                        | [LsaSetTrustedDomainInfoByName](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasettrusteddomaininfobyname)                                       |
| LsaSetTrustedDomainInformation                       | [LsaSetTrustedDomainInformation](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsasettrusteddomaininformation)                                     |
| LsaStorePrivateData                                  | [LsaStorePrivateData](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsastoreprivatedata)                                                           |
| LsaValidateProcUniqueLuid                            | [LsaValidateProcUniqueLuid](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsavalidateprocuniqueluid)                                               |
| MD4Final                                             | [MD4Final](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-md4final)                                                                                 |
| MD4Init                                              | [MD4Init](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-md4init)                                                                                   |
| MD4Update                                            | [MD4Update](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-md4update)                                                                               |
| MD5Final                                             | [MD5Final](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-md5final)                                                                                 |
| MD5Init                                              | [MD5Init](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-md5init)                                                                                   |
| MD5Update                                            | [MD5Update](https://learn.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-md5update)                                                                               |
| MIDL_user_free_Ext                                   | [MIDL_user_free](https://learn.microsoft.com/en-us/windows/win32/api/rpcdce/nf-rpcdce-midl_user_free)                                                                         |
| MSChapSrvChangePassword                              | [MSChapSrvChangePassword](https://learn.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-mschapsrvchangepassword)                                                   |
| MSChapSrvChangePassword2                             | [MSChapSrvChangePassword2](https://learn.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-mschapsrvchangepassword2)                                                 |
| MakeAbsoluteSD                                       | [MakeAbsoluteSD](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-makeabsolutesd)                                                       |
| MakeAbsoluteSD2                                      | [MakeAbsoluteSD2](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-makeabsolutesd2)                                                     |
| MakeSelfRelativeSD                                   | [MakeSelfRelativeSD](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-makeselfrelativesd)                                               |
| MapGenericMask                                       | [MapGenericMask](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-mapgenericmask)                                                       |
| NotifyBootConfigStatus                               | [NotifyBootConfigStatus](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-notifybootconfigstatus)                                                       |
| NotifyChangeEventLog                                 | [NotifyChangeEventLog](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-notifychangeeventlog)                                                           |
| NotifyServiceStatusChange                            | [NotifyServiceStatusChange](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-notifyservicestatuschangew)                                                  |
| NotifyServiceStatusChangeA                           | [NotifyServiceStatusChangeA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-notifyservicestatuschangea)                                                 |
| NotifyServiceStatusChangeW                           | [NotifyServiceStatusChangeW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-notifyservicestatuschangew)                                                 |
| NpGetUserName                                        | [NpGetUserName](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-npgetusername)                                                                         |
| ObjectCloseAuditAlarmA                               | [ObjectCloseAuditAlarmA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-objectcloseauditalarma)                                                       |
| ObjectCloseAuditAlarmW                               | [ObjectCloseAuditAlarmW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-objectcloseauditalarmw)                                                       |
| ObjectDeleteAuditAlarmA                              | [ObjectDeleteAuditAlarmA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-objectdeleteauditalarma)                                                     |
| ObjectDeleteAuditAlarmW                              | [ObjectDeleteAuditAlarmW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-objectdeleteauditalarmw)                                                     |
| ObjectOpenAuditAlarmA                                | [ObjectOpenAuditAlarmA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-objectopenauditalarma)                                                         |
| ObjectOpenAuditAlarmW                                | [ObjectOpenAuditAlarmW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-objectopenauditalarmw)                                                         |
| ObjectPrivilegeAuditAlarmA                           | [ObjectPrivilegeAuditAlarmA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-objectprivilegeauditalarma)                                               |
| ObjectPrivilegeAuditAlarmW                           | [ObjectPrivilegeAuditAlarmW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-objectprivilegeauditalarmw)                                               |
| OpenBackupEventLogA                                  | [OpenBackupEventLogA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openbackupeventloga)                                                             |
| OpenBackupEventLogW                                  | [OpenBackupEventLogW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openbackupeventlogw)                                                             |
| OpenEncryptedFileRawA                                | [OpenEncryptedFileRawA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openencryptedfilerawa)                                                         |
| OpenEncryptedFileRawW                                | [OpenEncryptedFileRawW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openencryptedfileraww)                                                         |
| OpenEventLogA                                        | [OpenEventLogA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openeventloga)                                                                         |
| OpenEventLogW                                        | [OpenEventLogW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-openeventlogw)                                                                         |
| OpenProcessToken                                     | [OpenProcessToken](https://learn.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openprocesstoken)                                               |
| OpenSCManagerA                                       | [OpenSCManagerA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-openscmanagera)                                                                         |
| OpenSCManagerW                                       | [OpenSCManagerW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-openscmanagerw)                                                                         |
| OpenServiceA                                         | [OpenServiceA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-openservicea)                                                                             |
| OpenServiceW                                         | [OpenServiceW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-openservicew)                                                                             |
| OpenThreadToken                                      | [OpenThreadToken](https://learn.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-openthreadtoken)                                                 |
| OpenThreadWaitChainSession                           | [OpenThreadWaitChainSession](https://learn.microsoft.com/en-us/windows/win32/api/wct/nf-wct-openthreadwaitchainsession)                                                       |
| OpenTraceA                                           | [OpenTraceA](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-opentracea)                                                                             |
| OpenTraceW                                           | [OpenTraceW](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-opentracew)                                                                             |
| OperationEnd                                         | [OperationEnd](https://learn.microsoft.com/en-us/windows/win32/api/operationstatus/nf-operationstatus-operationend)                                                           |
| OperationStart                                       | [OperationStart](https://learn.microsoft.com/en-us/windows/win32/api/operationstatus/nf-operationstatus-operationstart)                                                       |
| PerfCloseQueryHandle                                 | [PerfCloseQueryHandle](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfclosequeryhandle)                                                           |
| PerfCreateInstance                                   | [PerfCreateInstance](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfcreateinstance)                                                               |
| PerfDecrementULongCounterValue                       | [PerfDecrementULongCounterValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfdecrementulongcountervalue)                                       |
| PerfDecrementULongLongCounterValue                   | [PerfDecrementULongLongCounterValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfdecrementulonglongcountervalue)                               |
| PerfDeleteCounters                                   | [PerfDeleteCounters](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfdeletecounters)                                                               |
| PerfDeleteInstance                                   | [PerfDeleteInstance](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfdeleteinstance)                                                               |
| PerfEnumerateCounterSet                              | [PerfEnumerateCounterSet](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfenumeratecounterset)                                                     |
| PerfEnumerateCounterSetInstances                     | [PerfEnumerateCounterSetInstances](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfenumeratecountersetinstances)                                   |
| PerfIncrementULongCounterValue                       | [PerfIncrementULongCounterValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfincrementulongcountervalue)                                       |
| PerfIncrementULongLongCounterValue                   | [PerfIncrementULongLongCounterValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfincrementulonglongcountervalue)                               |
| PerfOpenQueryHandle                                  | [PerfOpenQueryHandle](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfopenqueryhandle)                                                             |
| PerfQueryCounterData                                 | [PerfQueryCounterData](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfquerycounterdata)                                                           |
| PerfQueryCounterInfo                                 | [PerfQueryCounterInfo](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfquerycounterinfo)                                                           |
| PerfQueryCounterSetRegistrationInfo                  | [PerfQueryCounterSetRegistrationInfo](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfquerycountersetregistrationinfo)                             |
| PerfQueryInstance                                    | [PerfQueryInstance](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfqueryinstance)                                                                 |
| PerfRegCloseKey                                      | [PerfRegCloseKey](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfregclosekey)                                                                     |
| PerfRegEnumKey                                       | [PerfRegEnumKey](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfregenumkey)                                                                       |
| PerfRegEnumValue                                     | [PerfRegEnumValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfregenumvalue)                                                                   |
| PerfRegQueryInfoKey                                  | [PerfRegQueryInfoKey](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfregqueryinfokey)                                                             |
| PerfRegQueryValue                                    | [PerfRegQueryValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfregqueryvalue)                                                                 |
| PerfRegSetValue                                      | [PerfRegSetValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfregsetvalue)                                                                     |
| PerfSetCounterRefValue                               | [PerfSetCounterRefValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfsetcounterrefvalue)                                                       |
| PerfSetCounterSetInfo                                | [PerfSetCounterSetInfo](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfsetcountersetinfo)                                                         |
| PerfSetULongCounterValue                             | [PerfSetULongCounterValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfsetulongcountervalue)                                                   |
| PerfSetULongLongCounterValue                         | [PerfSetULongLongCounterValue](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfsetulonglongcountervalue)                                           |
| PerfStartProvider                                    | [PerfStartProvider](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfstartprovider)                                                                 |
| PerfStartProviderEx                                  | [PerfStartProviderEx](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfstartproviderex)                                                             |
| PerfStopProvider                                     | [PerfStopProvider](https://learn.microsoft.com/en-us/windows/win32/api/perflib/nf-perflib-perfstopprovider)                                                                   |
| PrivilegeCheck                                       | [PrivilegeCheck](https://learn.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-privilegecheck)                                                                           |
| PrivilegedServiceAuditAlarmA                         | [PrivilegedServiceAuditAlarmA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-privilegedserviceauditalarma)                                           |
| PrivilegedServiceAuditAlarmW                         | [PrivilegedServiceAuditAlarmW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-privilegedserviceauditalarmw)                                           |
| ProcessIdleTasks                                     | [ProcessIdleTasks](https://learn.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-processidletasks)                                                                 |
| ProcessIdleTasksW                                    | [ProcessIdleTasksW](https://learn.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-processidletasks)                                                                |
| ProcessTrace                                         | [ProcessTrace](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-processtrace)                                                                         |
| QueryAllTracesA                                      | [QueryAllTracesA](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-queryalltracesa)                                                                   |
| QueryAllTracesW                                      | [QueryAllTracesW](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-queryalltracesw)                                                                   |
| QueryLocalUserServiceName                            | [QueryLocalUserServiceName](https://learn.microsoft.com/en-us/windows/win32/api/secext/nf-secext-querylocaluserservicename)                                                   |
| QueryRecoveryAgentsOnEncryptedFile                   | [QueryRecoveryAgentsOnEncryptedFile](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-queryrecoveryagentsonencryptedfile)                                 |
| QuerySecurityAccessMask                              | [QuerySecurityAccessMask](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-querysecurityaccessmask)                                     |
| QueryServiceConfig2A                                 | [QueryServiceConfig2A](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryserviceconfig2a)                                                             |
| QueryServiceConfig2W                                 | [QueryServiceConfig2W](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryserviceconfig2w)                                                             |
| QueryServiceConfigA                                  | [QueryServiceConfigA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryserviceconfiga)                                                               |
| QueryServiceConfigW                                  | [QueryServiceConfigW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryserviceconfigw)                                                               |
| QueryServiceDynamicInformation                       | [QueryServiceDynamicInformation](https://learn.microsoft.com/en-us/windows/win32/api/secext/nf-secext-queryservicedynamicinformation)                                         |
| QueryServiceLockStatusA                              | [QueryServiceLockStatusA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryservicelockstatusa)                                                       |
| QueryServiceLockStatusW                              | [QueryServiceLockStatusW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryservicelockstatusw)                                                       |
| QueryServiceObjectSecurity                           | [QueryServiceObjectSecurity](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryserviceobjectsecurity)                                                 |
| QueryServiceStatus                                   | [QueryServiceStatus](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryservicestatus)                                                                 |
| QueryServiceStatusEx                                 | [QueryServiceStatusEx](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryservicestatusex)                                                             |
| QueryTraceA                                          | [QueryTraceA](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-querytracea)                                                                           |
| QueryTraceProcessingHandle                           | [QueryTraceProcessingHandle](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-querytraceprocessinghandle)                                             |
| QueryTraceW                                          | [QueryTraceW](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-querytracew)                                                                           |
| QueryUserServiceName                                 | [QueryUserServiceName](https://learn.microsoft.com/en-us/windows/win32/api/secext/nf-secext-queryuserservicename)                                                             |
| QueryUserServiceNameForContext                       | [QueryUserServiceNameForContext](https://learn.microsoft.com/en-us/windows/win32/api/secext/nf-secext-queryuserservicenameforcontext)                                         |
| QueryUsersOnEncryptedFile                            | [QueryUsersOnEncryptedFile](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-queryusersonencryptedfile)                                                   |
| ReadEncryptedFileRaw                                 | [ReadEncryptedFileRaw](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-readencryptedfileraw)                                                             |
| ReadEventLogA                                        | [ReadEventLogA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-readeventloga)                                                                         |
| ReadEventLogW                                        | [ReadEventLogW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-readeventlogw)                                                                         |
| RegCloseKey                                          | [RegCloseKey](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regclosekey)                                                                               |
| RegConnectRegistryA                                  | [RegConnectRegistryA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regconnectregistrya)                                                               |
| RegConnectRegistryExA                                | [RegConnectRegistryExA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regconnectregistryexa)                                                           |
| RegConnectRegistryExW                                | [RegConnectRegistryExW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regconnectregistryexw)                                                           |
| RegConnectRegistryW                                  | [RegConnectRegistryW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regconnectregistryw)                                                               |
| RegCopyTreeA                                         | [RegCopyTreeA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcopytreea)                                                                             |
| RegCopyTreeW                                         | [RegCopyTreeW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcopytreew)                                                                             |
| RegCreateKeyA                                        | [RegCreateKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeya)                                                                           |
| RegCreateKeyExA                                      | [RegCreateKeyExA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeyexa)                                                                       |
| RegCreateKeyExW                                      | [RegCreateKeyExW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeyexw)                                                                       |
| RegCreateKeyTransactedA                              | [RegCreateKeyTransactedA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeytransacteda)                                                       |
| RegCreateKeyTransactedW                              | [RegCreateKeyTransactedW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeytransactedw)                                                       |
| RegCreateKeyW                                        | [RegCreateKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regcreatekeyw)                                                                           |
| RegDeleteKeyA                                        | [RegDeleteKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeya)                                                                           |
| RegDeleteKeyExA                                      | [RegDeleteKeyExA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeyexa)                                                                       |
| RegDeleteKeyExW                                      | [RegDeleteKeyExW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeyexw)                                                                       |
| RegDeleteKeyTransactedA                              | [RegDeleteKeyTransactedA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeytransacteda)                                                       |
| RegDeleteKeyTransactedW                              | [RegDeleteKeyTransactedW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeytransactedw)                                                       |
| RegDeleteKeyValueA                                   | [RegDeleteKeyValueA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeyvaluea)                                                                 |
| RegDeleteKeyValueW                                   | [RegDeleteKeyValueW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeyvaluew)                                                                 |
| RegDeleteKeyW                                        | [RegDeleteKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletekeyw)                                                                           |
| RegDeleteTreeA                                       | [RegDeleteTreeA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletetreea)                                                                         |
| RegDeleteTreeW                                       | [RegDeleteTreeW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletetreew)                                                                         |
| RegDeleteValueA                                      | [RegDeleteValueA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletevaluea)                                                                       |
| RegDeleteValueW                                      | [RegDeleteValueW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdeletevaluew)                                                                       |
| RegDisablePredefinedCache                            | [RegDisablePredefinedCache](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdisablepredefinedcache)                                                   |
| RegDisablePredefinedCacheEx                          | [RegDisablePredefinedCacheEx](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdisablepredefinedcacheex)                                               |
| RegDisableReflectionKey                              | [RegDisableReflectionKey](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regdisablereflectionkey)                                                       |
| RegEnableReflectionKey                               | [RegEnableReflectionKey](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenablereflectionkey)                                                         |
| RegEnumKeyA                                          | [RegEnumKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenumkeya)                                                                               |
| RegEnumKeyExA                                        | [RegEnumKeyExA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenumkeyexa)                                                                           |
| RegEnumKeyExW                                        | [RegEnumKeyExW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenumkeyexw)                                                                           |
| RegEnumKeyW                                          | [RegEnumKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenumkeyw)                                                                               |
| RegEnumValueA                                        | [RegEnumValueA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenumvaluea)                                                                           |
| RegEnumValueW                                        | [RegEnumValueW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regenumvaluew)                                                                           |
| RegFlushKey                                          | [RegFlushKey](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regflushkey)                                                                               |
| RegGetKeySecurity                                    | [RegGetKeySecurity](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-reggetkeysecurity)                                                                   |
| RegGetValueA                                         | [RegGetValueA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-reggetvaluea)                                                                             |
| RegGetValueW                                         | [RegGetValueW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-reggetvaluew)                                                                             |
| RegLoadAppKeyA                                       | [RegLoadAppKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regloadappkeya)                                                                         |
| RegLoadAppKeyW                                       | [RegLoadAppKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regloadappkeyw)                                                                         |
| RegLoadKeyA                                          | [RegLoadKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regloadkeya)                                                                               |
| RegLoadKeyW                                          | [RegLoadKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regloadkeyw)                                                                               |
| RegLoadMUIStringA                                    | [RegLoadMUIStringA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regloadmuistringa)                                                                   |
| RegLoadMUIStringW                                    | [RegLoadMUIStringW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regloadmuistringw)                                                                   |
| RegNotifyChangeKeyValue                              | [RegNotifyChangeKeyValue](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regnotifychangekeyvalue)                                                       |
| RegOpenCurrentUser                                   | [RegOpenCurrentUser](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopencurrentuser)                                                                 |
| RegOpenKeyA                                          | [RegOpenKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenkeya)                                                                               |
| RegOpenKeyExA                                        | [RegOpenKeyExA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenkeyexa)                                                                           |
| RegOpenKeyExW                                        | [RegOpenKeyExW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenkeyexw)                                                                           |
| RegOpenKeyTransactedA                                | [RegOpenKeyTransactedA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenkeytransacteda)                                                           |
| RegOpenKeyTransactedW                                | [RegOpenKeyTransactedW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenkeytransactedw)                                                           |
| RegOpenKeyW                                          | [RegOpenKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenkeyw)                                                                               |
| RegOpenUserClassesRoot                               | [RegOpenUserClassesRoot](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regopenuserclassesroot)                                                         |
| RegOverridePredefKey                                 | [RegOverridePredefKey](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regoverridepredefkey)                                                             |
| RegQueryInfoKeyA                                     | [RegQueryInfoKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryinfokeya)                                                                     |
| RegQueryInfoKeyW                                     | [RegQueryInfoKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryinfokeyw)                                                                     |
| RegQueryMultipleValuesA                              | [RegQueryMultipleValuesA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regquerymultiplevaluesa)                                                       |
| RegQueryMultipleValuesW                              | [RegQueryMultipleValuesW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regquerymultiplevaluesw)                                                       |
| RegQueryReflectionKey                                | [RegQueryReflectionKey](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryreflectionkey)                                                           |
| RegQueryValueA                                       | [RegQueryValueA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryvaluea)                                                                         |
| RegQueryValueExA                                     | [RegQueryValueExA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryvalueexa)                                                                     |
| RegQueryValueExW                                     | [RegQueryValueExW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryvalueexw)                                                                     |
| RegQueryValueW                                       | [RegQueryValueW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regqueryvaluew)                                                                         |
| RegRenameKey                                         | [RegRenameKey](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regrenamekey)                                                                             |
| RegReplaceKeyA                                       | [RegReplaceKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regreplacekeya)                                                                         |
| RegReplaceKeyW                                       | [RegReplaceKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regreplacekeyw)                                                                         |
| RegRestoreKeyA                                       | [RegRestoreKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regrestorekeya)                                                                         |
| RegRestoreKeyW                                       | [RegRestoreKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg-regrestorekeyw)                                                                                   |
| RegSaveKeyA                                          | [RegSaveKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regsavekeya)                                                                               |
| RegSaveKeyExA                                        | [RegSaveKeyExA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regsavekeyexa)                                                                           |
| RegSaveKeyExW                                        | [RegSaveKeyExW](https://learn.microsoft.com/en-us/windows/win32/api/winreg-nf-winreg-regsavekeyexw)                                                                           |
| RegSaveKeyW                                          | [RegSaveKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regsavekeyw)                                                                               |
| RegSetKeySecurity                                    | [RegSetKeySecurity](https://learn.microsoft.com/en-us/windows/win32/api/winreg-nf-winreg-regsetkeysecurity)                                                                   |
| RegSetKeyValueA                                      | [RegSetKeyValueA](https://learn.microsoft.com/en-us/windows/win32/api/winreg-nf-winreg-regsetkeyvaluea)                                                                       |
| RegSetKeyValueW                                      | [RegSetKeyValueW](https://learn.microsoft.com/en-us/windows/win32/api/winreg-nf-winreg-regsetkeyvaluew)                                                                       |
| RegSetValueA                                         | [RegSetValueA](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regsetvaluea)                                                                             |
| RegSetValueExA                                       | [RegSetValueExA](https://learn.microsoft.com/en-us/windows/win32/api/winreg-nf-winreg-regsetvalueexa)                                                                         |
| RegSetValueExW                                       | [RegSetValueExW](https://learn.microsoft.com/en-us/windows/win32/api/winreg-nf-winreg-regsetvalueexw)                                                                         |
| RegSetValueW                                         | [RegSetValueW](https://learn.microsoft.com/en-us/windows/win32/api/winreg/nf-winreg-regsetvaluew)                                                                             |
| RegUnLoadKeyA                                        | [RegUnLoadKeyA](https://learn.microsoft.com/en-us/windows/win32/api/winreg-nf-winreg-regunloadkeya)                                                                           |
| RegUnLoadKeyW                                        | [RegUnLoadKeyW](https://learn.microsoft.com/en-us/windows/win32/api/winreg-nf-winreg-regunloadkeyw)                                                                           |
| RegisterEventSourceA                                 | [RegisterEventSourceA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-registereventsourcea)                                                           |
| RegisterEventSourceW                                 | [RegisterEventSourceW](https://learn.microsoft.com/en-us/windows/win32/api/winbase-nf-winbase-registereventsourcew)                                                           |
| RegisterIdleTask                                     | [RegisterIdleTask](https://learn.microsoft.com/en-us/windows/win32/api/realtimeapiset-nf-realtimeapiset-registeridletask)                                                     |
| RegisterServiceCtrlHandlerA                          | [RegisterServiceCtrlHandlerA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-registerservicectrlhandlera)                                               |
| RegisterServiceCtrlHandlerExA                        | [RegisterServiceCtrlHandlerExA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc-nf-winsvc-registerservicectrlhandlerexa)                                           |
| RegisterServiceCtrlHandlerExW                        | [RegisterServiceCtrlHandlerExW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc-nf-winsvc-registerservicectrlhandlerexw)                                           |
| RegisterServiceCtrlHandlerW                          | [RegisterServiceCtrlHandlerW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc-nf-winsvc-registerservicectrlhandlerw)                                               |
| RegisterTraceGuidsA                                  | [RegisterTraceGuidsA](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-registertraceguidsa)                                                           |
| RegisterTraceGuidsW                                  | [RegisterTraceGuidsW](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-registertraceguidsw)                                                           |
| RegisterWaitChainCOMCallback                         | [RegisterWaitChainCOMCallback](https://learn.microsoft.com/en-us/windows/win32/api/wct/nf-wct-registerwaitchaincomcallback)                                                   |
| RemoveTraceCallback                                  | [RemoveTraceCallback](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-removetracecallback)                                                           |
| ReportEventA                                         | [ReportEventA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-reporteventa)                                                                           |
| ReportEventW                                         | [ReportEventW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-reporteventw)                                                                           |
| RevertToSelf                                         | [RevertToSelf](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-reverttoself)                                                           |
| SaferCloseLevel                                      | [SaferCloseLevel](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safercloselevel)                                                                   |
| SaferComputeTokenFromLevel                           | [SaferComputeTokenFromLevel](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safercomputetokenfromlevel)                                             |
| SaferCreateLevel                                     | [SaferCreateLevel](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safercreatelevel)                                                                 |
| SaferGetLevelInformation                             | [SaferGetLevelInformation](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safergetlevelinformation)                                                 |
| SaferGetPolicyInformation                            | [SaferGetPolicyInformation](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safergetpolicyinformation)                                               |
| SaferIdentifyLevel                                   | [SaferIdentifyLevel](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-saferidentifylevel)                                                             |
| SaferRecordEventLogEntry                             | [SaferRecordEventLogEntry](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-saferrecordeventlogentry)                                                 |
| SaferSetLevelInformation                             | [SaferSetLevelInformation](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safersetlevelinformation)                                                 |
| SaferSetPolicyInformation                            | [SaferSetPolicyInformation](https://learn.microsoft.com/en-us/windows/win32/api/winsafer/nf-winsafer-safersetpolicyinformation)                                               |
| SetAclInformation                                    | [SetAclInformation](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-setaclinformation)                                                 |
| SetFileSecurityA                                     | [SetFileSecurityA](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setfilesecuritya)                                                                   |
| SetFileSecurityW                                     | [SetFileSecurityW](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setfilesecurityw)                                                                   |
| SetKernelObjectSecurity                              | [SetKernelObjectSecurity](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-setkernelobjectsecurity)                                     |
| SetNamedSecurityInfoA                                | [SetNamedSecurityInfoA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-setnamedsecurityinfoa)                                                           |
| SetNamedSecurityInfoExA                              | [SetNamedSecurityInfoExA](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-setnamedsecurityinfoexa)                                                       |
| SetNamedSecurityInfoExW                              | [SetNamedSecurityInfoExW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-setnamedsecurityinfoexw)                                                       |
| SetNamedSecurityInfoW                                | [SetNamedSecurityInfoW](https://learn.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-setnamedsecurityinfow)                                                           |
| SetServiceBits                                       | [SetServiceBits](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-setservicebits)                                                                         |
| SetServiceObjectSecurity                             | [SetServiceObjectSecurity](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-setserviceobjectsecurity)                                                     |
| SetThreadToken                                       | [SetThreadToken](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-setthreadtoken)                                                       |
| SetTokenInformation                                  | [SetTokenInformation](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-settokeninformation)                                             |
| StartServiceA                                        | [StartServiceA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-startservicea)                                                                           |
| StartServiceCtrlDispatcherA                          | [StartServiceCtrlDispatcherA](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-startservicectrldispatchera)                                               |
| StartServiceCtrlDispatcherW                          | [StartServiceCtrlDispatcherW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-startservicectrldispatcherw)                                               |
| StartServiceW                                        | [StartServiceW](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-startservicew)                                                                           |
| StopTraceA                                           | [StopTraceA](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-stoptracea)                                                                             |
| StopTraceW                                           | [StopTraceW](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-stoptracew)                                                                             |
| SystemFunction001                                    | [SystemFunction001](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction002                                    | [SystemFunction002](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction003                                    | [SystemFunction003](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction004                                    | [SystemFunction004](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction005                                    | [SystemFunction005](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction006                                    | [SystemFunction006](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction007                                    | [SystemFunction007](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction008                                    | [SystemFunction008](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction009                                    | [SystemFunction009](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction010                                    | [SystemFunction010](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction011                                    | [SystemFunction011](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction012                                    | [SystemFunction012](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction013                                    | [SystemFunction013](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction014                                    | [SystemFunction014](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction015                                    | [SystemFunction015](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction016                                    | [SystemFunction016](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction017                                    | [SystemFunction017](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction018                                    | [SystemFunction018](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| SystemFunction019                                    | [SystemFunction019](https://learn.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsarqsecret)                                                                     |
| TraceEvent                                           | [TraceEvent](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-traceevent)                                                                             |
| TraceEventInstance                                   | [TraceEventInstance](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-traceeventinstance)                                                             |
| TraceMessage                                         | [TraceMessage](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-tracemessage)                                                                         |
| TraceMessageVa                                       | [TraceMessageVa](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-tracemessageva)                                                                     |
| TraceQueryInformation                                | [TraceQueryInformation](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-tracequeryinformation)                                                       |
| TraceSetInformation                                  | [TraceSetInformation](https://learn.microsoft.com/en-us/windows/win32/api/evntrace/nf-evntrace-tracesetinformation)                                                           |
| WmiCloseBlock                                        | [WmiCloseBlock](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmicloseblock)                                                                                 |
| WmiDevInstToInstanceNameA                            | [WmiDevInstToInstanceNameA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmidevinsttoinstancenamea)                                                         |
| WmiDevInstToInstanceNameW                            | [WmiDevInstToInstanceNameW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmidevinsttoinstancenamew)                                                         |
| WmiEnumerateGuids                                    | [WmiEnumerateGuids](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmienumerateguids)                                                                         |
| WmiExecuteMethodA                                    | [WmiExecuteMethodA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiexecutemethoda)                                                                         |
| WmiExecuteMethodW                                    | [WmiExecuteMethodW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiexecutemethodw)                                                                         |
| WmiFileHandleToInstanceNameA                         | [WmiFileHandleToInstanceNameA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmifilehandletoinstancenamea)                                                   |
| WmiFileHandleToInstanceNameW                         | [WmiFileHandleToInstanceNameW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmifilehandletoinstancenamew)                                                   |
| WmiFreeBuffer                                        | [WmiFreeBuffer](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmifreebuffer)                                                                                 |
| WmiMofEnumerateResourcesA                            | [WmiMofEnumerateResourcesA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmimofenumerateresourcesa)                                                         |
| WmiMofEnumerateResourcesW                            | [WmiMofEnumerateResourcesW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmimofenumerateresourcesw)                                                         |
| WmiNotificationRegistrationA                         | [WmiNotificationRegistrationA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wminotificationregistrationa)                                                   |
| WmiNotificationRegistrationW                         | [WmiNotificationRegistrationW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wminotificationregistrationw)                                                   |
| WmiOpenBlock                                         | [WmiOpenBlock](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiopenblock)                                                                                   |
| WmiQueryAllDataA                                     | [WmiQueryAllDataA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiqueryalldataa)                                                                           |
| WmiQueryAllDataMultipleA                             | [WmiQueryAllDataMultipleA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiqueryalldatamultiplea)                                                           |
| WmiQueryAllDataMultipleW                             | [WmiQueryAllDataMultipleW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiqueryalldatamultiplew)                                                           |
| WmiQueryAllDataW                                     | [WmiQueryAllDataW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiqueryalldataw)                                                                           |
| WmiQueryGuidInformation                              | [WmiQueryGuidInformation](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiqueryguidinformation)                                                             |
| WmiQuerySingleInstanceA                              | [WmiQuerySingleInstanceA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiquerysingleinstancea)                                                             |
| WmiQuerySingleInstanceMultipleA                      | [WmiQuerySingleInstanceMultipleA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiquerysingleinstancemultiplea)                                             |
| WmiQuerySingleInstanceMultipleW                      | [WmiQuerySingleInstanceMultipleW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiquerysingleinstancemultiplew)                                             |
| WmiQuerySingleInstanceW                              | [WmiQuerySingleInstanceW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmiquerysingleinstancew)                                                             |
| WmiReceiveNotificationsA                             | [WmiReceiveNotificationsA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmireceivenotificationsa)                                                           |
| WmiReceiveNotificationsW                             | [WmiReceiveNotificationsW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmireceivenotificationsw)                                                           |
| WmiSetSingleInstanceA                                | [WmiSetSingleInstanceA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmisetsingleinstancea)                                                                 |
| WmiSetSingleInstanceW                                | [WmiSetSingleInstanceW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmisetsingleinstancew)                                                                 |
| WmiSetSingleItemA                                    | [WmiSetSingleItemA](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmisetsingleitema)                                                                         |
| WmiSetSingleItemW                                    | [WmiSetSingleItemW](https://learn.microsoft.com/en-us/windows/win32/api/wmi/nf-wmi-wmisetsingleitemw)                                                                         |
| WriteEncryptedFileRaw                                | [WriteEncryptedFileRaw](https://learn.microsoft.com/en-us/windows/win32/api/winefs/nf-winefs-writeencryptedfileraw)                                                           |

---

## advpack.dll

#### Export table:

```
1   0x00005b80 0x165005b80 GLOBAL FUNC 0    ADVPACK.dll DelNodeRunDLL32
2   0x00005b80 0x165005b80 GLOBAL FUNC 0    ADVPACK.dll DelNodeRunDLL32A
3   0x00006350 0x165006350 GLOBAL FUNC 0    ADVPACK.dll DoInfInstall
4   0x00006350 0x165006350 GLOBAL FUNC 0    ADVPACK.dll DoInfInstallA
5   0x00006440 0x165006440 GLOBAL FUNC 0    ADVPACK.dll DoInfInstallW
6   0x000178a0 0x1650178a0 GLOBAL FUNC 0    ADVPACK.dll FileSaveRestore
7   0x000178a0 0x1650178a0 GLOBAL FUNC 0    ADVPACK.dll FileSaveRestoreA
8   0x000092f0 0x1650092f0 GLOBAL FUNC 0    ADVPACK.dll LaunchINFSectionA
9   0x0000e600 0x16500e600 GLOBAL FUNC 0    ADVPACK.dll LaunchINFSectionEx
10  0x0000e600 0x16500e600 GLOBAL FUNC 0    ADVPACK.dll LaunchINFSectionExA
11  0x0000a5e0 0x16500a5e0 GLOBAL FUNC 0    ADVPACK.dll RegisterOCX
12  0x0000a410 0x16500a410 GLOBAL FUNC 0    ADVPACK.dll RegisterOCXW
13  0x00019140 0x165019140 GLOBAL FUNC 0    ADVPACK.dll AddDelBackupEntry
14  0x00019140 0x165019140 GLOBAL FUNC 0    ADVPACK.dll AddDelBackupEntryA
15  0x00019220 0x165019220 GLOBAL FUNC 0    ADVPACK.dll AddDelBackupEntryW
16  0x00002300 0x165002300 GLOBAL FUNC 0    ADVPACK.dll AdvInstallFile
17  0x00002300 0x165002300 GLOBAL FUNC 0    ADVPACK.dll AdvInstallFileA
18  0x00002410 0x165002410 GLOBAL FUNC 0    ADVPACK.dll AdvInstallFileW
19  0x00010a00 0x165010a00 GLOBAL FUNC 0    ADVPACK.dll CloseINFEngine
20  0x0000c150 0x16500c150 GLOBAL FUNC 0    ADVPACK.dll DelNode
21  0x0000c150 0x16500c150 GLOBAL FUNC 0    ADVPACK.dll DelNodeA
22  0x0000c1b0 0x16500c1b0 GLOBAL FUNC 0    ADVPACK.dll DelNodeRunDLL32W
23  0x0000c220 0x16500c220 GLOBAL FUNC 0    ADVPACK.dll DelNodeW
24  0x00010a30 0x165010a30 GLOBAL FUNC 0    ADVPACK.dll ExecuteCab
25  0x00010a30 0x165010a30 GLOBAL FUNC 0    ADVPACK.dll ExecuteCabA
26  0x00010b90 0x165010b90 GLOBAL FUNC 0    ADVPACK.dll ExecuteCabW
27  0x00013700 0x165013700 GLOBAL FUNC 0    ADVPACK.dll ExtractFiles
28  0x00013700 0x165013700 GLOBAL FUNC 0    ADVPACK.dll ExtractFilesA
29  0x00013b40 0x165013b40 GLOBAL FUNC 0    ADVPACK.dll ExtractFilesW
30  0x00019230 0x165019230 GLOBAL FUNC 0    ADVPACK.dll FileSaveMarkNotExist
31  0x00019230 0x165019230 GLOBAL FUNC 0    ADVPACK.dll FileSaveMarkNotExistA
32  0x00019300 0x165019300 GLOBAL FUNC 0    ADVPACK.dll FileSaveMarkNotExistW
33  0x000113a0 0x1650113a0 GLOBAL FUNC 0    ADVPACK.dll FileSaveRestoreOnINF
34  0x000113a0 0x1650113a0 GLOBAL FUNC 0    ADVPACK.dll FileSaveRestoreOnINFA
35  0x000114e0 0x1650114e0 GLOBAL FUNC 0    ADVPACK.dll FileSaveRestoreOnINFW
36  0x00019320 0x165019320 GLOBAL FUNC 0    ADVPACK.dll FileSaveRestoreW
37  0x0000c650 0x16500c650 GLOBAL FUNC 0    ADVPACK.dll GetVersionFromFile
38  0x0000c650 0x16500c650 GLOBAL FUNC 0    ADVPACK.dll GetVersionFromFileA
39  0x0000c6e0 0x16500c6e0 GLOBAL FUNC 0    ADVPACK.dll GetVersionFromFileEx
40  0x0000c6e0 0x16500c6e0 GLOBAL FUNC 0    ADVPACK.dll GetVersionFromFileExA
41  0x0000c760 0x16500c760 GLOBAL FUNC 0    ADVPACK.dll GetVersionFromFileExW
42  0x0000c830 0x16500c830 GLOBAL FUNC 0    ADVPACK.dll GetVersionFromFileW
43  0x00011830 0x165011830 GLOBAL FUNC 0    ADVPACK.dll IsNTAdmin
44  0x0000ca80 0x16500ca80 GLOBAL FUNC 0    ADVPACK.dll LaunchINFSection
45  0x00011a00 0x165011a00 GLOBAL FUNC 0    ADVPACK.dll LaunchINFSectionExW
46  0x0000ca90 0x16500ca90 GLOBAL FUNC 0    ADVPACK.dll LaunchINFSectionW
47  0x0000ce50 0x16500ce50 GLOBAL FUNC 0    ADVPACK.dll NeedReboot
48  0x0000ce90 0x16500ce90 GLOBAL FUNC 0    ADVPACK.dll NeedRebootInit
49  0x00011bf0 0x165011bf0 GLOBAL FUNC 0    ADVPACK.dll OpenINFEngine
50  0x00011bf0 0x165011bf0 GLOBAL FUNC 0    ADVPACK.dll OpenINFEngineA
51  0x00011cb0 0x165011cb0 GLOBAL FUNC 0    ADVPACK.dll OpenINFEngineW
52  0x00011dc0 0x165011dc0 GLOBAL FUNC 0    ADVPACK.dll RebootCheckOnInstall
53  0x00011dc0 0x165011dc0 GLOBAL FUNC 0    ADVPACK.dll RebootCheckOnInstallA
54  0x00011e80 0x165011e80 GLOBAL FUNC 0    ADVPACK.dll RebootCheckOnInstallW
55  0x00003d90 0x165003d90 GLOBAL FUNC 0    ADVPACK.dll RegInstall
56  0x00003d90 0x165003d90 GLOBAL FUNC 0    ADVPACK.dll RegInstallA
57  0x00003e30 0x165003e30 GLOBAL FUNC 0    ADVPACK.dll RegInstallW
58  0x00015f90 0x165015f90 GLOBAL FUNC 0    ADVPACK.dll RegRestoreAll
59  0x00015f90 0x165015f90 GLOBAL FUNC 0    ADVPACK.dll RegRestoreAllA
60  0x00016010 0x165016010 GLOBAL FUNC 0    ADVPACK.dll RegRestoreAllW
61  0x000160a0 0x1650160a0 GLOBAL FUNC 0    ADVPACK.dll RegSaveRestore
62  0x000160a0 0x1650160a0 GLOBAL FUNC 0    ADVPACK.dll RegSaveRestoreA
63  0x00012000 0x165012000 GLOBAL FUNC 0    ADVPACK.dll RegSaveRestoreOnINF
64  0x00012000 0x165012000 GLOBAL FUNC 0    ADVPACK.dll RegSaveRestoreOnINFA
65  0x00012110 0x165012110 GLOBAL FUNC 0    ADVPACK.dll RegSaveRestoreOnINFW
66  0x000161c0 0x1650161c0 GLOBAL FUNC 0    ADVPACK.dll RegSaveRestoreW
67  0x0000cec0 0x16500cec0 GLOBAL FUNC 0    ADVPACK.dll RunSetupCommand
68  0x0000cec0 0x16500cec0 GLOBAL FUNC 0    ADVPACK.dll RunSetupCommandA
69  0x0000cfe0 0x16500cfe0 GLOBAL FUNC 0    ADVPACK.dll RunSetupCommandW
70  0x00012320 0x165012320 GLOBAL FUNC 0    ADVPACK.dll SetPerUserSecValues
71  0x00012320 0x165012320 GLOBAL FUNC 0    ADVPACK.dll SetPerUserSecValuesA
72  0x00012480 0x165012480 GLOBAL FUNC 0    ADVPACK.dll SetPerUserSecValuesW
73  0x0000d1d0 0x16500d1d0 GLOBAL FUNC 0    ADVPACK.dll TranslateInfString
74  0x0000d1d0 0x16500d1d0 GLOBAL FUNC 0    ADVPACK.dll TranslateInfStringA
75  0x00012b70 0x165012b70 GLOBAL FUNC 0    ADVPACK.dll TranslateInfStringEx
76  0x00012b70 0x165012b70 GLOBAL FUNC 0    ADVPACK.dll TranslateInfStringExA
77  0x00012d00 0x165012d00 GLOBAL FUNC 0    ADVPACK.dll TranslateInfStringExW
78  0x0000d360 0x16500d360 GLOBAL FUNC 0    ADVPACK.dll TranslateInfStringW
79  0x00012d70 0x165012d70 GLOBAL FUNC 0    ADVPACK.dll UserInstStubWrapper
80  0x00012d70 0x165012d70 GLOBAL FUNC 0    ADVPACK.dll UserInstStubWrapperA
81  0x00012df0 0x165012df0 GLOBAL FUNC 0    ADVPACK.dll UserInstStubWrapperW
82  0x00013190 0x165013190 GLOBAL FUNC 0    ADVPACK.dll UserUnInstStubWrapper
83  0x00013190 0x165013190 GLOBAL FUNC 0    ADVPACK.dll UserUnInstStubWrapperA
84  0x00013210 0x165013210 GLOBAL FUNC 0    ADVPACK.dll UserUnInstStubWrapperW
```

#### Exported Functions and Documentation

| Exported Function      | Documentation Link                                                                                                     |
|------------------------|------------------------------------------------------------------------------------------------------------------------|
| DelNodeRunDLL32        | [DelNodeRunDLL32](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-delnoderundll32)              |
| DelNodeRunDLL32A       | [DelNodeRunDLL32A](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-delnoderundll32a)            |
| DoInfInstall           | [DoInfInstall](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-doinfinstall)                    |
| DoInfInstallA          | [DoInfInstallA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-doinfinstall)                   |
| DoInfInstallW          | [DoInfInstallW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-doinfinstall)                   |
| FileSaveRestore        | [FileSaveRestore](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesaverestore)              |
| FileSaveRestoreA       | [FileSaveRestoreA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesaverestore)             |
| LaunchINFSectionA      | [LaunchINFSectionA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-launchinfsectiona)          |
| LaunchINFSectionEx     | [LaunchINFSectionEx](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-launchinfsectionex)        |
| LaunchINFSectionExA    | [LaunchINFSectionExA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-launchinfsectionex)       |
| RegisterOCX            | [RegisterOCX](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-registerocx)                      |
| RegisterOCXW           | [RegisterOCXW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-registerocx)                     |
| AddDelBackupEntry      | [AddDelBackupEntry](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-adddelbackupentry)          |
| AddDelBackupEntryA     | [AddDelBackupEntryA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-adddelbackupentry)         |
| AddDelBackupEntryW     | [AddDelBackupEntryW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-adddelbackupentry)         |
| AdvInstallFile         | [AdvInstallFile](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-advinstallfile)                |
| AdvInstallFileA        | [AdvInstallFileA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-advinstallfile)               |
| AdvInstallFileW        | [AdvInstallFileW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-advinstallfile)               |
| CloseINFEngine         | [CloseINFEngine](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-closeinfengine)                |
| DelNode                | [DelNode](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-delnode)                              |
| DelNodeA               | [DelNodeA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-delnode)                             |
| DelNodeRunDLL32W       | [DelNodeRunDLL32W](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-delnoderundll32w)            |
| DelNodeW               | [DelNodeW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-delnode)                             |
| ExecuteCab             | [ExecuteCab](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-executecab)                        |
| ExecuteCabA            | [ExecuteCabA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-executecab)                       |
| ExecuteCabW            | [ExecuteCabW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-executecab)                       |
| ExtractFiles           | [ExtractFiles](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-extractfiles)                    |
| ExtractFilesA          | [ExtractFilesA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-extractfiles)                   |
| ExtractFilesW          | [ExtractFilesW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-extractfiles)                   |
| FileSaveMarkNotExist   | [FileSaveMarkNotExist](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesavemarknotexist)    |
| FileSaveMarkNotExistA  | [FileSaveMarkNotExistA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesavemarknotexist)   |
| FileSaveMarkNotExistW  | [FileSaveMarkNotExistW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesavemarknotexist)   |
| FileSaveRestoreOnINF   | [FileSaveRestoreOnINF](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesaverestoreoninf)    |
| FileSaveRestoreOnINFA  | [FileSaveRestoreOnINFA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesaverestoreoninf)   |
| FileSaveRestoreOnINFW  | [FileSaveRestoreOnINFW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesaverestoreoninf)   |
| FileSaveRestoreW       | [FileSaveRestoreW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-filesaverestore)             |
| GetVersionFromFile     | [GetVersionFromFile](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-getversionfromfile)        |
| GetVersionFromFileA    | [GetVersionFromFileA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-getversionfromfile)       |
| GetVersionFromFileEx   | [GetVersionFromFileEx](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-getversionfromfileex)    |
| GetVersionFromFileExA  | [GetVersionFromFileExA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-getversionfromfileex)   |
| GetVersionFromFileExW  | [GetVersionFromFileExW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-getversionfromfileex)   |
| GetVersionFromFileW    | [GetVersionFromFileW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-getversionfromfile)       |
| IsNTAdmin              | [IsNTAdmin](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-isntadmin)                          |
| LaunchINFSection       | [LaunchINFSection](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-launchinfsection)            |
| LaunchINFSectionExW    | [LaunchINFSectionExW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-launchinfsectionex)       |
| LaunchINFSectionW      | [LaunchINFSectionW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-launchinfsection)           |
| NeedReboot             | [NeedReboot](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-needreboot)                        |
| NeedRebootInit         | [NeedRebootInit](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-needrebootinit)                |
| OpenINFEngine          | [OpenINFEngine](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-openinfengine)                  |
| OpenINFEngineA         | [OpenINFEngineA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-openinfengine)                 |
| OpenINFEngineW         | [OpenINFEngineW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-openinfengine)                 |
| RebootCheckOnInstall   | [RebootCheckOnInstall](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-rebootcheckoninstall)    |
| RebootCheckOnInstallA  | [RebootCheckOnInstallA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-rebootcheckoninstall)   |
| RebootCheckOnInstallW  | [RebootCheckOnInstallW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-rebootcheckoninstall)   |
| RegInstall             | [RegInstall](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-reginstall)                        |
| RegInstallA            | [RegInstallA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-reginstall)                       |
| RegInstallW            | [RegInstallW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-reginstall)                       |
| RegRestoreAll          | [RegRestoreAll](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regrestoreall)                  |
| RegRestoreAllA         | [RegRestoreAllA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regrestoreall)                 |
| RegRestoreAllW         | [RegRestoreAllW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regrestoreall)                 |
| RegSaveRestore         | [RegSaveRestore](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regsaverestore)                |
| RegSaveRestoreA        | [RegSaveRestoreA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regsaverestore)               |
| RegSaveRestoreOnINF    | [RegSaveRestoreOnINF](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regsaverestoreoninf)      |
| RegSaveRestoreOnINFA   | [RegSaveRestoreOnINFA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regsaverestoreoninf)     |
| RegSaveRestoreOnINFW   | [RegSaveRestoreOnINFW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regsaverestoreoninf)     |
| RegSaveRestoreW        | [RegSaveRestoreW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-regsaverestore)               |
| RunSetupCommand        | [RunSetupCommand](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-runsetupcommand)              |
| RunSetupCommandA       | [RunSetupCommandA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-runsetupcommand)             |
| RunSetupCommandW       | [RunSetupCommandW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-runsetupcommand)             |
| SetPerUserSecValues    | [SetPerUserSecValues](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-setperusersecvalues)      |
| SetPerUserSecValuesA   | [SetPerUserSecValuesA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-setperusersecvalues)     |
| SetPerUserSecValuesW   | [SetPerUserSecValuesW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-setperusersecvalues)     |
| TranslateInfString     | [TranslateInfString](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-translateinfstring)        |
| TranslateInfStringA    | [TranslateInfStringA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-translateinfstring)       |
| TranslateInfStringEx   | [TranslateInfStringEx](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-translateinfstringex)    |
| TranslateInfStringExA  | [TranslateInfStringExA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-translateinfstringex)   |
| TranslateInfStringExW  | [TranslateInfStringExW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-translateinfstringex)   |
| TranslateInfStringW    | [TranslateInfStringW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-translateinfstring)       |
| UserInstStubWrapper    | [UserInstStubWrapper](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-userinststubwrapper)      |
| UserInstStubWrapper    | [UserInstStubWrapper](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-userinststubwrapper)      |
| UserInstStubWrapperA   | [UserInstStubWrapperA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-userinststubwrapper)     |
| UserInstStubWrapperW   | [UserInstStubWrapperW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-userinststubwrapper)     |
| UserUnInstStubWrapper  | [UserUnInstStubWrapper](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-useruninststubwrapper)  |
| UserUnInstStubWrapperA | [UserUnInstStubWrapperA](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-useruninststubwrapper) |
| UserUnInstStubWrapperW | [UserUnInstStubWrapperW](https://learn.microsoft.com/en-us/windows/win32/api/advpack/nf-advpack-useruninststubwrapper) |

---

## aeinv.dll

#### Export table:

```
1   0x0005b850 0x18005b850 GLOBAL FUNC 0    AEINV.dll CreateAppxPackageInventory
2   0x0005bbb0 0x18005bbb0 GLOBAL FUNC 0    AEINV.dll CreateAppxPackageInventoryExtracted
3   0x0005c000 0x18005c000 GLOBAL FUNC 0    AEINV.dll CreateSoftwareInventory
4   0x0000d840 0x18000d840 GLOBAL FUNC 0    AEINV.dll GetAppInfo2
4   0x0000d840 0x18000d840 GLOBAL FUNC 0    AEINV.dll GetAppInfo2aeinv
5   0x0000e960 0x18000e960 GLOBAL FUNC 0    AEINV.dll GetAppInfo
6   0x0005d460 0x18005d460 GLOBAL FUNC 0    AEINV.dll GetAppInventory
7   0x0000e9f0 0x18000e9f0 GLOBAL FUNC 0    AEINV.dll GetCachedAppInventory
8   0x0005f3d0 0x18005f3d0 GLOBAL FUNC 0    AEINV.dll GetDetailedAppInventory
9   0x00060b50 0x180060b50 GLOBAL FUNC 0    AEINV.dll GetDetailedAppInventoryFile
10  0x0000f600 0x18000f600 GLOBAL FUNC 0    AEINV.dll GetDetailedAppInventoryOrphanFile
11  0x00062620 0x180062620 GLOBAL FUNC 0    AEINV.dll UpdateSoftwareInventoryW
```

#### Exported Functions and Documentation

| Exported Function                   | Description/Documentation Link                                                                                                                |
|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| CreateAppxPackageInventory          | [CreateAppxPackageInventory](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-createappxpackageinventory)                   |
| CreateAppxPackageInventoryExtracted | [CreateAppxPackageInventoryExtracted](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-createappxpackageinventoryextracted) |
| CreateSoftwareInventory             | [CreateSoftwareInventory](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-createsoftwareinventory)                         |
| GetAppInfo2                         | [GetAppInfo2](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-getappinfo2)                                                 |
| GetAppInfo                          | [GetAppInfo](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-getappinfo)                                                   |
| GetAppInventory                     | [GetAppInventory](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-getappinventory)                                         |
| GetCachedAppInventory               | [GetCachedAppInventory](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-getcachedappinventory)                             |
| GetDetailedAppInventory             | [GetDetailedAppInventory](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-getdetailedappinventory)                         |
| GetDetailedAppInventoryFile         | [GetDetailedAppInventoryFile](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-getdetailedappinventoryfile)                 |
| GetDetailedAppInventoryOrphanFile   | [GetDetailedAppInventoryOrphanFile](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-getdetailedappinventoryorphanfile)     |
| UpdateSoftwareInventoryW            | [UpdateSoftwareInventoryW](https://learn.microsoft.com/en-us/windows/win32/api/aeinv/nf-aeinv-updatesoftwareinventoryw)                       |

---

## aepic.dll

#### Export table:

```
100 0x00027a60 0x180027a60 GLOBAL FUNC 0    AEPIC.dll Ordinal_100
101 0x0000d940 0x18000d940 GLOBAL FUNC 0    AEPIC.dll Ordinal_101
102 0x00007010 0x180007010 GLOBAL FUNC 0    AEPIC.dll Ordinal_102
103 0x00038720 0x180038720 GLOBAL FUNC 0    AEPIC.dll Ordinal_103
104 0x000279b0 0x1800279b0 GLOBAL FUNC 0    AEPIC.dll Ordinal_104
105 0x00009730 0x180009730 GLOBAL FUNC 0    AEPIC.dll Ordinal_105
106 0x00027740 0x180027740 GLOBAL FUNC 0    AEPIC.dll Ordinal_106
107 0x0000a600 0x18000a600 GLOBAL FUNC 0    AEPIC.dll Ordinal_107
108 0x00038780 0x180038780 GLOBAL FUNC 0    AEPIC.dll Ordinal_108
109 0x000276d0 0x1800276d0 GLOBAL FUNC 0    AEPIC.dll Ordinal_109
110 0x00045590 0x180045590 GLOBAL FUNC 0    AEPIC.dll GetAppInventoryCore
111 0x0001cb10 0x18001cb10 GLOBAL FUNC 0    AEPIC.dll GetPrivacyLevel
112 0x00047d50 0x180047d50 GLOBAL FUNC 0    AEPIC.dll UpdateSoftwareInventoryTC2
113 0x00038e90 0x180038e90 GLOBAL FUNC 0    AEPIC.dll DllCanUnloadNow
114 0x00038ec0 0x180038ec0 GLOBAL FUNC 0    AEPIC.dll DllGetActivationFactory
115 0x00038370 0x180038370 GLOBAL FUNC 0    AEPIC.dll PicAmiClose
116 0x00038380 0x180038380 GLOBAL FUNC 0    AEPIC.dll PicAmiInitialize
117 0x0001c430 0x18001c430 GLOBAL FUNC 0    AEPIC.dll PicFreeFileInfo
118 0x0000fb00 0x18000fb00 GLOBAL FUNC 0    AEPIC.dll PicRetrieveFileInfo
119 0x00038390 0x180038390 GLOBAL FUNC 0    AEPIC.dll PicRetrieveFileInfoAppx
120 0x00038560 0x180038560 GLOBAL FUNC 0    AEPIC.dll PicRetrieveFileLastRunTime
121 0x00038650 0x180038650 GLOBAL FUNC 0    AEPIC.dll PicUpdateFileLastRunTime
```

#### Exported Functions and Documentation

| Exported Function          | Description/Documentation Link                                                                                              |
|----------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| Ordinal_100 to Ordinal_109 | Ordinal exports, documentation not available.                                                                               |
| GetAppInventoryCore        | [GetAppInventoryCore](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-getappinventorycore)               |
| GetPrivacyLevel            | [GetPrivacyLevel](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-getprivacylevel)                       |
| UpdateSoftwareInventoryTC2 | [UpdateSoftwareInventoryTC2](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-updatesoftwareinventorytc2) |
| DllCanUnloadNow            | [DllCanUnloadNow](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-dllcanunloadnow)                       |
| DllGetActivationFactory    | [DllGetActivationFactory](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-dllgetactivationfactory)       |
| PicAmiClose                | [PicAmiClose](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-picamiclose)                               |
| PicAmiInitialize           | [PicAmiInitialize](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-picamiinitalize)                      |
| PicFreeFileInfo            | [PicFreeFileInfo](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-picfreefileinfo)                       |
| PicRetrieveFileInfo        | [PicRetrieveFileInfo](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-picretrievefileinfo)               |
| PicRetrieveFileInfoAppx    | [PicRetrieveFileInfoAppx](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-picretrievefileinfoappx)       |
| PicRetrieveFileLastRunTime | [PicRetrieveFileLastRunTime](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-picretrievefilelastruntime) |
| PicUpdateFileLastRunTime   | [PicUpdateFileLastRunTime](https://learn.microsoft.com/en-us/windows/win32/api/aepic/nf-aepic-picupdatefilelastruntime)     |

---

## agentactivationruntime.dll

#### Export table:

```
1   0x00001480 0x180001480 GLOBAL FUNC 0    agentactivationruntime.dll ?CreateAgentActivationRuntime@@YA?AV?$shared_ptr@VIAgentActivationRuntime@VoiceAgentServices@Microsoft@@@std@@XZ
2   0x00001640 0x180001640 GLOBAL FUNC 0    agentactivationruntime.dll ?GetAgentActivationRuntime@@YA?AV?$shared_ptr@VIAgentActivationRuntime@VoiceAgentServices@Microsoft@@@std@@XZ
3   0x000017d0 0x1800017d0 GLOBAL FUNC 0    agentactivationruntime.dll ?GetLoggerInstance@@YAAEAVLogger@VoiceAgentServices@Microsoft@@XZ
4   0x000017e0 0x1800017e0 GLOBAL FUNC 0    agentactivationruntime.dll ?ReleaseAgentActivationRuntime@@YAXXZ
```

#### Exported Functions and Documentation

| Exported Function                                                                                                | Description/Documentation Link                                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ?CreateAgentActivationRuntime@@YA?AV?$shared_ptr@VIAgentActivationRuntime@VoiceAgentServices@Microsoft@@@std@@XZ | [CreateAgentActivationRuntime](https://learn.microsoft.com/en-us/windows/win32/api/agentactivationruntime/nf-agentactivationruntime-createagentactivationruntime)   |
| ?GetAgentActivationRuntime@@YA?AV?$shared_ptr@VIAgentActivationRuntime@VoiceAgentServices@Microsoft@@@std@@XZ    | [GetAgentActivationRuntime](https://learn.microsoft.com/en-us/windows/win32/api/agentactivationruntime/nf-agentactivationruntime-getagentactivationruntime)         |
| ?GetLoggerInstance@@YAAEAVLogger@VoiceAgentServices@Microsoft@@XZ                                                | [GetLoggerInstance](https://learn.microsoft.com/en-us/windows/win32/api/agentactivationruntime/nf-agentactivationruntime-getloggerinstance)                         |
| ?ReleaseAgentActivationRuntime@@YAXXZ                                                                            | [ReleaseAgentActivationRuntime](https://learn.microsoft.com/en-us/windows/win32/api/agentactivationruntime/nf-agentactivationruntime-releaseagentactivationruntime) |
