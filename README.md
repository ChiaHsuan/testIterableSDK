1 This project is setup with the docs: 

https://reactnative.dev/docs/environment-setup

2 Run the project

```
npm install or yarn install
npx pod-install
npx react-native run-ios
```

3 Then get the error
```
** BUILD FAILED **


The following build commands failed:
	CompileSwiftSources normal x86_64 com.apple.xcode.tools.swift.compiler
	CompileSwift normal x86_64 /Users/daydream/test/testIterableSDK/ios/Pods/Iterable-iOS-SDK/swift-sdk/Internal/DependencyContainer.swift
	CompileSwift normal x86_64 /Users/daydream/test/testIterableSDK/ios/Pods/Iterable-iOS-SDK/swift-sdk/Internal/DeviceInfo.swift
	CompileSwift normal x86_64 /Users/daydream/test/testIterableSDK/ios/Pods/Iterable-iOS-SDK/swift-sdk/Internal/IterableHtmlMessageViewController.swift
(4 failures)

```


System info

```
System:
    OS: macOS 10.15.7
    CPU: (8) x64 Intel(R) Core(TM) i7-4770HQ CPU @ 2.20GHz
    Memory: 2.44 GB / 16.00 GB
    Shell: 5.7.1 - /bin/zsh
  Binaries:
    Node: 10.15.3
    Yarn: 1.22.10
    npm: 6.4.1
    Watchman: 4.9.0
  Managers:
    CocoaPods: 1.9.3
  SDKs:
    iOS SDK:
      Platforms: iOS 13.6, DriverKit 19.0, macOS 10.15, tvOS 13.4, watchOS 6.2
    Android SDK:
      API Levels: 23, 24, 25, 26, 27, 28, 29
      Build Tools: 23.0.1, 25.0.1, 25.0.3, 26.0.0, 26.0.1, 26.0.2, 26.0.3, 27.0.1, 27.0.3, 28.0.0, 28.0.2, 28.0.3, 29.0.2, 29.0.3
      System Images: android-16 | Intel x86 Atom, android-16 | Google APIs Intel x86 Atom, android-24 | Google APIs Intel x86 Atom, android-26 | Google APIs Intel x86 Atom, android-27 | Google APIs Intel x86 Atom
      Android NDK: Not Found
  IDEs:
    Android Studio: 4.0 AI-193.6911.18.40.6514223
    Xcode: 11.6/11E708 - /usr/bin/xcodebuild
  Languages:
    Java: 1.8.0_111 - /Library/Java/JavaVirtualMachines/jdk1.8.0_111.jdk/Contents/Home/bin/javac
    Python: 2.7.16 - /usr/bin/python
  npmPackages:
    @react-native-community/cli: Not Found
    react: 16.13.1 => 16.13.1
    react-native: 0.63.4 => 0.63.4
    react-native-macos: Not Found
  npmGlobalPackages:
    *react-native*: Not Found
```
