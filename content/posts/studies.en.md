---
date: '2016-02-28T18:25:21+03:00'
draft: false
title: 'Research Projects'
---
#### January 2013 — June 2026.

### Timezero Game Forum App.
#### 2013

Developed a native iOS application for interacting with the Timezero game forum (not a webview).

Core functionality: browsing sections and pages, refreshing articles, user authorization, editing and publishing posts, and creating new topics. Implemented networking, HTML parsing, content rendering with necessary graphics, and page caching and updating.

{{< gallery layout="grid" id="gallery22" >}}
  {{< figure src="images/personal/forum/1.png" caption="Forum Main Screen">}}
  {{< figure src="images/personal/forum/2.png" caption="Forum Sections">}}
  {{< figure src="images/personal/forum/3.png" caption="Topic Page Selection">}}
  {{< figure src="images/personal/forum/4.png" caption="Post Creation Form">}}
  {{< figure src="images/personal/forum/5.png" caption="Post Creation Form">}}
  {{< figure src="images/personal/forum/6.png" caption="Forum Page">}}
{{< /gallery >}}

Language: Objective-C. Core frameworks: CoreText, ImageIO, Core Graphics, Core Image, UIKit, System Configuration.

---

### Music Player App.

Integrated OAuth authorization via the native VKontakte SDK, streamed audio, and managed the playback queue.

{{< gallery layout="grid" id="gallery30" >}}
  {{< figure src="images/personal/music/music1.jpg" >}}
  {{< figure src="images/personal/music/music2.jpg" >}}
  {{< figure src="images/personal/music/music3.jpg" >}}
{{< /gallery >}}

Language: Objective-C. Core Frameworks: UIKit, Core Graphics, VK iOS SDK.

---

### Gists App.
#### 2018

Explored the Github REST API, OAuth 2.0 authorization, and pagination of large data lists.

{{< gallery layout="grid" id="gallery14">}}
  {{< figure src="images/personal/gists/gists_2.jpg" >}}
  {{< figure src="images/personal/gists/gists_3.jpg" >}}
  {{< figure src="images/personal/gists/gists_5.jpg" >}}
  {{< figure src="images/personal/gists/gists_6.jpg" >}}
  {{< figure src="images/personal/gists/gists_7.jpg" >}}
  {{< figure src="images/personal/gists/gists_10.jpg" >}}
{{< /gallery >}}

Project Language: Swift 3.0.

[Project on Github](https://github.com/infoweb77/Github-Gists)

---

### Google Maps Utils.

Optimized the processing of over 7500 geo-objects on a map by porting the algorithm from Objective-C to pure Swift.

{{< gallery layout="grid" id="gallery19" >}}
  {{< figure src="images/personal/maps/maps1.jpg" >}}
  {{< figure src="images/personal/maps/maps2.jpg" >}}
  {{< figure src="images/personal/maps/maps3.jpg" >}}
{{< /gallery >}}

Language: Swift 2.0. Core Framework: GoogleMaps.

[Project on Github](https://github.com/infoweb77/GoogleMapsUtils_test)

---

### "Weather in Russia" App.
#### 2019

Designed the UI and architecture for a weather application based on data provided by the OpenWeather API. Displayed weather for the current location and saved cities.

{{< gallery layout="grid" id="gallery10" >}}
  {{< figure src="images/personal/weather/weather_1.jpg" caption="Main Screen. Current Location/Favorites">}}
  {{< figure src="images/personal/weather/weather_2.jpg" caption="Weather in Current Location.">}}
  {{< figure src="images/personal/weather/weather_3.jpg" caption="Weather in Moscow.">}}
  {{< figure src="images/personal/weather/weather_4.jpg" caption="Weather in St. Petersburg.">}}
  {{< figure src="images/personal/weather/weather_5.jpg" caption="Weather in Yeysk.">}}
  {{< figure src="images/personal/weather/weather_6.jpg" caption="Editing the Main Screen.">}}
{{< /gallery >}}

Language: Swift 4.2.
Core Frameworks: SnapKit, CoreData, Alamofire, Swinject.

---

### ArchWeather App Collection.
#### 2019

To practically explore the differences in architectural approaches for iOS apps, I created a collection of simple single-screen weather applications using various architectures (MVC, MVP, MVVM, VIPER, Redux, etc.).

Implemented Architectural Patterns:
- **mvc** - Standard MVC template recommended by Apple. Uses the composition pattern to reduce ViewController size.
- **mvp** - Standard MVP template.
- **mvvm-closures** - Binds ViewController and ViewModel using Swift closures and functions.
- **mvvm-rxswift-pure** - Uses RxSwift and Observables as the binding mechanism between ViewController and ViewModel.
- **mvvm-rxswift-subjects-observables** - Uses RxSwift with Observables as ViewModel outputs and Subjects as ViewModel inputs.
- **reactorkit** - Uses ReactorKit as a framework for reactive and unidirectional Swift applications.
- **rxfeedback-mvc** - Uses RxFeedback within the MVC architecture.
- **viper** - Uses the VIPER architecture.

Language: Swift 4.2.

[Project on Github](https://github.com/infoweb77/iOS-architecture-examples)

---

### Data Structures & Algorithms in Swift.
#### 2020

To prepare for the algorithmic portion of interviews, I studied fundamental data structures and algorithms based on the book **Data Structures & Algorithms in Swift** by the raywenderlich team.

{{< gallery layout="grid" id="gallery42"  >}}
  {{< figure src="images/webb/struct.jpg" >}}
{{< /gallery >}}

Language: Swift 4.2.

[Project on Github](https://github.com/infoweb77/Algorithms)

---

### SuperStorage App
#### 2025

**SuperStorage** is a cloud file manager that allows users to browse files, download them for local viewing, and track progress. The main goal was to practically explore Swift's modern concurrency model (async/await) and the Combine framework, comparing different asynchronous data loading strategies.

{{< gallery layout="grid" id="gallery6" >}}
  {{< figure src="images/personal/storage/storage_1.jpg" caption="File List">}}
  {{< figure src="images/personal/storage/storage_2.jpg" caption="Tariff Plans">}}
  {{< figure src="images/personal/storage/storage_4.jpg" caption="File Download Progress">}}
  {{< figure src="images/personal/storage/storage_5.jpg" caption="Downloaded File Preview">}}
  {{< figure src="images/personal/storage/storage_6.jpg" caption="Parallel Download of File Parts">}}
{{< /gallery >}}

[Project on Github](https://github.com/infoweb77/SuperStorage)

---

### Kuchi App
#### 2025

A flashcard application for learning Japanese.
The main goal was to learn SwiftUI adaptive layout techniques. Worked with text and images, text fields and buttons, created a simple registration form, containers, controls (switches, color pickers), @State & @Binding properties, gesture recognition, etc.

iOS Version

{{< gallery layout="grid" id="gallery7" >}}
  {{< figure src="images/personal/kuchi/kuchi_1.jpg" caption="Login Screen">}}
  {{< figure src="images/personal/kuchi/kuchi_2.jpg" caption="Study Card">}}
  {{< figure src="images/personal/kuchi/kuchi_3.jpg" caption="Card Swiping">}}
  {{< figure src="images/personal/kuchi/kuchi_5.jpg" caption="Check Screen">}}
  {{< figure src="images/personal/kuchi/kuchi_6.jpg" caption="Correct Answer">}}
  {{< figure src="images/personal/kuchi/kuchi_7.jpg" caption="Settings Screen">}}
  {{< figure src="images/personal/kuchi/kuchi_8.jpg" caption="Card Color Selection">}}
  {{< figure src="images/personal/kuchi/kuchi_10.jpg" caption="Dark Theme">}}
  {{< figure src="images/personal/kuchi/kuchi_12.jpg" caption="Card Swiping">}}
{{< /gallery >}}

macOS Version

{{< gallery layout="grid" id="gallery8" >}}
  {{< figure src="images/personal/kuchi/kuchi_14.jpg" caption="Login Screen">}}
  {{< figure src="images/personal/kuchi/kuchi_15.jpg" caption="Settings Screen">}}
  {{< figure src="images/personal/kuchi/kuchi_16.jpg" caption="Study Card">}}
  {{< figure src="images/personal/kuchi/kuchi_17.jpg" caption="Correct Answer">}}
  {{< figure src="images/personal/kuchi/kuchi_18.jpg" caption="Study Card">}}
{{< /gallery >}}

[Kuchi on Github](https://github.com/infoweb77/Kuchi)

---

### Mountain Airport App
#### 2025

Continued learning SwiftUI layout.
Topics covered: app navigation, advanced data lists, modal sheets and alerts, custom graphics and animation.

{{< gallery layout="grid" id="gallery9" >}}
  {{< figure src="images/personal/airport/airport_1.jpg" caption="Login Screen">}}
  {{< figure src="images/personal/airport/airport_2.jpg" caption="Flight Time">}}
  {{< figure src="images/personal/airport/airport_3.jpg" caption="Achievements Screen">}}
  {{< figure src="images/personal/airport/airport_6.jpg" caption="Search">}}
  {{< figure src="images/personal/airport/airport_7.jpg" caption="Search Results">}}
  {{< figure src="images/personal/airport/airport_8.jpg" caption="Departing Flights">}}
  {{< figure src="images/personal/airport/airport_9.jpg" caption="Flight Information">}}
  {{< figure src="images/personal/airport/airport_10.jpg" caption="Flight Information">}}
  {{< figure src="images/personal/airport/airport_11.jpg" caption="Terminal Information">}}
{{< /gallery >}}

[MountainAirport on Github](https://github.com/infoweb77/MountainAirport)

---