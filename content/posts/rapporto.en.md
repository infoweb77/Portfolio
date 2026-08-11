+++
title = 'Rapporto'
date = 2026-06-30T07:07:07+01:00
draft = false
+++
## Senior iOS Developer.
#### March 2021 — June 2026.
#### www.rapporto.ru

### Product:
Rapporto is a B2B platform enabling banks and large retailers to send personalized push notifications with interactive multimedia content to their clients.

### Key Achievements:

#### SDK Architecture & Functionality.

Designed the architecture for two Rapporto iOS Push SDKs (Obj-C and Swift). The library ensures the delivery of push notification statuses (Delivered / Opened / Swiped) to the server. Correctly handles diverse content types - images, HTML, GIFs, video, and audio files. Added the ability to configure the app group name via the info.plist file.

#### Implementation of Live Activities and Dynamic Island.

Implementing Live Activities for the Swift SDK was a complex and interesting challenge. It required enabling dynamic data updates on the Lock Screen (e.g., delivery status or currency exchange rates) in real-time. This feature resulted in an average **15% increase in CTR** for clients' marketing campaigns.

#### Security and Compliance with 152-FZ.

Integrated encryption for HTTP request headers, protected the SDK from debugging, and obfuscated the library's internal logic by configuring symbol visibility (Visibility Hidden) and verifying the final ARM64 binary using Ghidra.
Collaborated with the team to develop a technology for content masking and dynamic substitution to comply with Federal Law No. 152-FZ, eliminating the need to transmit personal data to external servers. Implemented the client-side part of this technology in my SDKs.

#### Build Automation and Distribution.

Wrote a Shell script that automatically generates `podspec`, `Package.swift`, and archives binaries. Publishing the SDK is now a single-command process, eliminating human error and accelerating update releases. Integration time for B2B clients was reduced to 30 minutes, reaching a total audience of 20+ applications.

#### Demo Applications and Documentation.

Created 6 demo applications (3 native iOS + 2 cross-platform for Flutter and React Native + PWA for web push), serving as guides for developers integrating the SDK. Combined with detailed documentation, this reduced support inquiries by 70%.

Demo Apps: [Obj-C](https://github.com/zgr-im/zgr-push-service-ios-sdk/tree/main/sample_Objective-C) and [Swift](https://github.com/zgr-im/zgr-push-service-ios-sdk/tree/main/sample_Swift)

Documentation Examples:
- iOS - SDK Integration [Manually](https://doc.rapporto.ru/push_service/sdk/mobile/manually_install.html), via Package Managers [Cocoapods](https://doc.rapporto.ru/push_service/sdk/mobile/pod_install.html), [SPM](https://doc.rapporto.ru/push_service/sdk/mobile/spm_install.html).
- React Native - [Integration](https://doc.rapporto.ru/push_service/sdk/mobile/RN_install.html) and [Usage](https://doc.rapporto.ru/push_service/sdk/mobile/RN_usage.html).
- Flutter - [Integration](https://doc.rapporto.ru/push_service/sdk/mobile/flutter_install.html) and [Usage](https://doc.rapporto.ru/push_service/sdk/mobile/flutter_usage.html).

**Details on each demo application:**

---

**• TestApp (Native iOS, Obj-C SDK)**
Application for testing the Objective-C version of the SDK.

{{< gallery layout="grid" id="gallery1" >}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_1.jpg" caption="Main Screen">}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_2.jpg" caption="History Screen">}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_4.jpg" caption="Network Debug">}}
{{< /gallery >}}

<style>
.video-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}
@media (max-width: 768px) {
  .video-grid {
    grid-template-columns: 1fr;
  }
}
.video-grid video {
  width: 100%;
  height: auto;
}
</style>

<div class="video-grid">
  <div>
    {{< video src="video/imagepush.mp4" >}}
     <p style="text-align: center; margin-top: 8px;">Push with image and buttons</p>
  </div>
  <div>
    {{< video src="video/videopush.mp4" >}}
     <p style="text-align: center; margin-top: 8px;">Push with video</p>
  </div>
</div>

---

**• Rapporto Push (Native iOS, Swift SDK)**
Primary demo application for the Swift SDK with full functionality.

{{< gallery layout="grid" id="gallery2" >}}
  {{< figure src="images/rapp/la/LA_1.jpg" caption="Live Activity on Lock Screen">}}
  {{< figure src="images/rapp/la/LA_2.jpg" caption="Dynamic Island on Lock Screen">}}
  {{< figure src="images/rapp/la/LA_3.jpg" caption="Example of masked text in a push notification">}}
{{< /gallery >}}

<div class="video">
  {{< video src="video/demo.mp4" >}}
    <p style="text-align: left; margin-top: 8px;">Rapporto Push App Overview Video</p>
</div>

---

<div class="video">
  {{< video src="video/LA_video.mp4" >}}
    <p style="text-align: center; margin-top: 8px;">Live Activities in the Rapporto Push App</p>
</div>

---

**• React Native Application** (Swift SDK Integration)

{{< gallery layout="grid" id="gallery5"  >}}
  {{< figure src="images/rapp/rn/RN_3.jpg" caption="Push History, Simple Text Push">}}
  {{< figure src="images/rapp/rn/RN_2.jpg" caption="Push History, Push with Image">}}
  {{< figure src="images/rapp/rn/RN_4.jpg" caption="Push on Lock Screen with PNG Image">}}
{{< /gallery >}}

---

**• Flutter Application** (Swift SDK Integration)

<div class="video">
  {{< video src="video/flutter_1.mp4" >}}
    <p style="text-align: left; margin-top: 8px;">Push with image in Flutter app</p>
</div>

---

<div class="video">
  {{< video src="video/flutter_21.mp4" >}}
    <p style="text-align: center; margin-top: 8px;">Simulator and macOS Console - Sending Delivered status to server on push arrival</p>
</div>

---

**• PWA (Web Push SDK)**.
PWA application with an integrated Web Push SDK.

{{< gallery layout="grid" id="gallery4" >}}
  {{< figure src="images/rapp/web/web_1.jpg" caption="Push on iOS device">}}
  {{< figure src="images/rapp/web/web_2.jpg" caption="Push on Google Pixel">}}
  {{< figure src="images/rapp/web/entry.jpg" caption="Splash Screen">}}
  {{< figure src="images/rapp/web/login.jpg" caption="Login Screen">}}
  {{< figure src="images/rapp/web/empty.jpg" caption="No Notifications Yet">}}
  {{< figure src="images/rapp/web/pushes.jpg" caption="Push History">}}
{{< /gallery >}}

---

#### Ensured unit test coverage of the SDK core at 70%.

{{< gallery layout="grid" id="gallery41" >}}
  {{< figure src="images/rapp/pushes/old_app/tests_1.png" caption="127 unit tests, all green">}}
{{< /gallery >}}

#### Web Push SDK

In 2025, I developed a JavaScript SDK for PWA and browsers with support for Service Workers, IndexedDB, and sending push statuses to the server. Also implemented dynamic content substitution, images, and buttons in pushes (where browser-supported).
*The corresponding gallery is provided above in the PWA section.*

#### Kotlin MultiPlatform
In late autumn 2025, together with an Android developer, we started a project for a new client application (currently on hold due to changing business priorities); UI development using SwiftUI.

{{< gallery layout="grid" id="gallery3" >}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_4.jpg" caption="Main Screen. General info on sends and statuses across all channels">}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_5.jpg" caption="Detailed info on sends and statuses per channel">}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_1.jpg" caption="Analytics Section. Detailed Report Screen">}}
{{< /gallery >}}

---

**Tech Stack:** Swift, Objective‑C, JavaScript, Dart; UIKit, SnapKit; Core Data, AppGroups, Live Activities/ActivityKit; Swinject; CocoaPods, SPM, Carthage; Fastlane, XcodeGen; GCD, async/await; XCTest.