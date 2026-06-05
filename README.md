# Практическая работа по web-разработке — Bērnu Veikals

Одностраничный сайт интернет-магазина товаров для детей и родителей. Проект собран как набор последовательных учебных заданий: от адаптивной HTML/CSS-верстки до Bootstrap 5 версии с интерактивными компонентами.

## Структура проекта

| Path | Description |
|---|---|
| `task-3/` | Адаптивная HTML/CSS-верстка главной страницы. |
| `task-4/` | Версия с CSS-стилизацией, hover/focus effects, shadows, gradients, filters, transitions и формами. |
| `task-5/` | Bootstrap 5 версия главной страницы с сохраненной сеткой `container -> row -> col`. |
| `task-6/` | Bootstrap 5 версия с 11 Bootstrap widgets, включая `Carousel`. |
| `Figma/` | Reference exports из Figma: full-page макеты, SVG-блоки и исходные материалы. |
| `Word docs/` | Исходные документы и style guide. |
| `wireframe-capture/` | Wireframe/reference capture. |

В reference-папках есть короткие `README.md`, которые поясняют назначение материалов.

> В текущей рабочей папке найдены `task-3`, `task-4`, `task-5` и `task-6`. Если `task-1` и `task-2` также нужны для сдачи в одном репозитории, их стоит добавить отдельными папками `task-1/` и `task-2/`.

## Выполненные задания

| Task | Description | Technologies |
|---|---|---|
| `task-3` | Adaptive layout главной страницы | HTML5, CSS3, Flexbox, CSS Grid |
| `task-4` | CSS styling and effects | HTML5, CSS3 effects, transitions, animations, forms |
| `task-5` | Bootstrap layout | HTML5, CSS3, Bootstrap 5 CSS |
| `task-6` | Bootstrap widgets | HTML5, CSS3, Bootstrap 5 CSS/JS |

## Bootstrap widgets в task-6

В `task-6` подключены и настроены 11 Bootstrap-компонентов:

1. Navbar Collapse
2. Dropdown
3. Offcanvas
4. ScrollSpy
5. Modal
6. Toast
7. Tooltip
8. Popover
9. Accordion
10. Collapse
11. Carousel

## Как открыть проект

Каждое задание автономно: внутри папки есть свой `index.html`, `styles.css` и локальные `assets`.

Можно открыть файл напрямую в браузере:

```text
task-6/index.html
```

Или запустить локальный server из нужной папки:

```bash
cd "task-6"
python3 -m http.server 4176
```

После запуска открыть:

```text
http://localhost:4176/
```

Для остальных заданий можно использовать аналогичные порты:

| Task | Suggested local URL |
|---|---|
| `task-3` | `http://localhost:4173/` |
| `task-4` | `http://localhost:4174/` |
| `task-5` | `http://localhost:4175/` |
| `task-6` | `http://localhost:4176/` |

## Проверка перед публикацией

Перед загрузкой на GitHub стоит проверить:

- в репозиторий не попали `.DS_Store`;
- все папки `task-*` открываются локально;
- изображения и SVG загружаются без missing refs;
- в `task-5` и `task-6` не сломана Bootstrap grid;
- в `task-6` работают все Bootstrap widgets.

## Примечания

- В проекте нет `package.json`, `node_modules` и сборщика.
- Сторонние библиотеки, кроме Bootstrap в `task-5`/`task-6`, не используются.
- Reference-папки `Figma/`, `Word docs/` и `wireframe-capture/` сохранены без изменений.
