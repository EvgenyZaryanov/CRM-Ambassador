# CRM-Ambassador - Амбассадоры Яндекса

## Описание

Это web приложение позволяет управлять сообществом амбассадоров Яндекс Практикума, которое будет приносить прогнозиуремый поток маркетинговых привлечений в месяц.

![FireShot Capture 032 - CRM - Profile](https://github.com/EvgenyZaryanov/CRM-Ambassador/assets/128030479/1aeae654-ba34-4e0b-8840-0a38fb533be9)  
![FireShot Capture 033 - CRM - create profile](https://github.com/EvgenyZaryanov/CRM-Ambassador/assets/128030479/f24387e9-3edb-41ba-ae80-27fadf4b77ff)
![FireShot Capture 035 - CRM - content](https://github.com/EvgenyZaryanov/CRM-Ambassador/assets/128030479/1ce01d2e-e706-4680-bbbc-d3a2fc8d13d6)


[**Ссылка на оригинальный репозиторий проекта**](https://github.com/levinnsk/ambassador-hakaton)

## Применяемые технологии

-   CSS
-   HTML
-   Флэкс верстка
-   Грид верстка
-   Псевдоклассы в CSS
-   Создана файловая структура по БЭМ (Nested).
-   Использован JS для открытия и закрытия попап окон, создание, удаление карточек.
-   Валидация с помощью JS.
-   ООП, JS разбит на модули
-   Material UI
-   API
-   React
-   React routing
-   Сделана регистрация и авторизация пользователей

## Разработчики

-   [Станислав Угланов](https://github.com/levinnsk)
-   [Евгений Зарянов](https://github.com/EvgenyZaryanov)
-   [Дмитрий Данильченко](https://github.com/DimaDanilchenko)

## Доработки в следующем релизе

-   Модуль настройки
-   Модуль аналитики
-   Модуль задач
-   Улучшение стабильности и работоспособности приложения

# Инструкция по запуску, разработке и сборке

## Подготовка рабочего места:

1. Скачать и установить node js версии 21.x.x [по ссылке https://nodejs.org/en](https://nodejs.org/en).
2. Скачать и установить Visual Studio Code [по ссылке https://code.visualstudio.com/](https://code.visualstudio.com/).
3. В Visual Studio Code установить плагины:

-   ESLint
-   Prettier - Code formatter

4. Создать папку на диске, например ambassador_crm.
5. В Visual Studio Code открыть папку ambassador_crm и открыть командную строку (сочетание клавиш Ctrl + ~).
6. В командной строке выполнить команду

```bash
npm install
```

## Запуск разработки:

1. В командной строке выполнить команду

```bash
npm run dev
```

2. [По ссылке http://localhost:5173/](http://localhost:5173/) откроется веб-приложение.
3. При необходимости внести изменения в код.

## Запуск сборки:

1. В командной строке выполнить команду

```bash
npm run build
```

2. В папке dist соберется рабочий пакет веб-приложения, который можно размещать на удаленном ресурсе.
