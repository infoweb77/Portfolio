---
date: '2016-02-27T18:25:21+03:00'
draft: false
title: 'Learning'
---

## iOS Platform Studies
#### August 2010 — February 2016.

A period of active exploration of the iOS ecosystem (Objective-C, early Swift). Completed numerous pet projects to learn specialized technologies.

---

## System Programming & Data Handling:

### Classic Photos App.

Solved a UI blocking issue during batch photo processing. Offloaded Sepia filter application (Core Image) to concurrent NSOperation queues, ensuring a smooth UX during mass photo loading.

{{< gallery layout="grid" id="gallery29" >}}
  {{< figure src="images/apps/photo/photo1.jpg" >}}
  {{< figure src="images/apps/photo/photo2.jpg" >}}
  {{< figure src="images/apps/photo/photo3.jpg" >}}
{{< /gallery >}}

Language: Swift 1.2. Core Framework: Core Image.

---

### iRegex App.

Studied regular expressions to build a flexible validation system for user input forms.

{{< gallery layout="grid" id="gallery32" >}}
  {{< figure src="images/apps/reg/reg1.jpg" >}}
  {{< figure src="images/apps/reg/reg2.jpg" >}}
  {{< figure src="images/apps/reg/reg3.jpg" >}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: Core Graphics, Foundation, UIKit.

---

### ConferencePlannerForGeeks App.

Integrated with system Calendar and Reminders applications to automate conference trip planning.

{{< gallery layout="grid" id="gallery33" >}}
  {{< figure src="images/apps/plan/plan1.jpg" >}}
  {{< figure src="images/apps/plan/plan2.jpg" >}}
  {{< figure src="images/apps/plan/plan3.jpg" >}}
  {{< figure src="images/apps/plan/plan4.jpg" >}}
  {{< figure src="images/apps/plan/plan5.jpg" >}}
  {{< figure src="images/apps/plan/plan6.jpg" >}}
{{< /gallery >}}

Language: Objective-C.

---

## Complex Interfaces & Graphics:

### Flikr Search for iPad App.

Explored asynchronicity and UI Collection View. Created 4 custom cell layouts and optimized the loading of high-resolution images from the Flickr API without performance degradation during scrolling.

{{< gallery layout="grid" id="gallery23" >}}
  {{< figure src="images/apps/flikr/flikr1.png" >}}
  {{< figure src="images/apps/flikr/flikr2.png" >}}
  {{< figure src="images/apps/flikr/flikr3.png" >}}
  {{< figure src="images/apps/flikr/flikr4.png" >}}
  {{< figure src="images/apps/flikr/flikr5.png" >}}
  {{< figure src="images/apps/flikr/flikr6.png" >}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: Core Graphics, QuartzCore, UIKit, MessageUI.

---

### Textkit Magazine App.

Parsed the book Alice's Adventures in Wonderland to create a multi-column layout with dynamic pagination and text styling within a standard UIKit application.

{{< gallery layout="grid" id="gallery27" >}}
  {{< figure src="images/apps/read/read1.jpg" >}}
  {{< figure src="images/apps/read/read2.jpg" >}}
  {{< figure src="images/apps/read/read3.jpg" >}}
  {{< figure src="images/apps/read/read4.jpg" >}}
  {{< figure src="images/apps/read/read5.jpg" >}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: TextKit, Core Graphics, Foundation, UIKit.

---

### Googly Puff App.

Detected faces in photos from the device library in a background thread and overlaid animated effects (googly eyes) in real-time.

{{< gallery layout="grid" id="gallery28" >}}
  {{< figure src="images/apps/good/goog1.jpg" >}}
  {{< figure src="images/apps/good/goog2.jpg" >}}
  {{< figure src="images/apps/good/goog3.jpg" >}}
  {{< figure src="images/apps/good/goog4.jpg" >}}
  {{< figure src="images/apps/good/goog5.jpg" >}}
  {{< figure src="images/apps/good/goog6.jpg" >}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: Core Graphics, Core Image, QuartzCore, UIKit.

---

### NASA TV App.

Explored Grand Central Dispatch (GCD) and the Multitasking API. Used background queues to download video and app assets.

{{< gallery layout="grid" id="gallery25" >}}
  {{< figure src="images/apps/nasa/NASA_TV_1.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_2.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_3.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_4.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_5.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_6.jpg" >}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: Core Graphics, Security, MobileCoreServices, QuartzCore, CFNetwork, AudioToolbox, Parse, MediaPlayer, CoreData, UIKit, System Configuration, Multitasking API.

---

## Third-Party Service Integrations:

### Cafe Hunter App.

Used the Facebook Graph API to search for local businesses near the user (LBS service).

{{< gallery layout="grid" id="gallery24" >}}
  {{< figure src="images/apps/hunter/hunter1.jpg" >}}
  {{< figure src="images/apps/hunter/hunter2.jpg" >}}
  {{< figure src="images/apps/hunter/hunter3.jpg" >}}
  {{< figure src="images/apps/hunter/hunter4.jpg" >}}
  {{< figure src="images/apps/hunter/hunter5.jpg" >}}
  {{< figure src="images/apps/hunter/hunter6.jpg" >}}
{{< /gallery >}}

Language: Swift 1.2. Core Framework: Facebook iOS SDK.

---

### FlyMeThere App.

Built multi-modal routes (car → plane → car) between arbitrary points on Earth.

{{< gallery layout="grid" id="gallery31" >}}
  {{< figure src="images/apps/fly/fly1.jpg" >}}
  {{< figure src="images/apps/fly/fly2.jpg" >}}
  {{< figure src="images/apps/fly/fly3.jpg" >}}
  {{< figure src="images/apps/fly/fly4.jpg" >}}
  {{< figure src="images/apps/fly/fly5.jpg" >}}
  {{< figure src="images/apps/fly/fly5.jpg" >}}
{{< /gallery >}}

Language: Objective-C. Core Framework: MapKit.

---

## Hardware-Specific Development & PassKit:

### Pass Preview App.

Loaded, signed with a valid certificate, and correctly displayed pkpass tickets in the simulator.

{{< gallery layout="grid" id="gallery26" >}}
  {{< figure src="images/apps/pass/pass1.jpg" >}}
  {{< figure src="images/apps/pass/pass2.jpg" >}}
  {{< figure src="images/apps/pass/pass3.jpg" >}}
  {{< figure src="images/apps/pass/pass4.jpg" >}}
  {{< figure src="images/apps/pass/pass5.jpg" >}}
  {{< figure src="images/apps/pass/pass6.jpg" >}}
{{< /gallery >}}

Language: Objective-C. Core Framework: PassKit.

---

## Game Development:

### Star Combat

Programmed game logic, collision physics, and particle systems (fire, explosions).

{{< gallery layout="grid" id="gallery34" >}}
  {{< figure src="images/games/star/star1.png" >}}
  {{< figure src="images/games/star/star2.png" >}}
  {{< figure src="images/games/star/star3.png" >}}
  {{< figure src="images/games/star/star4.png" >}}
  {{< figure src="images/games/star/star5.png" >}}
  {{< figure src="images/games/star/star6.png" >}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: SpriteKit, Core Graphics, Core Motion, QuartzCore, AVFoundation, UIKit.

---

### Monkey Jump

Integrated with Game Center: sending challenges to friends and posting results to global leaderboards.

{{< gallery layout="grid" id="gallery35" >}}
  {{< figure src="images/games/monkey/monkey1.png" caption="Game Center Login">}}
  {{< figure src="images/games/monkey/monkey2.png" caption="Game Entry">}}
  {{< figure src="images/games/monkey/monkey3.png" caption="Main Game Screen">}}
  {{< figure src="images/games/monkey/monkey4.png" caption="Game Over Screen">}}
  {{< figure src="images/games/monkey/monkey5.png" caption="Leaderboard Page">}}
  {{< figure src="images/games/monkey/monkey6.png" caption="Player Achievements Page">}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: GameKit, Core Graphics, SpriteKit, UIKit.

---

### Hangman

Configured In-App Purchases for game monetization.

{{< gallery layout="grid" id="gallery36" >}}
  {{< figure src="images/games/hang/hang1.png" >}}
  {{< figure src="images/games/hang/hang2.png" >}}
  {{< figure src="images/games/hang/hang3.png" >}}
  {{< figure src="images/games/hang/hang4.png" >}}
  {{< figure src="images/games/hang/hang5.png" >}}
  {{< figure src="images/games/hang/hang6.png" >}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: StoreKit, Core Graphics, QuartzCore, AVFoundation, UIKit.

---

### Reversi

Wrote basic AI logic for a Reversi game. The computer plays as black.

{{< gallery layout="grid" id="gallery37" >}}
  {{< figure src="images/games/rever/rever1.png" >}}
  {{< figure src="images/games/rever/rever2.png" >}}
  {{< figure src="images/games/rever/rever3.png" >}}
{{< /gallery >}}

Language: Swift 1.2. Core Frameworks: Foundation, UIKit.

---

### XORK!

An experiment in separating game logic (JS engine) and presentation (Native UI) within a single application.

{{< gallery layout="grid" id="gallery38" >}}
  {{< figure src="images/games/xor/xor1.png" >}}
  {{< figure src="images/games/xor/xor2.png" >}}
  {{< figure src="images/games/xor/xor3.png" >}}
{{< /gallery >}}

Languages: Objective-C, JavaScript. Core Frameworks: Foundation, UIKit, JavaScript Core, Core Graphics.

---