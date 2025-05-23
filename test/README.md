# РЕСТООКИ

## О проекте

Рестооки - это веб-приложение для бронирования столиков в ресторане. Проект разработан с использованием современных веб-технологий и предлагает пользователям удобный интерфейс для просмотра меню, бронирования времени посещения и регистрации в системе.

## Функциональность

- **Просмотр меню ресторана** - пользователи могут просматривать доступные блюда с детальной информацией о составе, калорийности и цене
- **Бронирование столиков** - система позволяет выбрать удобную дату и время посещения с указанием количества гостей
- **Регистрация и авторизация** - пользователи могут создать аккаунт для отслеживания своих бронирований и получения специальных предложений
- **Адаптивный дизайн** - интерфейс корректно отображается на устройствах различного размера

## Технологии

- HTML5, CSS3, JavaScript (ES6+)
- Модульная архитектура JavaScript
- Адаптивная верстка
- Динамическая валидация форм

## Структура проекта

```
test/
├── index.html          # Главная страница
├── style.css           # Стили CSS
├── script.js           # Основной JavaScript файл
├── assets/
│   ├── js/
│   │   ├── menu.js     # Модуль меню
│   │   ├── booking.js  # Модуль бронирования
│   │   └── ...         # Другие JavaScript модули
│   ├── css/            # Дополнительные CSS файлы
│   └── img/            # Изображения
└── ...
```

## Запуск проекта

Для запуска проекта локально выполните:

```bash
cd test
python -m http.server 8080
```

После этого проект будет доступен по адресу http://localhost:8080

## Особенности реализации

- **Модуль меню** - обеспечивает интерактивный просмотр блюд с подробной информацией при клике
- **Модуль бронирования** - включает валидацию форм, ограничение доступных дат и времени, маску ввода телефона
- **Система уведомлений** - информирует пользователя о результатах действий

## Авторство

Проект разработан как демонстрационная версия веб-приложения для ресторана. 