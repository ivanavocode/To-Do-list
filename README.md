

TODO LIST
================

link: https://ivanavocode.github.io/React-project/
----------

Установка
----------
Установить зависимости из package.json(..\project\package.json) cmd --> npm i

```sh
Комманды  npm run...
    start, --запуск проекта
    build, -- сборка
```

  - __components__
    - __app__
      - [app.js]                # основной компонент, содержит основную логику приложения
    - __app-header__
      - [app-header.js]         # отображает заголовок и статус дел(активно,закончено)
    - __item-add-from__
      - [item-add-form.js]      # компонент содержит форму для создания новой задачи
    - __item-status-filter__
      - [item-status-filter.js] # производит сортировку по выбранному критерию(all, active, done)
    - __search-panel__
      - [search-panel.js]       # панель поиска задачи
    - __todo-list__
      - [todo-list.js]          # отображает список дел
    - __todo-list-item__
      - [todo-list-item.js]     # child component todo-list создает  элемент списка
  - [index.js]

