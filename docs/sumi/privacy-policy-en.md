---
layout: default
title: Privacy Policy - Sumi
lang: en
---

# Privacy Policy

[日本語](./privacy-policy.html)

Last updated: July 20, 2026

## Introduction

"Sumi" (hereinafter referred to as "the App") is a one-time-purchase privacy app that automatically detects faces and personal information in your screenshots and photos, then lets you mask them with mosaic, blur, or ink blackout before you save or share.

The defining feature of the App is that **it makes no network connections whatsoever**. This Privacy Policy explains this design and how the App handles data.

## Information the App Collects

**The App does not collect any personal information.**

- The App has no server-communication capability, so photos, detection results, and settings are never transmitted anywhere
- No advertising or analytics SDKs (such as Firebase or AdMob) are included
- There is no account registration or login
- The App does not collect crash reports or usage analytics

## On-Device Processing

Every feature of the App runs entirely on your device.

### 1. Photo Library Access

- **Read**: To let you select photos to process (via PhotosPicker; the App does not request full library access)
- **Write (add-only)**: To save masked images

Selected or processed photos are never transmitted outside the App.

### 2. Automatic Detection

The App uses Apple's Vision and Natural Language frameworks, entirely on-device, to detect:

- **Faces**: the bounding region of faces in a photo
- **QR codes / barcodes**: coded regions within the image
- **Text recognition (OCR)**: email addresses, phone numbers, URLs, street addresses, postal codes, credit card numbers, monetary amounts, and other sensitive digit sequences
- **Custom keywords**: words you register yourself in Settings, such as your name or company name
- **Names (experimental, off by default)**: an experimental feature that estimates personal names, primarily in English. Because accuracy is limited, it is disabled by default and can be enabled in Settings

All of this detection happens entirely on your device. Detection results (bounding boxes and recognized text) are never transmitted or shared externally. Results are held in memory only while you're editing and are discarded when you close the App.

### 3. Masking and Saved Data

- Mosaic, blur, and ink (blackout) masks are baked into the image, which is then re-rendered before saving
- Saved images do not contain EXIF metadata such as timestamp or GPS location (this is removed as part of the re-rendering process)

### 4. My Keywords Feature

- Words you register in Settings (such as your name or company) are stored only in on-device storage (an App Group–shared UserDefaults)
- This information is never transmitted externally
- You can delete any keyword at any time from Settings

### 5. Share Extension

- You can invoke the App from the share sheet of other apps to process an image
- This processing also happens entirely on-device. No network communication occurs beyond the App Group used to share settings between the main app and the share extension

## Information Sharing

The App shares no data with any third party. Since no third-party SDKs (advertising, analytics, etc.) are used, there is no recipient to share data with in the first place.

## Your Rights

- You can change photo library access permissions at any time in your device settings
- You can delete any registered keyword at any time from the Settings screen
- Uninstalling the App removes any on-device settings (including registered keywords)

## Data Retention

- Photo data: processed only in memory on your device and not retained by the App (if you choose to save, the result is stored as a normal photo in your library)
- Detection results: held in memory only during the active editing session and discarded when you close the App
- Registered keywords and settings: stored on-device and never transmitted externally

## Children's Privacy

The App is not intended for children under 13. Because the App has no data-collection capability at all, it does not collect personal information from any user, including children under 13.

## Security

Because the App makes no network connections, there is no risk of data leakage in transit. Protection of on-device data relies on iOS's built-in security features.

## Changes to This Privacy Policy

This Privacy Policy may be changed without notice. In case of significant changes, we will update the "Last updated" date on this page. We recommend that you review this page periodically.

## Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us:

- Support URL: [https://aoi-27.github.io/privacy_policy/sumi/privacy-policy-en.html](https://aoi-27.github.io/privacy_policy/sumi/privacy-policy-en.html)

---

This Privacy Policy is governed by the laws of Japan.
