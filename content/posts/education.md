---
date: '2016-02-27T18:25:21+03:00'
draft: false
title: 'Обучение'
---

## Изучение платформы iOS
#### Август 2010 — Февраль 2016.

Период активного освоения экосистемы Apple: Objective-C, ранний Swift, ключевые фреймворки и паттерны проектирования. Реализовал десятки pet-проектов, которые позволили глубоко изучить как системные API (Core Data, MapKit, PassKit), так и специализированные технологии (SpriteKit, StoreKit, TextKit, GCD).

----

## Системное программирование и работа с данными:

### Приложение Classic Photos. 

Решал проблему блокировки интерфейса при пакетной обработке фотографий. Вынес применение фильтра Sepia (Core Image) в конкурентные очереди NSOperation, обеспечив плавный UX при массовой загрузке.

{{< gallery layout="grid" id="gallery29" >}}
  {{< figure src="images/apps/photo/photo1.jpg" >}}
  {{< figure src="images/apps/photo/photo2.jpg" >}}
  {{< figure src="images/apps/photo/photo3.jpg" >}}
{{< /gallery >}}

Язык - Swift 1.2. Основной фреймворк - Core Image.

---

### Приложение iRegex. 

Изучение регулярных выражений для создания гибкой системы валидации форм ввода данных пользователя.

{{< gallery layout="grid" id="gallery32" >}}
  {{< figure src="images/apps/reg/reg1.jpg" >}}
  {{< figure src="images/apps/reg/reg2.jpg" >}}
  {{< figure src="images/apps/reg/reg3.jpg" >}}
{{< /gallery >}}

Язык - Objective-C. Основные фреймворки: Core Graphics, Foundation, UIKit.

---

### Приложение ConferencePlannerForGeeks. 

Интеграция с системными приложениями Calendar и Reminders для автоматизации планирования поездок на конференции.

{{< gallery layout="grid" id="gallery33" >}}
  {{< figure src="images/apps/plan/plan1.jpg" >}}
  {{< figure src="images/apps/plan/plan2.jpg" >}}
  {{< figure src="images/apps/plan/plan3.jpg" >}}
  {{< figure src="images/apps/plan/plan4.jpg" >}}
  {{< figure src="images/apps/plan/plan5.jpg" >}}
  {{< figure src="images/apps/plan/plan6.jpg" >}}
{{< /gallery >}}

Язык - Objective-C. 

---

## Работа со сложными интерфейсами и графикой:

### Приложение Flikr Search for iPad. 

Изучал асинхронность и UI Collection View. Создал 4 кастомные раскладки ячеек и оптимизировал загрузку тяжелых изображений из Flickr API без падения производительности при скроллинге.

{{< gallery layout="grid" id="gallery23" >}}
  {{< figure src="images/apps/flikr/flikr1.png" >}}
  {{< figure src="images/apps/flikr/flikr2.png" >}}
  {{< figure src="images/apps/flikr/flikr3.png" >}}
  {{< figure src="images/apps/flikr/flikr4.png" >}}
  {{< figure src="images/apps/flikr/flikr5.png" >}}
  {{< figure src="images/apps/flikr/flikr6.png" >}}
{{< /gallery >}}

Язык - Objective-C. Основные фрэймворки: Core Graphics, QuartzCore, UIKit, MessageUI. 

---

### Приложение Textkit Magazine. 

Парсинг книги Alice's Adventures in Wonderland и создание многоколоночной верстки с динамической пагинацией и стилизацией текста внутри стандартного UIKit-приложения.

{{< gallery layout="grid" id="gallery27" >}}
  {{< figure src="images/apps/read/read1.jpg" >}}
  {{< figure src="images/apps/read/read2.jpg" >}}
  {{< figure src="images/apps/read/read3.jpg" >}}
  {{< figure src="images/apps/read/read4.jpg" >}}
  {{< figure src="images/apps/read/read5.jpg" >}}
{{< /gallery >}}

Язык - Objective-C. Основные фрэймворки: TextKit, Core Graphics, Foundation, UIKit.

---

### Приложение Googly Puff. 

Детекция лиц на фотографиях из библиотеки устройства в фоновом потоке и наложение анимированных эффектов (googly eyes) в реальном времени.

{{< gallery layout="grid" id="gallery28" >}}
  {{< figure src="images/apps/good/goog1.jpg" >}}
  {{< figure src="images/apps/good/goog2.jpg" >}}
  {{< figure src="images/apps/good/goog3.jpg" >}}
  {{< figure src="images/apps/good/goog4.jpg" >}}
  {{< figure src="images/apps/good/goog5.jpg" >}}
  {{< figure src="images/apps/good/goog6.jpg" >}}
{{< /gallery >}}

Язык - Objective-C. Основные фреймворки: Core Graphics, Core Image, QuartzCore, UIKit.

---

### Приложение NASA TV. 

Осваивал Grand Central Dispatch (GCD) и Multitasking API. Применял фоновые очереди для загрузки видео и файлов приложения.

{{< gallery layout="grid" id="gallery25" >}}
  {{< figure src="images/apps/nasa/NASA_TV_1.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_2.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_3.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_4.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_5.jpg" >}}
  {{< figure src="images/apps/nasa/NASA_TV_6.jpg" >}}
{{< /gallery >}}

Язык - Objective-C. Основные фрэймворки: Core Graphics, Security, MobileCoreServices, QuartzCore, CFNetwork, AudioToolbox, Parse, MediaPlayer, CoreData, UIKit, System Configuration, Multitasking API. 

--- 

## Интеграции со сторонними сервисами:

### Приложение Cafe Hunter. 

Использование Facebook Graph API для поиска локального бизнеса поблизости от пользователя (LBS-сервис).

{{< gallery layout="grid" id="gallery24" >}}
  {{< figure src="images/apps/hunter/hunter1.jpg" >}}
  {{< figure src="images/apps/hunter/hunter2.jpg" >}}
  {{< figure src="images/apps/hunter/hunter3.jpg" >}}
  {{< figure src="images/apps/hunter/hunter4.jpg" >}}
  {{< figure src="images/apps/hunter/hunter5.jpg" >}}
  {{< figure src="images/apps/hunter/hunter6.jpg" >}}
{{< /gallery >}}

Язык - Swift 1.2. Основной фрэймворк - Facebook iOS SDK. 

---

### Приложение FlyMeThere. 

Построение мультимодальных маршрутов (авто → авиа → авто) между произвольными точками земного шара.

{{< gallery layout="grid" id="gallery31" >}}
  {{< figure src="images/apps/fly/fly1.jpg" >}}
  {{< figure src="images/apps/fly/fly2.jpg" >}}
  {{< figure src="images/apps/fly/fly3.jpg" >}}
  {{< figure src="images/apps/fly/fly4.jpg" >}}
  {{< figure src="images/apps/fly/fly5.jpg" >}}
  {{< figure src="images/apps/fly/fly5.jpg" >}}
{{< /gallery >}}

Язык - Objective-C. Основной фреймворк - MapKit.

---

## Разработка под конкретное железо и PassKit:

### Приложение Pass Preview. 

Загрузка, подпись валидным сертификатом и корректное отображение pkpass-билетов в симуляторе.

{{< gallery layout="grid" id="gallery26" >}}
  {{< figure src="images/apps/pass/pass1.jpg" >}}
  {{< figure src="images/apps/pass/pass2.jpg" >}}
  {{< figure src="images/apps/pass/pass3.jpg" >}}
  {{< figure src="images/apps/pass/pass4.jpg" >}}
  {{< figure src="images/apps/pass/pass5.jpg" >}}
  {{< figure src="images/apps/pass/pass6.jpg" >}}
{{< /gallery >}}

Язык - Objective-C. Основной фрэймворк - PassKit.

---

## Игровая разработка:

### Star Combat 

Программирование игровой логики, физики столкновений и систем частиц (огонь, взрывы).

{{< gallery layout="grid" id="gallery34" >}}
  {{< figure src="images/games/star/star1.png" >}}
  {{< figure src="images/games/star/star2.png" >}}
  {{< figure src="images/games/star/star3.png" >}}
  {{< figure src="images/games/star/star4.png" >}}
  {{< figure src="images/games/star/star5.png" >}}
  {{< figure src="images/games/star/star6.png" >}}
{{< /gallery >}}

Язык - Objective-C. Основные фреймворки: SpriteKit, Core Graphics, Core Motion, QuartzCore, AVFoundation, UIKit.

--

### Monkey Jump  

Интеграция с Game Center: отправка вызовов (challenges) друзьям и публикация результатов в глобальных лидербордах.

{{< gallery layout="grid" id="gallery35" >}}
  {{< figure src="images/games/monkey/monkey1.png" caption="Вход в Game Center">}}
  {{< figure src="images/games/monkey/monkey2.png" caption="Вход в игру">}}
  {{< figure src="images/games/monkey/monkey3.png" caption="Основное окно игры">}}
  {{< figure src="images/games/monkey/monkey4.png" caption="Экран окончания игры">}}
  {{< figure src="images/games/monkey/monkey5.png" caption="Страница лидеров">}}
  {{< figure src="images/games/monkey/monkey6.png" caption="Страница достижений игрока">}}
{{< /gallery >}}

Язык - Objective-C. Основные фреймворки: GameKit, Core Graphics, SpriteKit, UIKit.

---

### Hangmam  

Настройка In-App Purchases для монетизации игры.

{{< gallery layout="grid" id="gallery36" >}}
  {{< figure src="images/games/hang/hang1.png" >}}
  {{< figure src="images/games/hang/hang2.png" >}}
  {{< figure src="images/games/hang/hang3.png" >}}
  {{< figure src="images/games/hang/hang4.png" >}}
  {{< figure src="images/games/hang/hang5.png" >}}
  {{< figure src="images/games/hang/hang6.png" >}}
{{< /gallery >}}

Язык - Objective-C. Основные фреймворки: StoreKit, Core Graphics, QuartzCore, AVFoundation, UIKit.

---

### Reversi

Написание базовой AI-логики для игры в Реверси. Компьютер играет черными.

{{< gallery layout="grid" id="gallery37" >}}
  {{< figure src="images/games/rever/rever1.png" >}}
  {{< figure src="images/games/rever/rever2.png" >}}
  {{< figure src="images/games/rever/rever3.png" >}}
{{< /gallery >}}

Язык - Swift 1.2. Основные фреймворки: Foundation, UIKit. 

---

### XORK!

Эксперимент по разделению логики (JS-движок) и представления (Native UI) в рамках одного приложения.

{{< gallery layout="grid" id="gallery38" >}}
  {{< figure src="images/games/xor/xor1.png" >}}
  {{< figure src="images/games/xor/xor2.png" >}}
  {{< figure src="images/games/xor/xor3.png" >}}
{{< /gallery >}}

Языки - Objective-C, JavaScript. Основные фреймворки: Foundation, UIKit, JavaScript Core, Core Graphics.

---

