# Splash Screen Implementation

This document explains how to implement a Splash Screen in your Android project using the latest guidelines and best practices.

## Overview

The Splash Screen is the first screen that appears when the app is launched. It provides a visually appealing introduction and ensures a smooth transition to the main content of the app.

### Key Features:
- Displays app branding (logo and name).
- Ensures a smooth transition to the main activity.
- Uses Android's SplashScreen API for consistent behavior across devices.

---

## Steps to Implement

### 1. Add Dependencies (if required)
Ensure your app uses the latest Android API for Splash Screens.

```gradle
implementation 'androidx.core:core-splashscreen:1.0.1'
