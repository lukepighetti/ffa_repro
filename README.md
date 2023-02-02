### ruby --version

```
ruby 3.2.0 (2022-12-25 revision a528908271) [arm64-darwin21]
```
    
### pod --version

```
1.11.3
```

### sw_vers

```
ProductName:	macOS
ProductVersion:	12.6
BuildVersion:	21G115

```

### flutter doctor -v

```
[✓] Flutter (Channel stable, 3.7.1, on macOS 12.6 21G115 darwin-arm64, locale en-US)
    • Flutter version 3.7.1 on channel stable at /Users/lukepighetti/development/flutter/flutter
    • Upstream repository https://github.com/flutter/flutter.git
    • Framework revision 7048ed95a5 (29 hours ago), 2023-02-01 09:07:31 -0800
    • Engine revision 800594f1f4
    • Dart version 2.19.1
    • DevTools version 2.20.1

[✓] Android toolchain - develop for Android devices (Android SDK version 32.1.0-rc1)
    • Android SDK at /Users/lukepighetti/Library/Android/sdk
    • Platform android-32, build-tools 32.1.0-rc1
    • Java binary at: /Applications/Android Studio.app/Contents/jre/Contents/Home/bin/java
    • Java version OpenJDK Runtime Environment (build 11.0.11+0-b60-7772763)
    • All Android licenses accepted.

[✓] Xcode - develop for iOS and macOS (Xcode 14.2)
    • Xcode at /Applications/Xcode.app/Contents/Developer
    • Build 14C18
    • CocoaPods version 1.11.3

[✓] Chrome - develop for the web
    • Chrome at /Applications/Google Chrome.app/Contents/MacOS/Google Chrome

[✓] Android Studio (version 2021.1)
    • Android Studio at /Applications/Android Studio.app/Contents
    • Flutter plugin can be installed from:
      🔨 https://plugins.jetbrains.com/plugin/9212-flutter
    • Dart plugin can be installed from:
      🔨 https://plugins.jetbrains.com/plugin/6351-dart
    • Java version OpenJDK Runtime Environment (build 11.0.11+0-b60-7772763)

[✓] VS Code (version 1.74.3)
    • VS Code at /Applications/Visual Studio Code.app/Contents
    • Flutter extension version 3.58.0

[✓] Connected device (3 available)
    • iPhone 14 Pro (mobile) • C07630F2-F933-4011-AED6-8A044F91969F • ios            • com.apple.CoreSimulator.SimRuntime.iOS-16-2 (simulator)
    • macOS (desktop)        • macos                                • darwin-arm64   • macOS 12.6 21G115 darwin-arm64
    • Chrome (web)           • chrome                               • web-javascript • Google Chrome 109.0.5414.119

[✓] HTTP Host Availability
    • All required HTTP hosts are available

• No issues found!
```



```
dyld[53238]: Library not loaded: @rpath/FBSDKCoreKit.framework/FBSDKCoreKit
```

<details>
```
dyld[53238]: Library not loaded: @rpath/FBSDKCoreKit.framework/FBSDKCoreKit
  Referenced from: <E803861E-0359-3FAE-8D73-0422043D664B> /Users/lukepighetti/Library/Developer/CoreSimulator/Devices/C07630F2-F933-4011-AED6-8A044F91969F/data/Containers/Bundle/Application/AEEE7A99-8E6D-403E-B49F-8533D2D10FBA/Runner.app/Runner
  Reason: tried: '/Users/lukepighetti/Library/Developer/Xcode/DerivedData/Runner-amqpqurrcvpysffnskommxgpvneg/Build/Products/Debug-iphonesimulator/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2, not in dyld cache), '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2, not in dyld cache), '/Users/lukepighetti/Library/Developer/CoreSimulator/Devices/C07630F2-F933-4011-AED6-8A044F91969F/data/Containers/Bundle/Application/AEEE7A99-8E6D-403E-B49F-8533D2D10FBA/Runner.app/Frameworks/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/Users/lukepighetti/Library/Developer/CoreSimulator/Devices/C07630F2-F933-4011-AED6-8A044F91969F/data/Containers/Bundle/Application/AEEE7A99-8E6D-403E-B49F-8533D2D10FBA/Runner.app/Frameworks/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/Users/lukepighetti/Library/Developer/CoreSimulator/Devices/C07630F2-F933-4011-AED6-8A044F91969F/data/Containers/Bundle/Application/AEEE7A99-8E6D-403E-B49F-8533D2D10FBA/Runner.app/Frameworks/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2, not in dyld cache), '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2, not in dyld cache), '/Users/lukepighetti/Library/Developer/CoreSimulator/Devices/C07630F2-F933-4011-AED6-8A044F91969F/data/Containers/Bundle/Application/AEEE7A99-8E6D-403E-B49F-8533D2D10FBA/Runner.app/Frameworks/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/Users/lukepighetti/Library/Developer/CoreSimulator/Devices/C07630F2-F933-4011-AED6-8A044F91969F/data/Containers/Bundle/Application/AEEE7A99-8E6D-403E-B49F-8533D2D10FBA/Runner.app/Frameworks/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/Users/lukepighetti/Library/Developer/CoreSimulator/Devices/C07630F2-F933-4011-AED6-8A044F91969F/data/Containers/Bundle/Application/AEEE7A99-8E6D-403E-B49F-8533D2D10FBA/Runner.app/Frameworks/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/System/Library/Frameworks/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2)
Library not loaded: @rpath/FBSDKCoreKit.framework/FBSDKCoreKit
  Referenced from: <E803861E-0359-3FAE-8D73-0422043D664B> /Users/lukepighetti/Library/Developer/CoreSimulator/Devices/C07630F2-F933-4011-AED6-8A044F91969F/data/Containers/Bundle/Application/AEEE7A99-8E6D-403E-B49F-8533D2D10FBA/Runner.app/Runner
  Reason: tried: '/Users/lukepighetti/Library/Developer/Xcode/DerivedData/Runner-amqpqurrcvpysffnskommxgpvneg/Build/Products/Debug-iphonesimulator/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2), '/usr/lib/swift/FBSDKCoreKit.framework/FBSDKCoreKit' (errno=2, not in dyld cache), '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/swift/FBSDKCoreKit.framework/FB
dyld config: DYLD_SHARED_CACHE_DIR=/Users/lukepighetti/Library/Developer/CoreSimulator/Caches/dyld/21G115/com.apple.CoreSimulator.SimRuntime.iOS-16-2.20C52 DYLD_ROOT_PATH=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot DYLD_LIBRARY_PATH=/Users/lukepighetti/Library/Developer/Xcode/DerivedData/Runner-amqpqurrcvpysffnskommxgpvneg/Build/Products/Debug-iphonesimulator:/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/introspection DYLD_INSERT_LIBRARIES=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/libBacktraceRecording.dylib:/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/libMainThreadChecker.dylib:/usr/lib/libRPAC.dylib:/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/Developer/Library/PrivateFrameworks/DTDDISupport.framework/libViewDebuggerSupport.dylib DYLD_FRAMEWORK_PATH=/Users/lukepighetti/Library/Developer/Xcode/DerivedData/Runner-amqpqurrcvpysffnskommxgpvneg/Build/Products/Debug-iphonesimulator DYLD_FALLBACK_FRAMEWORK_PATH=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/System/Library/Frameworks DYLD_FALLBACK_LIBRARY_PATH=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib
(lldb)  
```
</details>
