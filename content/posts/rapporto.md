+++
title = 'Раппорто'
date = 2026-06-30T07:07:07+01:00
draft = false
+++
## Старший iOS-программист.
#### Март 2021 — Июнь 2026.
#### www.rapporto.ru 

### Продукт:  
Rapporto — это B2B-платформа, через которую банки и крупные ритейлеры отправляют клиентам персонализированные push-уведомления c интерактивным мультимедиа-контентом. 

### Ключевые достижения:

#### Проектирование архитектуры SDK и безопасность.

Спроектировал архитектуру двух Rapporto iOS Push SDK (Obj-C и Swift). Библиотека обеспечивает доставку на сервер статусов пуш-сообщения (Delivered / Opened / Swiped). Реализовано шифрование сетевых запросов, защита SDK от дебаг-режима. Корректно работает с разнообразным контентом - картинки, html, gif, видео- и аудио-файлы. Добавлена возможность настройки имени группы приложения через файл info.plist. 

#### Внедрение Live Activities и Dynamic Island.

Одной из сложных и интересных задач стала реализация Live Activities для Swift SDK. Нужно было обеспечить динамическое обновление данных на Lock Screen (например, статус доставки заказа или курс валюты) в реальном времени. Это нововведение дало клиентам рост CTR маркетинговых кампаний **в среднем на 15%**.

#### Безопасность и соответствие 152-ФЗ.

Разработали командой технологию маскирования и динамической подмены контента для соблюдения ФЗ-152, исключив передачу ПДн на внешние серверы. Реализовал клиентскую часть технологии в своих SDK. 

#### Автоматизация сборки и дистрибуции.

Написал скрипт Shell, который автоматически генерирует `podspec`, `Package.swift` и архивирует бинарники. Теперь релиз SDK происходит одной командой, что исключает человеческий фактор и ускорило выпуск обновлений в несколько раз. Время интеграции для B2B-клиентов сократилось до 30 минут, общая аудитория — 20+ приложений. 

#### Демо-приложения и документация.

Создал 6 демо-приложений (3 нативных iOS + 2 кроссплатформенных на Flutter и React Native + PWA для web-пушей), которые используются в качестве руководства для разработчиков при интеграции SDK в их приложения. Вместе с подробной документацией это сократило поток вопросов в техподдержку на 70%. 

Демо-приложения: [Obj-C](https://github.com/zgr-im/zgr-push-service-ios-sdk/tree/main/sample_Objective-C) и [Swift](https://github.com/zgr-im/zgr-push-service-ios-sdk/tree/main/sample_Swift)

Примеры документации: 
- iOS - интеграция SDK в приложение [в ручном режиме](https://doc.rapporto.ru/push_service/sdk/mobile/manually_install.html), с помощью менеджеров пакетов [Cocoapods](https://doc.rapporto.ru/push_service/sdk/mobile/pod_install.html), [SPM](https://doc.rapporto.ru/push_service/sdk/mobile/spm_install.html).; 
- React Native - [интеграция](https://doc.rapporto.ru/push_service/sdk/mobile/RN_install.html) и [использование](https://doc.rapporto.ru/push_service/sdk/mobile/RN_usage.html); 
- Flutter - [интеграция](https://doc.rapporto.ru/push_service/sdk/mobile/flutter_install.html) и [использование](https://doc.rapporto.ru/push_service/sdk/mobile/flutter_usage.html).


**Подробнее о каждом демо-приложении:**

---

**• TestApp (нативное iOS, Obj-C SDK)**  
Приложение для тестирования Obj-C версии SDK.

{{< gallery layout="grid" id="gallery1" >}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_1.jpg" caption="Основной экран">}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_2.jpg" caption="Экран истории">}}
  {{< figure src="images/rapp/pushes/old_app/oldApp_4.jpg" caption="Дебаг сетевых запросов">}}
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
    {{< video src="video/imagepush.MP4" >}}
     <p style="text-align: center; margin-top: 8px;">пуш с картинкой и кнопками</p>
  </div>
  <div>
    {{< video src="video/videopush.MP4" >}}
     <p style="text-align: center; margin-top: 8px;">Пуш с видео</p>
  </div>
</div>

---

**• Rapporto Push (нативное iOS, Swift SDK)**  
Основное демо-приложение для Swift SDK с полным функционалом.

{{< gallery layout="grid" id="gallery2" >}}
  {{< figure src="images/rapp/la/LA_1.jpg" caption="LA на Lock Screen">}}
  {{< figure src="images/rapp/la/LA_2.jpg" caption="Dynamic Island на Lock Screen">}}
  {{< figure src="images/rapp/la/LA_3.jpg" caption="пример маскированного текста в пуш-сообщении">}}
{{< /gallery >}}

<div class="video">
  {{< video src="video/new_demo.MP4" >}}
    <p style="text-align: left; margin-top: 8px;">Видеообзор приложения Rapporto Push</p>
</div>

---

<div class="video">
  {{< video src="video/LA_video.mp4" >}}
    <p style="text-align: center; margin-top: 8px;">Live Activities в приложении Rapporto Push</p>
</div>

---

**• React Native-приложение** (интеграция Swift SDK) 

{{< gallery layout="grid" id="gallery5"  >}}
  {{< figure src="images/rapp/rn/RN_3.jpg" caption="История пушей, простые текстовые пуши">}}
  {{< figure src="images/rapp/rn/RN_2.jpg" caption="История пушей, пуш с картинкой">}}
  {{< figure src="images/rapp/rn/RN_4.jpg" caption="Пуш на Lock Sreen с png-картинкой">}}
{{< /gallery >}}

---

**• Flutter-приложение** (интеграция Swift SDK) 

<div class="video">
  {{< video src="video/flutter_1.mp4" >}}
    <p style="text-align: left; margin-top: 8px;">Пуш с картинкой в приложении Flutter</p>
</div> 

---

<div class="video">
  {{< video src="video/flutter_21.mp4" >}}
    <p style="text-align: center; margin-top: 8px;">Симулятор и консоль macOS - отправка статуса Delivered на сервер в момент прихода пуша</p>
</div> 

---

**• PWA (Web Push SDK)**.
PWA-приложение с встроенной Web Push SDK.

{{< gallery layout="grid" id="gallery4" >}}
  {{< figure src="images/rapp/web/web_1.jpg" caption="Пуш на ios-устройстве">}}
  {{< figure src="images/rapp/web/web_2.jpg" caption="Пуш на Google Pixel">}}
  {{< figure src="images/rapp/web/entry.jpg" caption="Сплеш-скрин">}}
  {{< figure src="images/rapp/web/login.jpg" caption="Экран логина" >}}
  {{< figure src="images/rapp/web/empty.jpg" caption="Уведомлений пока нет">}}
  {{< figure src="images/rapp/web/pushes.jpg" caption="История пушей">}}
{{< /gallery >}}

---

#### Обеспечил юнит-покрытие кода SDK на уровне 70%. 

{{< gallery layout="grid" id="gallery41" >}}
  {{< figure src="images/rapp/pushes/old_app/tests_1.png" caption="127 unit-тестов, все зеленые" >}}
{{< /gallery >}} 

#### Web Push SDK
 
В 2025году написал на JavaScript SDK для PWA и браузеров с поддержкой Service Workers, IndexedDB, отправкой на сервер статусов пушей. Также реализованы динамическая подмена контента, картинки и кнопки в пушах (если поддерживает браузер).
*Соответствующая галерея уже приведена выше в разделе PWA.*

#### Kotlin MultiPlatform
В конце осени 2025 года совместно с Android-разработчиком начали проект нового приложения для клиентов (заморожен из-за смены приоритетов бизнеса), вёрстку вёл на SwiftUI.

{{< gallery layout="grid" id="gallery3" >}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_4.jpg" caption="Главный экран. Общая информация по отправкам и статусам по всем направлениям">}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_5.jpg" caption="Детальная информация по отправкам и статусам по направлению">}}
  {{< figure src="images/rapp/pushes/newApp_KMP/newApp_1.jpg" caption="Раздел Аналитики. Экран детального отчета">}}
{{< /gallery >}}

---

**Стек:** Swift, Objective‑C, JavaScript, Dart; UIKit, SnapKit; Core Data, AppGroups, Live Activities/ActivityKit; Swinject; CocoaPods, SPM, Carthage; Fastlane, XcodeGen; GCD, async/await; XCTest.
