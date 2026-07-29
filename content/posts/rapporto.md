+++
title = 'Раппорто'
date = 2026-06-30T07:07:07+01:00
draft = false
+++
## Старший iOS-программист.
#### Март 2021 — Июнь 2026.
#### www.rapporto.ru 

### Продукт: платформа Rapporto Push для отправки персонализированных уведомлений с поддержкой мультимедиа-контента и Live Activities.

#### Ключевые достижения:

- **Разработал 3 SDK (iOS Obj-C, iOS Swift, Web JS)**, которые используются более чем в 20-и приложениях клиентов компании.
- **Спроектировал архитектуру SDK**, ориентированную на лёгкость интеграции: минимальный порог входа (< 30 минут на интеграцию), гибкая настройка через конфигурационный файл, поддержка всех актуальных пакетных менеджеров.
- **Внедрил Live Activities в Swift SDK** — это позволило клиентам показывать динамические уведомления на Lock Screen и в Dynamic Island.
- **Настроил скрипты для автоматической сборки SDK** в том числе с созданием файлов необходимых для публикации в CocoaPods / SPM / Carthage.
- **Создал эталонные демо-приложения** (4 нативных + 2 кроссплатформенных на Flutter и React Native), которые используются Sales-командой для презентаций клиентам, а также в качестве руководства для разработчиков при интеграции SDK в их приложения.
- **Провёл исследование и внедрил** динамическую подмену контента в пушах для соответствия SDK закону о защите ПД.
- **Провёл исследование и внедрил** мультимедиа-контент в сообщениях (html//images/gif/video/audio).
- **Внедрил** в SDK шифрование определенного контента, защиту от дебага и другие меры безопасности.
- **Обеспечил юнит-покрытие кода SDK на уровне 70%**.

* **WebPush SDK** (5 релизов, 5 задач). 

Функционал - IndexedDB, service worker, безопасность, статусы доставки/просмотра пушей, динамическая подмена контента, картинки и кнопки в пушах (если поддерживает браузер).

#### 4 нативных приложения:
- TestApp (Obj-C + Obj-C SDK, Core Data, Interface Builder, App Groups, Notification Service + Notification Content Extensions, 17 релизов);
- DemoApp (Swift + Swift SDK, Core Data, SnapKit, App Groups, Notification Service + Notification Content Extensions);
- Rapporto Push (Swift + Swift SDK, Core Data, SnapKit, App Groups, Notification Service + Notification Content Extensions, 12 релизов);
- PWA Push App (React + WebPush SDK, Vite, JS, IndexedDB, 5 релизов).

####  2 кроссплатформенных приложения:
- FlutterApp + Swift SDK - пример интеграции Swift SDK в приложение Flutter
- ReactNativeApp + Swift SDK - пример интеграции Swift SDK в приложение React Native

---
		
В 2021 году был реализован Push SDK на языке Obj-C и тестовое приложение для него. 
    
SDK обеспечивает доставку на сервер статусов пуш-сообщения (Delivered / Opened / Swiped). Обеспечено шифрование сетевых запросов, защита SDK от дебаг-режима. Корректно работает с разнообразным контентом - картинки, html, gif, видео- и аудио-файлы. Добавлена возможность настройки имени группы приложения через файл info.plist. 

Написаны скрипты для публикации SDK как в форме .xcarchive, так и для менеджеров пакетов (Cocoapods и Swift Package Manager). 
    
Создана документация для партнеров по различным вариантам интеграции SDK - [в ручном режиме](https://doc.rapporto.ru/push_service/sdk/mobile/manually_install.html), с помощью менеджеров пакетов [Cocoapods](https://doc.rapporto.ru/push_service/sdk/mobile/pod_install.html), [SPM](https://doc.rapporto.ru/push_service/sdk/mobile/spm_install.html).

В приложение встроен компонент CocoaDebug для дебага сетевых запросов и отслеживания конфигурации приложения.

По просьбе одного из клиентов была проведена доработка - возможность настройки группы для приложения через файл info.plist.

Покрытие SDK unit-тестами составило около 70%.

---

{{< gallery layout="grid" id="gallery1" >}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_1.jpg" >}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_2.jpg" >}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_3.jpg" >}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_4.jpg" >}}
  {{< figure src="images/rapp/pushes/old_app/screen2.png" >}}
  {{< figure src="images/rapp/pushes/old_app/tests_1.png" >}}
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
    {{< video src="video/image+buttons1.MP4" >}}
     <p style="text-align: center; margin-top: 8px;">Пуш с кноками</p>
  </div>
  <div>
    {{< video src="video/video1.MP4" >}}
     <p style="text-align: center; margin-top: 8px;">Пуш с видео</p>
  </div>
</div>

---

В 2023 году Push SDK был переписан на язык Swift и также было написано новое тестовое приложение.
    
Добавлен новый функционал - работа с Live Activities и с пушами с чувствительными данными - когда пуш отсылается с маскированием данных (например - персональных), по приходе сообщения на устройство SDK запрашивает информацию у сервера и отображает пуш (пример маскированных данных можно увидеть на третьей картинке).

Была переработана система логгирования SDK - логи стали выводиться в нативную консоль macOS (пример работы с консолью можно увидеть в разделе Flutter, 2-ое видео). 

---

{{< gallery layout="grid" id="gallery2" >}}
  {{< figure src="images/rapp/la/LA_1.jpg" >}}
  {{< figure src="images/rapp/la/LA_2.jpg" >}}
  {{< figure src="images/rapp/la/LA_3.jpg" >}}
{{< /gallery >}}

{{< video src="video/new_demo.MP4" >}}

{{< video src="video/LA_video.mp4" >}}

---

### Новое приложение для клиентов на основе технологии Kotlin MultiPlatform. 

В конце 2025 года вместе с Android-программистом была начата работа над новым приложением. В настоящее время проект заморожен.

Верстка - SwiftUI.

{{< gallery layout="grid" id="gallery3" >}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_4.jpg" >}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_5.jpg" >}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_1.jpg" >}}
{{< /gallery >}}

---

