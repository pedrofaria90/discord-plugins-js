# [CrashRecovery](https://1lighty.github.io/BetterDiscordStuff/?plugin=CrashRecovery "CrashRecovery") Changelog
### 1.0.3
- Implemented fixes that allow patches to work properly on canary using Powercord.

### 1.0.2
- Fixed error fetching responsible plugins sometimes.
- Fixed issue with Zere not consistently coding BdApi.getPlugin between BBD and BBD Beta.

### 1.0.1
- Fixed some binding issue causing an error.

### 1.0.0
- Added extra info in console, mainly a cleaned up stack trace, decoded react errors and a component stack, to help plugin developers.
- Powercord support has been added, plugin can now detect and potentially disable any misbehaving plugins that are causing the client to repeatedly crash.

### 0.1.8
- Crash fix.

### 0.1.7
- Changed to module.exports because useless backwards incompatbile changes are the motto for BBD apparently.

### 0.1.6
- Removed usage of soon to be deprecated globals.

### 0.1.5
- Fixed startup error in console

### 0.1.4
- Improved detection accuracy
- Added failsafe in case something goes wrong when: initializing, starting or when trying to display the recover button
- Added third step when trying to recover, as to not switch channels unless required, can be disabled in settings.
- Plugin is no longer experimental

### 0.1.3
- Fixed crash if XenoLib or ZeresPluginLib were missing

### 0.1.2
- Fixed crash screen being blank if a plugin failed to stop properly.
- Now closes all modals, including the special types that are not stored inside ModalStack.

### 0.1.1
- Fixed failing to recover from a crash if a plugin is preventing it.

### 0.1.0
- Initial release
- Should handle most crashes on its own.
