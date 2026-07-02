# Hidden API

![Maven Central](https://img.shields.io/maven-central/v/com.clauto.hidden/stub)

Unify all hidden APIs used by Clauto apps into a library.

## Usage

- Setup [HiddenApiRefinePlugin](https://github.com/ClautoApps/HiddenApiRefinePlugin)
- `implementation 'com.clauto.hidden:compat:<version>'`
- `compileOnly 'com.clauto.hidden:stub:<version>'`

## Changelog

### 4.3.0

- Add some `IWindowManager` APIs

### 4.2.0

- Build `compat` with HiddenApiRefine plugin, this will fix `ActivityManagerApis#getContentProviderExternal` crash on pre-API 26

### 4.1.0

- Use `com.clauto.cl.buildcompat`

### 4.0.0

- Update `AppOpsManagerHidden`
- Add `WindowManagerHidden`
- Add `IBatteryPropertiesRegistrar` APIs
- Fix `registerReceiverWithFeature` on Android R (#5)
- Update HiddenApiRefine plugin

### 3.4.0

- Add some DisplayManager APIs

### 3.2.0

- Add "historical ops" related APIs

### 3.1.0

- Add `android.provider.DeviceConfig`

### 3.0.0

- (Breaking change) Update `UidObserverAdapter`
- Add `ActivityManager#UID_OBSERVER_` values

### 2.3.2

- Add `checkSignatures` `checkUidSignatures`
