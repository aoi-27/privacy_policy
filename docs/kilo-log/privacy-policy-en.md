---
layout: default
title: Privacy Policy - Kilo-Log
lang: en
---

# Privacy Policy

[日本語](./privacy-policy.html)

Last updated: June 28, 2026

## Introduction

"Kilo-Log" (hereinafter referred to as "the App") is a weight management application for recording body weight and meals, and visualizing your progress through graphs. This Privacy Policy explains how we handle personal information in the App.

## Information We Collect

### 1. Weight and Meal Data

The App stores the following data locally on your device only for the purpose of recording and managing your weight and meals:

- Weight and body fat percentage records (date and value)
- Mood (great / good / normal / poor) and notes
- Meal records (meal name, calories, meal type)
- Target weight, starting weight, and goal deadline

This data is stored only on your device (via SwiftData) and is never transmitted to external servers.

### 2. HealthKit Data

With your permission, the App accesses Apple HealthKit to sync weight data:

- **Read**: Bulk import of past weight data
- **Write**: Saving recorded weight to the Health app

Retrieved HealthKit data is never transmitted to external servers. HealthKit integration is an optional feature; if you do not grant permission, you can still use the App to record and manage your data.

### 3. Biometric Authentication and PIN Lock

The App uses the following for its App Lock feature:

- **Face ID / Touch ID**: Biometric authentication via LocalAuthentication Framework (processed entirely on-device)
- **PIN code**: A 4-digit PIN stored in the iOS Keychain (secure credential storage)

None of this authentication information is transmitted to external servers.

### 4. Advertising Data (AdMob)

The App uses Google AdMob to display banner advertisements. AdMob may collect the following information to optimize ad delivery:

- Advertising identifier (IDFA)
- Device information
- App usage information
- Ad interaction information

At launch, the App displays a consent dialog via Google's User Messaging Platform (UMP), followed by Apple's App Tracking Transparency (ATT) permission dialog.

For more details, please see [Google's Privacy Policy](https://policies.google.com/privacy).

## How We Use Information

The collected information is used for the following purposes:

1. Providing app functionality (weight and meal recording, management, and graph display)
2. Syncing weight data via HealthKit integration
3. Providing the App Lock feature
4. Improving app quality and fixing bugs
5. Delivering advertisements

## Information Sharing

Information collected by the App may be shared with the following third-party service:

- **Google AdMob**: For ad delivery

Weight and meal data, HealthKit data, biometric authentication information, and PIN are never shared with any third party.

## Your Rights

You have the following rights:

- You can change HealthKit data access permissions (read and write) in your device settings
- You can limit the use of the advertising identifier (IDFA) in your device settings
- You can disable App Lock or change your PIN in the App's settings
- You can stop future information collection by uninstalling the App (this will also remove the PIN stored in the Keychain)

## Data Retention Period

- Weight and meal data: Stored only on the device and never transmitted externally by the App
- HealthKit data: Accessed and written on-device only; not transmitted externally by the App
- PIN code: Stored in the Keychain and removed when the App is uninstalled
- Advertising data: Stored according to AdMob policies

## Children's Privacy

The App is not intended for children under 13 years of age. We do not knowingly collect personal information from children under 13.

## Security

We implement appropriate technical and organizational security measures to protect your information. Your PIN code is securely stored in the iOS Keychain. However, please understand that no method of transmission over the Internet or electronic storage is 100% secure.

## Changes to This Privacy Policy

This Privacy Policy may be changed without notice. In case of significant changes, we will update the "Last updated" date on this page. We recommend that you review this page periodically.

## Third-Party Service Privacy Policies

Privacy policies of third-party services used by the App:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [AdMob (Google Ads)](https://support.google.com/admob/answer/6128543)

## Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us:

- Support URL: [https://aoi-27.github.io/privacy_policy/kilo-log/privacy-policy.html](https://aoi-27.github.io/privacy_policy/kilo-log/privacy-policy.html)

---

This Privacy Policy is governed by the laws of Japan.
