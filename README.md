<p align="center">
  <img src="assets/banner.png" width="100%" alt="Корзина КБЖУ">
</p>

<h1 align="center">Корзина КБЖУ</h1>

<p align="center">
Современное Android-приложение для анализа продуктовой корзины, расчёта КБЖУ и планирования питания.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-34-34A853?style=for-the-badge&logo=android&logoColor=white">
  <img src="https://img.shields.io/badge/Java-17-E76F00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Offline-First-2E7D32?style=for-the-badge">
  <img src="https://img.shields.io/badge/Privacy-First-1B5E20?style=for-the-badge">
  <img src="https://img.shields.io/badge/Version-1.0-4CAF50?style=for-the-badge">
</p>

<p align="center">
  <a href="https://voynich-studio.github.io">Сайт</a>
  ·
  <a href="https://voynich-studio.github.io/privacy-policy.html">Политика конфиденциальности</a>
  ·
  <a href="mailto:voynichstudio@mail.ru">Поддержка</a>
</p>

---

## О приложении

**Корзина КБЖУ** помогает анализировать продуктовую корзину, рассчитывать калории, белки, жиры и углеводы, контролировать питание и понимать, насколько выбранных продуктов хватит для достижения поставленной цели.

Приложение работает полностью офлайн, не требует регистрации, не содержит рекламы и хранит пользовательские данные только на устройстве.

---

## Демонстрация

<p align="center">
  <img src="gif/demo.gif" width="320" alt="Демонстрация приложения">
</p>

---

## Почему именно Корзина КБЖУ

| Преимущество              | Описание                                          |
| ------------------------- | ------------------------------------------------- |
| Privacy First             | Данные пользователя хранятся только на устройстве |
| Offline First             | Приложение работает без подключения к интернету   |
| Без регистрации           | Не нужно создавать аккаунт                        |
| Без рекламы               | Интерфейс не перегружен рекламными блоками        |
| Анализ корзины            | Приложение показывает КБЖУ и запас продуктов      |
| Пользовательские продукты | Можно добавлять собственные продукты              |

---

## Основные возможности

* автоматический расчёт КБЖУ;
* анализ продуктовой корзины;
* оценка покрытия целей питания;
* расчёт запаса продуктов в днях;
* персональные рекомендации;
* встроенная база продуктов;
* добавление пользовательских продуктов;
* локальное хранение данных;
* работа без интернета;
* отсутствие рекламы.

---

## Скриншоты

| Главная                                      | Корзина                                        |
| -------------------------------------------- | ---------------------------------------------- |
| <img src="screenshots/home.png" width="320"> | <img src="screenshots/basket.png" width="320"> |

| Анализ                                           | Продукты                                         |
| ------------------------------------------------ | ------------------------------------------------ |
| <img src="screenshots/analysis.png" width="320"> | <img src="screenshots/products.png" width="320"> |

| Профиль                                         |
| ----------------------------------------------- |
| <img src="screenshots/profile.png" width="320"> |

---

## Технологии

<p>
  <img src="https://img.shields.io/badge/Java-111111?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Android%20SDK-111111?style=for-the-badge&logo=android&logoColor=3DDC84">
  <img src="https://img.shields.io/badge/Material%20Design-111111?style=for-the-badge&logo=materialdesign&logoColor=white">
  <img src="https://img.shields.io/badge/XML-111111?style=for-the-badge">
  <img src="https://img.shields.io/badge/Gradle-111111?style=for-the-badge&logo=gradle&logoColor=white">
  <img src="https://img.shields.io/badge/SharedPreferences-111111?style=for-the-badge">
  <img src="https://img.shields.io/badge/Git-111111?style=for-the-badge&logo=git&logoColor=F05032">
</p>

---

## Архитектура

```text
UI
│
├── Главная
├── Корзина
├── Анализ
├── Продукты
└── Профиль
        │
        ↓
Business Logic
        │
        ↓
SharedPreferences
        │
        ↓
Local Storage
```

Подробное описание архитектуры находится в файле `ARCHITECTURE.md`.

---

## План развития

| Версия |      Статус | Описание                              |
| ------ | ----------: | ------------------------------------- |
| 1.0    |      Готово | Базовая версия приложения             |
| 1.1    |    В работе | Улучшение интерфейса и оптимизация    |
| 2.0    | Планируется | Smart Basket                          |
| 3.0    | Планируется | Smart Menu                            |
| 4.0    | Планируется | AI-рекомендации                       |
| 5.0    | Планируется | Синхронизация и резервное копирование |

Подробный план развития находится в файле `ROADMAP.md`.

---

## Google Play

Приложение готовится к публикации в Google Play.

После прохождения проверки ссылка появится в этом разделе.

---

## Документация

* `ROADMAP.md` — план развития приложения;
* `CHANGELOG.md` — история изменений;
* `ARCHITECTURE.md` — архитектура проекта;
* `PRIVACY.md` — краткое описание подхода к конфиденциальности;
* `CONTRIBUTING.md` — правила участия в проекте;
* `LICENSE` — лицензия проекта.

---

## Разработчик

**Voynich Studio**

Сайт: https://voynich-studio.github.io
Политика конфиденциальности: https://voynich-studio.github.io/privacy-policy.html
Email: [voynichstudio@mail.ru](mailto:voynichstudio@mail.ru)

---

<p align="center">
  <b>Voynich Studio</b><br>
  Building useful Android apps
</p>
