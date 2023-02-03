## Error log

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

## Environment

### arch

```
arm64
```

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
ProductName:		macOS
ProductVersion:		13.2
BuildVersion:		22D49
```

### xcodebuild -version

```
Xcode 14.2
Build version 14C18
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

### pubspec.yaml

```
name: ffa
description: A new Flutter project.
publish_to: 'none' 
version: 1.0.0+1

environment:
  sdk: '>=2.19.1 <3.0.0'

dependencies:
  flutter:
    sdk: flutter

  cupertino_icons: ^1.0.2
  flutter_facebook_auth: ^5.0.7

dev_dependencies:
  flutter_test:
    sdk: flutter

  flutter_lints: ^2.0.0

flutter:
  uses-material-design: true
```

### ios/Runner/Info.plist

```
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>CFBundleDevelopmentRegion</key>
	<string>$(DEVELOPMENT_LANGUAGE)</string>
	<key>CFBundleDisplayName</key>
	<string>Ffa</string>
	<key>CFBundleExecutable</key>
	<string>$(EXECUTABLE_NAME)</string>
	<key>CFBundleIdentifier</key>
	<string>$(PRODUCT_BUNDLE_IDENTIFIER)</string>
	<key>CFBundleInfoDictionaryVersion</key>
	<string>6.0</string>
	<key>CFBundleName</key>
	<string>ffa</string>
	<key>CFBundlePackageType</key>
	<string>APPL</string>
	<key>CFBundleShortVersionString</key>
	<string>$(FLUTTER_BUILD_NAME)</string>
	<key>CFBundleSignature</key>
	<string>????</string>
	<key>CFBundleVersion</key>
	<string>$(FLUTTER_BUILD_NUMBER)</string>
	<key>LSRequiresIPhoneOS</key>
	<true/>
	<key>UILaunchStoryboardName</key>
	<string>LaunchScreen</string>
	<key>UIMainStoryboardFile</key>
	<string>Main</string>
	<key>UISupportedInterfaceOrientations</key>
	<array>
		<string>UIInterfaceOrientationPortrait</string>
		<string>UIInterfaceOrientationLandscapeLeft</string>
		<string>UIInterfaceOrientationLandscapeRight</string>
	</array>
	<key>UISupportedInterfaceOrientations~ipad</key>
	<array>
		<string>UIInterfaceOrientationPortrait</string>
		<string>UIInterfaceOrientationPortraitUpsideDown</string>
		<string>UIInterfaceOrientationLandscapeLeft</string>
		<string>UIInterfaceOrientationLandscapeRight</string>
	</array>
	<key>UIViewControllerBasedStatusBarAppearance</key>
	<false/>
	<key>CADisableMinimumFrameDurationOnPhone</key>
	<true/>
	<key>UIApplicationSupportsIndirectInputEvents</key>
	<true/>
</dict>
</plist>
```

### ios/Podfile

```
# Uncomment this line to define a global platform for your project
platform :ios, '12.0'

# CocoaPods analytics sends network stats synchronously affecting flutter build latency.
ENV['COCOAPODS_DISABLE_STATS'] = 'true'

project 'Runner', {
  'Debug' => :debug,
  'Profile' => :release,
  'Release' => :release,
}

def flutter_root
  generated_xcode_build_settings_path = File.expand_path(File.join('..', 'Flutter', 'Generated.xcconfig'), __FILE__)
  unless File.exist?(generated_xcode_build_settings_path)
    raise "#{generated_xcode_build_settings_path} must exist. If you're running pod install manually, make sure flutter pub get is executed first"
  end

  File.foreach(generated_xcode_build_settings_path) do |line|
    matches = line.match(/FLUTTER_ROOT\=(.*)/)
    return matches[1].strip if matches
  end
  raise "FLUTTER_ROOT not found in #{generated_xcode_build_settings_path}. Try deleting Generated.xcconfig, then run flutter pub get"
end

require File.expand_path(File.join('packages', 'flutter_tools', 'bin', 'podhelper'), flutter_root)

flutter_ios_podfile_setup

target 'Runner' do
  use_frameworks!
  use_modular_headers!

  flutter_install_all_ios_pods File.dirname(File.realpath(__FILE__))
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    flutter_additional_ios_build_settings(target)
  end
end
```
