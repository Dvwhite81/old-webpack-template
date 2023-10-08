[node]: https://nodejs.org/ru
[pulls]: https://github.com/GuVictory/webpack-vanilla-template/pulls

# Webpack Vanilla JavaScript — Базовый шаблон

Это начальный шаблон разработки — идеальное решение, которое поможет вам начать работу над проектом в кратчайшие сроки, без необходимости устанавливать и настраивать среду разработки с нуля каждый раз, когда вы начинаете работать.

Этот шаблон идеально подходит для разработчиков, которые хотят создавать быстрые и надежные веб-приложения с использованием следующих технологий как: **JavaScript**, **ESLint**, **Prettier**, **Webpack**, **Babel**, **Core-JS**!

## :package: Что входит в шаблон?

Этот начальный шаблон оснащен всеми необходимыми инструментами для создания основы веб-приложения, вот что в него входит:

-   **JavaScript**: Язык программирования, используемый в основном для создания динамического веб-контента и интерактивных пользовательских интерфейсов;

-   **SASS**: Препроцессор CSS, который добавляет в CSS такие функции, как переменные, вложенность и миксины, упрощая написание и поддержку большого количества CSS;
-   **PostCSS**: Инструмент для преобразования CSS с помощью плагинов JavaScript, позволяющий добавлять новые функции в CSS и улучшать процесс разработки:

    -   **Autoprefixer**: Плагин PostCSS, который добавляет префиксы поставщиков к свойствам CSS, обеспечивая кросс-браузерную совместимость;
    -   **CSSnano**: Плагин PostCSS, который минимизирует код CSS, уменьшая размер файла и улучшая время загрузки страницы;

-   **Webpack**: Инструмент сборки и разработки приложения:
    -   **Babel**: Компилятор, используемый как для компиляции, так и для объединения JavaScript в поддерживаемый код, совместимый с разными браузерами;
    -   **Core-JS**: Модульная стандартная библиотека, предоставляющая полифиллы для новых функций, представленных в последних спецификациях `ECMAScript`, и помогающая обеспечить кросс-браузерную совместимость;

И еще пара инструментов, которые улучшают процесс разработки:

-   **ESLint**: Инструмент для обеспечения соблюдения стандартов написания кода и выявления потенциальных ошибок;
-   **Prettier**: Средство форматирования кода, которое автоматически форматирует код в соответствии с единым стилем, облегчая его чтение и обслуживание;

---

## :computer: Начало работы

### Prerequisites:

-   JavaScript [Node][node];

### Чтобы начать работать с шаблоном:

-   Внутри этого репозитория:

    -   нажать на кнопку **"Use this template"** <br/> или
    -   нажать на кнопку **"Fork"** <br/> или
    -   **склонировать** репозиторий `git clone https://github.com/GuVictory/webpack-vanilla-template.git YOUR-PROJECT-NAME`;

-   Откройте терминал в папке проекта:
    -   Чтобы **установить** зависимости: `npm install`;
    -   Чтобы **запустить** сервер для разработки: `npm run start`;
    -   Чтобы **собрать** приложение готовое к **продакшену**: `npm run build`;
    -   Чтобы **посмотреть** как будет вести себя **оптимизорованное приложение для продакшена**: `npm run preview`;

---

## :globe_with_meridians: Поддержка браузеров

Предоставленная конфигурация обеспечивает работу в **92.3 %** **основных браузеров**.

Чтобы поддерживать более широкий процент браузеров и соответствовать требованиям вашего проекта, обновите файл конфигурации `./.browserslistrc`:

1. `last 3 versions`: версия каждого браузера;
2. `> 0.2%`: статистика использования браузера;
3. `not dead`: браузер официально поддерживается и обновляется;

---

## :busts_in_silhouette: Хочу доработать код

Возможность доработать код — это то, что делает тулзы с открытым исходным кодом таким замечательным местом для обучения, вдохновения и творчества.
Приветствуется любой вклад: большой или маленький, это могут быть обновления документации, добавление новых функций или что-то большее.

### Как законтрибуить:

1.  Для новой фичи:
    1.  Сделайте форк этого репозитория
    2.  Создайте в своем форке ветку: `git checkout -b feat/NEW-FEATURE`;
    3.  Добавьте свои изменения: `git add PATH/TO/FILENAME.EXTENSION`;
    4.  Закомитте свои изменения: `git commit -m "feat: NEW FEATURE"`;
    5.  Залейте на ветку: `git push origin feat/NEW-FEATURE`;
2.  Для исправления багов:
    1.  Сделайте форк этого репозитория
    2.  Создайте в своем форке ветку: `git checkout -b fix/BUG-FIX`;
    3.  Добавьте свои изменения: `git add PATH/TO/FILENAME.EXTENSION`;
    4.  Закомитте свои изменения: `git commit -m "fix: BUG FIX"`;
    5.  Залейте на ветку: `git push origin fix/BUG-FIX`;
3.  Откройте новый [pull request][pulls];

---
