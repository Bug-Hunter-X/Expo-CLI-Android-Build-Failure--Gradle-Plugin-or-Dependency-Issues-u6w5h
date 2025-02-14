# Expo CLI Android Build Failure: Gradle Plugin or Dependency Issues

This repository demonstrates a common but difficult-to-diagnose bug encountered when building Android APKs using the Expo CLI. The issue stems from conflicts or missing dependencies related to the Android Gradle plugin version.  The actual code may be fine, but the build process fails due to underlying configuration problems.

## Problem Description

The Expo CLI build process for Android fails with unhelpful error messages.  These messages often point to Gradle plugin version incompatibilities or missing dependencies. This makes it challenging to pinpoint the exact cause of the failure.

## Solution

The solution involves carefully reviewing the Android build configuration and possibly updating dependencies or resolving conflicts in the `android/build.gradle` files. In some cases, cleaning the project or reinstalling dependencies might be necessary. More advanced solutions may involve investigating the Gradle plugin version compatibility matrix.

## How to Reproduce

1. Clone this repository.
2. Attempt to build an Android APK using `expo build:android`.
3. Observe the Gradle error messages.
4. Implement the solution found in `bugSolution.js` to resolve the issue. 