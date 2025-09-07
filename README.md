# Awesome iOS Developer Experience ⚡

A curated collection of tools, frameworks, and resources specifically focused on improving the **Developer Experience (DevEx)** for native iOS development. This list emphasizes productivity, build performance, testing efficiency, debugging capabilities, and overall workflow optimization.

## Table of Contents

- [Build System & Performance](#build-system--performance)
- [CI/CD & Automation](#cicd--automation)
- [Testing Frameworks](#testing-frameworks)
- [Debugging & Profiling](#debugging--profiling)
- [Code Quality & Analysis](#code-quality--analysis)
- [Dependency Management](#dependency-management)
- [Documentation & Generation](#documentation--generation)
- [Analytics & Monitoring](#analytics--monitoring)
- [GitHub Actions for iOS](#github-actions-for-ios)
- [Contributing](#contributing)

---

## Build Systems
Tools for optimizing build times, managing project configuration, and improving compilation workflows.

### Build System 

- **[Xcode Build](https://developer.apple.com/documentation/xcode/improving-the-speed-of-incremental-builds)** `recommended` - Apple's official guide for optimizing incremental build performance
- **[Tuist](https://github.com/tuist/tuist)** `recommended` - Tool for generating and maintaining Xcode projects at scale 
- **[Bazel for iOS](https://github.com/bazelbuild/rules_apple)** - Google's build system with distributed caching (requires significant setup)
- **[Buck2](https://github.com/facebook/buck2)** - Meta's build system (limited iOS community adoption)

### Build Output Formatting

- **[xcbeautify](https://github.com/cpisciotta/xcbeautify)** `recommended` - Modern Swift-based xcodebuild formatter
- **[xcpretty](https://github.com/xcpretty/xcpretty)** - Classic Ruby-based formatter (superseded by xcbeautify)

---

## Analytics & Monitoring
Performance monitoring, crash reporting, and build analytics for tracking app health and development metrics.

### Production Monitoring

- **[Crashlytics](https://firebase.google.com/products/crashlytics)** `recommended` - Firebase crash reporting
- **[Sentry](https://sentry.io/for/mobile/)** - Error tracking and performance monitoring

### Build Analytics & Monitoring

- **[xcmetrics](https://github.com/spotify/xcmetrics)** `recommended` - Spotify's Xcode build analytics platform
- **[BuildBuddy](https://www.buildbuddy.io/)** - Build observability platform with iOS support
- **[Emerge Tools](https://www.emergetools.com/)** - App size analysis and build optimization

---

## CI/CD & Automation
Continuous integration, deployment pipelines, and automation tools for streamlining iOS release workflows.

### Automation Frameworks

- **[fastlane](https://fastlane.tools/)** `recommended` - Industry-standard iOS automation toolkit
- **[Xcode Cloud](https://developer.apple.com/xcode-cloud/)** - Apple's native CI/CD service
- **[Codemagic](https://codemagic.io/)** - Dedicated mobile CI/CD platform
- **[Bitrise](https://bitrise.io/)** - Mobile-focused CI/CD with extensive iOS support

### Result Parsing & Reporting

- **[xcresulttool](https://developer.apple.com/documentation/xcode/xcresulttool)** `recommended` - Apple's built-in result bundle parser
- **[xcparse](https://github.com/ChargePoint/xcparse)** `recommended` - Tool for parsing Xcode result bundles 

---

## Testing Frameworks
Comprehensive testing tools covering unit tests, UI automation, mocking, and snapshot testing for iOS applications.

### Unit Testing

- **[Swift Testing](https://swift.org/blog/swift-testing/)** `recommended` - Apple's modern testing framework (iOS 18+)
- **[XCTest](https://developer.apple.com/documentation/xctest)** - Apple's legacy testing framework
- **[Quick & Nimble](https://github.com/Quick/Quick)** - BDD testing framework for Swift 

### UI Testing

- **[XCUITest](https://developer.apple.com/documentation/xctest/user_interface_tests)** `recommended` - Apple's UI testing framework
- **[EarlGrey](https://github.com/google/EarlGrey)** - Google's native iOS UI testing framework 
- **[Maestro](https://github.com/mobile-dev-inc/maestro)** - Cross-platform mobile UI testing

### Snapshot Testing

- **[swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing)** `recommended` - Point-Free's snapshot testing
- **[iOSSnapshotTestCase](https://github.com/uber/ios-snapshot-test-case)** - Uber's snapshot testing library 

---

## Debugging & Profiling
Advanced debugging tools, performance profilers, and runtime analysis for identifying and resolving iOS app issues.

### Apple Tools

- **[Xcode Instruments](https://developer.apple.com/xcode/features/)** `recommended` - Apple's profiling and analysis tool suite
- **[Xcode Debugger](https://developer.apple.com/documentation/xcode/debugging)** `recommended` - Built-in LLDB debugging capabilities
- **[OSLog](https://developer.apple.com/documentation/oslog)** `recommended` - Apple's unified logging system

### Third-Party Debugging

- **[Flipper](https://github.com/facebook/flipper)** - Meta's mobile debugging platform 
- **[FLEX](https://github.com/FLEXTool/FLEX)** - In-app debugging and exploration tool 
- **[Reveal](https://revealapp.com/)** - Runtime view debugging (commercial)

---

## Code Quality & Analysis
Static analysis, linting, formatting, and code metrics tools for maintaining high-quality Swift and Objective-C codebases.

### Static Analysis & Linting

- **[SwiftLint](https://github.com/realm/SwiftLint)** `recommended` - Industry-standard Swift linter
- **[swift-format](https://github.com/apple/swift-format)** `recommended` - Apple's official Swift formatter 
- **[SwiftFormat](https://github.com/nicklockwood/SwiftFormat)** `recommended` - Third-party Swift formatter

### Code Analysis & Metrics

- **[periphery](https://github.com/peripheryapp/periphery)** `recommended` - Unused code detection tool
- **[Tailor](https://github.com/sleekbyte/tailor)** - Swift static analysis 
- **[SonarQube Swift Plugin](https://github.com/Backelite/sonar-swift)** - Enterprise code quality platform

---

## Dependency Management
Package managers and tools for managing third-party libraries, development tools, and project dependencies.

### Package Managers

- **[Swift Package Manager](https://swift.org/package-manager/)** `recommended` - Apple's official package manager
- **[CocoaPods](https://cocoapods.org/)** - Ruby-based dependency manager 
- **[Carthage](https://github.com/Carthage/Carthage)** - Decentralized dependency manager 

### Tool Management

- **[Mint](https://github.com/yonaskolb/Mint)** - Swift package installation and management
- **[homebrew-bundle](https://github.com/Homebrew/homebrew-bundle)** `recommended` - Dependency management for development tools

---

## Documentation & Generation
Code generation tools and documentation generators for reducing boilerplate and maintaining project documentation.

### Code Generation

- **[Sourcery](https://github.com/krzysztofzablocki/Sourcery)** `recommended` - Swift code generation tool
- **[SwiftGen](https://github.com/SwiftGen/SwiftGen)** `recommended` - Asset and localization code generator

### Documentation
- **[DocC](https://www.swift.org/documentation/docc/)** `recommended` - Official Swift documentation generator
- **[SwiftDoc](https://github.com/SwiftDocOrg/swift-doc)** - Swift documentation generator
- **[jazzy](https://github.com/realm/jazzy)** - Documentation generator for Swift/Objective-C

---

## GitHub Actions for iOS

*Specialized GitHub Actions and workflows designed specifically for iOS development, testing, and deployment.*

### Official Actions

- **[setup-xcode](https://github.com/maxim-lobanov/setup-xcode)** - Xcode version management 
- **[ios-build-action](https://github.com/yukiarrr/ios-build-action)** - Complete iOS build workflow 

### Community Actions

- **[cache-restore](https://github.com/actions/cache)** `recommended` - Dependency caching for faster builds
- **[upload-artifact](https://github.com/actions/upload-artifact)** `recommended` - Build artifact management

### Workflow Templates

- **[iOS CI/CD Templates](https://github.com/actions/starter-workflows/tree/main/ci)** - Official GitHub workflow starters
- **[fastlane GitHub Actions](https://docs.fastlane.tools/best-practices/continuous-integration/github/)** `recommended` - Integration guides

---

**🏷️ Recommended Tag**: Tools marked with `recommended`, at a minimum, are actively maintained, comprehensive documentation, and strong iOS community support. 

Note: This list focuses specifically on Developer Experience for native iOS development. For general iOS development resources, see [awesome-ios](https://github.com/vsouza/awesome-ios) and [awesome-swift](https://github.com/matteocrippa/awesome-swift).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the awesome-ios-devex contributors have waived all copyright and related or neighboring rights to this work.

