## 1.0.0
- Depend on `flutter_callkeep_platform_interface` 1.0.0
- Rewrite our API to use `flutter_callkeep_platform_interface` and `flutter_callkeep_platform_interface` to provide a common API for all platforms
- (Web) Add support for web. 
- (Android/iOS) Add `acceptCall` implementation
- (iOS) No longer return `answerCall` and `outgoingCall` when audio session is activated.
- (Android) Fix crash when registering receiver on Android 13+

## 0.3.4
- (Android) Support Gradle plugin 8+
- (Android) Fix FullScreenIntent not being removed when `endAllCalls` is called (#63)

## 0.3.3

- (iOS) Clear outgoing and answercall properly.
- (iOS) Use `connectedAt` to set when outgoing call connects.
- (Dart) Update constraints to use version 3 and above
## 0.3.2

- Stop decrypting handle on iOS
## 0.3.1+1

- Add default Android values and fix example app
- Update example app dependencies
- Bump example app iOS deployment target to iOS 11
- Bump example app Android minimum SDK version to 33

## 0.3.1

- Improve calls management on iOS implementation

## 0.3.0

- Rework API based on `flutter_callkit_incoming`'s API, add iOS implementation and fix bugs (BREAKING CHANGE)

## 0.2.3

- (android) Fix PendingIntent missing mutability flag error on API 31+

## 0.2.2

- (android) Fix override parameters for Flutter 3.0 support

## 0.2.1

- (android) Replace jcenter with mavenCentral

## 0.2.0

- Migrate to null safety

## 0.1.9

- (android) Upgrade to v2 embedding and Gradle 7.0.2

## 0.1.8

- (ios) Fix bridging header import
- (android) Don't launch custom call activity on Answer / Decline actions in displayCustomCall

## 0.1.7

- (ios) Fix podspec name

## 0.1.6

- Allow setting ringtone uri on custom notification (#6)

## 0.1.5

- Add ability to customize heads-up notification (#5)

## 0.1.4

- Add `dismissCustomIncomingCall` function (#4)

## 0.1.3

- Add `displayCustomIncomingCall` function (#3)

## 0.1.2

- Add `isCurrentDeviceSupported` property
- Allow calling `backToForeground` from background task

## 0.1.1

- Support the v2 Android embedder plugins API

## 0.1.0

🎉 Initial release
