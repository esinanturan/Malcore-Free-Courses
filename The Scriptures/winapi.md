<p align="center">
    <img src="../.github/winapi.png" height="256" width="256">
</p>

# What is this?

This is an attempt to add all exported functions from the Windows DLL files located in `System32` and `sysWOW64`. This will be an ongoing project and will probably take a long time to do. Each exported function will also have the link (if available) to the functions documentation.

# System32

### DLL Files List

- [ztrace_maps](#ztrace_mapsdll)
- [aadauthhelper](#aadauthhelperdll)
- [aadcloudap](#aadcloudapdll)
- [aadjcsp](#aadjcspdll)
- [aadtb](#aadtbdll)
- [aadWamExtension](#aadwamextensiondll)
- [AarSvc](#aarsvcdll)
- [AboutSettingsHandlers](#aboutsettingshandlersdll)
- [AboveLockAppHost](#abovelockapphostdll)

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

## aadcloudap.dll

#### Export table:
```
1   0x00005d30 0x180005d30 GLOBAL FUNC 0    AADCLOUDAP.dll CloudAPPluginInitialize
2   0x00006160 0x180006160 GLOBAL FUNC 0    AADCLOUDAP.dll DllRegisterServer
3   0x00006160 0x180006160 GLOBAL FUNC 0    AADCLOUDAP.dll DllUnregisterServer
```

## aadjcsp.dll

#### Export table:
```
1   0x000046e0 0x1800046e0 GLOBAL FUNC 0    AADJCSP.dll DllGetClassObject
```

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

## aadWamExtension.dll

#### Export table:
```
1   0x000080e0 0x1800080e0 GLOBAL FUNC 0    aadWamExtension.dll DllCanUnloadNow
2   0x00008140 0x180008140 GLOBAL FUNC 0    aadWamExtension.dll DllGetActivationFactory
3   0x00008340 0x180008340 GLOBAL FUNC 0    aadWamExtension.dll DllGetClassObject
```

## AarSvc.dll

#### Export table:
```
1   0x000054a0 0x1800054a0 GLOBAL FUNC 0    AarSvc.dll DllCanUnloadNow
2   0x00005190 0x180005190 GLOBAL FUNC 0    AarSvc.dll DllGetActivationFactory
3   0x00005390 0x180005390 GLOBAL FUNC 0    AarSvc.dll DllGetClassObject
4   0x000055f0 0x1800055f0 GLOBAL FUNC 0    AarSvc.dll ServiceMain
```

## AboutSettingsHandlers.dll

#### Export table:
```
1   0x00003b00 0x180003b00 GLOBAL FUNC 0    AboutSettingsHandlers.dll GetSetting
```

## AboveLockAppHost.dll

#### Export table:
```
1   0x00009300 0x180009300 GLOBAL FUNC 0    AboveLockAppHost.dll DllCanUnloadNow
2   0x00017370 0x180017370 GLOBAL FUNC 0    AboveLockAppHost.dll DllGetActivationFactory
3   0x00009370 0x180009370 GLOBAL FUNC 0    AboveLockAppHost.dll DllGetClassObject
```