---
date: '2019-09-30T17:10:36+03:00'
draft: false
title: 'MFC Webbankir'
---
## Senior iOS Developer.
#### October 2018 — September 2019.

#### www.webbankir.com

### Product:
An application for managing microloans and consumer lending for Webbankir.

### Key Achievements:

- #### Release Manager.
From February 2019, I took over application release preparation: organizing pre-release testing, final bug fixes, preparing marketing screenshots and App Store texts, and communicating with managers. Over 8 months, I managed **6 releases and 5 hotfixes** — all successfully passed review, **none** were rejected by Apple.

- #### App Redesign.
As part of the redesign, I overhauled the main screen and detailed loan card. Introduced smooth transition animations between states (e.g., expanding the payment schedule), creating the illusion of faster performance on older iPhones. Rewrote/created from scratch: payment screens, partner payment screens, card binding screens, etc. In total, over 60% of the application screens were migrated to the new design.

- #### New Revenue Stream — POS Lending.
Developed the module for processing point-of-sale (POS) loans. Within the first two months post-release, the loan conversion rate increased by 12% compared to the web version of the service. This became a new traffic channel and generated commission income from retail partners.

- #### Reducing Technical Debt.
Proposed migrating the app from callbacks to **Promises** (PromiseKit library). This eliminated complex nested network request calls and reduced bugs related to loading states by **70%**.

- #### Code Quality.
Established and enforced mandatory code reviews within the team of 3 developers, implemented XcodeGen templates, and introduced unified guidelines for naming conventions and organizing class extensions into separate files. This improved code consistency and facilitated collaboration.

---

{{< gallery layout="grid" id="gallery21"  >}}
  {{< figure src="images/webb/webbankir_2.jpg" caption="Main App Screen">}}
  {{< figure src="images/webb/webbankir_1.jpg" caption="Loan Application Screen">}}
  {{< figure src="images/webb/webbankir_3.jpg" caption="Payment Options Selection">}}
  {{< figure src="images/webb/webbankir_4.jpg" caption="Card Payment Screen">}}
  {{< figure src="images/webb/webbankir_5.jpg" caption="Loan History Screen">}}
  {{< figure src="images/webb/webbankir_6.jpg" caption="Loan Calculation and Application Screen">}}
{{< /gallery >}}

---

App Language: Swift 4.2.
Core Frameworks: Alamofire, SnapKit, Promises, RxSwift; Fastlane (for deployment); XcodeGen (for project generation).