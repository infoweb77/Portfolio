---
date: '2016-02-28T18:25:21+03:00'
draft: false
title: 'Исследовательские проекты'
---
#### Январь 2013 — Июнь 2026.

### Форум игры Timezero. 
#### 2013 г.

**Продукт:** Нативное iOS-приложение для работы с форумом игры Timezero (не WebView).

**Выполненные задачи:**
- Реализовал просмотр разделов и страниц, обновление статей, авторизацию, редактирование и публикацию записей, создание новых тем.
- Настроил сетевое взаимодействие, парсинг HTML, отображение контента и графики, кеширование и обновление страниц.

{{< gallery layout="grid" id="gallery22" >}}
  {{< figure src="images/personal/forum/1.png" caption="Главный экран форума">}}
  {{< figure src="images/personal/forum/2.png" caption="Разделы форума">}}
  {{< figure src="images/personal/forum/3.png" caption="Выбор страниц темы">}}
  {{< figure src="images/personal/forum/4.png" caption="Форма для публикации сообщения">}}
  {{< figure src="images/personal/forum/5.png" caption="Форма для публикации сообщения">}}
  {{< figure src="images/personal/forum/6.png" caption="Страница форума">}}
{{< /gallery >}}


Язык - Objective-C. Основные фрэймворки: CoreText, ImageIO, Core Graphics, Core Image, UIKit, System Configuration. 

---

### Приложение Music Player. 
#### 2014 г.

Работа с авторизацией OAuth через нативный SDK ВКонтакте, стриминг аудиопотока и управление очередью воспроизведения.

{{< gallery layout="grid" id="gallery30" >}}
  {{< figure src="images/personal/music/music1.jpg" >}}
  {{< figure src="images/personal/music/music2.jpg" >}}
  {{< figure src="images/personal/music/music3.jpg" >}}
{{< /gallery >}}

Язык - Objective-C. Основные фреймворки: UIKit, Core Graphics, VK iOS SDK.

---

### Приложение Gists. 
#### 2018 г.

**Продукт:** Приложение для работы с Github REST API.

**Выполненные задачи:**
- Изучил авторизацию OAuth 2.0, пагинацию больших списков данных, отображение gist-шаблонов кода с фильтрацией по статусам (Public / Starred / My Gists).

{{< gallery layout="grid" id="gallery14">}}
  {{< figure src="images/personal/gists/gists_2.jpg" >}}
  {{< figure src="images/personal/gists/gists_3.jpg" >}}
  {{< figure src="images/personal/gists/gists_5.jpg" >}}
  {{< figure src="images/personal/gists/gists_6.jpg" >}}
  {{< figure src="images/personal/gists/gists_7.jpg" >}}
  {{< figure src="images/personal/gists/gists_10.jpg" >}}
{{< /gallery >}}

Язык проекта - Swift 3.0. 

[Проект на Github](https://github.com/infoweb77/Github-Gists)

---

### Google Maps Utils. 

**Продукт:** Тестовое приложение для отработки алгоритма кластеризации на Google Maps.

**Выполненные задачи:**
- Оптимизировал обработку >7500 геообъектов на карте, портировав алгоритм с Objective-C на чистый Swift.

{{< gallery layout="grid" id="gallery19" >}}
  {{< figure src="images/personal/maps/maps1.jpg" >}}
  {{< figure src="images/personal/maps/maps2.jpg" >}}
  {{< figure src="images/personal/maps/maps3.jpg" >}}
{{< /gallery >}}

Язык - Swift 2.0. Основной фрэймворк: GoogleMaps. 

[Проект на Github](https://github.com/infoweb77/GoogleMapsUtils_test)

---

### Приложение "Погода в России".
#### 2019 г.

**Продукт:** Погодное приложение на основе OpenWeather API.

**Выполненные задачи:**
- Разработал дизайн и архитектуру, реализовал отображение погоды в текущем местоположении и в сохранённых городах. 
    
{{< gallery layout="grid" id="gallery10" >}}
  {{< figure src="images/personal/weather/weather_1.jpg" caption="Главный экран. Текущее местоположение/Избранное">}}
  {{< figure src="images/personal/weather/weather_2.jpg" caption="Погода в текущем местоположении.">}}
  {{< figure src="images/personal/weather/weather_3.jpg" caption="Погода в Москве.">}}
  {{< figure src="images/personal/weather/weather_4.jpg" caption="Погода в Питере.">}}
  {{< figure src="images/personal/weather/weather_5.jpg" caption="Погода в Ейске.">}}
  {{< figure src="images/personal/weather/weather_6.jpg" caption="Редактирование главного экрана.">}}
{{< /gallery >}}

Язык - Swift 4.2.
Основные фреймворки - SnapKit, CoreData, Alamofire, Swinject.

---

### Коллекция приложений ArchWeather.
#### 2019 г. 

**Продукт:** Коллекция одностраничных погодных приложений, реализованных с разными архитектурными подходами.

**Выполненные задачи:**
- Изучил на практике различия в архитектурных подходах: MVC, MVP, MVVM (closures), MVVM (RxSwift), ReactorKit, RxFeedback (MVC), VIPER.   

Язык - Swift 4.2.

[Проект на Github](https://github.com/infoweb77/iOS-architecture-examples)

---

### Структуры данных и алгоритмы на Swift.  
#### 2020 г.

**Продукт:** Учебный проект для подготовки к алгоритмической секции интервью.

**Выполненные задачи:**
- Изучил основные структуры данных и алгоритмы (деревья, сортировки, графы) по книге **Data Structures & Algorithms in Swift** от raywenderlich. 

{{< gallery layout="grid" id="gallery42"  >}}
  {{< figure src="images/webb/struct.jpg" >}}
{{< /gallery >}}


Язык - Swift 4.2.

[Проект на Github](https://github.com/infoweb77/Algorithms)

---

### Приложение SuperStorage
#### 2025 г.
 
**Продукт:** Облачный файловый менеджер для изучения async/await и Combine.

**Выполненные задачи:**
- Реализовал три стратегии загрузки: Silver (один блок), Gold (прогресс через AsyncStream), Cloud 9 (параллельные чанки через TaskGroup). 
- Освоил современную конкурентную модель Swift (async/await) и фреймворк Combine на практике, сравнив различные стратегии асинхронной загрузки данных.

{{< gallery layout="grid" id="gallery6" >}}
  {{< figure src="images/rapp/edu/storage/storage_1.jpg" caption="Список файлов">}}
  {{< figure src="images/rapp/edu/storage/storage_2.jpg" caption="Тарифные планы">}}
  {{< figure src="images/rapp/edu/storage/storage_4.jpg" caption="Процесс загрузки файла">}}
  {{< figure src="images/rapp/edu/storage/storage_5.jpg" caption="Превью загруженного файла">}}
  {{< figure src="images/rapp/edu/storage/storage_6.jpg" caption="Параллельная загрузка частей файла">}}
{{< /gallery >}}

[Проект на Github](https://github.com/infoweb77/SuperStorage)

---

### Приложение Kuchi
#### 2025 г.


**Продукт:** Приложение для изучения японского языка с помощью карточек.

**Выполненные задачи:**
- Изучил методы адаптивной вёрстки SwiftUI: работа с текстом и изображениями, текстовыми полями и кнопками, создание формы регистрации, контейнеры, контролы<!--(@State & @Binding)-->, распознавание жестов.
- Приложение работает как на iOS, так и на macOS из одного кода.

**iOS-версия**

{{< gallery layout="grid" id="gallery7" >}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_1.jpg" caption="Экран авторизации">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_2.jpg" caption="Карточка для обучения">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_3.jpg" caption="Свайп карточек">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_5.jpg" caption="Экран проверки">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_6.jpg" caption="Правильный ответ">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_7.jpg" caption="Экран настроек">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_8.jpg" caption="Выбор цвета карточек">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_10.jpg" caption="Темная тема">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_12.jpg" caption="Свайп карточек">}}
{{< /gallery >}}

**macOS-версия**

{{< gallery layout="grid" id="gallery8" >}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_14.jpg" caption="Экран входа">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_15.jpg" caption="Экран настроек">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_16.jpg" caption="Карточка для обучения">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_17.jpg" caption="Правильный ответ">}}
  {{< figure src="images/rapp/edu/kuchi/kuchi_18.jpg" caption="Карточка для обученияи">}}
{{< /gallery >}}

[Kuchi на Github](https://github.com/infoweb77/Kuchi)

---

### Приложение Mountain Airport
#### 2025 г.

**Продукт:** Информационное приложение аэропорта.

**Выполненные задачи:**
- Продолжил изучение SwiftUI: навигация, продвинутые списки данных, модальные окна и алерты, кастомная графика и анимация.
- Навыки SwiftUI пригодились при вёрстке Kotlin MultiPlatform-приложения в Rapporto.

{{< gallery layout="grid" id="gallery9" >}}
  {{< figure src="images/rapp/edu/airport/airport_1.jpg" caption="Экран входа">}}
  {{< figure src="images/rapp/edu/airport/airport_2.jpg" caption="Время полета">}}
  {{< figure src="images/rapp/edu/airport/airport_3.jpg" caption="Экран достижений">}}
  {{< figure src="images/rapp/edu/airport/airport_6.jpg" caption="Поиск">}}
  {{< figure src="images/rapp/edu/airport/airport_7.jpg" caption="Результаты поиска">}}
  {{< figure src="images/rapp/edu/airport/airport_8.jpg" caption="Вылетающие рейсы">}}
  {{< figure src="images/rapp/edu/airport/airport_9.jpg" caption="Информация о рейсах">}}
  {{< figure src="images/rapp/edu/airport/airport_10.jpg" caption="Информация о рейсе">}}
  {{< figure src="images/rapp/edu/airport/airport_11.jpg" caption="Информация о терминале">}}
{{< /gallery >}}

[MountainAirport на Github](https://github.com/infoweb77/MountainAirport)

---